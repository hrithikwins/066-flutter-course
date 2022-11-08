#### [easy] Rahul had faced a tough time debugging null dereference error in Javascript. But he's quite fascinated by the Null Safety feature in dart. With sound null safety variables are ‘non-nullable’ by default.
There are few ways to make a variable null safe.
make the variable nullVar nullable so that null value can be assigned to it
`
int i = null;
print(i); //null

`


solution: add int? as dataType to make it nullable (int? i = null;) [read more about null operators](https://dart.dev/null-safety/understanding-null-safety#null-operators)

### [easy] What type of parameter does this makeCoffee function take?
//this question is the make users understand about null safety in practice to have a better understanding of the concept an duse for reusable widgets
`
```
// Using null safety:
makeCoffee(String coffee, [String? dairy]) {
  if (dairy != null) {
    print('$coffee with $dairy');
  } else {
    print('Black $coffee');
  }
}
```

answer: optional parameter .. they [read more about optional parameters](https://dart.dev/guides/language/language-tour#optional-parameters)

###

 <!-- var i = {
   "task": "Programming",
   "school": "pathshala"
 };

    print(i!["school"]);
  print(i["game"]); -->



  ### [easy] Here in the flow, check for whether the value of b is null and assign it the value of 42 only if it's null


````
var a = 24;
var b;
----------
  print(a + b);
````

answer:   b ??= 42; (the ?? operator checks for the value to be null ... ) or b = b ?? 42; [read more about null operators](https://dart.dev/null-safety/understanding-null-safety#null-operators)

---
### ?. and cascade operators pending

TODO:
### [easy] How do you use ?. here in cascade operator

[read more about cascade operator](https://dart.dev/guides/language/language-tour#cascade-notation-)




----------------------------------------
In the bloodBank show `Enabling/disabling null safety` in pub.yaml



