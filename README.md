# Unit 18 PWA Homework: Online/Offline Budget Trackers

Add functionality to our existing Budget Tracker application to allow for offline access and functionality.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

#### Offline Functionality:

  * Enter deposits and expenses offline:
  -- uses service-worker.js file to cache data even when app is offline

* When brought back online:
-- offline entries should be added to tracker using cached data stored

#### User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

----------------------
#### Business Context
Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

#### Technologies and Tools Utilized:
* node.js
* express
* mongoDB / mongoose
* PWA tools: service-worker.js and webmanifest
* Google Dev Tools
* jQuery
* Bootstrap
* Heroku

#### Installation
```npm server.js```

#### Deployed Application hosted by Heroku:
https://rocky-castle-04167.herokuapp.com/

#### ScreenShots
<div align="center">
<a href="https://ibb.co/myYdCC8"><img src="https://i.ibb.co/dp3X00g/Screen-Shot-2020-06-17-at-4-32-06-PM.png" alt="Screen-Shot-2020-06-17-at-4-32-06-PM" border="0"></a>
<br>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/Wcmb6Yv/Screen-Shot-2020-06-17-at-4-32-49-PM.png" alt="Screen-Shot-2020-06-17-at-4-32-49-PM" border="0"></a>
<br>
<a href="https://ibb.co/7bgygd2"><img src="https://i.ibb.co/XVyJyrS/Screen-Shot-2020-06-17-at-4-33-25-PM.png" alt="Screen-Shot-2020-06-17-at-4-33-25-PM" border="0"></a>
</div>


#### Questions

tjeansouth@gmail.com

