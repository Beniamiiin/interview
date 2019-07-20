## Задача 1

Не хватает `mutating`
 
```
struct IntStack {
    
    var items = [Int]()
    
    func add(x: Int) {
        items.append(x)
    }
    
}
```