## Задача 1

```
class A {
    weak var b: B?
}

class B {
    weak var a: A?
}

weak var a: A?
weak var b: B?

func configure() {
    a = A()
    b = B()
    a?.b = b
    b?.a = a
    print(a) // В плейграунде будет не nil, а в проекте будет nil
}

configure()

print(a) // nil
print(b) // nil
print(a?.b) // nil
print(b?.a) // nil
```