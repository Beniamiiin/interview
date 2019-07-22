## Задача 4

```
func makeIncrementer() -> (() -> Int, () -> Int) {
    var runningTotal = 0
    
    func incrementer() -> Int {
        runningTotal += 1
        return runningTotal
    }
    
    func incrementer2() -> Int {
        runningTotal += 1
        return runningTotal
    }
    
    return (incrementer, incrementer2)
}

let x = makeIncrementer()

x.0() // 1
x.1() // 2
```

https://forums.swift.org/t/capturing-structs-by-reference/3527