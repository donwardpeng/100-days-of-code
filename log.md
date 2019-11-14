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

### Day 51: May 6, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Messed around with themes and navigation via named routes. Still need to determine more on Firebase Remote Config. 

**Thoughts**: Went down a bit of a rabbit hole today trying to get Firebase Remote Config to work with theming. Going to spend one more day on it before moving to a new topic. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 52: May 7, 2019
##### (Google I/O - took the day off from coding to learn a ton on Flutter)

### Day 52: May 8, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Flutter DevTools now run in VSCode for me - immensely helpful. Also dug into the Inherited Widget today. 

**Thoughts**: Was excited about the addition to MLKit of Google Translate. Thought I would try it out but quickly realized that it is only supported natively for the moment (to be fair it was announced yesterday). It would be great to be able to run translation services right on device - incredibly powerful. 
 
**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 53: May 9, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Mostly research today into the Element Tree, Widget Tree and Render Tree. Additionally I dug into how InheritedWidget works.

**Thoughts**: The Element Tree, Widget Tree and Render Tree do not seem to be covered in many of the intro tutorials to Flutter, but from I now understand, they are important to understand to understand some of the nuisances of the UI (like the need for keys).

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 54: May 10, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Started on RemoteConfig and setting the theme by calling RemoteConfig before runApp is called in main(). Also looked into InheritedWidget more - I am fairly certain that another pattern I got from a blog posting is exactly the implementation of an InheritedWidget with just another name.

**Thoughts**: Watched a ton of video's on various Widgets, and the Wdiget Tree, Element Tree and Render Tree. I totally understand them now - this video was a huge help -> https://www.youtube.com/watch?v=dkyY9WCGMi0&t=7s" 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 55: May 11, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Very close on setting the theme via RemoteConfig - just need to figure out how to trigger the fetch of the Remote Config data. 

**Thoughts**: I think I figured out a way to wrap the widget that RunApp needs returned in a FutureBuilder to allow for RemoteConfig to be setup first thing on app run. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 55: May 12, 2019
##### Mother's Day - I took it off

### Day 56: May 13, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Finished the code to call remote config on app start. Still need some debugging.' 

**Thoughts**: Got some good experience with the debugger today as I needed to sort through a rather long stack trace to fix a bug in my remote config code. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 57: May 14, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Debugged Remote Config - got it working. Needed to push the publish button in the Firebase Console to get it to work - duh! Also refactored some code and added a Snackbar to the add alarm screen. Still need to debug it. 

**Thoughts**: A wish list item -> more Flutter/Firebase Remote Config examples would be great in the git repo. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 58: May 15, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Taught a course on Flutter and Firebase to the Windsor GDG group - 38 people tonight.  

**Thoughts**: Interesting how everyone asks if Flutter is a thing - I think that depends on the community uptake and adoption of it. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 59: May 16, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Success! Achieving my goal all along with Remote Config - updating theming from the Remote Config values. 

**Thoughts**: This whole exercise of trying to change the theme of the app based on a Firebase Remote Config values has led me down some rabbit holes teaching me about the Widget, Element, and Render trees as well giving me more experience with Future's and async functions in Flutter. Well worth the effort when I look back on it all.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 60: May 17, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Reconsidered the functionality of the app now that I have all of the functional pieces together. Going to modify the bottom action nav bar to accomodate my new design. 

**Thoughts**: As I get further into Flutter I am continually impressed with the flexibility to quickly change the UI, as well as the myriad of cool things that others have built to create slick, responsive UI's.

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 60: May 18, 2019
##### (Day Off)

### Day 61: May 19, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Started working on an animated bottom app bar - needed to pick up animations first although. 

**Thoughts**: In all of my work to pick up and learn Flutter and Firebase I overlooked animations. This seems like a great intro to them -> https://medium.com/flutter-io/zero-to-one-with-flutter-43b13fd7b354

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 61: May 20, 2019
##### (Day Off - Sick)


### Day 62: May 21, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Took a detour - Decided to look into a Flutter Web App. Started modifying the Hello World app. 

**Thoughts**: I wonder how much of the standard Flutter widgets are ready for web. According to the site it is not production ready, but I have to imagine for a simple site it could be ok. 

