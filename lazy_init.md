​[useyourloaf.com](https://useyourloaf.com/blog/swift-lazy-property-initialization/)​

**Direct Assignment** : The simplest approach, where properties are assigned initial values at the time of declaration. For example:​

```swift
let fontSize: CGFloat = 24.0
var spacing: CGFloat = 16.0
```


Optionals are initialized to `nil` by default.​[stackoverflow.com
+1
avanderlee.com
+1](https://stackoverflow.com/questions/24107938/lazy-property-initialization-in-swift) **Using an Initializer** : If a property isn't assigned an initial value during its declaration, it must be set within an initializer to ensure all stored properties have appropriate initial values by the time an instance is created. For instance:​
```swift
class Book {
  let title: String

  init(title: String) {
    self.title = title
  }
}
```


It's preferable to assign initial values during declaration when they are constant.​**Using a Closure** : For properties requiring more setup, a closure can be utilized to initialize the property, keeping the setup close to the property declaration. 

```swift
let button: UIButton = {
  let button = UIButton(type: .system)
  button.titleLabel?.font = UIFont.systemFont(ofSize: ViewMetrics.fontSize)
  return button
}()
```


The closure is executed once when the containing type is initialized, and its return value is assigned to the property.​[hackingwithswift.com
+5
useyourloaf.com
+5
forums.swift.org
+5](https://useyourloaf.com/blog/swift-lazy-property-initialization/) **The Lazy Way** : Lazy initialization defers the creation of a property's initial value until it's actually needed, which is beneficial when the initialization is resource-intensive. In Swift, this is achieved using the `lazy` keyword:​[stackoverflow.com
+4
useyourloaf.com
+4
Dhiwise
+4](https://useyourloaf.com/blog/swift-lazy-property-initialization/) 

```swift
lazy var decimalFormatter: NumberFormatter = {
  let formatter = NumberFormatter()
  formatter.numberStyle = .decimal
  return formatter
}()
```


Lazy properties are always declared with `var`, and the closure is called upon the property's first access, which can occur after the initialization of the instance.​[useyourloaf.com
+1
Dhiwise
+1](https://useyourloaf.com/blog/swift-lazy-property-initialization/) **​The article "Swift Lazy Property Initialization" from Use Your Loaf discusses various methods of initializing stored properties in Swift, emphasizing the use of lazy properties for efficient resource management.​**Direct Assignment** : The simplest approach, where properties are assigned initial values at the time of declaration. For example:​

```swift
let fontSize: CGFloat = 24.0
var spacing: CGFloat = 16.0
```


Optionals are initialized to `nil` by default.​[stackoverflow.com
+1
avanderlee.com
+1](https://stackoverflow.com/questions/24107938/lazy-property-initialization-in-swift) **Using an Initializer** : If a property isn't assigned an initial value during its declaration, it must be set within an initializer to ensure all stored properties have appropriate initial values by the time an instance is created. For instance:​[hackingwithswift.com
+5
useyourloaf.com
+5
avanderlee.com
+5](https://useyourloaf.com/blog/swift-lazy-property-initialization/) 

```swift
class Book {
  let title: String

  init(title: String) {
    self.title = title
  }
}
```


It's preferable to assign initial values during declaration when they are constant.​**Using a Closure** : For properties requiring more setup, a closure can be utilized to initialize the property, keeping the setup close to the property declaration. 

```swift
let button: UIButton = {
  let button = UIButton(type: .system)
  button.titleLabel?.font = UIFont.systemFont(ofSize: ViewMetrics.fontSize)
  return button
}()
```


The closure is executed once when the containing type is initialized, and its return value is assigned to the property.​[hackingwithswift.com
+5
useyourloaf.com
+5
forums.swift.org
+5](https://useyourloaf.com/blog/swift-lazy-property-initialization/) **The Lazy Way** : Lazy initialization defers the creation of a property's initial value until it's actually needed, which is beneficial when the initialization is resource-intensive. In Swift, this is achieved using the `lazy` keyword:​[stackoverflow.com
+4
useyourloaf.com
+4
Dhiwise
+4](https://useyourloaf.com/blog/swift-lazy-property-initialization/) 

```swift
lazy var decimalFormatter: NumberFormatter = {
  let formatter = NumberFormatter()
  formatter.numberStyle = .decimal
  return formatter
}()
```


Lazy properties are always declared with `var`, and the closure is called upon the property's first access, which can occur after the initialization of the instance.​[useyourloaf.com
+1
Dhiwise
+1](https://useyourloaf.com/blog/swift-lazy-property-initialization/) Accessing `self`** : When the initial value of a property depends on other properties or methods of the instance, using a lazy property allows access to `self` within the closure, as the closure is executed after the instance is fully initialized. 

```swift
var spacing: CGFloat = 16.0 {
  didSet {
    stackView.spacing = spacing
  }
}

lazy var stackView: UIStackView = {
  let stackView = UIStackView()
  stackView.spacing = spacing
  return stackView
}()
```


This approach is convenient for declaring user interface components that depend on other instance properties. **Points to Remember** : 
- Within the closure, referencing other instance properties or methods doesn't require `self`.
 
- The closure isn't escaping, so there's no need to use `[weak self]` to avoid retain cycles.
 
- Be cautious of thread safety; if multiple threads access a lazy property simultaneously before it's initialized, there's no guarantee it will be initialized only once.


