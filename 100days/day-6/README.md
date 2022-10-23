# Loops
---

## for loop

In for loops you can run code over an collection of items from a set, array etc. In this example you temporarily store all the items from `platforms` in `os`. This allows it to execute the code multiple times until you run out of items.

Example:
```swift
let platforms = ["iOS", "macOS", "tvOS", "watchOS"]

for os in platforms {
    print("Swift works great on \(os).")
}
```

You can also define a range like `1...12 which would store all numbers of 1 to 12 in i for every loop.

## while loop

A while loop runs as long as the given condition is true.

Example:
```swift
var countdown = 10

while countdown > 0 {
    print("\(countdown)…")
    countdown -= 1
}

print("Blast off!")
```