**Link to work:** [My Snooze App](https://github.com/donwardpeng/Flutter_Playground_v2://github.com/donwardpeng/mysnooze)

### Day 63: May 22, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Got a early version of the Michigan GDG DevFest Conference site started in Flutter for Web. Figured out the dependencies, and how assets work. 

**Thoughts**: This was pretty cool - once I got all of the dependencies in place and read the short migration plan to migrate a mobile app Flutter project to a web project, it felt like I was doing normal Flutter development. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 64: May 23, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added a photo carousel to the Flutter Web app. I adapted a lot of code from one of the example Flutter apps for Web.

**Thoughts**: Still getting a feel for how screen real estate translates on Flutter for Web between what I know on mobile. Additionally, if this project were to be adopted for other uses, I need to figure out how to store string resources in Flutter. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 65: May 24, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Fiddled with the image carousel. Ran into a problem where the webdev would not autoload anymore and had to debug in - flutter clean fixed the issue. 

**Thoughts**: Spent 10-15 minutes debugging why the website in dev was showing up as a blank screen. I experienced this once or twice with mobile development where somehow the hot reload messes up the build and 'flutter clean' is all that seems to fix the project.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 65: May 25, 2019
##### (Took a family day)


### Day 66: May 26, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Dived into creating a string resource file and trying to get localization working - tried one library - https://pub.dev/packages/gen_lang#-readme-tab- but it does not seem to work with Flutter for Web yet. I ended up rolling my own json file with strings that I decode and use per page in the app. 

**Thoughts**: Still looking into localization for a Flutter project - the solution provided in the Flutter documentation seems super complicated. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 67: May 27, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Tried to use a FutureBuilder to read in the JSON string resource values. I understand how to use the FutureBuilder, unfortunately I have it performing an infinite update on the UI - need to fix this."
 
**Thoughts**: Flutter supports reactive programming in a lot of ways - determining wich one is needed when sometimes trips me up. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 68: May 28, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added strings, a bottom app bar and cleaned up the main page design a bit.
 
**Thoughts**: Goal - have the DevFest site finished and up and production ready by the end of the week - I have high confidence I can make this happen. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 69: May 29, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Continued to stylize the main page of the site. Also tried to get a new web page to open, and unexpectedly ran into issues since this does not seem to be supported yet in Flutter Web. 

**Thoughts**: Still on track for my goal, although I still need to figure out how to open an existing URL from a button click on the page. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 70: May 30, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: A bit more style - most of the time spent trying to get an external site to open in a browser window from a Flutter button. I know what does not work - I think dart:html may hold the answer. 

**Thoughts**: I searched quite a bit of documentation, StackOverflow answers and Flutter Web repo's to figure this problem out - I am resolved to try to get something put together, it might not be a conventional solution.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 71: June 1, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Finally got the Call for Papers button working to open a site.I used the dart:html window.open method to open it. Also I re-organized the project and added a Team button.

**Thoughts**: Need to fix an issue with loading the Team page, and build the site for Firebase hosting.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 72: June 2, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Got the teams page working with cardviews with an image and name for each member of the team. Still need to figure out how to get the back button in the browser to work on the teams page. 

**Thoughts**: Got the page hosted in Firebase hosting - learned how to build it and deploy it to prod. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 73: June 3, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Made the app responsive with Large and Small screen size support using MediaQuery. 

**Thoughts**: Using MediaQuery I can definitely see how to support phone, tablet and web all from one code base that accounts for the different designs/layouts that make sense for each. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 73: June 4, 2019
##### Took a day off since I hosted a User Group meeting on TensorFlow
 
### Day 74: June 5, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added the Flutter widget, cleaned up the main page and added social media buttons to the teams page. Lastly, the page went live in production today at https://www.michigandevfest.com/#/. 

**Thoughts**: It is interesting (and useful) that there is a Flutter logo widget in the Flutter framework. This is the first time I have ever seen a UI element to display the frameworks logo as part of the framework.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 75: June 6, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added flipping cards for the team page, and scaffolded out a generic card for a person. This can be used for speakers in the future. 

**Thoughts**: Supporting a small/large screen layout seems the way to go for Flutter Web.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 76: June 7, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Cleaned up project files, added app wide state and fixed the buttons for navigation so they do not double up on themselves. Also got a dev hosting site set up in Firebase to test stuff out before going to prod.

**Thoughts**: Timely find - it looks like the Flutter team recently released an example project showing how to parse JSON. This will be a huge help as I make the site configurable from JSON files.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 77: June 9, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Started looking into JSON conversion and porting over the project Hoverboard JSON config file. 

**Thoughts**: I have been thinking about how to structure the data for configuring the website to be used by other conference organizers and came to the realization that other organizers have used project Hoverboard's config and are used to it. To make it easy for them and to have a chance at some adoption - I am going to use the same config structure. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 78: June 10, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Settled on one font for the site, cleaned up more of the content and layout and refactored some of the classes. 

**Thoughts**: I started to look at the Hoverboard project and need to dig in further to see if I can figure out how to host the config in Firebase Firestore from the Flutter for Web app. This support would make the project truly reusable by others. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 79: June 12, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Explored various possibilities to get Cloud Firestore working in Flutter for Web. Since the Flutter plugin system is not yet working for Flutter for Web, I can not use the Flutter Firebase plugin. I tried using the dart:js library but it seemed to tedious. Trying out the Dart Firebase project now, and I am pretty close to use it.
 
**Thoughts**: If this works, I may be the only one doing this since I have yet to see any other examples or codebases using this technique as an interim measure. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 80: June 13, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Continued to work on adding the Firebase and Cloud Firestore dart libraries. Also looked into adding an appbar sliver to the footer. Looking to get a pattern established for all of the data read in and the speakers, sponsors and other pages to use. 

**Thoughts**: I may need to shelf the work on the Firebase integration for a few days so I can dig really deep on it. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 81: June 15, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Started parsing JSON to bring in data. Going to use this approach so I am prepared for when we need to add speakers and sponsors. I will tackle the problem of Firebase sync later. 
**Thoughts**: For some reason I have a huge stack trace of errors when I bring in the firestore.dart imports - need to take a good 1-2 hours and debug what is going on. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 82: June 16, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Looked at Json parsing for Flutter - looked into dart:convert and json_serializable. Started to code using json_serializable. Since I am using existing Json from the site we used last year, I had to figure out how to handle a Json file that starts with an unnamed array. Still working on it.
 
**Thoughts**: Interesting that Flutter can not use runtime reflection to determine Json structure like in GSON and Jackson. Thus the need for a bit more coding using dart:convert or json_serializable. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 83: June 17, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Implement Json_Serializable for the organizing team Json file. Learned a lot about Darts build_runner, the Json_Serializable class, Json Annotations and the factory constuctor.  

**Thoughts**: When I get a chance I need to read the Effective Dart guide - this will help me learn all the nuances of the language and better understand how the source code in Flutter is written. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 84: June 19, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Still working on parsing Json and making the necessary http requests. 

**Thoughts**: There are alot of examples of how to parse Json from strings included within dart files. I am still working on finding a good example of parsing it from a json file on the server.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 85: June 20, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Successfully parsing the teams Json now. Need to align it with the data objects I created for it in the project. This is a good pattern. 

**Thoughts**: What I learned and did not see documented, Json files go in the web/assets folder if you want them exposed on a website in Flutter.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 86: June 21, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Success! Reading the team Json into the State object for the app. Now to start using it. 

**Thoughts**: I learned that top level arrays in JSon are not handled well using the json_serializable library, therefore I just converted the JSon top level array to an object. 

### Day 87: June 22, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Using the team member Json to generate everything on the team page with the except of the GDG chapter they belong to. Need to add one more field for each team member to the Json.

**Thoughts**: Just found a reason to use the json_serializable code generator library - I need to add some fields to my Json and it should make it pretty easy. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 88: June 23, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Finished off the team's page with reading from a Json file, both for the large and small layout. Brought in the sponsors Json file and am able to parse it into a data object using json_serializable.

**Thoughts**: Now that I know how json_serializable works, spinning up more data objects for various pages (sponsors, speakers, sessions) should be easy. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 89: June 24, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Added the sponsors page and sponsors navigation button to all of the headers. Refactored out the header and footer code for the project to one codebase. Also I added the Json files to Firebase Cloud Store so anyone from the team can modify them without needing to build and deploy the project. 

**Thoughts**: Now it is really easy to add new pagers with content since I have the structure for each page laid out. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 90: June 25, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: The sponsors page is scaffolded in - trying to debug the Data Objects for it. 

**Thoughts**: With Firebase Cloud Storage, I am going to try and add all of the assets and config for the project to it, to make the website truly configurable without any coding. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 91: June 27, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Working to add a Code of Conduct page loaded from an HTML document into the Flutter app. 

**Thoughts**: Trying to keep everything designed to be reused for other conferences.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 92: June 28, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Code of Conduct Page completed. I could not find a good way to embed HTML into an existing Flutter for Web page, thus I just hosted the static HTML page in Firebase Cloud Storage and open a separate tab for the page. 

**Thoughts**: When Flutter for Web allows the Flutter packages to be fully used, then displaying HTML in a site will be much easier.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 93: June 29, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Code of Conduct page is live in prod. Debugged the sponsors page, and fixed how I was parsing Json. The data is now displaying, just need to clean up the UI for the sponsors page. 

**Thoughts**: Debugging mismatches in Json naming issues when serializing it is not easy - there must be a better way than just print statements. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 94: June 30, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: I started with the Teams page for the Sponsors page, and ended up simplifying the design and layout for the Sponsors page by using a GridView Widget with Card Widgets for each Sponsor. 

**Thoughts**: I realized that I have storing all of my Json and some Html in Firebase Cloud Storage, but have not stored images there. I need to figure out if I can use relative path names for in Firebase Cloud Storage or need to use the full url (which could be pretty messy). 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 95: July 2, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: For smaller screens, the header with all of it's buttons was too large, thus I replaced it with a side navigation drawer on smaller screens.

**Thoughts**: The cool thing about creating the side navigation drawer - it is the exact same code for the web as what I would use for a mobile app in Flutter. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 96: July 3, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Dug into the Firebase Cloud Storage documentation and learned about the way URL's are constructed for resources stored there. Based on this I created a helped class to encode a relative path location to a resource to it's Firebase Cloud Storage location. Got this working for 90% of the site now (json, and images). 

**Thoughts**: The URL names used by Firebase Cloud Storage originally confused me due to extra tokens that are appended to the URL. I learned that the tokens are not needed.  

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 97: July 4, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Cleaned up Json for speakers and sessions, and halfway complete with the classes for json_serializable to serialize the Json. 

**Thoughts**: Last thing to complete for the website - the speakers and sessions pages. Going to finish it off before the 100 days is complete :) 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 98: July 5, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Finished converting all of the Json to Data Objects for speakers and the schedule. This is a bit tricky since for a conference app, speakers and the schedule intermingle in the data structures (ie a speaker has a timeslot with a session). 

