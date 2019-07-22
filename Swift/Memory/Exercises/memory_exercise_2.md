## Задача 2

```
struct I {
    var x = 0
    
    var increment: (() -> ())?
}

var i = I()

i.increment = { i.x += 1 }

var copy = i
copy.increment?()
copy.increment?()
copy.increment?()
print(copy.x)
print(i.x)
```

Guess what’s the value of copy.x printed above? 0! You’d probably expect 3 and that copy holds a copy of i and copy.increment?() increments copy.x. But remember that closures and their environment can’t be copied. That’s why copy is a “partial” copy of i. Value of x has been copied, but property increment of copy holds a reference to increment of i with x of i in the captured environment. Calling copy.increment?() will follow the reference and increment value of x on the original i instead of copy.

https://desiatov.com/swift-reference-cycles#advanced