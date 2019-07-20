## Задача 2

```
let queue = DispatchQueue.global()
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
2
3
```