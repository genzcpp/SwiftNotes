```
import Foundation

// Function with two closure parameters
func performTask(
    onSuccess successHandler: () -> Void,
    onFailure failureHandler: () -> Void
) {
    let isSuccess = Bool.random() // Randomly decide success or failure

    if isSuccess {
        successHandler()
    } else {
        failureHandler()
    }
}

// Calling the function with explicit closure arguments
performTask { print("Success!") } onFailure: { print("Failure!") }

performTask(onSuccess: {
    print("Success!")
}, onFailure: {
    print("Failure!")
})
```