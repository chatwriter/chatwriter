# Chatwriter
Simultaneous messenger / word processor

## Features

### Rapid Composition
Sharing thoughts a sentence at a time makes it possible to update common information about what is believed, or not believed, on various topics. 

This application is designed to update collections of common information in both dialogue and document form in real time, so that documents can be drafted at the speed their subject matter can be discussed. 

### Rationalism
Discussion is good for producing ever-clearer indications about what all is believed or not believed about topics both general and specific. This is done when we build on or justify our beliefs in response to the input of others, or ask questions that suggest further complexities to a topic. 

This software enables one to encode such forms of interaction, so that discussing a point automatically develops paragraphs out of the exchange, and the act of questioning lends structure to the store of common information.

### Non-conflicting Collaboration
Paragraphs can communicate differing viewpoints while falling under the same topic. It should therefore be possible to share a common  document outline, while at the same time reserving the right to include paragraphs one believes and exclude paragraphs one does not.



### Rationalism


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
