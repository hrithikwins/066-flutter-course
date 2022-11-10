![image](https://media.geeksforgeeks.org/wp-content/uploads/20200604231710/gfg1-300x210.png)

### [easy] How can you position the child within the Container widget

- [ ] Using the alignment property
- [ ] Using the padding property
- [ ] Using the margin property
- [ ] Using the child property
      answer: using alignment property [Read More about alignment](https://api.flutter.dev/flutter/widgets/Alignment-class.html)

### [easy] Can we setup custom dimensions for the Container widget?

- [ ] Yes
- [ ] No
      answer: yes, the height and width properties of the container take in values of 'double' datatype [Read More about Container](https://api.flutter.dev/flutter/widgets/Container-class.html)

### [medium] What would be the height of blue container in this case

```
Container(
  height: 200,
  color: Colors.red,
  child: Container(
    height: double.infinity,
    width: 200,
    color: Colors.blue,
  ),
)
```

answer: The blue container will be 200px in height as double.infinity is the maximum height of parent element (red container). [Read More about double.infinity](https://api.flutter.dev/flutter/dart-core/double/infinity-constant.html)

### [medium] What would be the height of red container in this case

```
Container(
  height: MediaQuery.of(context).size.height /2,
  color: Colors.red,
  child: Container(
    height: 200,
    width: 200,
    color: Colors.blue,
  ),
)
```

answer: the inner container (blue container) will take 200px and outer container will take half of screen i.e, 50% of the screen height. [Read More about MediaQuery](https://api.flutter.dev/flutter/widgets/MediaQuery-class.html)

### [medium] what would be the height of hte red container in this case

```
Container(
  color: Colors.red,
 padding: EdgeInsets.all(10.0),
  child: Container(
    height: 200,
    width: 200,
    color: Colors.blue,
  ),
)
```

answer: the red container will take 220px as padding is added to the red container. [Read More about EdgeInsets](https://api.flutter.dev/flutter/painting/EdgeInsets-class.html)

### [medium] What would be the height of the red container in this case

```
Container(
  color: Colors.red,
 margin: EdgeInsets.all(10.0),
  child: Container(
    height: 200,
    width: 200,
    color: Colors.blue,
  ),
)
```

answer: the red container will take 200px .. margin is added to the red container which is outside of the margin [Read More about EdgeInsets](https://api.flutter.dev/flutter/painting/EdgeInsets-class.html)

### [medium] What would be the height of the red container in this case

```
Container(
  color: Colors.red,
 margin: EdgeInsets.all(10.0),
  child: Container(
    height: 200,
    width: 200,
    color: Colors.blue,
  ),
)
```

answer: it'll be still 200px as the margin is added to the red container which is outside of the container [Read More about container Layout ](https://docs.flutter.dev/development/ui/layout#container)

### [medium] What would be the height of the red container in this case

```
Container(
  color: Colors.red,
  child: Container(
    margin: EdgeInsets.all(10.0),
    height: 200,
    width: 200,
    color: Colors.blue,
  ),
)
```
answer: it'll be 220px as the margin is added to the blue container which is inside the red container [Read More about container Layout ](https://docs.flutter.dev/development/ui/layout#container)



### [difficult] Given, the container has a border of 5px ..what is the new size of the container

```
.container {
  width: 100,
  height: 100,
  border:
  Border.all(
                    width: 5,
                    color: Colors.red
                ),
}
```
answer: 110px height and 110px width .. as border is added to the container on all sides


### [difficult] Which of these is not a property of BoxShadow of box decoration

- blurRadius
- offset
- spreadRadius
- blurStyle
- backgroundColor
answer: backgroundColor .. there is a property as 'color' for BoxShadow of box but no property as 'backgroundColor' [read more](https://api.flutter.dev/flutter/painting/BoxShadow-class.html)

### [medium] Which of these properties of BoxDecoration Class help make the container rounded
- boxSide
- borderRadius
- borderSide
- circularRadius
answer: borderRadius .. [read more](https://api.flutter.dev/flutter/painting/BoxDecoration-class.html)

### [difficult] Can you add a custom background shape to the Container
- Yes
- No
answer: Yes using the 'shape' property .. [read more](https://api.flutter.dev/flutter/painting/BoxShadow-class.html)



