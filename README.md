# PWA - Budget Tracker

This [Progressive Web App](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps) will track your budget online and offline, no matter where you are.

A PWA has the following features:

* __Progressive__: If the user has an old browser (IE 11), the application will still work as a normal web app, without delivering any progressive function.

* __Works offline__: With service workers we can decide which assets or data requests to cache and make available when the user is offline or on low quality networks.

* __Safe__: Service workers can only be installed using a secure connection (HTTPS or localhost. We will discuss this in detail later).

* __Re-engage__: Increases users re-engagement through web notifications, that work in the background, allowing to reach our users even if the application is closed.

* __Installable__: Thanks to the web app manifest a PWA can be installed on the user's device home screen.

* __Responsive__: Fits any device: desktop, mobile or tablet.

In this project, I added functionality to an existing Budget Tracker application to allow offline access and functionality.

Now, the user is able to add expenses and deposits to the budget with or without an Internet connection. When entering transactions offline, they should populate the total when brought back online.

__Offline Functionality__:

  * Enter deposits offline.
  * Enter expenses offline.
  * Save files locally in browser's .
  * Save data locally in indexedDB.
  * Service worker intercepts communication between app and database. 

__Online Functionality__:

  * Offline entries are added to tracker automatically.

- - -
## User Story

AS A user
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

As a business traveler
I WANT a fast and easy way to track the money and access the information anytime and anywhere, 
SO THAT I can work offline and have the same functionality.

AS a user 
I WANT to work on the Budget App without an internet connection
AND WHEN I input any budget transaction (withdrawal, deposit, etc)
THEN I WANT the transacton to be shown on the page, 
AND AUTOMATICALLY ADDED to the database when the connection is back online.

- - -

## Deployed Application URL 

[Heroku - PWA Budget Tracker](https://github.com/tomaspz/pwa-budget-tracker)

- - -

## Github repository URL 

[GitHub Repo - PWA Budget Tracker](https://github.com/tomaspz/pwa-budget-tracker)
