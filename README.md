
# Этот репозиторий содержит примеры использования RxJava для изучения программирования на Java.

## Особенности проекта 

- Базовые примеры использования RxJava (Observable, Observer, операторы)
- Примеры многопоточности (Schedulers)
- Работа с ошибками и их обработка
- Примеры комбинирования потоков данных
- И другие практические примеры


## Структура проекта 
├── README.md
└── src
    ├── main
    │   └── java
    │       └── rx
    │           ├── Disposable.java
    │           ├── Observable.java
    │           ├── Observer.java
    │           ├── operators
    │           │   ├── Filter.java
    │           │   ├── FlatMap.java
    │           │   └── Map.java
    │           ├── Scheduler.java
    │           └── schedulers
    │               ├── Computation.java
    │               ├── IO.java
    │               └── Single.java
    ├── pom.xml
    └── test
        └── java
            └── rx
                ├── ObservableTest.java
                ├── OperatorsTest.java
                └── SchedulerTest.java

## Заупск проекта 

```
mnv clean install
```


