# Complex data types
---

## Arrays

To declare an array, you simply create a new variable which has its content written in brackets like this `[item, item]`. Using the `.append()` function, you can append items of the same type at the end of the array. To get an item inside an array you use this line:

```swift
names = [2]
```

To remove an item from an array you use the `.remove()` function like this:

```swift
names.remove(at: 2)
```

You can also order an array by using `.sorted()` or `.reversed()`:

```swift
names.sorted()
names.reversed()
```

## Dictionaries 

In Dictionaries you can define a value with its own value name. If you want to fetch a value that is not in the dictionary, you can define a default value to return instead of `nil`. 

Example:
```swift
let capitals = [
	"Germany": "Berlin"
	"France": "Paris"
	"England": "London"
	"The Netherlands": "Amsterdam"
]

capitals["England"] // Returns London
capitals["Belgium", default: "unknown"] // Retunrns unknown 
```

## Enumerations

Enumerations allow you to use predefined values later in your code so you don't make typing mistakes later on. 

Example: 
```swift
enum seasons {
	case winter
	case summer
	case autumn
	case spring
}

var currentSeason = seasons.autumn
```

