### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.Example: `==` and `!=`** 

```swift
struct Person: Equatable {
    var name: String
    var age: Int

    static func == (lhs: Person, rhs: Person) -> Bool {
        return lhs.name == rhs.name && lhs.age == rhs.age
    }
}

let person1 = Person(name: "Alice", age: 25)
let person2 = Person(name: "Alice", age: 25)
let person3 = Person(name: "Bob", age: 30)

print(person1 == person2) // true
print(person1 != person3) // true
```
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.Example: `==` and `!=`** 

```swift
struct Person: Equatable {
    var name: String
    var age: Int

    static func == (lhs: Person, rhs: Person) -> Bool {
        return lhs.name == rhs.name && lhs.age == rhs.age
    }
}

let person1 = Person(name: "Alice", age: 25)
let person2 = Person(name: "Alice", age: 25)
let person3 = Person(name: "Bob", age: 30)

print(person1 == person2) // true
print(person1 != person3) // true
```
Example: `<` for Sorting** For comparisons (`<`, `>`), conform to `Comparable`.

```swift
struct Rectangle: Comparable {
    var width: Double
    var height: Double
    var area: Double { width * height }

    static func < (lhs: Rectangle, rhs: Rectangle) -> Bool {
        return lhs.area < rhs.area
    }
}

let r1 = Rectangle(width: 4, height: 5)  // area = 20
let r2 = Rectangle(width: 3, height: 6)  // area = 18

print(r1 < r2)  // false
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.Example: `==` and `!=`** 

```swift
struct Person: Equatable {
    var name: String
    var age: Int

    static func == (lhs: Person, rhs: Person) -> Bool {
        return lhs.name == rhs.name && lhs.age == rhs.age
    }
}

let person1 = Person(name: "Alice", age: 25)
let person2 = Person(name: "Alice", age: 25)
let person3 = Person(name: "Bob", age: 30)

print(person1 == person2) // true
print(person1 != person3) // true
```
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.Example: `==` and `!=`** 

```swift
struct Person: Equatable {
    var name: String
    var age: Int

    static func == (lhs: Person, rhs: Person) -> Bool {
        return lhs.name == rhs.name && lhs.age == rhs.age
    }
}

let person1 = Person(name: "Alice", age: 25)
let person2 = Person(name: "Alice", age: 25)
let person3 = Person(name: "Bob", age: 30)

print(person1 == person2) // true
print(person1 != person3) // true
```
Example: `<` for Sorting** For comparisons (`<`, `>`), conform to `Comparable`.

```swift
struct Rectangle: Comparable {
    var width: Double
    var height: Double
    var area: Double { width * height }

    static func < (lhs: Rectangle, rhs: Rectangle) -> Bool {
        return lhs.area < rhs.area
    }
}

let r1 = Rectangle(width: 4, height: 5)  // area = 20
let r2 = Rectangle(width: 3, height: 6)  // area = 18

print(r1 < r2)  // false
```


---

Overloading Compound Assignment Operators (`+=`, `-=`, `*=`, `/=`)** When overloading compound assignment operators, modify `lhs` in place by using `inout`.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.Example: `==` and `!=`** 

```swift
struct Person: Equatable {
    var name: String
    var age: Int

    static func == (lhs: Person, rhs: Person) -> Bool {
        return lhs.name == rhs.name && lhs.age == rhs.age
    }
}

let person1 = Person(name: "Alice", age: 25)
let person2 = Person(name: "Alice", age: 25)
let person3 = Person(name: "Bob", age: 30)

print(person1 == person2) // true
print(person1 != person3) // true
```
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.Example: `==` and `!=`** 

```swift
struct Person: Equatable {
    var name: String
    var age: Int

    static func == (lhs: Person, rhs: Person) -> Bool {
        return lhs.name == rhs.name && lhs.age == rhs.age
    }
}

let person1 = Person(name: "Alice", age: 25)
let person2 = Person(name: "Alice", age: 25)
let person3 = Person(name: "Bob", age: 30)

print(person1 == person2) // true
print(person1 != person3) // true
```
Example: `<` for Sorting** For comparisons (`<`, `>`), conform to `Comparable`.

```swift
struct Rectangle: Comparable {
    var width: Double
    var height: Double
    var area: Double { width * height }

    static func < (lhs: Rectangle, rhs: Rectangle) -> Bool {
        return lhs.area < rhs.area
    }
}

let r1 = Rectangle(width: 4, height: 5)  // area = 20
let r2 = Rectangle(width: 3, height: 6)  // area = 18

