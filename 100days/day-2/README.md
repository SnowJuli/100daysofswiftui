# Booleans and advanced Strings
---

## Booleans

Booleans have only two possible values: true or false. These values can be changed by doing it manually with a reassignment, by using the .toggle function or by using an `!` in front of the boolean

Example: 

```swift
var isAttachable = false
isAttachable.toggle() // returns true
isAttachable = !isAttachable // returns false
```

## Combining Strings

In Swift you can combine strings together with the  `+` operator in combination of strings aswell as variables. 

## String Interpolation

This is a better way to join strings with variables since its more efficent in power and perfomance. It allows you also to implement integers into strings which is not possible with the `+` operator.

Example:

## String interpolation

Swift can handle variables by providing a backslash with brackets `\(variable)`

Example
```swift
var name = "Juli"
var age = 17
var str = "My name is \(name) and I'm \(age) years old"
```






