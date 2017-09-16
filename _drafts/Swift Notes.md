#Swift Notes
* Older versions of swift before 4 would break older versions.
* Swift doesn't need a main method or function.
* Don't need import statements.
* Don't need main functions/methods.
* Don't need to return result to the OS.
* Swift is a type safe language.
* Swift infers variable type from the initial value (Type Inference).
* Swift enforces your datatype unlike JavaScript.
* Swift compiles to machine code. It is not an interpreted language. It's fully compiled in advance.

##Variables
* var playerName
* variables in lower camel case.
* you have to write var to create a variable. it's the only way.
* If there is no initial data the datatype must be specified.
```
var bonusScore: Int
```
* variable names begin w/ lower case and types begin with upper case.
* no space before the colon you can but don't.

```
var progressPercentage: Double
```
* Type annotation missing in pattern error will be thrown if you don't declare the type.
* You can write type annotation and the type but it's not necessary.

##Constants
* Use let to assign Constants.
* Just swap var with let, everything else is the same as variables.
```Swift
let myConstantMessage = "Hello
```
* Once assigned can't change
* Will receive error "Cannot assign value".
* Constants are highly encouraged.
* Will get a warning if XCODE sees a variable that could be a constant.
```
let message = "Should this be a variable"
```
"Variable 'message' was never mutated; consider changing to 'let' constant"
* Swift compiler will make optimizations for constants it won't for variables.
* Using constants is safer.
* Value of a constant doesn't have to be fixed at compile time as long there's logic to initialize it in the program.
```
let currentMonth: String
```
* Constants and variables must be initialized before we use them.


##XCODE
* attempts to parse code as you write.
* swift playground shows results of swift as you write it.
* results dim to grey as the playground re-evaluates the code after changes.
* XCODE uses LLDB to do debugging.
