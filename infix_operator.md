In Swift, **infix operators**  are operators that are placed between two operands, such as `+`, `-`, `*`, `/`, and custom operators. Swift allows you to define your own **custom infix operators**  and control their precedence and associativity.

---

**Defining a Custom Infix Operator** 
To define a custom infix operator in Swift, follow these steps:
 
1. **Declare the operator**  with a precedence group (optional but recommended).
 
2. **Define the operator function**  with two parameters.
**Example 1: Creating a Custom Infix Operator** 

```swift
// Step 1: Define the operator
infix operator ** : MultiplicationPrecedence

// Step 2: Implement the operator function
func ** (lhs: Int, rhs: Int) -> Int {
    return Int(pow(Double(lhs), Double(rhs)))
}

// Usage
let result = 2 ** 3  // 2^3 = 8
print(result)
```


---

**Operator Precedence and Associativity** Swift lets you specify **precedence**  and **associativity**  for custom operators using `precedencegroup`.**Defining a Custom Precedence Group** 

```swift
// Step 1: Define a custom precedence group
precedencegroup ExponentiationPrecedence {
    associativity: right
    higherThan: MultiplicationPrecedence
}

// Step 2: Declare the operator with the precedence group
infix operator ^^ : ExponentiationPrecedence

// Step 3: Implement the operator function
func ^^ (lhs: Int, rhs: Int) -> Int {
    return Int(pow(Double(lhs), Double(rhs)))
}

// Usage
let value = 2 ^^ 3 ^^ 2  // Equivalent to 2^(3^2) = 2^9 = 512
print(value)
```
**Precedence & Associativity Rules**  
- `associativity: left` → Groups operations from left to right.
 
- `associativity: right` → Groups operations from right to left.
 
- `higherThan:` → Specifies that the operator has a higher precedence than another operator.
 
- `lowerThan:` → Specifies that the operator has a lower precedence than another operator.


---

**Example 2: Custom String Concatenation Operator** You can also create custom operators for other types like `String`:

```swift
infix operator +! : AdditionPrecedence

func +! (lhs: String, rhs: String) -> String {
    return lhs.uppercased() + " " + rhs.lowercased()
}

// Usage
let sentence = "hello" +! "WORLD"
print(sentence)  // "HELLO world"
```


---

**Built-in Infix Operators** 
Swift provides several built-in infix operators, such as:
 
- Arithmetic: `+`, `-`, `*`, `/`, `%`
 
- Comparison: `==`, `!=`, `>`, `<`, `>=`, `<=`
 
- Logical: `&&`, `||`
 
- Assignment: `=`, `+=`, `-=`, `*=`, `/=`
 
- Bitwise: `&`, `|`, `^`, `<<`, `>>`
 
- Range: `...`, `..<`
 
- Nil-coalescing: `??`


---
