In Swift, operators can be used as functions by referring to them directly using their symbolic names. This is useful in functional programming contexts like `map`, `reduce`, and `filter`, or when passing operators as arguments to functions.
### Examples: 
1. **Using Operators as Functions** 
You can use operators as functions by wrapping them in parentheses:


```swift
let sum = (+)(10, 5)  // Equivalent to 10 + 5
print(sum)  // Output: 15
```
2. **Using Operators in Higher-Order Functions** This is particularly useful when using functions like `map`, `reduce`, and `sorted`:

```swift
let numbers = [1, 2, 3, 4, 5]

// Using `*` as a function in `map`
let doubled = numbers.map(*2)
print(doubled)  // Output: [2, 4, 6, 8, 10]

// Using `+` as a function in `reduce`
let sumOfNumbers = numbers.reduce(0, +)
print(sumOfNumbers)  // Output: 15
```
3. **Custom Operators as Functions** 
You can define custom operators and use them as functions:


```swift
infix operator **

func ** (base: Int, power: Int) -> Int {
    return Int(pow(Double(base), Double(power)))
}

// Using the custom operator normally
let result = 2 ** 3  // Output: 8

// Using the custom operator as a function
let powFunction = (**)
print(powFunction(2, 3))  // Output: 8
```
4. **Comparisons with Operators as Functions** 
Comparison operators can also be used as functions:


```swift
let values = [3, 1, 4, 2]
let sortedValues = values.sorted(by: <) // Equivalent to `sorted(by: { $0 < $1 })`
print(sortedValues)  // Output: [1, 2, 3, 4]
```

Using operators as functions makes Swift code more concise and expressive, especially when working with collections and functional programming patterns. 🚀