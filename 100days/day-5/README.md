# Conditions
---

## If-Statements

If-Statements check if a condition is true or false and can execute code based on its result. Conditions can be expressed by booleans but aswell as by providing logical operators like `< , > , >= , <= , ==`

Example:
```swift
var result = 85

if result >= 80 {
	print("Congrats, you passed")
}
```

If you want to check for multiple conditions you can use the `&&` (and) expression or `||` (or).

## If-Else-Statements

If you want to check for other conditions but with different results you just use the `else if`  keyword until the last check which should always be used with the `else`  keyword. 

Example:
```swift
var result = 85

if result >= 80 {
	print("Congrats, you passed")
} else if result < 70 {
	print("At least you tried your best")
} else {
	print("What?")
}
```

## Switch Statements

Switch Statements are a very fast way of checking a condition. Instead of having `else if` chains you use `case` to set your value and the code that should be executed. Switch Statements can also be used with enums. `default:` value must be used if you want to display a default value.

```swift
switch forecast {
case .sun:
    print("It should be a nice day.")
case .rain:
    print("Pack an umbrella.")
case .wind:
    print("Wear something warm")
case .snow:
    print("School is cancelled.")
default:
    print("Our forecast generator is broken!")
}
```



