# 100 Days Of Code - Log

### Day 0: March 4, 2019
##### (Start of Flutter Project - worked on navigation between pages)

**Today's Progress**: Added navigation between two pages.

**Thoughts:** Learned how to add navigation between pages with Flutter using the Navigator and push/popping screens from the stack. Also learned to use the SizedBoxwidget to ensure a widget fills the entire width of a screen.

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground)

### Day 1: March 5, 2019
##### (Started on TensorFlow.js Project)

**Today's Progress**: Started on TensorFlow.js Project

**Thoughts:** Learned how to load a pretrained Keras model into a JavaScript file using TensorFlow.js. 

**Link to work:** [No Link Yet]()

### Day 2: March 6, 2019
##### (Continued on TensorFlow.js Project)

**Today's Progress**: Continued on TensorFlow.js Project. Ran data through the model.

**Thoughts:** Learned how to run a array throught the TensorFlow model using the tf.predict method. Needed to create a proper sized tensor to allow the data to be used in the method. Interesting how JavaScript arrays are typically rowsxcolumns and creating tensors can change all of it.

**Link to work:** [No Link Yet]()

### Day 3: March 7, 2019
##### (Continued on Flutter Project - continued on passing info between pages)

**Today's Progress**: Passing info between pages.

**Thoughts:** Learned how to move data between two pages using than syntax (similar to promises in JavaScript.

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground)


### Day 4: March 8, 2019
##### (Continued on TensorFlow.js Project)

**Today's Progress**: Refactored the array that I was using for the tf.predict method to be a tensor. Also tested out the model using an tensor consisting of all 1's. Worked on the JavaScript to collect data for the model.

**Thoughts:** I have a better understanding of tensors and with the most recent TensorFlow Dev Summit, having been able to get a better idea of how TensorFlow.js fits into the entire ecosystem.

**Link to work:** [No Link Yet]()


### Day 5: March 9, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Added the Product Image to the Product Details page. Learned how to overide the back buttons on the Product's Page. Added a login screen to the app, and used the Navigator push_replacement method to remove the login screen from the stack. 

**Thoughts:** Learned more screen control and app flow code today. 

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground)

### Day 6: March 10, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Learned about and added a Hero Animation. Refactored the Add Image button to a FAB. Started to figure out animations and planning ahead for animations on the product details page. 

**Thoughts:** Learned a bit about animations today - need to learn more tomorrow

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground)

### Day 7: March 11, 2019
##### (Day Off - Wife's Birthday and we got a new puppy.)

** Day Off

### Day 7: March 12, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Added username and password fields to the app. Used the ObscureField property of the TextField to create a password field. Still need to figure out how to add the password lock icon beside the password field without the row blowing up. 

**Thoughts:** Need to dig deeper in how to manage width of widgets in a row.

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground)


### Day 8: March 13, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Fixed issues with the row blowing up and added the password visibility button with full functionality for it on the login screen. 

**Thoughts:** The row widget in Flutter evaluates all of it's children to determine who fits where. By wrapping any variable sized elements in a Expanded Widget they are forced to take on the available space only and not cause the row to blow-up.

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground)


### Day 9: March 14, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Added a navigation drawer, added another Hero image and integrated Firebase in the iOS app. 

**Thoughts:** Learned that the Navigator.pushReplacement method to change screens does not support Hero animations. Also learned how to add Firebase Integration to an iOS app in Flutter. 

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground)

### Day 10: March 15, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Started to integrate Firebase Analytics into Flutter. Followed the instructions, but ran into issue somewhere along the line since nothing is showing up yet. 

**Thoughts:** The Firebase docs for Flutter can somewhat difficult to follow. One pitfall of using a cross-platform development platform like Flutter is that sometimes you need to know a bit of the underlying platform. 

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground)

### Day 11: March 16, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Continued to work with Firebase Analytics. Analytics appears if I build the project in XCode, although it is still wonky. Learning a bunch about packages in Flutter. Next steps -> rebuild the project from scratch since I probably messed up some config file. I will copy over my existing code to the new project.  

**Thoughts:** The Firebase docs for Flutter can somewhat difficult to follow. One pitfall of using a cross-platform development platform like Flutter is that sometimes you need to know a bit of the underlying platform. 

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground)


### Day 12: March 17, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Started a new Flutter project with Firebase analytics added, and then added all of my screens and custom files. This made all of the project config work and Firebase analytics works well. Started a new git repo for the project.  

**Thoughts:** Sometimes it is worth restarting with a new project if config settings get messed up - especially if you have the luxury of doing so. I am learning well how Flutter's package system works.

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground_v2)


### Day 13: March 18, 2019
##### (Day off since I presented on TensorFlow to 25 people at the Detroit Google Developers group)

