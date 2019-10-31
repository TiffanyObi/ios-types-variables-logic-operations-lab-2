# Types Variables Logic and Operations Lab 2

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit

## Question 1

You are given three grades obtained by 3 students, which are stored in variables `grade1`, `grade2`, `grade3` and all of type `Double`.
Create a variable called `yourGrade` of type `Double` and give it a value.
Print `"above average"` if your grade is greater than the class average or `"below average"` otherwise.

```swift
var grade1 = 7.0
var grade2 = 9.0
var grade3 = 5.0

// your code here

var yourGrade = 8.5

if yourGrade > 7.0 {
    print("Above Average")
} else {
    print("Below Average")
}
```

***
## Question 2

You are given a number. Print even if the number is even or odd otherwise.

```swift
let number = 2

// your code here

if number % 2 == 0 {
    print("Even")
} else {
    print("Odd")
}
```

***
## Question 3

You are given two numbers `a` and `b`. Print `"divisible"` if `a` is divisible by `b` and `"not divisible"` otherwise.

```swift
var a = 12
var b = 3

// code here

if a % b == 0 {
print("Divisible")
} else {
    print("Not Divisible")
}
```

***
## Question 4

You are given three variables `a`, `b` and `c`. Check if at least two variables have the same value. If that is true, print `"At least two variables have the same value"` otherwise print `"All the values are different"`.

```swift
var a = 2
var b = 3
var c = 2

// your code here

if a == b || a == c || b == c {
    print("At least two variables have the same value")
} else {
    print("All variables are different")
}


```

***
## Question 5

You are working on a smart-fridge. The smart-fridge knows how old the eggs and bacon in it are. You know that eggs spoil after 3 weeks (21 days) and bacon after one week (7 days). Given `baconAge` and `eggsAge` (both in days) determine if you can cook bacon and eggs, or which ingredients you need to throw out. If you can cook bacon and eggs, print `"you can cook bacon and eggs"`. If you need to throw out any ingredients, for each one print a line with the text `"throw out"` + bacon or eggs.

```swift
var baconAge = 6 // the bacon is 6 days old
var eggsAge = 12 // eggs are 12 days old

// your code here

if baconAge <= 7 && eggsAge <= 21 {
    print("You can cook eggs and bacon")
}else if eggsAge > 21  {
    print(" throw out eggs")
} else {
    print("you can eat your eggs")
}
if baconAge > 7 {
    print("Throw out bacon")
} else {
    print("You can eat your bacon")

```


***
## Question 6

You are given a year, determine if it’s a leap year. A leap year is a year containing an extra day. It has 366 days instead of the normal 365 days. The extra day is added in February, which has 29 days instead of the normal 28 days. Leap years occur every 4 years. 2012 was a leap year and 2016 will also be a leap year.
The above rule is valid except that every 100 years special rules apply. Years that are divisible by 100 are not leap years if they are not also divisible by 400. For example 1900 was not a leap year, but 2000 was. Print `"Leap year!"` or `"Not a leap year!"` depending on the year you are provided.

```swift
let year = 2014

// your code here
```

***
## Question 7

If you use `random()` it will give you a random number within a specified range. Generate a random number and use it to simulate a coin toss. Print `"heads"` or `"tails"`.

```swift
let randomNum = Int.random(in: 0...100)


if (randomNum % 2 == 0) {
    print("Heads")
} else {
    print("Tails")
    }```

Hint: use an if/else block along with the `%` operator

***
```
## Question 8

You are given four variables `a`, `b`, `c` and `d`. Print the value of the smallest one.

```swift
var x = 5
var y = 6
var c = 3
var d = 4

// your code here
var x = 5
var y = 6
var c = 3
var d = 4

let array = [x,y,c,d]


 print("\(array.min() ?? 0)")


```

***
## Question 9

Which of the following expressions evaluate to true?

```swift
a. 3 == 2 || 9 == 9
b. !(3 > 3)
c. !(true || false)
d. (4 < 3 || 4 > 3) && ("Message: " == "Message: ")
e. !(3 != 3)

///// Answer: A, B, C, D, E
```

***
## Question 10

Given the below, which of the following expressions evaluate to true?

```swift
 let x = 5 > 4
 let y = 100 / 10 == 1
 let z = 6
```

```swift
a. x && y
b. x || y || z == 1
c. ("five" == "5" || "FIVE" == "five" || 5 == 3 + 2) && !y
d. (x && y) || z > 6
e. !(z < 6) && !y && !x

///// Answer: B, C

```


***
## Question 11

What is true about Integers in computers?

```swift
a. Integers must have a positive or negative sign always.
b. The maximum value for Integers is +∞.
c. Integer types in computers take up a fixed amount of memory.
d. Integers may contain decimals.

///// Answer: C
```


***
## Question 12

Select all the code snippets below that will compile.

```swift
a. let numberOfPages: Int = 500
b. let numberOfChapters = "For Whom The Bell Tolls"
c. let nameOfBook: Int = 14
d. let yearPublished = "Nineteen-thirty-five"


///// Answer: A, B, C, D
```

***
## Question 13

What will the code below print?  Complete this exercise without using an IDE (Integrated Developer Environment) or calculator 

```swift
var a = 20
var b = 5
var c = 4

//// Answer:

a += b = a==25
b -= c =   b==1
b * (c + a) = 100
(b * c) + a = 40
b %= a == 5
b %= c == 1

print(a + b + c) = 29

```

***
## Question 14

let div = 11 / 4

```swift
1. The value of div is ____________________(or write "div1 will not compile")

