Intro Chapter 3
===

## UI Elements

In iOS we make views by dragging UI elements onto a screen in a storyboard file. Each of these elements corresponds to something you will see on your app if you run it on your phone. There are specific elements to fit different use cases, here are a few:

- `UILabel`: for displaying text on the screen
- `UIButton`: for displaying text that a user can tap
- `UISlider`: a sliding button you can drag to get a value
- `UIImageView`: a view that holds an image
- `UIView`: an empty view that you can customize to just about anything

## Custom Types

We know of such types as `String`, `Int` and `Bool`, but we can create our own types as well.

These custom types that we create will have two types of information in them:

1. Data (variables)
2. Action (functions, also called methods)

To create your own custom type, you can use the following syntax:

```swift
// Create a custom type called `Person`
class Person: NSObject {
    
    var name: String = "Josh"

    func sayHello() {
        print("Hello, my name is \(Josh)")
    }
}

// Use that custom type
let josh = Person() // create an object by calling its class name like a function
josh.sayHello() // prints 'Hello, my name is Josh'
```

We can call functions on an object or access variables inside an object using a .[varOrFuncName]. For instance in the above demo, `print("\(josh)")` would print `Josh` to the console.

Custom types are used to help us organize data and pieces of our program. For example Apple has a custom type called `UIView` that helps us interact with any UI elements on the screen.