# Java8

1️⃣ Lambda Expressions

Write shorter and cleaner code

Used for functional programming

Removes boilerplate code (no need for anonymous classes)


2️⃣ Functional Interfaces

Interface with only one abstract method

Enables Lambda expressions

Common ones:

Runnable

Callable

Comparator

Predicate

Function

Consumer

Supplier

3️⃣ Stream API

Used to process collections (List, Set, Map)

Supports filtering, mapping, sorting, reducing

Key concepts:

filter

map

collect

forEach

reduce

Supports parallel processing

4️⃣ Method References

Shorthand for lambda expressions

Improves readability

Types:

Static method reference

Instance method reference

Constructor reference

5️⃣ Default Methods in Interfaces

Interfaces can now have method implementations

Helps in backward compatibility

Keyword used:

default

6️⃣ Static Methods in Interfaces

Interfaces can have static utility methods

Called using interface name

7️⃣ Optional Class

Helps avoid NullPointerException

Represents a value that may or may not be present

Key methods:

isPresent

ifPresent

orElse

orElseGet

orElseThrow

8️⃣ New Date and Time API (java.time)

Immutable and thread-safe

Replaces old Date and Calendar

Important classes:

LocalDate

LocalTime

LocalDateTime

ZonedDateTime

Period

Duration

9️⃣ Nashorn JavaScript Engine

Execute JavaScript code inside Java

Faster than Rhino (older engine)

🔟 CompletableFuture

Advanced asynchronous programming

Non-blocking execution

Better alternative to Future

Supports:

Chaining

Combining multiple async tasks

Exception handling

1️⃣1️⃣ Parallel Streams

Stream operations run in parallel

Uses Fork/Join framework

Improves performance for large data sets

1️⃣2️⃣ New Collection Methods

Added useful methods to Collection interface

Examples:

forEach

removeIf

spliterator

stream()

parallelStream()

1️⃣3️⃣ Map Enhancements

New useful methods:

forEach

getOrDefault

putIfAbsent

compute

computeIfAbsent

merge

1️⃣4️⃣ Base64 Encoding & Decoding

Built-in support for Base64

Types:

Basic

URL

MIME

1️⃣5️⃣ Type Annotations

Annotations can be applied anywhere

Helps in better static analysis

1️⃣6️⃣ Repeating Annotations

Same annotation can be used multiple times

1️⃣7️⃣ Improved JVM & Performance Enhancements

Better memory management

Faster execution

Internal optimizations
