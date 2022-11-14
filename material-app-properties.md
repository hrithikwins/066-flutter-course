

### [easy] Is it important to have a material ancestor in scaffold
- yes
- no

[improve this question]

answer: yes, if you don't have a material ancestor

your app would have a black background and most of the widgets would not be painted in the UI and throw an error


### [medium] Every Material App we can use a widget that gives the default banner, background color, and has API for adding drawers, snack bars, and bottom sheets. What is the name of the widget which helps to provide such details
- MaterialApp
- Scaffold
- ListView
- HomeBuilder
answer: Scaffold [read more] (https://api.flutter.dev/flutter/material/Scaffold-class.html)

### [easy] There are several properties that can be passed to the widget, To change the background of Scaffold, we use the property
- scaffoldBackgroundColor
- backgroundColor
- homeBackground

answer: scaffoldBackgroundColor [read more](https://api.flutter.dev/flutter/material/ThemeData/scaffoldBackgroundColor.html)


### [medium] Hide the debug mode banner in your flutter application

```
MaterialApp(
  home: Scaffold(
    appBar: AppBar(
      title: const Text('Home'),
    ),
  ),
  _____________: false,
)
```

answer: debugShowCheckedModeBanner [read more](https://api.flutter.dev/flutter/material/MaterialApp/debugShowCheckedModeBanner.html)



### [easy] Which property of scaffold helps you to add the Layouting widgets like Column, Row, ListView, etc
- body
- home
- layout
- child
answer: body


