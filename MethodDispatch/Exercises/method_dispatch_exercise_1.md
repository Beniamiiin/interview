## Задача 1

```
protocol MyProtocol {
	// func extensionMethod() // как поменяется результат, если разкоментить эту строчку?
}
struct MyStruct: MyProtocol {}
extension MyStruct {
    func extensionMethod() {
        print("In Struct")
    }
}
extension MyProtocol {
    func extensionMethod() {
        print("In Protocol")
    }
}
 
let myStruct = MyStruct()
let prot: MyProtocol = myStruct
 
myStruct.extensionMethod() // “In Struct”
prot.extensionMethod() // “In Protocol”
```