# Loops Exit Ticket

Fork and clone this repo. On your fork, answer and commit the follow questions. When you are finished, submit the link to your repo on Canvas.

## Question 1

What will the code below print?

```swift
var myNum = 8

for number in 4..<8{
    if number == 7 {
        break
    } else {
        myNum += number
    }
}

print(myNum)
```

## Question 2

Which of the following loops will print out all the numbers between 1 and 100, inclusive?  Select all that apply.

**A)**
```swift
for i in 1..<100 {
    print(i)
}
```

**B)**
```swift
for j in 1...100 {
    print(j)
}
```

**C)**
```swift
for k in 1..<1000 where k < 101 {
    print(k)
}
```

**D)**
```swift
for l in 1...100 where _ < 101 {
    print(l)
}
```

## Question 3

How many times will the code below print **"Nesting!"** ?

```swift
for _ in 1...10{
    for _ in 1...10{
        print("Nesting!")
    }
}
```

## Question 4

Which of the loops below will run forever? Select all that apply.

**A)**
```swift
var q = 0

while q%2 != 1 {
    print("Hello Problem Two!")
    q += 2
}
```

**B)**
```swift
var r = 0

while r < 10 {
    print("Hi there!")
    r += 11
}
```

**C)**
```swift
var s = 0

while 3 != 3 {
    print("Howdy!")
    s += 1
}
```

**D)**
```swift
var t = 0

while t == t{
    print("Ahoy-hoy!")
    t += 1
}
```
