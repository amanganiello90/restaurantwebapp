
# Angular 5 Restaurant Web App

<img src="https://img.shields.io/github/stars/amanganiello90/restaurantwebapp.svg">&nbsp;<a href="https://github.com/amanganiello90/restaurantwebapp/issues"><img src="https://img.shields.io/github/issues/amanganiello90/restaurantwebapp.svg"></a>&nbsp; [![Join the chat at https://gitter.im/restaurantwebapp/Lobby](https://badges.gitter.im/restaurantwebapp/Lobby.svg)](https://gitter.im/restaurantwebapp/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) 

You can also view the **ionic app** version on [ionic restaurant app](https://github.com/amanganiello90/ionic3restaurantapp).
There are **two different Angular 5 app** with the same structure: a project for **an admin dashboard** and another for **a web app site**.

## Dashboard App

**For a demo of the dashboard send an email:** angelo.mang@libero.it


|:------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------|

##  Web App Site
**For a demo of the web app send an email:** angelo.mang@libero.it


|:------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------|



|For a donation | [![](https://www.paypal.com/en_US/IT/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=XTC895QYD28TC) |
|:------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------|


Overview
========

Specifically, your pack consists of the following four
directories:

    * [project]
      Includes an Angular project. This is the project
      that is suggested to be used for development.
    * [license]
      Includes the License information and references to
      third-party licenses.
	* [documentation]
      Includes the documentation html page.
      
Firebase integration
========
Every App uses firebase backend. Therefore, you have to register on [firebase](https://firebase.google.com/).
There is a realtime db and api. The app use a json file as db that you can retrieve from firebase with a get call specifying https://[PROJECT_ID].firebaseio.com/.json , where PROJECT_ID is the id assigned when you create a project on firebase.
See [here](https://dev.to/aurelkurtula/introduction-to-firebases-real-time-database-89l) specially to set db rules in order to read and write on db with api.

Brief installation guide
------------------------

REQUIREMENT
========
* npm (installed with nodeJS) --> https://nodejs.org


STEPS TO USE
========
* enter in the project folder
* npm install
* Then ```npm start``` to view on your local browser the app
* If you want to only build in Angular dev mode and generate the app in dist folder ```npm run build.dev```
* If you want to only build in Angular prod mode and generate the app in dist folder ```npm run build.prod```
* After build you can host your app in firebase with [firebase cli](https://firebase.google.com/docs/hosting/). Remember to select hosting option and single page app type.


Problems/Questions
--------
If you experience any problem, please post a message to my email below and submit your question:
*angelo.mang@libero.it*
