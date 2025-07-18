# PriceUp

### A simple PWA for pricing jobs, in this case, Blinds and Plantation Shutters
**This will be used by a family member for their business.**

## Goal

The user wants a simple way for pricing jobs from the excel files that they have. 

## Plan

Build a simple, responsive, secure web app that the user can install on mobile or desktop.
---

The app itself will be a simple python flask script that will allow the user to upload the csv [**and excel in the future**] documents that contain the pricing 'matrix'.

It will then process and clean the data using a seperate data cleaning script using python and pandas.

Final use case will look like this: Take in individual window measurements (as its focused on blinds) and produce a list containing the window details and individual price that has been generated via the data set that was cleaned.

Can then save this in the database.


## Tech Stack

- ### Frontend: 
    HTML, CSS, Js
- ### Backend
    Flask
- ### Database
    SQLite