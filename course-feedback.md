Blood Bank Application

- Date & Time in Dart could be added (much needed but not necessary)
- about pub.dev
- users should be guided to upload their app to playstore?
- deploying to testflight
- significant gap between 'stateful widgets' and 'state Management in flutter' Reason could be that they're learning the API part along, so practically getting familiar with the statemanagement and they need global state management later on
- textField widget is explained under stateful widget

##### Flow of the story

- students are familiar with Scaffold and basic page structuring
- with the safeArea and getting screen size, could be much relevant when they start using container.. so this might/not be right
- now they go with the container
- After learning container clearly and how to size them
- They add Text inside container
- Adding interactability .. now the [buttons could also be included here.. to have their perspective that GestureDetector, Inkwell and Buttons fall in same category] .... I'm only assuming that gesture detector is not going to be introducing stateful and rather just using 'print' statements here to print them to the console.
- At this point they should be bit familiar with either Navigation or should go with the Center, Row,Column ..etc layout, because here we're introducing a new widget 'image' .. and we wish to keep it on the same screen (layout) or maybe on a new screen (navigation)<br/>
  Navigation is a shortcut and layout is a better choice

  -working with images ...great here they can add images.. but after this can be textfields here.. so that they can get on to play with the data creation, they will be introduced to controllers .... again they can print this data to their console, probably greet the user with their name or something like this

- 'Levelling up dartDS' could be moved a step bottom, I think at this point the best thing would be to avoid breaking flow with the 'flutter fun'
- we have listview.builder twice (i personally think the second place is much better.. because they're gonna get issues with scrolling, so they learn the user of SingleChildScrollView.. and then they get familiar with ListView and ListView.builder

- in stateful and stateless=>Textfield widget topic could have better and elaborative topic as 'Controllers'

- State Managementi n flutter => Global States could introduce folder structure as well ..about architectures like MVVM MVC etc.
- I think till this point they will be very much familiar with working in a team as well

### Introduction to Mobile App Development

| Introduction to Mobile app development                      | Blood Bank                                                                                |
| ----------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Introduction to Flutter, the need to learn flutter          | Creating a New Flutter App                                                                |
| Setting up, vs code, emulator, Running first app in flutter | Changing the content in pubspec.yaml, reinventing scaffold, creating a transparent AppBar |
| Keywords                                                    | -                                                                                         |
| Variables and Datatypes                                     |
| Operations                                                  |
| Functions, named and required parameters                    | Login Function                                                                            |
| Sound null safety in dart                                   | making the login function null safe                                                       |
| Introduction to the Project - Blood Bank                    | Navigating to pages
General Development Flow in Course
What is a widget, its properties and usage
What is material App Widget and scaffold Widget | Creating a new Scaffold with Stateless
What is a safearea widget and finding app screen dimentions | Changing background using scaffoldBackground ..
App Bar and Floating action button | Not relevant
Learning Container Widget, the father of all widgets | Getting ahead with the second page
Container decoration, height and widget | cont.
Margin and padding in container | cont.
SizedBox and Divider | Not relevant
Text widget and its properties | Styling their sizes and colors
Gesture Detector and on press | Helping to add click to container
Image Widget, working with assets and Images | Not relevant
Selecting color in flutter | Changing them in the app
Working with lists and iterating on them |
Learning Maps and its usecase
Center Layout
Custom Alignment Layout
Rows and Column Layout
Mainaxis and cross axis alignment
Listview and Builder
Scrolling in flutter
SingleChildScrollView
Stack Layout
Listview and Builder
Classes and Objects
Class Variables and Methods
Inheritance and its usecases
Routing in flutter, route stack
Passing data through routes
Named routing
Tree of Widgets and ancestors
Stateless Widgets and understading its working
Statefull Widgets and set state
Widget lifecycle, Init, destroy
Textfield Widget
Converting a stateless widget into stateful widget
App Theme Widget | Adding fonts as well
Keeping a global level theme
Changing theme from any page
Widget Extraction
Hot reload, error inspection via stacktrace
Flutter UI Inspector
The concept of Futures, How to make a async function
then and catch callback
Basic Error Handling
Awaiting a future
Client- server and data communication b/w them
Json Objects, Serialization and deserialization
Converting models to map to json and vise-versa
Authentication, Autherisation and its need
Data Persistence by SQL and Nosql databases overview
Setting up firestore in project
Auth Service : Sign up user with email and password
Connecting with firestore, learning documents and collections
Getting data from firestote cloud to client
CRUD operations : Data snapshot and updaing data to cloud from client
Future Builder Widget and connecting it with a future
Stream and stream builder and connecting it with cloud snapshot
Setting firebase rules for tight security
Learning about widget rebuilds and State managment
Learning Provider State Management
Bringing business logic under provider
