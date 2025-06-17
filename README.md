
Этот репозиторий содержит примеры использования RxJava для изучения программирования на Java.


- Базовые примеры использования RxJava (Observable, Observer, операторы)
- Примеры многопоточности (Schedulers)
- Работа с ошибками и их обработка
- Примеры комбинирования потоков данных
- И другие практические примеры


/src/main/java/
    /basics               - Основные концепции RxJava
        ○ CreatingObservables.java   - Способы создания Observable
        ○ HelloRxJava.java          - Простейший пример
        ○ Subscribers.java         - Различные варианты подписчиков
    
    /operators            - Операторы RxJava
        ○ FilteringOperators.java   - Фильтрация данных
        ○ TransformingOperators.java - Преобразование данных
        ○ UtilityOperators.java     - Вспомогательные операторы
    
    /multithread          - Многопоточность
        ○ SchedulersExample.java    - Работа с планировщиками
        ○ ConcurrencyExample.java   - Примеры параллельной работы
    
    /error                - Обработка ошибок
        ○ ErrorHandling.java        - Основные стратегии
        ○ RetryExamples.java        - Примеры повторных попыток
    
    /combining            - Комбинирование потоков
        ○ MergeAndConcat.java      - Слияние потоков
        ○ ZipAndCombine.java       - Комбинирование данных
    
    /advanced             - Продвинутые темы
        ○ Backpressure.java        - Работа с backpressure
        ○ CustomOperators.java     - Создание своих операторов
