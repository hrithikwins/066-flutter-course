### You can use either single or double quotes to create a string. How do we create multiline string in dart
- using triple quotes
- Using `<pre>` tag
- Using the escape characters
- By prefixing 'r' at the start

(The answer is a & c)


### Rewrite the print statement using string interpolation
```
void main(){
   String name = "Programming";
   var college = "Pathshala";
   //without interpolation
   print("Name is " + name + " college is " + college);
  //with interpolation
  --------------------------
}
  ```
  answer : print("Name is $name college is $college');


  ### Concatenate the following string and print  'ProgrammingPathshala' in the console
```
  void main(){
   String name = "Programming";
   var college = "Pathshala";
   //concatenation goes here
  ----------------------------------
}
```
answer : print(name + college)


### what is a raw string
- A string which treats escape characters as string as well



### Turn the following string to a raw string
```
   String text = ___"Hello this is a text \n I am in a newline";
   ```
   Adding 'r' before this string


### What will be the output of the code
`
print(int.parse('0x42'))
`

answer:66


### What is the speciality of num.parse()
- It takes the string and converts it to either an integer or double
- It converts any string to their numeric equivalent

answer: a

### What parameter will you pass to convert Hexadecimal number to integer using int.parse()
`
print(int.parse('42', __________: 16))
`

- radix
- base
- power
- hex

answer: radix


### Convert the following string to integer
```
var fruits = '10 fruits'';
var intFruits = int.parse(fruits.______(' ')[0]);
print(intFruits);
```
answer: split

### Check whether a string contains another string 'fruit'.
````
var fruits = '10 fruits'';
var checkFruits = fruits.______('fruits');
print(checkFruits);
````

answer: contains


### Check whether a string starts with string 'Mango''.
````
var fruits = 'Mango fruits'';
var checkStart = fruits.______('Mango');
print(checkStart);
````

answer: startsWith


### Check whether a string ends with string 'Tree''.
````
var trees = 'Mango Tree'';
var checkIfEnds = trees.______('Tree');
print(checkIfEnds);
````

answer: endsWith


### how do you find the location of a string inside a string.
answer: using indexOf

### Grab the string 'odd' from this phrase and print it
```
print('Never odd or even'.____);
```
answer: .substring(6,9)

### Convert the strings to upperCase and lowerCase respectively
 ```
 var baseString =  "WEb WoRLd";
 var convertedCase = baseString.
 print(convertedCase);

 ```
- toUpperCase()
- toLowerCase()

### Remove the spaces from the string
```
var stringWithSpace = '  hello  ';
var trimmedString = stringWithSpace._________
print(trimmedString)
```

###  Check whether a string is empty.
```
var isEmptyString = assert(''.______);
print(isEmptyString);
```
- isEmpty

###
replaceAll


### Check whether the following has the dataType of integer or not
```
var someData = 30;
var dataType = someData.___________;
print(dataType)
```

answer: runtimeType





- int.parse
double.parse
split()
tostring()
runtimeType

