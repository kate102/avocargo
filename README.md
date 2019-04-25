<h1 align="center">avocargo</h1>

## Introduction
I have been asked to write a app for a friend. 
His company brings the worlds finest avocados from Mexico to London. 
He supplies restaurants and retailers. 
Currently his clients order via text, WhatsApp, email and voicemail. 
Delivery days are Monday, Wednesday and Friday.

On the morning of delivery day, my friend and the driver meet at the warehouse. 
My friend provides a list of clients and their requirements that he has generated from the various communication methods and they load the van.

## User Stories
- My friend would like  a single ordering system that all of the clients could use
- He would also like this system to generate a list of orders based on delivery date
- Finally it would be nice if it also generated invoices

## Modelling
This model shows the MVP of this app
![avo_model1](https://github.com/kate102/avocargo/blob/master/images/model_1.jpg)

## Tech
I have decided to write this in `Javascript` and use `Jasmine` to TDD it.

## Testing
- jasmin is used for testing and the test suite is held in the file avocargoSpec.js.
- The file is refered to in the SpecRunner.html file.
- To run the tests you run `open SpecRunner.html`
