# Real Estate React client 🏘️

## What's this project is about

- [🔥 Deployed Version 🔥](https://desolate-refuge-17574.herokuapp.com/)

Real estate for sale & for rent website. Real estate website's visitors can easily filter their searches by type, location, price, and other predefined and custom criteria. Each property goes with a detailed description, community and property features, location, price, and a great image gallery.
Buyer of real estate can find contacts of seller. In case seller enabled online appointment feature for advertisement - buyer can fill in form to make online appointment request.

**Disclaimer:**
This project was merely a learning exercise as well as my first sizeable project delving into React, Redux & other used technologies.

## Technologies Used

- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Redux-Thunk](https://github.com/reduxjs/redux-thunk)
- [GitHub](http://github.com)
- [Express](https://expressjs.com/)
- [PostgresQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/)
- [react-moment](https://github.com/headzoo/react-moment#readme)
- [Leaflet](https://leafletjs.com/)
- [Cloudinary](https://cloudinary.com/)
- [Cloudinary-React](https://cloudinary.com/documentation/react_integration)

## Terms & Conditions

This project was created in 2 and a half weeks. React Site & API Server was built as Portfolio project, after a Full-Stack Developer cource: [Codaisseur](https://codaisseur.com/).

## Main goals of this project:

- Create Full Stack App independently
  - Using new knowleges from Full Stack course
  - Finding and using new technologies for specific tasks
- Brainstorm idea
- Create Wireframes & Datastructure
- Train Git Usage
  - Work on different branches
  - Create regular PR
  - Write a small summary when you make a PR
  - Create regular commits
  - Make sure latest working version is always on the master branch
- Finish the exististing functionality and polish
- Style Project
- Deploy project

## Installation & Setup Guide

- git clone git@github.com:jkarelins/real-estate-site.git
- cd real-estate-site
- npm install
- npm run start

# Datastructure for db

#### Advertisement

- isForSale: Boolean,
- isForRent: Boolean,
- realEstateType: TEXT - can select from categories

- adress
- postcode
- city
- price
- Year of construction
- year of last renovation
- Living space
- Number of rooms/bedrooms/bathrooms
- description
- Status: Available/sold
- Energy label
- Heating
- Warm water - Boiler/central
- Location Description
- Garden - optional
- Type of parking

Extras(especially for rent):
e.g.:
optical internet
free parking
city view/nature view / cannal view
air conditioner
bath

#### User

username: TEXT,
password: TEXT,
email: TEXT,
phoneNumber: Text,

## Calendar

Used to make a new appointment:

Each calendar event has:

- hasOne Customer
- hasOne Seller
- date: Date
- time: time
- message: TEXT
- customer PhoneNumber
- customer Email
- canceledByCustomer: Boolean
- canceledBySeller: Boolean
