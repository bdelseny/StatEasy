# Stat'Easy WebApp

This folder contains source code for Stat'Easy WebApp.

## What is Stat'Easy WebApp

The webapp is the application avaible throught internet.
It let users interact with a smooth interface for R.

## Tree structure

Stat'Easy WebApp is composed of a:
  - frontend 
  - backend

This is a modular application.
Both frontend and backend can be developed simultaneously and independantly.

### Frontend

The frontend is what the user will interact with.
The frontend is display in a browser, as mozilla firefox.
The frontend is developed in Angular 4+.
Because it is developed with Angular the result should be the same in many browser.

### Backend

The backend of the application is what make it works.
It is doing request to database, calling and executing R programs and some other calculations.
Users can not see or interact with the backend of the application.
The backend is developed in Java 8 with Maven and Spring.
