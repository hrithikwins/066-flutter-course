### Which of the following is NOT true about functions

- You can pass a function as a parameter to another function.
- You can assign a function to a variable,
- You can create a nameless anonymous function.
- If the function contains only a single expression or return statement, you can shorten it using arrow notation.
- You can only define functions inside the main() method

----
give reasons for more information and give explanation as well
passing function
---



### Return types are important in functions, how do you check and change the return type

<!--
 -->

```

void main(){
int _bananaCount = 10;
________ isDozen(int bananaCount) {
  return bananaCount == 12;
}

  print(isDozen(_bananaCount));
}


```
answer: bool
---
recursion functions also
--

### You're writing a program in dart to demonstrate nth Fibonacci number to demonstrate recursion in dart, how do you achieve that
<!-- how do we ask question here -->

```

int fibonacci(int n){
  if(n<=1)
    return n;
  return fibonacci(n-1)+fibonacci(n-2);
}


void main() {
  print(fibonacci(6));
}
```

answer: _____________  Read more about recursion function [Read more](https://www.tutorialkart.com/dart/dart-recursion-function/)




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
    return "The world is";
  }
  print(helloWorld());
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
[REad More](https://www.codevscolor.com/dart-optional-positional-named-default)



-- simple questions in functions to understand loops



how function is running in loop
while and do-while loops, for and etc as well


### Write a function to calculate the factorial of the number

```
void main() {
   var num = 5;
   var factorial = 1;

   while(num >=1) {
      factorial = factorial * num;
      num--;
   }
   print("The factorial  is ${factorial}");
}
```
answer: ------------------- [read more about ]
```

