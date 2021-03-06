# Online Offline Budget Tracker
A PWA application using Node.js, Express, MongoDB, and mongoose to allow users  to keep track of their money as well as input deposits and withdraw cash both online and offline.

## Functionality

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

## Deployed App on Heroku

[Budget Tracker Heroku Link](https://on-off-budget-tracker-pwa.herokuapp.com/)

![Budget-Tracker-Gif](Budget-Tracker-Gif.gif)




## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.

- - -

## Technology Used
* Node.js
* npm packages:
  * express
  * mongoose
  * morgan
  * compression
  * lite-server
* MongoDB
* Javascript
* HTML & CSS
* PWA (webmanifest & service workers)




