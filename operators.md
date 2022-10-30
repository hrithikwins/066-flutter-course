Arithmetic operators [done]
Equality and relational operators [done]
Type test operators
Assignment operators
Logical operators
Bitwise and shift operators
Conditional expressions
Cascade notation
Other operators

### There are several operators which help in arithmetic operations,. Here we've taken a function which is going to return a boolean when the number is even.
Hint: We need to have some operator which can return the remainder when divided by 2

```

bool checkEven(number){
  return (number _________==0);
}
print(checkEven(3));
```
answer: number % 2 [read about arithmetic operators](https://dart.dev/guides/language/language-tour#arithmetic-operators)

### Suppose you want to have a operator which can return the quotient only without caring for the remainder and the output be in integer(whole number) format

`print(5 __ 2 );` // outputs 2

answer: using the truncate division operator (~/) [read more about the truncate division operator](https://api.dart.dev/stable/2.10.4/dart-core/num/operator_truncate_divide.html)

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




<!-- ### How do you check for any two conditions to return true if both are true

```
void main(){
  print(2 == 2  __ 4 == 4);
}
``` -->

### In the below code print "Union Territory" if it is a state and has a

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
