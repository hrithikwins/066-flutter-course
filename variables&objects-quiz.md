##### What keyword be the data type of the flybyObjects if it's type is defined
`
var flybyObjects = ['Jupiter', 'Saturn', 'Uranus', 'Neptune'];
- List
- Array
- Enum
- None of the above

answer: List (Ordered group of objects are known as Lists in Dart)


#####  What would be the output of adding length and age together
`
double length = 40.02;
int age = 10;
print(age+length);
`
- Runtime exception ()
- Compile time exception
- Error: A value of type 'double' can't be assigned to a variable of type 'int'.
- 50.02
- 50
_________________________________________________



### Find the error and fix it.
`
int length = 40;
length = 50.2;
`

sol: change int to double


### correct the folllowing by adding the valid datatype
`
______________ image = {
  'tags': ['saturn'],
};

- Map<String,List<String>> (Here var would also work, but we want users to be aware of this strongly datatyped feature)
`


### Complete the following codeblock to print the number to the console
________ printInteger(int aNumber) {
  print('The number is $aNumber.');
}

void main() {
  var number = 42;
  printInteger(number);
}

answer: the return type is void ('void')


### What is the use of void keyword
- To declare a variable which has no meaning
- Declare a function that explicitly doesn't return a value
- Throw exception when any variable is not null safe
- Mark the top-level functions of the application


### The special, required, top-level function where app execution starts.
- runApp()
- main()
- WidgetBinding()
- MyApp()

answer: main() (after main is runApp)

### Everything you can place in a variable is an ____, and every ______ is an instance of a class
- function
- parameter
- object
- data


### Although Dart is strongly typed. So why does Dart allow the type annotations to be optional
- Dart can infer types
- Dart is not really strongly typed
- Dart is interpreted
- Dart is used for Flutter



### Identifiers can start with underscore (_)
- true
- false

### Uninitialized variables that have a nullable type have an initial value .
- null
- void
- 0
- " "

## Which of this is the superclass of all Dart classes except Null.
- Object
- Class
- Map
- void

##  Make the immutablePoint constructor as a compile-time constant

var p = __________ ImmutablePoint(2, 2);
