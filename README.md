## Memory(MRC/ARC)

#### Теория
1. [Счетчик ссылок у класса и структуры?](Memory/Answers/memory_1.md)
2. [Устройства памяти в свифте? WWDC видео](Memory/Answers/memory_2.md)
3. [RunLoop + NSRunLoopMode + autoreleasepool + NSThread + NSTimer](Memory/Answers/memory_3.md)
4. [unowned vs weak](Memory/Answers/memory_4.md)

#### Практика
1. [Задача 1](Memory/Exercises/memory_exercise_1.md)

## Multithreading(NSOperation/GCD)

#### Теория
1. [Отличие NSOperation и GCD](Multithreading/Answers/multithreading_1.md)
2. [GCD (group, barrier, sepahore)](Multithreading/Answers/multithreading_2.md)
3. [deadlock/livelock](Multithreading/Answers/multithreading_3.md)
4. [Как работает async и sync? Как работает под капотом? Как это связано с RunLoop?](Multithreading/Answers/multithreading_4.md)
5. [На каком потоке работает NSOperationQueue?](Multithreading/Answers/multithreading_5.md)
6. [В чем разница между потоками и очередями?](Multithreading/Answers/multithreading_6.md)
7. [Может ли быть у очереди несколько потоков, а наоборот?](Multithreading/Answers/multithreading_7.md)
8. [NSThread если не разбудить ранлуп умрет ли поток после выполнения одного цикла?](Multithreading/Answers/multithreading_8.md)
9. [Если запустить приложение в main.m без @autorealesepool что будет?](Multithreading/Answers/multithreading_9.md)

#### Практика
1. [Задача 1](Multithreading/Exercises/multithreading_exercise_1.md)
2. [Задача 2](Multithreading/Exercises/multithreading_exercise_1.md)
3. [Задача 3](Multithreading/Exercises/multithreading_exercise_1.md)

## Value and Reference types

#### Теория
1. [Какие структуры к чему относятся?](ValueAndReferenceTypes/Answers/value_and_reference_types_1.md)
2. [Какое отличие между типами?](ValueAndReferenceTypes/Answers/value_and_reference_types_2.md)
3. [Copy on write? Как реализовать самому?](ValueAndReferenceTypes/Answers/value_and_reference_types_3.md)

#### Практика
1. [Задача 1](ValueAndReferenceTypes/Exercises/value_and_reference_types_exercise_1.md)

## Method dispatch

#### Теория
1. [Какие есть?](MethodDispatch/Answers/method_dispatch_1.md)
2. [Где какие методы используются?](MethodDispatch/Answers/method_dispatch_2.md)
3. [Table Witness Table/Protocol Witness Table](MethodDispatch/Answers/method_dispatch_3.md)

#### Практика

1. [Задача 1](MethodDispatch/Exercises/method_dispatch_exercise_1.md)

## Generics

#### Теория
1. [В классах](Generics/Answers/generics_1.md)
2. [В структурах](Generics/Answers/generics_2.md)
3. [В протоколах(associatedtype, Swift Type Erasure)](Generics/Answers/generics_3.md)
4. [В енамах](Generics/Answers/generics_4.md)

#### Практика

*TODO*

## Stack and Heap

#### Теория
1. [Где инициализируется структура, а где класс?](StackAndHeap/Answers/stack_and_heap_1.md)
2. [Почему Array в свифте структура, а не класс?](StackAndHeap/Answers/stack_and_heap_2.md)
3. [Если инициализировать класс в функции, где он создатся на стэке или в куче?](StackAndHeap/Answers/stack_and_heap_3.md)
4. [wwdc 2016 stake heap](StackAndHeap/Answers/stack_and_heap_4.md)

#### Практика

*TODO*

## Architecture

#### Теория
1. [SOLID](Architecture/Answers/architecture_1.md)
2. [DRY/KISS/YAGNI](Architecture/Answers/architecture_2.md)
3. [Dessign patterns](Architecture/Answers/architecture_3.md)

#### Практика

*TODO*

## UIKit

#### Теория
1. [intrinsicContentSize](UIKit/Answers/uikit_1.md)
2. [content hugging and content compression resistance priorities](UIKit/Answers/uikit_2.md)
3. [calayer/uiview](UIKit/Answers/uikit_3.md)
4. [shouldRasterize](UIKit/Answers/uikit_4.md)
5. [viewWillLayoutSubviews](UIKit/Answers/uikit_5.md)
6. [Responder Chain](UIKit/Answers/uikit_6.md)
7. [uiview calayer animation](UIKit/Answers/uikit_7.md)
8. [anchor](UIKit/Answers/uikit_8.md)
9. [frame vs bounds, повороты](UIKit/Answers/uikit_9.md)

#### Практика

*TODO*

## Storage

#### Теория
1. [CoreData](Storage/Answers/storage_1.md)
2. [UserDefaults](Storage/Answers/storage_2.md)
3. [Keychain](Storage/Answers/storage_3.md)

#### Практика

*TODO*

## Access Control

#### Теория
1. [Разница между static и class?](AccessControl/Answers/access_control_1.md)
2. [Разница между public и open?](AccessControl/Answers/access_control_2.md)

#### Практика

*TODO*

## Algoritms and Data Structures

#### Теория
1. [Сложность алгоритма, Big(O)](AlgoritmsAndDataStructures/Answers/algoritms_and_data_structures_1.md)
2. [Сортировки](AlgoritmsAndDataStructures/Answers/algoritms_and_data_structures_2.md)
3. [Алгоритмы поиска](AlgoritmsAndDataStructures/Answers/algoritms_and_data_structures_3.md)
4. [Сложности операций в Array](AlgoritmsAndDataStructures/Answers/algoritms_and_data_structures_4.md)
5. [Сложности операций в Dictionary](AlgoritmsAndDataStructures/Answers/algoritms_and_data_structures_5.md)

#### Практика

*TODO*

## Advanced

#### Теория
1. [Как устроен словарь под капотом?](Advanced/Answers/advanced_1.md)
2. [Как устроен массив в памяти?](Advanced/Answers/advanced_2.md)
3. [Что нового в Swift 5?](Advanced/Answers/advanced_3.md)
4. [Optional closure, почему escaping?](Advanced/Answers/advanced_4.md)
5. [SwiftClass, side_table](Advanced/Answers/advanced_5.md)

#### Практика

*TODO*