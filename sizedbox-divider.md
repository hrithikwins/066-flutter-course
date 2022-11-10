### What is wrong with the below code
```
SizedBox(
  height: 100,
  width: 100,
  color: Colors.green,
  child: Container(
    color: Colors.red,
  ),
)
```

answer: 'Error at line 4 at color' ......we cannot pass color and other decoration properties to sizedbox as it's not a container. [Read More about sizedbox](https://api.flutter.dev/flutter/widgets/SizedBox-class.html)


### What is the size of the red container in this case
```
SizedBox(
  height: 100,
  width: 100,
  child: Container(
    color: Colors.red,
    height: 20,
    width: 20,
  ),
)
```

answer: 100px x 100px as sizedbox is a container and it will take the size of the child container [Read More about sizedbox](https://api.flutter.dev/flutter/widgets/SizedBox-class.html)


### How do you put a horizontal line in flutter
answer: using Divider