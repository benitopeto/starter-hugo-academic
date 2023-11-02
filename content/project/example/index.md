---
slides: example
url_pdf: ""
title: SQL PROJECT
summary: ""
url_video: ""
date: 2016-04-27T00:00:00.000Z
external_link: ""
url_slides: ""
subtitle: Challenge 1 - Steve's Car Showroom
tags:
  - Deep Learning
links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
url_code: ""
---
![](sgl-img.png "Intro Steve runs a top-end car showroom but his data analyst has just quit and left him without his crucial insights. Can you analyse the following data to provide him with all the answers he requires?")

![](imgtables.jpg)

```sql
CREATE TABLE cars (
car_id INT PRIMARY KEY,
make VARCHAR(50),
type VARCHAR(50),
style VARCHAR(50),
cost_$ INT
);
```

```sql
INSERT INTO cars (car_id, make, type, style, cost_$)
VALUES (1, 'Honda', 'Civic', 'Sedan', 30000),
(2, 'Toyota', 'Corolla', 'Hatchback', 25000),
(3, 'Ford', 'Explorer', 'SUV', 40000),
(4, 'Chevrolet', 'Camaro', 'Coupe', 36000),
(5, 'BMW', 'X5', 'SUV', 55000),
(6, 'Audi', 'A4', 'Sedan', 48000),
(7, 'Mercedes', 'C-Class', 'Coupe', 60000),
(8, 'Nissan', 'Altima', 'Sedan', 26000);

CREATE TABLE salespersons (
salesman_id INT PRIMARY KEY,
name VARCHAR(50),
age INT,
city VARCHAR(50)
);
```