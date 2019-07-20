## Задача 1

```
let queue = DispatchQueue.main
print(0)
queue.async {
    print(1)
    queue.sync {
        print(2)
    }
    print(3)
}
print(4)

0
4
1
и все, deadlock, 2 не распечатается
```