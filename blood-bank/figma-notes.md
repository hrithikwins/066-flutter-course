## Splash Screen
The splash Screen.. has an initState to check if the user is loggedIn and after a few seconds, redirects to the appropritate Screen (shared_preferences needed)
Widgets used: Center, Container, Image.asset


## Onboarding Screens
1. PageView Widget to wrap all three pages in them for scrolling
2. Each Child (in PageView) having a  Column where the column has the Image and the text (possibilities are also for a bottom indicator)


## Mobile Verification (OTP)
Logic: Verify Mobile Number using Firebase (initiaite the signin, then wait for OTP and all such) bit complicated because here users are going to learn about how to use any SDK and it's methods, having good understanding with dart is must...

2. Store 'isLoggedIn' or something similiar in the shared_preference,
Some external packages used: https://pub.dev/packages/otp_text_field
TextField widget also used here in advanced way



## Sign UP
Use of Form widget, Column and also some advanced scrolling, because here the 'sign up' and 'register for checkup' will be fixed and body will be scrolling in the page


## Home Screen (Registered)
Taking Name from the previous page and displaying (Passing Arguments through pages)

Blood Group also from previous page

Based on Age, it verifies for donor status

## Navigation Drawer
Can tell about keys here

## Find Donor Requests

Basic Form elements and states here

This then sends an API post request or better firebase

Send request shows request sent




## Requests Screen
You'll get request with your own blood type, gender and relation
Who is the patient, patient is blood receiver


## Chat Screen
Firebase Messaging
Working with Futures and firestore snapshots


## maps
google_maps, mark getLocationPermissions....what are permissions and what apis are exposed by android and iOS


<!--
What does this communicate button do?


Can remove this call icon -->


