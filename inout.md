
You: 

swift inout

ChatGPT: 

In Swift, the `inout` keyword is used to pass a parameter by reference instead of by value. This allows a function to modify the value of the parameter and have that modification persist outside of the function scope.**In Swift, the `inout` keyword is used to pass a parameter by reference instead of by value. This allows a function to modify the value of the parameter and have that modification persist outside of the function scope.How `inout` Works** 
- Normally, function parameters are constants and cannot be modified inside the function.
 
- Using `inout`, the function gets a reference to the original value rather than a copy.
 
- The caller must pass the argument using the `&` prefix.
**Example 1: Modifying an Integer** 

```swift
func doubleValue(_ number: inout Int) {
    number *= 2
}

var myNumber = 10
doubleValue(&myNumber)
print(myNumber) // Output: 20
```
**Example 2: Swapping Two Values** 

```swift
func swapValues(_ a: inout Int, _ b: inout Int) {
    let temp = a
    a = b
    b = temp
}

var x = 5
var y = 10
swapValues(&x, &y)
print(x, y) // Output: 10 5
```
**Example 3: Modifying an Array** 

```swift
func appendElement(_ array: inout [String], element: String) {
    array.append(element)
}

var names = ["Alice", "Bob"]
appendElement(&names, element: "Charlie")
print(names) // Output: ["Alice", "Bob", "Charlie"]
```
**Key Points**  
- The `inout` parameter must be a **variable**  (not a constant or a literal).
 
- The caller must use the `&` symbol when passing an argument.
 
- `inout` **cannot be used with default parameter values** .
 
- `inout` parameters **cannot be optional**  (`inout Int?` is not allowed directly).
Would you like a more advanced use case, such as using `inout` in a closure? 🚀
