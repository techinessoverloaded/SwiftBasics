**Published by Arunprasadh C on 21 Apr 2022** • *Last Updated on 21 Apr 2022*

## Variables, Literals and Constants in Swift
### Literals
Literals are used to represent data values like Int or any other Data Type value in the Source Code. 

**Example :**
```swift
45 // Int Literal
"Hello World" // String Literal
3.14 // Floating-point Literal
```
We can assign values to Variables and Constants by means if Literals.

### Variables
In the previous Topic Pages, you would have seen the word "Variable" in many places. In fact, it is quite hard to write a program without using variables. Why is it so ? It is so because, a Variable as its name suggests, is used for storing a named variable value (value that can be changed). In Swift, variables can be declared by using `var` Keyword. 

**Example :**
```swift
var a = 45 // Statement 1
var b: String = "Hello" // Statement 2
```
As we saw in the Previous Topic, Swift can infer the Data Type of variable using the assigned Literal. This kind of declaration is used in Statement 1 above. On the other hand, in Statement 2, the Data Type of the Variable is explicitly specified in the Declaration. This kind of explicit Type Specification is called as **Type Annotation** in Swift. The general syntax of **Type Annotation** is as shown below:
```swift
var variableName:<data type> = <optional initial value>
```
**Type Annotation** is not compulsory in Swift as Data Types are inferred automatically. Usually, **Type Annotations** are used for enhancing the readability of the code. **Type Annotations** also allow the variables to be declared without any initial value. These variables can be assigned with value in the later part of the code.

**Example :**
```swift
var word:String
// Some statements
word = "Hello"
```
### Constants
Constants can be considered as **Immutable** (or **read-only**) Variables. Constants allow the values to be assigned only once. After assignment, the value can't be changed. It can only be accessed.  In Swift, constants can be declared by using `let` Keyword. The general syntax of declaring constants is as follows:
```swift
let constantName = <initial value>
```
**Example :**
```swift
let pi = 3.14 // CONSTANT
var radius = 7 // VARIABLE
var area = pi*radius*radius // VARIABLE
```
As with variables, **Type Annotations** can also be used with Constants in Swift (Simply replace `var` with `let`).

<a href="https://techinessoverloaded.github.io/iOSAppDevBasics/index.html">&larr; Back to Index</a>
<br>
<span style="float: left">
<a href="https://techinessoverloaded.github.io/iOSAppDevBasics/datatypes.html">&larr; Data Types available in Swift</a>
</span>
<span style="float: right">
<a href="https://techinessoverloaded.github.io/iOSAppDevBasics/.html"> &rarr;</a>
</span>