Arithmetic operators [done]
Equality and relational operators [done]
Type test operators
Assignment operators
Logical operators
Bitwise and shift operators
Conditional expressions
Cascade notation
Other operators

### Check whether the following number is even

```

function checkEven(number){
  return (number _________);
}
print(checkEven(3));
```

answer: number % 2

### Calculate the output

`print(5 ~/ 2 );`
answer: 2

### Calculate the output of the following code

```
void main() {
  int a = 2;
  int b = 4;
  double c = 6;
    c += a + ++b + a++ / a + ++b;
  print(c);
}
```

answer: the value of 6(val of c) + 2 + 5 + 2(now 3) / 3 + 4
With DMAS it's first 2/3 = 0.66666 and rest of things to be added up...

## Confirm whether the data type is double

```
void main(){
   var x = 25;
   print( ______);
}
```

answer: x is double


### conditional: what will this function return
```
void main() {
   var n1 = null;
   var n2 = 15;
   var res = n1 ?? n2;
   print(res);
}
```
- value of n1
- checks for their values and returns boolean( 'false' if both are not equal)
- returns the pointer address between both the cells





<hr> Probably not valid questions
<hr>

[Read about cascade notations](https://dart.dev/guides/language/language-tour#cascade-notation)

<!-- ### How do you check for any two conditions to return true if both are true

```
void main(){
  print(2 == 2  __ 4 == 4);
}
``` -->

### How do you check for both the conditions to be true to return true (AND operation)

```
void main(){
  print(2 == 2  __ 4 == 5);
}

```
answer: && (logical AND) [read more](https://dart.dev/guides/language/language-tour#operators)

<hr/>
###

in the video

- equality
  -!=
  > <
  > +=
  > ++
  > &&
