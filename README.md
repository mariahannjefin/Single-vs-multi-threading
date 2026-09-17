# Single vs Multi Threading

## Use Case
Android Camera Application

## Objective
To demonstrate the difference between single-threading and multithreading and understand how thread execution affects the performance of an Android camera application.

## Single Threading
In a single-threaded approach, camera-related tasks are handled sequentially by one thread. This can cause delays when multiple operations need to be performed.

## Multithreading
In a multithreaded approach, multiple threads can handle different camera-related tasks concurrently, such as image processing, saving photos, and handling user interactions.

## Implementation
The programs are implemented in C and executed in Ubuntu.

- `singp.c` – Single-threading implementation
- `multip.c` – Multithreading implementation

## Compilation

### Single Threading

    gcc singp.c -o singp
    ./singp

### Multithreading

    gcc multip.c -o multip
    ./multip

## Output
The output screenshots demonstrate the execution of threads in both approaches.