**Thoughts**: We will see if I got the data structures right for the speakers and schedule once I start tying them together - trying to avoid to much looping to match speakers to sessions in the codebase when I need to display it all on the screen.

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 99: July 7, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Debugged speaker, session and schedule data into data objects. Refactored some of the contant value code, added the ability for the app to run offline (no Firebase Cloud Storage) and added a loading indicator while loading the page. 

**Thoughts**: Debugging Json that is not correct can be difficult - I need to see if I can add more debugging info for content creators for the site.  

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 100: July 8, 2019
##### (Continuing on a new Flutter Project)

**Today's Progress**: Finish mapping all of the Json data to internal data structures to allow for quick coding of the speaker, sessions and schedule pages - all referenced to each other.

**Thoughts**: While the site is not yet complete, in the past 30 or so days I am really happy with what I have completed considering Flutter for Web is not quite production ready - per the Flutter team. 

**Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)*Link to work:** [MIDevFest Site](https://github.com/donwardpeng/midevfest)

### Day 101: July 9, 2019
##### (Taking a month off to focus on completing some online courses for Deep Learning)

### Round 2 - Day 0: Oct 7, 2019
##### (Started a new Flutter Project)

**Today's Progress**: Started a new face detection Flutter project today. Ended up fighting issues with gradle and Flutter upgrades. 

**Thoughts**: More work to be done.

**Link to work:** None yet.

### Round 2 - Day 0 Again: Oct 9, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Fixed all of the issues with gradle and Flutter upgrades. Also got my iOS Simulator to be detected as a device since it was broken. Started scaffolding in the app, and hooking up it up to Firebase. 

**Thoughts**: Restarted the 100 Days since the last two days I could not get started due to life :)

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 1 Again: Oct 10, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Started working on the Face Detection Firebase code and understanding how to use it.

