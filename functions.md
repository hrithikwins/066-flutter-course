### Which of the following is NOT true about functions

- You can pass a function as a parameter to another function.
  -You can assign a function to a variable,
  -You can create a nameless anonymous function.
- If the function contains only a single expression or return statement, you can shorten it using arrow notation.
- You can only define functions inside the main() method




### Add valid function return type below

<!--
 -->

```
void main(){
final _nobleGases = const {
  2: 'helium',
  10: 'neon',
  18: 'argon',
};
______ isNoble(int atomicNumber) {
  return _nobleGases[atomicNumber] != null;
}

if(isNoble(1)){
  print("the gas is noble");
}else{
  print("the gas is not noble");
}
}

```
answer: bool



<!-- ### Named Optional parameters are  covered here -->


### Named parameters are optional unless they’re explicitly marked as required.

### How do you call this function having named parameters
```
void main(){
  print(greeting(_____________));
}

String greeting({String? firstName}){
  return "Hello $firstName";
}

```


###  correct the code below to make it work properly
```
void main(){
  function helloWorld(){
    print("The world is $hello");
  }
  print(helloWorld);
}
```
String / void instead of function

### use the function to print output to the console with
1. optional parameter
2. without optional parameter

```
void main(){
String say(String from, String msg, [String? device]) {
  var result = '$from says $msg';
  if (device != null) {
    result = '$result with a $device';
  }
  return result;
}
__________________
__________________
}
```
answer: print(say("Programmer", "hello", "console" ));
answer: print(say("Programmer", "hello" ));


### Which brackets do you use for named and optional positional parameters respectively
- {} for named parameters and [] for optional parameters
- {} for named and () for optional


