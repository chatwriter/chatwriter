# Chatwriter
Messaging / Word Processing System
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* [Nodejs](https://nodejs.org/en/) 
* [npm](https://www.npmjs.com/)

### Installing

Navigate to the project root and run the following command:

```bash
$ npm install
```

This will install all the necessary dependencies.

### Connecting to Firebase

Before you run, you'll need to set up your app's config to point to your firebase database.

* Go to [https://firebase.google.com/]() and set up a new account.
* In the Firebase Console, select "+ Add Project" to start a new project. Name it whatever you want.
* Once initialized, select "Add Firebase to your web app" on the Overview screen. A modal window will pop up that will look similar to this:
```
<script src="https://www.gstatic.com/firebasejs/4.13.0/firebase.js"></script>
<script>
  // Initialize Firebase
  var config = {
    apiKey: "AIzaSyBW2r_pSexU68jEfOZcsocktri9lLtPx2A",
    authDomain: "notional-test.firebaseapp.com",
    databaseURL: "https://notional-test.firebaseio.com",
    projectId: "notional-test",
    storageBucket: "notional-test.appspot.com",
    messagingSenderId: "779981740057"
  };
  firebase.initializeApp(config);
</script>
```
* Copy the 6 lines inside `var config = { ... };` and paste then in the `config/development.json` file in this project.
* Remember to wrap the key values in double-quotes
* Your project will now link to your firebase account.

### Running

After installing and linking to Firebase, type this into a terminal: 

```bash
$ npm start
```

When the application finishes initializing, open up a browser and navigate to [http://localhost:3000]()

## API Documentation

[Api documentation can be found here](docs/README.md)

***
