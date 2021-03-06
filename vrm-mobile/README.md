# OBK Volunteer Relationship Management - Mobile app

## OBK
A non-profit organisation providing food and services for the community.
They rely basically on volunteers to get things done, thus having a
VRMS (Volunteer Relationship Management System) is essential for their operations.

Visit www.obk.org.au to know more about them.

## Short History
This product started with a prototype using Swift for the mobile app, Ruby on Rails (API mode) for the back-end,
Angular 2 for the back office web app, and PostgreSql.

Then at an RHoK (Random Acts of Kindness) hackathon we've got a huge help from UX Designers, a Product Manager,
a Customer Experience expert, a Growth hacker, and defined much of the product and user requirements.

We decided to use React Native for the mobile app, React for the back office web app, and Firebase for the back-end.

This repo is only for the React Native mobile app.

## Get up and going

* Install XCode if you haven't
* `Run npm install`
* `npm install react-native-cli -g`
* Download Facebook SDK, and move to ~/Documents/FacebookSDK (download from https://developers.facebook.com/docs/ios/getting-started/)
* Check the version of the react-native-fdsdk npm package, (you may have to switch to 0.6.0 from 0.6.3)
* run React-native link
* May have to run `npm start -- --reset-cache`
* Check whether react packager has opened a terminal window; you have have to restart this at various stages to ensure it gets cleared.
* `react-native run-ios`

(This was working from node version 8.6, on npm v5.3)
