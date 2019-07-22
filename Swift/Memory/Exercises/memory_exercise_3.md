## Задача 3

```
class MyClass {
    
    var i = 1
    
}

struct MyStruct {
    
    var i = 1
    var myClass = MyClass()
    
    func printik() {
        print(i + myClass.i)
    }
}

var original = MyStruct()
original.i = 2
original.myClass.i = 3

var copyOfStruct = original
copyOfStruct.i = 5
copyOfStruct.myClass.i = 5

copyOfStruct.printik() // 10
original.printik() // 7
```

Guess what’s the value of copy.x printed above? 0! You’d probably expect 3 and that copy holds a copy of i and copy.increment?() increments copy.x. But remember that closures and their environment can’t be copied. That’s why copy is a “partial” copy of i. Value of x has been copied, but property increment of copy holds a reference to increment of i with x of i in the captured environment. Calling copy.increment?() will follow the reference and increment value of x on the original i instead of copy.

https://desiatov.com/swift-reference-cycles#advanced