**Link to work:** [TensorFlow Dev Summit Recap for the Detroit Google Developers Group](https://www.meetup.com/Detroit-Google-Developers-Group/events/259505517/Flutter Playground](https://github.com/donwardpeng/Flutter_Playground_v2)


### Day 14: March 18, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Added a connection to a Firebase Cloud Firestore database. Able to read image data into a Map from a Collection in Firestore. Next steps, use the image data in the app to load images.

**Thoughts:** I have been playing around Cloud Firestore for a few projects and am starting to develop a pattern of creating helper classes with static methods to return Collection data from the database. I need to look around and see if there is a best practice for this.

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground_v2)

### Day 15: March 19, 2019
##### (Day off - planning for an developer software conference)


### Day 15: March 20, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Still working on reading image data from Google Cloud Firestore database and displaying it in an image. Also learned quite a bit about StreamBuilder and streams for a project at work today. I want to incorporate them into this project soon. 

**Thoughts:** Been playing around with setState as well as StreamBuilders in Flutter. Need to do more research into how Streams can be used to communicate events within a Flutter app. 

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground_v2)

### Day 15: March 21, 2019
##### (Day Off)

### Day 16: March 22, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Added Firebase Push Notifications and tested the basic mechanism. Got the images to load over the network from Cloud Firestore. Started to implement the BLOC pattern. Next steps -> wiring up the Push Notifications to an action and implementing a StreamBuilder. 

**Thoughts:** Still research and working on Streams and StreamBuilders. Surprised how easy it was to add Firebase Push Notifications to the app.

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground_v2)

### Day 16: March 23, 2019
##### (Day Off - Sick)

### Day 17: March 24, 2019
##### (Continued on Flutter Project)

**Today's Progress**: Added Android Firebase push notifications and it was working. Tested out Android Studio - too much going on for right now - switched back to VS Code. Unfortunately I also broke the build of the push notifications on my Android phone due to a class loader issue with Firebase.  

**Thoughts:** Not much progress today, although I did learn more about Android and iOS push notifications and how to configure them. Broke some stuff, and also learned that Android Studio is complex. Switched bak to VSCode for now.

