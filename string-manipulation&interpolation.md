### Rahul is building an application where he needs some template messages to be inserted in the chat box, The template messages span more than 1 line and these have to be hard coded in the application as it's own feature.

```
String sendFirstMessage(receiverName){
  var firstMessage = __ Hello $receiverName! I am available as a blood donor.
   Kindly provide some more information about the patient.
  __;
  return firstMessage;
}
```
Adding triple quotes should be the solution

### How do you combine the following variables to print "ProgrammingPathshala" as the output
```

void main(){
String name = "Programming";
var college = "Pathshala";
//concatenation goes here

---

}

```
answer : print(name + college); or print("$name $college");


### what is a raw string. (Change the string below to a raw string)
- A string which does not give special treatment to escape characters in the string
```

String text = \_\_\_"Hello this is a text \n I am not in a newline";

```
Adding 'r' before this string


### You can also use int.parse to convert hexadecimal string to integer. What would be the output of the following hexadecimal
`
print(int.parse('0x42'))
`

answer:66 ..
[
  42 in hexadecimal is
4 x 16^1 + 2 x 16^0 => 64 + 2 = 66
]


<!-- ### In your age-calculator, you are telling the age of the users, and now you want to convert the string output of age to integer
- It takes the string and converts it to either an integer or double
- It converts any string to their numeric equivalent

answer: a -->

### You figured out that there is already a method in dart to ease your conversions. So you're now converting your binary number to decimal in a single line,
`
  print(int.parse("1001", ______: 2));
`

- radix
- base
- power
- hex

answer: radix [ more information](https://dart.dev/guides/libraries/library-tour#numbers)


### Let's remove the unit from the string and use the number for cost calculation
```

void main(){
  var item = '10 fruits';
var itemCount = int.parse(item.____(' ')[0]);
var itemCategory = item.____(' ')[1];
if(itemCategory == "fruits"){
  var cost = itemCount * 7;
  print("Cost is Rs $cost"); //Cost is Rs 70
}else{
  print("The item count is $itemCount");
}
}

```

answer: split


---
### Check whether a string contains the word 'fruit'.
```

var items = '10 fruits'';
var checkFruits = items.--------('fruits');
print(checkFruits);//true

```

answer: contains


### Check whether a string starts with string 'Rs''.
```
var price = 'Rs 20 per kg';
var checkINR = price.--------('Rs');
print(checkINR);//true

```

answer: startsWith


### Check whether a string ends with string unit 'kg''.
```

var price = 'Rs 20 per kg';
var checkKg = price.--------('kg');
print(checkKg);//true


````

answer: endsWith

### How do you get the measurement unit from this string
```
var price = 'Rs 20 per kg';
  var measuringUnit = price.----------(--,--);
  print(measuringUnit);
```

answer: .substring(10,12)



### How do you get the measurement unit from this string(part 2)
```
var price = 'Rs 280 per kg';
  int length = price.length;
  var measuringUnit = price.substring(----)
  print(measuringUnit);
```

answer: .substring(length -2) [the endIndex is optional](https://www.tutorialkart.com/dart/dart-substring/)


### In your word search puzzle, your users are entering the words they find in the puzzle, your task is to loop in each of the lines and check where is their word situated so that you can highlight those boxes
<!-- show practival use case ...to get array of food items  -->
<!-- suppose alexa is finding the song lyrics from a start -->

```
  var firstLineOfPuzzle = "azikwloxowpxnaevmncambridgeaaolnshglwilaxew";
var userInput = "cambridge";
print(firstLineOfPuzzle.-----(userInput));//18
```
answer: using indexOf



### Convert the strings to upperCase and lowerCase respectively
 ```
 var baseString =  "WEb WoRLd";
 var convertedCase = baseString.----------;
 print(convertedCase);

 ```
- toUpperCase()
- toLowerCase()

### Users in your chatbox are using empty spaces at the beginning and writing a short text at the end, how can you stop users from unnecessarily using empty space;
```
var stringWithSpace = '  hello  ';
var trimmedString = stringWithSpace._________
print(trimmedString)// hello
```

answer: trim()

###  Check whether the
```
var checkMessageForEmpty = assert('hello'.______);
print(checkMessageForEmpty);//false
```
- isEmpty

### Your co-developer is sending some shorthand words from backend which is not in a readable format
```

var unit = "40 ft 20 in";
print(unit.------("ft","feet").------("in","inches"));//40 feet 20 inches
```
replaceAll


### How do you check the datatype of a variable
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
<!--
````
### Rewrite the print statement using string interpolation
```
void main(){
String name = "Programming";
var college = "Pathshala";
//without interpolation
print("Name is " + name + " college is " + college);
//with interpolation

---

}

``` -->
<!-- answer : print("Name is $name college is $college'); -->
