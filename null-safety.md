#### Rahul had faced a tough time debugging null dereference error in Javascript. But he's quite fascinated by the Null Safety feature in dart. With sound null safety variables are ‘non-nullable’ by default.
There are few ways to make a variable null safe.
make the variable nullVar nullable so that null value can be assigned to it
`
int i = null;
print(i); //null

`


solution: add int? as dataType


### The best use case of nullable variables could be used in optional parameters
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


###

 <!-- var i = {
   "task": "Programming",
   "school": "pathshala"
 };

    print(i!["school"]);
  print(i["game"]); -->



  ### Here in the flow, check for whether the value of b is null and assign it the value of 42 only if it's null


````
var a = 24;
var b;
----------
  print(a + b);
````

answer:   b ??= 42; (the ?? operator checks for the value to be null ... ) or b = b ?? 42;

---
### ?. and cascade operators pending





----------------------------------------
In the bloodBank show `Enabling/disabling null safety` in pub.yaml



