# Building_blocks_mobile

Building Blocks Mobile App is the last project for CraftAcademy Cohort (Feb-April 2017). This is the app for housing societies that will allow tenants to send help message request, book a facility using their mobile phone, be updated with the latest events/news in their community.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for deployment and testing purposes.  See deployment for notes on how to deploy the project on a live system.

In order to organize the features needed for our project and track our progress, we used different tools such as:

**Pivotal Tracker**
[Pivotal Tracker for Building blocks](https://www.pivotaltracker.com/n/projects/2007795).

**GitHub**
[GitHub Pages](https://github.com/CraftAcademy/building_blocks_mobile).

###Ionic
The Ionic Framework command line utility makes it easy to start, build, run, and emulate Ionic apps. In addition, it comes with (optional!) integration with the Ionic Cloud, a set of mobile backend services perfect for Ionic apps.

###Cordova


###Installing
Install the latest Cordova and Ionic command-line tools
```
$ npm install -g cordova ionic
```
iOS development requires iOS simulator which you can install with
```
$ npm -g install ios-sim
```
Initiate your app (scaffold new Ionic tabs application)
```
$ ionic start building_blocks_mobile tabs
```
Once that is complete, run the following commands to add support for iOS and Android
```
$ cd bmi_calculator
$ ionic platform add ios
$ ionic platform add android
```
###Run the application
In your terminal run the following command to start a local server and run the application
```
$ ionic serve -c --lab
```
## Deployment
* [Heroku](https://building-blockz.herokuapp.com/) - to deploy, manage, and scale modern apps
* [Semaphore](https://semaphoreci.com/craftacademy/building_blocks_back_end) - for  continuous integration
