# Web Dev Starter Code

## To run

When running this website the functionality for the delete doesn't work in the live preview so you need to pull up the website either in safari or google chrome

## Project Spec

theWait

## General theme

theWait is going to be a lightweight, full stack wait list management application that will be designed to help restaurants manage people waiting to dine in. This website is designed for a first come first serve style restaurant, but gives customers accessibility to the wait list through the website.

This website could realistically be used for any sort of service that could require a wait list like a barbershop, nail salon, or any business that requires an organized list. The goal is to make the wait list process more organized for customers and business owners. 

## What it's going to do 

theWait will be a website that will provide customers with a web interface where users can:

-Add themselves to a wait list by entering a name and party size.
-View the current wait list in real time to get a sense of what to expect.
-Remove themselves from the wait list using some sort of Unique ID that each customer will have.

This website will give customers and business owners a sense of the wait and who's next up in line. It will give customers a platform to manage incoming traffic

## Target audience

theWait will be targeted mainly for smaller or local business owners who need a lightweight and simple browser based website that can handle regular business traffic like a wait list and give customers information to help them plan out what they can do while waiting on the wait list.

This website is going to be designed with mainly smaller restaurant usability in mind and is intended to give them something that is simple and not complex that will not require a lot of resources.

## Data it will manage

theWait will handle user data that includes:

- Name
- Additional notes for the restaurant to keep in mind
- an auto generated time stamp to gauge how long the wait will be and how long the customer has been waiting
- A Unique ID that will be auto generated that can help keep track for when a customer wants to delete themselves from the wait list. 

All of this data will be stored in a dynamoDB table and handled through a node.js Lambda backend like we used in our most recent lab.

API routes that this website will be using will be

- POST/waitlist -add a new user
- GET /waitlist - Retrieve all current users
- DELETE /waitlist/{id} - Remove a specific user from the wait list

## Stretch goals

Once the basic features of this website are implemented I would like to additionally add:

- Wait time estimation
- Some additional information about the restaurant
- A searchable list to pull up information on a specific customer.
- Scalability to handle more traffic for restaurants that are busier.


## Project Wireframe

![wireframe](https://app.moqups.com/fdaRQnprQjJwcxuNO36gkBM3w6U1Vmde/view/page/ad64222d5)


if the link above doesn't work I provided an image in the directory (wireframe.png).


## Sources

how to do transitions with buttons
https://developer.mozilla.org/en-US/docs/Web/CSS/transition

button animations

https://dev.to/webdeasy/top-20-css-buttons-animations-f41

background animations
https://www.sliderrevolution.com/resources/css-animated-background/




