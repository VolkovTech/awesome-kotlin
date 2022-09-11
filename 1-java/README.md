# Java

1. [**Java Core**](1-java-core/README.md)
   - I part
      - Exceptions
      - Enum
      - Strings
      - Object initialization. The order of initialization.
      - Static
      - Keywords, access modifiers
      - Interfaces vs abstract classes, similarities/differences
      - Primitives and wrappers (Why wrappers are needed)
      - Object, its methods
   - II part
      - Annotations
      - Reflection
      - Generics
   - III part
      - Wildcard, invariance and covariance, super и extends
        
2. [**Java Collections**](2-java-collections/README.md)
   - I part
      - Difference between array and collections
      - Iterator
      - Collection tree (briefly about each collection interface)
   - II part
      - Sortable Collections
      - HashMap, HashSet
      - ArrayList, LinkedList
   - III part
      - TreeMap + complexity of search, add, remove

3. [**Java Functional Programming**](3-java-functional-programming/README.md)
   - I part
      - Stream (General concepts)
      - Lambda
      - Functional interface
   - II part
      - What is the difference between a lambda and an anonymous class?
   - III part
      - How does the stream works?

  
4. [**Java JDBC**](4-java-jdbc/README.md)
    - I part
        - Ход запроса в БД
        - JDBC драйвер
    - II part
        - Отличия между statements
        - Уровни изоляций транзакций
              
5. [**Java Concurrency**](5-java-concurrency/README.md)
    - I part
        - Thread
        - JMM
        - Synchronized
    - II part
        - Thread pool
        - Atomic Long, Double, Reference
        - Потокобезопасные коллекции
        - Volatile
        - Как обеспечивается HB участков кода в java приложении
        - Happens Before
        - Deadlock
    - III part
        - Специфика работы параллельных стримов
        - Fork Join Pool
    
6. [**Java JVM**](6-java-jvm/README.md)
    - I part
        - Сборщик мусора (Общий принцип работы)
        - Хип, стек
        - Как работает JVM? (Те что происходит с кодом который мы пишем)
        - JVM, JDK
    - II part
        - JIT комлиллятор (что такое)
        - Jvm и GC флаги
        - Класслоадеры
        - Основные сборшики мусора
    - III part
        - Frames
        - Принцип работы Jit компиллятора

7. [**JVM lover**](7-jvm-lover/README.md)
    - I part
        - JMeter, wrk (k6) (долбежка приложения любым способом)
    - II part
        - VisualVM

8. [**Maven/Gradle**](8-maven-gradle/README.md)
   - I part
       - Structure of pom.xml
       - Assembly phases (compile, test, package, install, deploy)
       - Purpose of each phase
   - II part
       - Resolving dependency conflicts
       - Setting up repositories
       - Plugin (dependency) management
       - Bom
       - Parent
       - Multi-Module Projects
       - Profiles
   - III part
       - Plugin Development
