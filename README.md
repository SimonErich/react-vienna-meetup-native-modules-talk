# Live coding example
## Reaching React Native's limits. How to use native code in React Native
by Simon Auer

This is the running example of a simple react-native up including a native android module with "Toast" support.

### Run it

To run it, you just have to

**Clone this repo**

    git clone git@github.com:SimonErich/react-vienna-meetup-native-modules-talk.git
    cd react-vienna-meetup-native-modules-talk


**Install npm modules**

    npm install
    
or 
    
    yarn install
    
    
**Open Android Studio**

Open a new Android Studio project with the location `{YOUR_CLONE_ROOT}/react-vienna-meetup-native-modules-talk/android` folder and let it set all the sdk bindings and download gradle dependencies.
(you might have to install the SDKs first, if this is your first time using Android Studio)

It's important here, that you don't open the project root, but the `android` folder. :)
<p>&nbsp;</p>

**Open an Emulator**

Just (create and) open one in Android studio.


<p>&nbsp;</p>
    
    
**Run react-native bundler in one tab**

    npm start
    
or
    
    yarn start
    
    
**Open another terminal tab and start the application**

    react-native run-android
    
    

<p>&nbsp;</p>
<p>&nbsp;</p>

### More information and slides

To get more information and detailed description on what we did to get to this point, here are the slides to the talk with a bit more details on each step and the concept behind it.

http://bit.ly/2EjKHi8



### Need help?

Just post in React Vienna Slack and ping me. :)