**Link to work:** [Flutter Playground](https://github.com/donwardpeng/Flutter_Playground_v2)

### Day 18: March 25, 2019
##### (Started a new Flutter Project)

**Today's Progress**: Restarted the project from scratch - imported all of the Firebase libraries I needed and scaffolded in the login page and main page. The reason - to fix the issues I had with Firebase Push Notifications earlier on Android. 

**Thoughts:** Need to determine what Firebase libraries have issues with the AndroidX project - most notably, Firebase Auth and ML Kit would not bring down their libraries due to warning about AndroidX.
 
**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 19: March 26, 2019
##### (Started a new Flutter Project)

**Today's Progress**: Finally got push notifications to work on a device in Android - was not using the correct AndroidManifest settings for Flutter push. Also I now better understand Streams/Sinks and the BLoC pattern for apps. Next steps, I will start using it instead of setState() where it makes sense.

**Thoughts:** Streams/Sinks and using StreamBuilder seems like a much cleaner to force updates to the UI when needed. This video by Paolo Soares from Google on the BLoC pattern helped quite a bit: https://youtu.be/PLHln7wHgPE
 
**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 20: March 27, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added a primitive StreamBuilder. Started on a BLoC controller but it does not fully work yet. Combining the BLoC pattern with Streams and Sinks is taking a bit to learn. 

**Thoughts:** I made some more progress understanding Reactive Programming today. Dart's method of doing this is with Streams and Sinks, whereas it appears traditional Reactive Programming uses Observables and Subjects. Ran into a few examples online where they start by explaining Streams and Sinks, but mix in Reative Programming terminolgy. Still working to sort it all out - understanding this is important.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 21: March 28, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Today I fully implemented the BLoC pattern based on code from here: https://www.didierboelens.com/2018/08/reactive-programming---streams---bloc/. Additionally I totally understand how the Streams are setup, and commented it fully to re-inforce my learning. Next steps, adapt it to controlling the UI in my app. 

**Thoughts:** Finally understand how the BLoC pattern can be implemetned with streams/sinks. To re-inforce my learning, I fully commented the code I grabbed this from.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 22: March 29, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added Firebase Authenication to the project. Had to resolve all of the AndroidX issues with the Firebase Authenication Flutter plugin - this required the use of Android Studio (not sure if VS Code can do this). Brought in the Firebase Auth example login page and started hooking up Google, Facebook and Phone Number Auth. Google works, Facebook and Phone Number not yet.

**Thoughts:** Based on the dependency issues I ran into today with AndroidX and Firebase Auth for Flutter I think using Android Studio for developing Flutter apps that leverage Firebase services is the best (perhaps only) way. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 22.5: March 30, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Only worked on the project 1/2 hour today due to travel from a conference. Changed the Textfield inputs being used for Username and Password to TextFormField inputs. They function much better - need to add a validator to the Password and Username fields still. 

**Thoughts:** I like the way the TextFormField works better than rolling my Textfield inputs - especially for the Password input fields. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 23: March 31, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added Sign in with Google and Sign in with Facebook buttons from a plugin in the Flutter repo. Moved the Login with Uername/Password to a new page, and hooked up the Sign in with Google so that it works on Android. Still need to get iOS working with Sign in with Google. Facebook needs to work with both.
 
**Thoughts:** Super impressed with how easy it was to bring in the Sign in with Google/Facebook/Twitter buttons via a plugin. This is the way code should be. The plugin can be found here -> https://pub.dartlang.org/packages/flutter_auth_buttons#-readme-tab

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 24: April 1, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Got iOS Google login to work. Now both Android and iOS work for Google login. Almost have email/password login working.

**Thoughts:**: Continuing to get Auth working - I like how all of the authenication methods use the same basic mechanism - makes it easy to code them to work.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 25: April 2, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Completed Email/Password login. Started research on Facebook login integration - this is not as straightforward as I would have thought. 

**Thoughts:**: I learned that a TextController needs to live inside of a Stateful Widget if you wish to read out it's text value. Additionally, there does not seem to be good documentation on Facebook login integration with Firebase and Flutter. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 25: April 3, 2019
##### Took a day off

### Day 26: April 4, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Wired up the login by email and by Google screens to the rest of the app. Working on a snackbar to display on either successful or unsuccessful login. Implemented TextFormField change and focus listeners for the password field.

**Thoughts:**: Started to learn about Snackbar's and listeners. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 26: April 5, 2019
##### Took a day off to chase my kids and dog around the yard in the nice weather.

### Day 27: April 6, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Finished off email/password login fully with error handling. Added success and failure snackbars. Read up on how to use async/await keywords for Futures and how to deal with error catching from Futures.
 
**Thoughts:**: Learned more Futures in Dart. Also learned that handling user authenication and all of the error codes that can be return is a can of worms.
 
**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 28: April 7, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Finished off Google sign in. Changed the FAB to a inset in a Bottom App Bar. Started hooking up to data in the Cloud Firestore. 

**Thoughts:**: Alot of clean up today. Switched back to VS Code from Android Studio. It seems easier and quicker to use. 
 
**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 29: April 8, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Messed around with the Bottom Action Bar. Added an Alarm Model and started on a Helper Class to retrieve the values out of Firebase CloudStore. Still needs more work.
 
**Thoughts:**: Pulled in a LatLng library today since I needed to store location in the app. There seems to be a pretty rich library of Flutter plugins for things like this. I need to poke around and look at what is available some more.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 30: April 9, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added an update from Cloud Firestore
 of the data I need. Cleaned up some code with the main page.

**Thoughts:**: Ran into an issue with pulling location data from Cloud Firestore - turns out Firestore has it's own GeoPoint type in it's plugin.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 31: April 10, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added and tested that the collections I am reading from Cloud Firestore are dynamic. Next steps, need to write to Cloud Firestore.

**Thoughts:**: It is like magic, you create a ListView that has a StreamBuilder hooked into a Collection in Cloud Firestore, and as soon as the Collection changes in Cloud Firestore, the ListView updates. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 32: April 11, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Detour today -> Started a quick comparison between Flutter and React Native. Started a React Native app and followed the Quick Start. Had to brush up on React a bit (not too much).

**Thoughts:** I can see some similarities between the syntax of React Native and Flutter although I still think the engine that powers the app under the covers in Flutter is better. 

**Link to work:** [React_Native_Playground](https://github.com/donwardpeng/react_native_playground)

### Day 32: April 12, 2019
##### (Day off)

### Day 33: April 13, 2019
##### (React and ReactNative learning)

**Today's Progress**: Detour continued: Undertook a refresher/crash course on JavaScript ES2015 and React to better understand how ReactNative works. One more day of working with React and I will have a better idea of how ReactNative works. 

**Thoughts:** I continue to see similarities in the syntax of ReactNative and Flutter although Dart/Flutter seems much cleaner to me, coming from a mobile background. ReactNative must feel like home for web developers, although coming from a mobile development background, Flutter seems like an easier framework to pickup.

**Link to work:** [React_Playground](https://github.com/donwardpeng/react_playground)

### Day 34: April 14, 2019
##### (React and ReactNative learning)

**Today's Progress**: Detour continued: Continued to brush up on React - in particular props, state and components (basically it all).
 
**Thoughts:** Too early for me to tell, but it definitely seems like the syntax in React is much more verbose than what I see in Dart. 
 
**Link to work:** [React_Playground](https://github.com/donwardpeng/react_playground)

### Day 34: April 15, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Day off 

### Day 35: April 16, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Improving the styling of the login screen. Played with background images, fonts, alpha and box decorations. 

**Thoughts**: Following a tutorial on Medium on Flutter app development. It has some good info, although the way they have architected their code, shows that they come from a web background :)  

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 36: April 17, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Worked on the listview for the main page again - still trying to figure out how to get a GeoPoint out of a Firestore document object"

**Thoughts**: Working through the various options to put together a dynamic ListView. There are definitely a lot of combinations - glad to see that ListViews work as expected - not as they did in the early days of Android where one had to manage recycling of views and viewholders. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 37: April 18, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Needed to switch to some TensorFlow work today - study and working on CNN's and RNN's for some upcoming work I may have. 

**Thoughts**: Long term goal of mixing in a Machine Learning model I train with my Flutter project.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 38: April 19, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Continued on TensorFlow work today. Working through CNN's, as well as reviewed the various activations (signmoid, tanh, relu and softmax) out there. 

**Thoughts**: I read that Firebase MLKit is in progress for Flutter - sweet! 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 39: April 20, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Working to research more Firebase and Flutter integrations I can add to the project. Definitely want to add A/B testing and Remote Config. Started to research and etch in MLKit support also. 

**Thoughts**: Super excited that someone started a MLKit library for Flutter.
 
**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 40: April 21, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added global state to maintain users that are logged in and whether the app is loading up or not. Still need to debug it still. 

**Thoughts**: Needed to go back and maintain state for login, etc. Need to learn more about the InheritedWidget still.  

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 40: April 22, 2019
##### Day off
 
### Day 41: April 23, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added logout and login with Google - still need to fix some Snackbar's to indicate successful login 

**Thoughts**: Almost there with the login/logout functionality - having a global state object is helping.
 
**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 42: April 24, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Debugged some issues with Login, and rendering the login screens. Added an Alarm Card Widget for the Listview and also added more fields to the Alarm model. 

**Thoughts**: Learned about RawMaterialButtons, BoxedConstraints and the AspectRatio widget. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 42: April 25, 2019
##### Day Off - Sick

### Day 42: April 26, 2019
##### Day Off - Sick
 
### Day 42: April 27, 2019
##### Day Off - Sick
 
### Day 43: April 28, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Wired up some mock data to the AlarmList and added some styling. Still need to work out some of the functionality. 

**Thoughts**: Today I learned more on Themes, Colors, and Fonts. Additionally, I dug into variations of the arrow operator for iterating over lists, and returning values. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 44: April 29, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Upgraded Flutter, had to fix CocoaPods. Added some more styling and an empty list message. 

**Thoughts**: Learned a bunch about CocoaPod dependencies today as it seemed the Flutter upgrade broke many of them for the project. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 45: April 30, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Challenged myself to see how fast I could add a full screen dialog when the Add Alarm button was pressed - 25 minutes to research it and get it all functional. 

**Thoughts**: I love the fact that only one flag is needed when pushing a new screen onto the stack to cause it to become a full screen dialog. This seems like a great solution. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 46: May 1, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added the proper schema for alarms to the Cloud Firestore dB and added some data to it. Was able to remove all of the mocks I had and read from it to the main list. Next steps - get the add alarm button wired up.
 
**Thoughts**: Dug further into Cloud Firestore - ran into a classic chicken/egg problem of -> do I write a script to populate data in it, or just manually do it. I chose the latter since it seems faster, although writing a script could be worth it in the future. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 47: May 2, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Finished the code to successfully write alarms to Cloud Firestore. Also am able to read them back into the main list. Need to fix the loading of images since it is throwing a silent exception. 
 
**Thoughts**: I could not find an eloquent way to handle null values used in optional named parameters for Constructors. I ended up using default values instead, but would rather have some sort of assertion in place instead of relying on default values. Especially for things like the id of an item.  

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 48: May 3, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Refactoring, refactoring and more refactoring. 

**Thoughts**: Sometimes you have to step back and rip a bunch a stuff apart, tidy it up and refactor a bunch before moving forward with new features.
 
**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 49: May 4, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Learned about Firebase Remote Config and started adding it to the codebase. Ran into issues working with Futures. 

**Thoughts**: Need to dig into how to create functions that use the async/await keyword when they need to return something. Still wrapping my head around Futures in Dart.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 50: May 5, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Understand and implemented Firebase Remote Config. Also got the new Flutter DevTools running from the CLI (this is new with Flutter 1.2). 

**Thoughts**: Initially I tried to get the theming to change based on Flutter Remote Config, but determined that it's purpose does not appear to be for app wide theming. I got it working reading simple string values to change the colors of buttons as a first attempt.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

