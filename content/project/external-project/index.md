---
title: Guess the Number Python Game
date: 2016-04-27T00:00:00.000Z
summary: ""
tags:
  - Demo
external_link: ""
image:
  caption: Photo by Toa Heftiba on Unsplash
  focal_point: Smart
---
H﻿ow it works:

1. Choose the number range from 1 to 10000
2. Game should ask us to guess the number
3. Give a clue if the number is higher or lower than the guess
4. Inform the player if he won


   ```python
   from random import randint
   start=1
   end=1000

   value=randint(start, end)

   print("The computer choose a number between",start, "and",end)



   guess=None
   while guess!=value:
       text=input("guess the number :")
       guess=int(text)

       if(guess<value):
           print("Your guess is lower than the number")

       elif guess > value:
           
           print("Your guess is higher than the number")

   print("Congratulations  !! you guessed the number you wone")            
               
   ```

   ![](gamee.png)