**Thoughts**: It is amazing that MLKit for Flutter is supported to the degree it is. 

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 0 Again: Oct 14, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Re-starting the #100DaysOfCode Challenge since I have too busy. I rebuilt my Flutter environment for iOS today. 

**Thoughts**: Success - I am now ready to develop code and have my develop tools in place. 

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 1: Oct 15, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Registered and hooked up a Firebase project to the app. Started to download all of the pod files needed to support face detection using MLKit for iOS. Also reviewing the git repo to understand how the examples.

**Thoughts**: Interesting that you need separate configurations for Android and iOS for MLKit Vision when using Flutter. This is one of the rare times that I have encountered (the other being for Firebase support) that each platform needs special code when using Flutter. 

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 2: Oct 16, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Added Firebase Android support and MLKit Vision support. 

**Thoughts**: A thing I realized - using Face Detection on the simulator/emulator probably would be programatic with the camera. Thus I added Android support so I can run and debug on my Android phone. 

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 3: Oct 17, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Needed more configuration to support Android on-device face detect. Added the buttons and screen to perform face-detect. Started digging through the code examples to wire it up. 

**Thoughts**: The examples I see all use static images to do face detection on - I need to figure out how to do it on a live camera feed.  

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 4: Oct 18, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: More scaffolding and design for the app. Researching how to grab frames from the camera to run face detection on.

