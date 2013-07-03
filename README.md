SignIn-Android
==============

This application presets a sample login screen / account registration flow.  It allows a user to create an account, log in, and stores the credentials in the Android Account Manager.  

In particular this sample application highlights the following key backend tasks:

* Allow users to sign up and log in
* Store Credentials in Android AccountManager
* Integrate Login with Twitter or Facebook OAuth


## Set up Sign-In Project

1. Clone the project repository.
2. In Eclipse, go to __File &rarr; Import…__
3. Click __Android &rarr; Existing Android Code into Workspace__
4. __Browse…__ to set __Root Directory__ to the cloned repository from step 1
5. In the __Projects__ box, make sure the __MainActivity__ project check box is selected. Then click __Finish__.
6. Specify your app key and secret in `assets/kinvey.properties` constant variables
![key and secret]()


```java
app.key=MY_APP_KEY

app.secret=MY_APP_SECRET
```

## Required Libraries
The following libraries are required to run this sample: 
* [Kinvey Android Library](http://devcenter.kinvey.com/android/downloads)
* [Facebook SDK for Android](https://developers.facebook.com/android/)
* Google Play Services (Available in the *Android SDK Manager*)
