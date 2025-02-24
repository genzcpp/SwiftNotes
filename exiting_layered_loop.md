In Swift, you can break out of multiple layers of loops using **labeled statements** . By labeling the outer loop, you can use `break <label>` to exit that loop from within an inner loop.
### Example: 


```swift
outerLoop: for i in 1...3 {
    for j in 1...3 {
        print("i: \(i), j: \(j)")
        if i == 2 && j == 2 {
            print("Breaking out of both loops")
            break outerLoop
        }
    }
}
print("Loop exited")
```

### Output: 


```yaml
i: 1, j: 1
i: 1, j: 2
i: 1, j: 3
i: 2, j: 1
i: 2, j: 2
Breaking out of both loops
Loop exited
```

### Explanation: 
 
- `outerLoop:` labels the outer `for` loop.
 
- When `i == 2` and `j == 2`, `break outerLoop` stops both loops.

- Execution continues after the outer loop.
This works with `while` and `repeat-while` loops as well.
