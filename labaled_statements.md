
You: 
### Practical Use Cases for Labeled Statements in Swift 
Labeled statements in Swift (`labelName: statement`) are useful in specific cases where control flow needs to break or continue from nested loops or switch cases. Below are practical use cases:

---

1. **Breaking Out of Nested Loops** 
When dealing with nested loops, labeled statements allow breaking out of a specific outer loop instead of just the inner one.

#### Example: 


```swift
outerLoop: for i in 1...3 {
    for j in 1...3 {
        if i == 2 && j == 2 {
            print("Breaking outer loop at i=\(i), j=\(j)")
            break outerLoop // Exits both loops
        }
        print("i=\(i), j=\(j)")
    }
}
```
✅ **Use Case:**  Exiting from multiple nested loops at once.

---

2. **Continuing to an Outer Loop** Labeled `continue` helps when you need to skip the current iteration of an outer loop while inside an inner loop.
#### Example: 


```swift
outerLoop: for i in 1...3 {
    for j in 1...3 {
        if j == 2 {
            print("Skipping inner loop at i=\(i), j=\(j)")
            continue outerLoop // Skips the rest of the inner loop and continues with the next i
        }
        print("i=\(i), j=\(j)")
    }
}
```
✅ **Use Case:**  Skipping iterations in a nested loop without unnecessary flag variables.

---

3. **Breaking Out of a Switch Inside a Loop** If a `switch` statement is inside a loop, a labeled `break` can be used to exit the loop instead of just the `switch`.
#### Example: 


```swift
var numbers = [1, 2, 3, 4, 5]

loop: for num in numbers {
    switch num {
    case 3:
        print("Breaking out of loop at num=\(num)")
        break loop // Exits the loop completely
    default:
        print("Processing \(num)")
    }
}
```
✅ **Use Case:**  Exiting a loop from within a `switch` without checking conditions separately.

---

4. **Breaking Out of Nested Functions in Closures** 
Labeled statements can also be useful when breaking out of an enclosing scope in inline closures.

#### Example: 


```swift
func processNumbers() {
    let numbers = [10, 20, 30, 40, 50]

    numbersLoop: for num in numbers {
        print("Processing \(num)")

        numbers.forEach { innerNum in
            if innerNum == 30 {
                print("Breaking outer loop at \(innerNum)")
                break numbersLoop
            }
        }
    }
}

processNumbers()
```
✅ **Use Case:**  Exiting an outer loop from within a closure, which wouldn’t be possible with just `return` or `break` inside `forEach`.

---


### When to Use Labeled Statements 
🔹 When dealing with **nested loops**  and needing to break or continue the outer one.
🔹 When a **switch inside a loop**  requires exiting the whole loop, not just the switch.
🔹 When escaping an **outer scope from within a closure**  inside a loop.
Would you like examples for a specific use case in your Swift project? 🚀
