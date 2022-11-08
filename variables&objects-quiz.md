##### [easy] What keyword be the data type of the flybyObjects if it's type is defined
`
var flybyObjects = ['Jupiter', 'Saturn', 'Uranus', 'Neptune'];
- List
- Array
- Enum
- None of the above

answer: List (Ordered group of objects are known as Lists in Dart)


#####  [easy] What would be the output of adding length and age together
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


answer: 50.02 (will allow you to add a double and an int. but you cannot assing a double to an int) [Read More about Numbers](https://dart.dev/guides/language/language-tour#numbers)


### [difficult] Find the error and fix it.
`
int length = 40;
length = 50.2;
`

sol: change int to double


### [difficult] correct the folllowing by adding the valid datatype
`
______________ image = {
  'tags': ['saturn'],
};

- Map<String,List<String>> (Here var would also work, but we want users to be aware of this strongly datatyped feature) [read more about strongly typed language](https://en.wikipedia.org/wiki/Strong_and_weak_typing)

### [difficult] Complete the following codeblock to print the number to the console
________ printInteger(int aNumber) {
  print('The number is $aNumber.');
}

void main() {
  var number = 42;
  printInteger(number);
}

answer: the return type is void ('void') [read more](https://dart.dev/guides/language/language-tour#return-values)

### [difficult] What is the use of void keyword
- To declare a variable which has no meaning
- Declare a function that explicitly doesn't return a value
- Throw exception when any variable is not null safe
- Mark the top-level functions of the application
answer: Declare a function that explicitly doesn't return a value [more information](https://dart.dev/guides/language/language-tour#return-values)

### [easy] The special, required, top-level function where app execution starts.
- runApp()
- main()
- WidgetBinding()
- MyApp()
answer: main() (after main is runApp)


### [easy] Everything you can place in a variable is an ____, and every ______ is an instance of a class
- function
- parameter
- object
- data
answer: object (everything in dart is an object) [more information](https://dart.dev/guides/language/language-tour#everything-is-an-object)

### [easy] Although Dart is strongly typed. So why does Dart allow the type annotations to be optional
- Dart can infer types
- Dart is not really strongly typed
- Dart is interpreted
- Dart is used for Flutter
answer: Dart can infer types (Dart is strongly typed, but it can infer types)[more information](https://dart.dev/guides/language/sound-dart)


### [easy] Identifiers can start with underscore (_)
- true
- false
answer: true [naming conventions](https://dart.dev/guides/language/effective-dart/style#prefer-using-lowercamelcase-for-constant-names)

### [medium] what is the meaning of underscore (_) in dart variable names
- It is used to mark private variables
- It is used to mark public variables
- It is used to mark protected variables
- It is used to mark final variables
answer: It is used to mark private variables (private variables are not accessible outside the class)(https://dart.dev/guides/language/effective-dart/style#prefer-using--for-privatemember-names)


### [medium] Uninitialized variables that have a nullable type have an initial value .
- null
- void
- 0
- " "
answer: null (https://dart.dev/guides/language/language-tour#variables)

## Which of this is the superclass of all Dart classes except Null.
- Object
- Class
- Map
- void
answer: Object [read more](https://dart.dev/guides/language/language-tour#classes)


##  how do you make the immutablePoint constructor as a compile-time constant
var p = __________ ImmutablePoint(2, 2);
answer: const (https://dart.dev/guides/language/language-tour#final-and-const)
