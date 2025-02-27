**Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

Example: Using `$0` in `filter`** 

```swift
let evenNumbers = numbers.filter { $0 % 2 == 0 }

print(evenNumbers)  // Output: [2, 4]
```
✅ `$0` represents each element in the array.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

Example: Using `$0` in `filter`** 

```swift
let evenNumbers = numbers.filter { $0 % 2 == 0 }

print(evenNumbers)  // Output: [2, 4]
```
✅ `$0` represents each element in the array.

---

Example: Using `$0`, `$1` in `sorted`** 

```swift
let names = ["Alice", "Bob", "Charlie"]
let sortedNames = names.sorted { $0 > $1 }

print(sortedNames)  // Output: ["Charlie", "Bob", "Alice"]
```
✅ `$0` is the first value, `$1` is the second, and we compare them.

---

**3️⃣ When NOT to Use Shorthand Arguments**  
- When the closure has **complex logic** , explicit parameter names improve readability.
 
- If a closure has **more than 2-3 parameters** , it may be unclear which `$0`, `$1`, `$2` refer to.
 
- If readability is **compromised** , consider naming the parameters.
✅ **Example where shorthand arguments reduce clarity:** 

```swift
let compute: (Int, Int, Int) -> Int = { $0 + $1 * $2 }
```
🚨 ❌ This is **hard to read** . Instead, use named parameters:

```swift
let compute: (Int, Int, Int) -> Int = { base, multiplier, adder in
    return base + multiplier * adder
}
```


---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

Example: Using `$0` in `filter`** 

```swift
let evenNumbers = numbers.filter { $0 % 2 == 0 }

print(evenNumbers)  // Output: [2, 4]
```
✅ `$0` represents each element in the array.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

Example: Using `$0` in `filter`** 

```swift
let evenNumbers = numbers.filter { $0 % 2 == 0 }

print(evenNumbers)  // Output: [2, 4]
```
✅ `$0` represents each element in the array.

---

Example: Using `$0`, `$1` in `sorted`** 

```swift
let names = ["Alice", "Bob", "Charlie"]
let sortedNames = names.sorted { $0 > $1 }

print(sortedNames)  // Output: ["Charlie", "Bob", "Alice"]
```
✅ `$0` is the first value, `$1` is the second, and we compare them.

---

**3️⃣ When NOT to Use Shorthand Arguments**  
- When the closure has **complex logic** , explicit parameter names improve readability.
 
- If a closure has **more than 2-3 parameters** , it may be unclear which `$0`, `$1`, `$2` refer to.
 
- If readability is **compromised** , consider naming the parameters.
✅ **Example where shorthand arguments reduce clarity:** 

```swift
let compute: (Int, Int, Int) -> Int = { $0 + $1 * $2 }
```
🚨 ❌ This is **hard to read** . Instead, use named parameters:

```swift
let compute: (Int, Int, Int) -> Int = { base, multiplier, adder in
    return base + multiplier * adder
}
```


---

4️⃣ Removing Explicit `return` with Shorthand Arguments** When a closure consists of a **single expression** , Swift allows **implicit return** :

```swift
let divide: (Double, Double) -> Double = { $0 / $1 }

print(divide(10, 2))  // Output: 5.0
```
✅ No need for `return`.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

Example: Using `$0` in `filter`** 

```swift
let evenNumbers = numbers.filter { $0 % 2 == 0 }

print(evenNumbers)  // Output: [2, 4]
```
✅ `$0` represents each element in the array.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

Example: Using `$0` in `filter`** 

```swift
let evenNumbers = numbers.filter { $0 % 2 == 0 }

print(evenNumbers)  // Output: [2, 4]
```
✅ `$0` represents each element in the array.

---

Example: Using `$0`, `$1` in `sorted`** 

```swift
let names = ["Alice", "Bob", "Charlie"]
let sortedNames = names.sorted { $0 > $1 }

print(sortedNames)  // Output: ["Charlie", "Bob", "Alice"]
```
✅ `$0` is the first value, `$1` is the second, and we compare them.

---

**3️⃣ When NOT to Use Shorthand Arguments**  
- When the closure has **complex logic** , explicit parameter names improve readability.
 
- If a closure has **more than 2-3 parameters** , it may be unclear which `$0`, `$1`, `$2` refer to.
 
- If readability is **compromised** , consider naming the parameters.
✅ **Example where shorthand arguments reduce clarity:** 