**Thoughts**: Getting a better idea how to do face detection using the camera. 

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 4: Oct 19, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Took the day off.

### Round 2 - Day 5: Oct 20, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Followed a tutorial to get the Firebase MLKit Vision API to detect faces. Also dug into the source code for the Firebase MLKit face detection API example.  

**Thoughts**: The heavy lifting for face detection is all done by the Firebase MLKit Vision API - it returns bounding boxes, eyes open probabilities and a bunch of other info. Pretty slick. 

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 6: Oct 21, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Got face detect to work with images from the Gallery on iOS in the simulator. Working on an Android build issue that needs to be fixed before I can test it. 

**Thoughts**: Once I get Android working, the next steps are to add code to draw bounding boxes around the faces detect using a CustomPainter. 

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 7: Oct 22, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Taught an Intro to Flutter and worked a bit on getting Android working. Not a lot of progress on this yet. 

**Thoughts**: Once I get Android working, the next steps are to add code to draw bounding boxes around the faces detect using a CustomPainter. 

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 7: Oct 23, 2019
##### Took the day off. 

### Round 2 - Day 8: Oct 24, 2019
##### (Started a new Flutter Project for Face Detection)

**Today's Progress**: Got my Android emulator back up and running after totally corrupting it. Still fighting issues with getting an Android build to work - with all of the Flutter apps I have worked on, along with the web, I think I screwed up my Flutter build for Android along the line, since I can not build other Android apps I know have worked in the past. I have more things to try tomorrow.

**Thoughts**: Once i get my Android build working I can start debugging the face detect code. 

