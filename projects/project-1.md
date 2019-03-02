---
layout: project
type: project
image: images/wreck.png
title: Item Rental Service
permalink: projects/rental
# All dates must be YYYY-MM-DD format!
date: 2019-02-25
labels:
  - Javascript
  - NodeJS
  - React
summary: I was part of a team that created an inventory rental website built using NodeJS/Express, React and Redux.
---

<img class="ui medium right floated rounded image" src="../images/wreck.png">

In this project I was part of a team that built a website for an imaginary company that wanted customers to be able to rent equipment and track the history of items, and customers rental histories.

Project requirements included: 
* Admins must be able to add equipment with pictures.
* Admins must be able to add customers with names and contact info.
* There must be a history of rentals.
* You must be unable to rent an item that already has an existing rental on a given day.
* Customers should receive an email when a rental is created.
* Admins should be able to text the customer to let them know about a rental.

My Group built this project using Node, Express, React, and Redux. We also used libraries such as jest for testing, and nodemailer for email functionality.

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

View Here [Live View](https://wreck-ur-life.herokuapp.com).