let div2 = 11.0 / 4.0
2. The value of div2 is ________________________(or write "div2 will not compile")
let isEqual = div == div2

3. The value of isEqual is_____________________ (or write "isEqual will not compile")


```
Anwers:

let div = 11 / 4

print("The value of div is \(div)")
print("\(div) will not compile")

let div2 = 11.0 / 4.0
print("The value of div is \(div2)")
print("\(div2) will not compile")


let isEqual = Double(div) == div2

print("The value of isEqual is \(isEqual)")
print("\(isEqual) will not compile")


This is what printed in the console:

The value of div is 2
2 will not compile

The value of div is 2.75
2.75 will not compile

The value of isEqual is false
false will not compile
***
## Question 15
```swift
var n = 7.5

```

What is true about the variable n?

```swift
a. n is a Float
b. n is a Double
c. n is a Decimal
d. In is an Int

```
Answer: variable 'n' is a double. 

# Bonus 

***
## Question 1

What are the differences between Double and Int in the numbers they can represent and how they store them?

Answer: Ints are only whole numbers but Doubles are whole numbers and decimals. Doubles store numbers to a more exact measurement than Integers. 
***
## Question 2 

What are the differences between Float and Double?

Answer: Doubles hold twive as much data than Floats do. 
***

## Question 3

What will happen when the code below is run?

```swift

var width: Double = 49.8
var extraWidth: Float = 10.1
let totalWidth = width + extraWidth
print(totalWidth)

a. It will print 48.9
b. It will print 50.0
c. It will print 50
d. It will give a compile-time error

```
Answer: it will give a compile error because we cannot add floats and doubles. in order to add these two numbers we would have to cast the fload to a double. 
***
## Question 4 

You are given a number a. 
Print the last digit of a.

var abc: Int

```swift
//Example 1
//Input:
var abc = 123
print("\(abc % 10)")
//Output:
//3

//Example 2
//Input:
var abc = 337
print("\(def % 10)")
//Output:
//7


```

***

## Question 5 

Given an int, determine and print whether it is even or odd.

```swift
var number = 5

Example 1
Input: 
var number = 6

Expected Output: 
Even

```
Answer:
var numberA = 5

var numberB = 6


    if numberA % 2 == 0 {
        print("\(numberA) is even ")
    } else {
        print("\(numberA) is odd")
}
    if numberB % 2 == 0 {
        print("\(numberB) is even")
    } else {
        print("\(numberB) is odd")
}

***

## Question 6

You are given 2 Doubles a and b. Print their average

```swift
var a = 2.0
var b = 5.0

```
Answer:

var p = 2.0
var v = 5.0
var pv = (p + v) / 2
print("\(pv)")
***

## Question 7 

You are given 3 grades stored in 3 variables of type Double finalsGrade, midtermGrade, projectGrade. These grades are used to compute the grade for a class. finalsGrade represents 50% of the grade. midtermGrade represents 20% of the grade. projectGrade represents 30% of the final grade.

### Print the grade for the class.

```swift

var finalsGrade = 2.0
var midtermGrade = 4.0
var projectGrade = 3.0

```
Answer:
let classGrade = (finalsGrade / 0.5) + (midtermGrade / 0.3) + (projectGrade / 0.3)

print(classGrade)
***

## Question 8 

You have the cost of a meal at a restaurant stored in a variable mealCost of type Double. You would like to leave a tip of a certain percentage. The percentage is stored in a variable tip of type Int.

### Print the total cost of the meal.
```swift

Input: 
var mealCost:Double = 3.5
var tip:Int = 20


Output:
4.2

```
Answer:
var mealCost:Double = 3.5
var tip: Int = 20
let tipAmount = Double(Double(tip)/100)
let tipTotal = mealCost * tipAmount
let totalCost = mealCost + tipTotal
print(totalCost)
***

## Question 9

You are given three grades obtained by 3 students in a class stored in variables grade1, grade2, grade3 of typeDouble. You are also given your grade in the class stored in a variable yourGrade of type Double. Print above average if your grade is greater than the class average or below average” otherwise.

### Note: the average of the class includes your grade.
```swift

Input: 
var grade1 = 7.0
var grade2 = 9.0
var grade3 = 5.0
var yourGrade = 8.0

Output:
"above average"

```
Answer:
 var grade1 = 7.0
 var grade2 = 9.0
 var grade3 = 5.0
 var yourGrade = 8.0

var classGrade2: Double = 0.0
var numOfStudents : Double = 0.0
var arrayOfClassGrades = [grade1,grade2,grade3,yourGrade]

for grade in arrayOfClassGrades {
    classGrade2 += grade
    numOfStudents += 1.0
    print(classGrade2)
    }
var classAverage = classGrade2 / numOfStudents

if yourGrade > classAverage {
    print("Yay! At least i'm above average! 🤷🏾‍♀️")
}
***

## Question 10 

A farmer is harvesting wheat from a number of wheat fields, given in a variable numberOfFields of type Int. Each field produces the same quantity of wheat given in a variable wheatYieldof type Double. Sometimes the harvest is increased by 50% due to favorable weather conditions. You are given this information in a variable weatherWasGood of type Bool.

### Print the total amount of wheat that the farmer will harvest.

<img width="270" alt="Screen Shot 2019-09-12 at 1 50 33 PM" src="https://user-images.githubusercontent.com/43886240/64808175-c03a4180-d564-11e9-8502-4fcade888dc1.png">

```