**Link to work:** [Face Detect Git Repo](https://github.com/donwardpeng/flutter-face-detect-)*

### Round 2 - Day 9: Oct 27, 2019
##### (Started another new Flutter Project for Face Detection)

**Today's Progress**: Some progress - I determined that it is not my code that is causing my Android project to not compile. I started a totally new project that I could compile for Android, and started adding the needed libraries. The image_picker and camera plugins needed for firebase_ml kit seem to have duplicate dependencies. I think I was able to clean this up, but ran into another issue with building - it appears more crptic. I am going to give it another try tomorrow. I still have some options - one is to use the example from the mlkit repo since it seems to compile and the other is to check out some Medium articles I found about Face Detection.

**Thoughts**: This is the first time I have encountered some major dependency issues with libraries in Flutter. Time to learn to debug them!

**Link to work:** [Face Detect 2 Git Repo](https://github.com/donwardpeng/facedetect2)*

### Round 2 - Day 10: Oct 28, 2019
##### (Started another new Flutter Project for Face Detection)

**Today's Progress**: Tried a few more fixes to get the dependencies on my app working. Nothing worked. Started to follow a Medium article I read about to use Face Detect with MLKit. Maybe it will provide a better solution than what I have come up with.

**Thoughts**: Pretty much the same as yesterday -> this is the first time I have encountered some major dependency issues with libraries in Flutter. Time to learn to debug them!

**Link to work:** [Face Detect 2 Git Repo](https://github.com/donwardpeng/facedetect2)*

### Round 2 - Day 11: Oct 29, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Third time is the charm! Started a new project and got Firebase for Android working. I noticed that the correct version of the gradle plugin for Firebase is 3.2.1, and there is a note not to go any higher.

**Thoughts**: I also read the MLKit for Firebase Medium article I referenced earlier and it is a wash. It was written in July 2018 and a lot has changed since then. I also ran the MLKit example app on the Android emulator and it took awhile to detect faces. It uses version 17 of the library for MLKit, hopefullly version 19 is faster. 

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 12: Nov 1, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Success! I finally got the app to fully compile and run on Android. I sorted out all dependency issues and documented them. Now to debug the app and get the MLKit face detect code to execute on images I provide (both from the camera and the gallery). 

**Thoughts**: After dealing with dependency issues for a few days I realize that MLKit with Flutter can be finicky.

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 13: Nov 2, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Determined that I need to add a permission handler to allow for the app to open the gallery to allow users to pick a image to scan. Worked on coding this up. 

**Thoughts**: I am not sure why the example app for face detect does not request permissions and still works. I need to dig into this. 

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 14: Nov 4, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Still working on adding the permission_handler to handle the camera and gallery opening. I determined the reason the sample apps works without handling permissions. It uses an older version of the Image Picker library that took care of it. The version was 0.5.0 and apparently in 0.5.0+6, Image Picker no longer handles the permissions.

**Thoughts**: Back to working to implementing a permission_handler. 

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 14.5: Nov 5, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Only got 1/2 hour in today - researching how to use the permission handler and Android permissions. I have not looked at the documentation for Android permissions for quite a while and caught up on the stuff I missed.  

**Thoughts**: Interesting reading up on the specifics on how Android permissions changed with Android 6.0.  

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 15: Nov 6, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Success! The image picker from the gallery is running and face detect seems to be working! Need to add code to draw bounding rectangles on faces found.

**Thoughts**: The importance of cleaning the project and deleting old builds was what helped me get this done. With all of the dependencies I have been working with something was messed up with the builds.

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 16: Nov 7, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Now that the face detect ML model is running, I need to add Custom Painter's to draw rectangles on the original image to indicate where faces were found.

**Thoughts**: I need to trace out the FlutterFire MLVision example to fully understand how to do this. Tomorrow's task - pen to paper and drawing it all out.

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 17: Nov 8, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: The app now draws rectangles where it detects faces. I also modified the displayed photo since it was filling the screen and messing with the aspect ratio, thus causing a distorted image. I had to also modify and scale the drawn rectangles accordingly.

**Thoughts**: I traced out how the FlutterFire MLVision example works and this help me immensely to make changes for my app. 

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 18: Nov 10, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Changed the face detect code to detect landmarks (eyes, ears, nose, etc.). Tried to add a mustashe to each detected face using a CustomPainter, but my first attempt looks more like every detected face has a runny nose. Going to try another tactic to draw a mustashe on each face. 

**Thoughts**: A bit of math is all I need to get this to work.

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 19: Nov 12, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Cleaned up the face detect code and got it to draw mustashes on the detected faces.

**Thoughts**: I had to draw out how to draw a mustache on paper to get it coded properly.

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*

### Round 2 - Day 20: Nov 13, 2019
##### (Started a totally new Flutter Project for Face Detection)

**Today's Progress**: Got the mustache to draw on the detected face with the proper line width, etc. Also started to research how to select the image from the camera as well as what permissions I need to setup in Flutter for iOS to work.

**Thoughts**: Looking in the Firebase ML Vision Library documentation, there is a lot you can do with the Landmarks found on the detected faces. Pretty impressive how in-depth it is!

**Link to work:** [The Face Detector Git Repo](https://github.com/donwardpeng/thefacedetector)*