print(r1 < r2)  // false
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.Example: `==` and `!=`** 

```swift
struct Person: Equatable {
    var name: String
    var age: Int

    static func == (lhs: Person, rhs: Person) -> Bool {
        return lhs.name == rhs.name && lhs.age == rhs.age
    }
}

let person1 = Person(name: "Alice", age: 25)
let person2 = Person(name: "Alice", age: 25)
let person3 = Person(name: "Bob", age: 30)

print(person1 == person2) // true
print(person1 != person3) // true
```
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
**
### Swift Operator Overloading 
In Swift, you can overload operators to define custom behavior for existing operators (`+`, `-`, `*`, `/`, etc.) when used with your own types. This allows for more intuitive syntax when performing operations on custom objects.

---

**Basic Syntax** 
To overload an operator in Swift:
 
1. Define a `static` function inside the type (usually a `struct` or `class`).
 
2. Use the `operator` keyword followed by the function definition.
Example: Overloading `+` for a Custom Struct** 

```swift
struct Vector {
    var x: Double
    var y: Double

    static func + (lhs: Vector, rhs: Vector) -> Vector {
        return Vector(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
    }
}

let v1 = Vector(x: 3, y: 4)
let v2 = Vector(x: 1, y: 2)
let v3 = v1 + v2 // Vector(x: 4, y: 6)
```


---

Overloading Unary Operators (`-`, `!`, `~`)** Unary operators operate on a single operand. Define them as `prefix` or `postfix` if necessary.Example: Negation Operator (`-`)** 

```swift
struct Point {
    var x: Int
    var y: Int

    static prefix func - (point: Point) -> Point {
        return Point(x: -point.x, y: -point.y)
    }
}

let p1 = Point(x: 3, y: -7)
let p2 = -p1 // Point(x: -3, y: 7)
```


---

Overloading Comparison Operators (`==`, `<`, `>`)** For custom equality (`==`) and inequality (`!=`), conform to `Equatable`.Example: `==` and `!=`** 

```swift
struct Person: Equatable {
    var name: String
    var age: Int

    static func == (lhs: Person, rhs: Person) -> Bool {
        return lhs.name == rhs.name && lhs.age == rhs.age
    }
}

let person1 = Person(name: "Alice", age: 25)
let person2 = Person(name: "Alice", age: 25)
let person3 = Person(name: "Bob", age: 30)

print(person1 == person2) // true
print(person1 != person3) // true
```
Example: `<` for Sorting** For comparisons (`<`, `>`), conform to `Comparable`.

```swift
struct Rectangle: Comparable {
    var width: Double
    var height: Double
    var area: Double { width * height }

    static func < (lhs: Rectangle, rhs: Rectangle) -> Bool {
        return lhs.area < rhs.area
    }
}

let r1 = Rectangle(width: 4, height: 5)  // area = 20
let r2 = Rectangle(width: 3, height: 6)  // area = 18

print(r1 < r2)  // false
```


---

Overloading Compound Assignment Operators (`+=`, `-=`, `*=`, `/=`)** When overloading compound assignment operators, modify `lhs` in place by using `inout`.Example: `+=` Operator** 

```swift
struct Counter {
    var value: Int

    static func += (lhs: inout Counter, rhs: Int) {
        lhs.value += rhs
    }
}

var count = Counter(value: 10)
count += 5  // count.value is now 15
```


---

**Overloading Subscripts** 
Although not an operator, you can overload subscripts for custom behavior.


```swift
struct Matrix {
    private var grid: [[Int]]

    init(rows: Int, cols: Int, initialValue: Int = 0) {
        grid = Array(repeating: Array(repeating: initialValue, count: cols), count: rows)
    }

    subscript(row: Int, col: Int) -> Int {
        get { return grid[row][col] }
        set { grid[row][col] = newValue }
    }
}

var matrix = Matrix(rows: 2, cols: 2)
matrix[0, 1] = 5
print(matrix[0, 1]) // 5
```


---

**Defining Custom Operators** You can define completely new operators using `operator`.

```swift
infix operator **

extension Int {
    static func ** (lhs: Int, rhs: Int) -> Int {
        return Int(pow(Double(lhs), Double(rhs)))
    }
}

print(2 ** 3) // 8
```


---

**Conclusion** 
Operator overloading in Swift allows you to enhance readability and expressiveness in custom types. However, use it wisely—overloading too many operators can make code confusing rather than helpful.