```swift
let compute: (Int, Int, Int) -> Int = { $0 + $1 * $2 }
```
🚨 ❌ This is **hard to read** . Instead, use named parameters:

```swift
let compute: (Int, Int, Int) -> Int = { base, multiplier, adder in
    return base + multiplier * adder
}
```


---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

Example: Using `$0` in `filter`** 

```swift
let evenNumbers = numbers.filter { $0 % 2 == 0 }

print(evenNumbers)  // Output: [2, 4]
```
✅ `$0` represents each element in the array.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

****Shorthand Argument Names in Swift Closures** Swift provides **shorthand argument names**  (`$0`, `$1`, `$2`, etc.) to make closures more concise. These implicit argument names allow you to skip writing explicit parameter names.

---

1️⃣ Basic Usage of `$0`, `$1`, `$2`** 
When a closure receives parameters, Swift automatically assigns them numbered labels:
 
- **`$0`**  → First parameter
 
- **`$1`**  → Second parameter
 
- **`$2`**  → Third parameter, and so on.
Example: Using `$0` and `$1` in a Closure** 
Instead of writing:


```swift
let multiply: (Int, Int) -> Int = { a, b in
    return a * b
}
```
You can **simplify**  it using shorthand arguments:

```swift
let multiply: (Int, Int) -> Int = { $0 * $1 }

print(multiply(4, 5))  // Output: 20
```
✅ No need to declare `a, b` explicitly—Swift understands `$0` is the first parameter and `$1` is the second.

---

**2️⃣ Shorthand Arguments in Higher-Order Functions** Shorthand arguments are often used with **higher-order functions**  like `map`, `filter`, and `sorted`.Example: Using `$0` in `map`** 

```swift
let numbers = [1, 2, 3, 4]
let squares = numbers.map { $0 * $0 }

print(squares)  // Output: [1, 4, 9, 16]
```
Instead of writing `{ num in num * num }`, we simply use `$0`.

---

Example: Using `$0` in `filter`** 

```swift
let evenNumbers = numbers.filter { $0 % 2 == 0 }

print(evenNumbers)  // Output: [2, 4]
```
✅ `$0` represents each element in the array.

---

Example: Using `$0`, `$1` in `sorted`** 

```swift
let names = ["Alice", "Bob", "Charlie"]
let sortedNames = names.sorted { $0 > $1 }

print(sortedNames)  // Output: ["Charlie", "Bob", "Alice"]
```
✅ `$0` is the first value, `$1` is the second, and we compare them.

---

**3️⃣ When NOT to Use Shorthand Arguments**  
- When the closure has **complex logic** , explicit parameter names improve readability.
 
- If a closure has **more than 2-3 parameters** , it may be unclear which `$0`, `$1`, `$2` refer to.
 
- If readability is **compromised** , consider naming the parameters.
✅ **Example where shorthand arguments reduce clarity:** 

```swift
let compute: (Int, Int, Int) -> Int = { $0 + $1 * $2 }
```
🚨 ❌ This is **hard to read** . Instead, use named parameters:

```swift
let compute: (Int, Int, Int) -> Int = { base, multiplier, adder in
    return base + multiplier * adder
}
```


---

4️⃣ Removing Explicit `return` with Shorthand Arguments** When a closure consists of a **single expression** , Swift allows **implicit return** :

```swift
let divide: (Double, Double) -> Double = { $0 / $1 }

print(divide(10, 2))  // Output: 5.0
```
✅ No need for `return`.

---

5️⃣ Using `$0` in Trailing Closure Syntax** When a closure is the **last parameter**  of a function, you can use **trailing closure syntax** .
Example without trailing closure:


```swift
let doubledNumbers = numbers.map({ $0 * 2 })
```
Example **with**  trailing closure:

```swift
let doubledNumbers = numbers.map { $0 * 2 }
```
✅ **Cleaner and more Swift-like!** 

---

**🔹 Summary: When to Use Shorthand Arguments?** 

| Scenario | Use $0, $1? | Example | 
| --- | --- | --- | 
| Single-parameter closures | ✅ Yes | { $0 * 2 } | 
| Simple expressions | ✅ Yes | { $0 + $1 } | 
| Higher-order functions (map, filter, sorted) | ✅ Yes | { $0 * $0 } | 
| Multi-line closures | ❌ No | Use named parameters instead | 
| More than 2-3 parameters | ❌ No | Use named parameters for clarity | 

Shorthand arguments are **powerful** , but use them **only when they improve readability** . 🚀
Would you like any more examples? 😊
