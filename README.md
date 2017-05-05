# Building_blocks_mobile

Building Blocks Mobile App is the last project for CraftAcademy Cohort (Feb-April 2017). This is the app for housing community that will allow tenants to send help message request, book a facility using their mobile phone, be updated with the latest events/news in their community.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for deployment and testing purposes.  See deployment for notes on how to deploy the project on a live system.

In order to organize the features needed for our project and track our progress, we used different tools such as:

**Pivotal Tracker**
[Pivotal Tracker for Building blocks](https://www.pivotaltracker.com/n/projects/2007795).

**GitHub**
[GitHub Pages](https://github.com/CraftAcademy/building_blocks_mobile).

### Ionic
The Ionic Framework command line utility makes it easy to start, build, run, and emulate Ionic apps. In addition, it comes with (optional!) integration with the Ionic Cloud, a set of mobile backend services perfect for Ionic apps.

### Installing
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
$ cd building_blocks_mobile
$ ionic platform add ios
$ ionic platform add android
```
### Run the application
In your terminal run the following command to start a local server and run the application
```
$ ionic serve -c --lab
```
## Running the test

### Create user account
In order to use the app, the tenant must register and login.

#### Registration form:

<br>
<img height="550" width="700" src = "https://github.com/jocontreras/building_blocks_mobile/blob/update_readme/www/img/registration.png" />
<br>

#### Login form:

<br>
<img height="550" width="700" src = "https://github.com/jocontreras/building_blocks_mobile/blob/update_readme/www/img/signin.png" />
<br>

### Send Help Request message
This is the tab where the tenant can write and send the help request message to the administrator of the building.

<br>
<img height="550" width="700" src = "https://github.com/jocontreras/building_blocks_mobile/blob/update_readme/www/img/message_request.png" />
<br>

### List of Facilities
This is the tab where tenants can find the facilities available in their building/community

<br>
<img height="550" width="700" src = "https://github.com/jocontreras/building_blocks_mobile/blob/update_readme/www/img/facilities.png" />
<br>

### Book a facility
This is where the tenants can check and book facilities

<br>
<img height="550" width="700" src = "https://github.com/jocontreras/building_blocks_mobile/blob/update_readme/www/img/booking.png" />
<br>

View of facilities availability

<br>
<img height="550" width="700" src = "https://github.com/jocontreras/building_blocks_mobile/blob/update_readme/www/img/booked.png" />
<br>


## Authors
**Casper Jureskog** - https://github.com/casperjureskog <br>
**Fabian Lundgren** - https://github.com/fabianlundgren<br>
**Felix Fottander** - https://github.com/fottander<br>
**Jennifer Contreras** - https://github.com/jocontreras<br>
**Johan Schantz** - https://github.com/Scharrre97<br>

## Acknowledgments

Special thanks to our dear coaches:
* Amber Wilkie
* Thomas Ochman
* Raoul Diffou
* Sigu Magwa
