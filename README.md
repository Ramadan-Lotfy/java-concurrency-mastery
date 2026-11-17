
# Java Concurrency Mastery

A comprehensive, hands-on guide to mastering concurrency in Java.

Learn how Java threads work, understand the differences between
platform and virtual threads, explore synchronization mechanisms,
and build scalable concurrent applications.

From fundamentals to advanced JVM concurrency concepts.

## Learning Objectives

By completing this repository, you will be able to:

- Understand processes, threads, concurrency, and parallelism.
- Create and manage Java threads.
- Understand platform threads and virtual threads.
- Work with ExecutorService, Future, and CompletableFuture.
- Understand synchronization and thread safety.
- Prevent race conditions, deadlocks, and livelocks.
- Apply Java Memory Model principles.
- Understand virtual thread scheduling and internals.
- Choose the appropriate concurrency mechanism for each workload.
- Build and benchmark real-world concurrent applications.

## Technology Stack

| Technology | Purpose |
|---|---|
| Java 21+ | Core language and concurrency APIs |
| Maven | Dependency and build management |
| JUnit 5 | Automated testing |
| JMH | Performance benchmarking |
| Java Flight Recorder | Performance analysis |
| GitHub Actions | Continuous integration |

## Prerequisites

- Basic Java programming knowledge.
- Familiarity with object-oriented programming.
- Basic understanding of exceptions and collections.
- JDK 21 or later.
- Maven 3.9 or later.

## Learning Roadmap

### Phase 1: Repository Foundation
- Project structure
- Maven configuration
- Documentation conventions
- Build and testing infrastructure

### Phase 2: Concurrency Fundamentals
- Processes vs threads
- Concurrency vs parallelism
- Thread lifecycle and states
- Thread creation
- Runnable, Callable, and Future

### Phase 3: Platform Threads
- Creating platform threads
- Thread pools
- ExecutorService
- Scheduled executors
- ForkJoinPool

### Phase 4: Synchronization
- Race conditions
- synchronized
- Intrinsic locks
- ReentrantLock
- ReadWriteLock
- StampedLock
- Semaphore
- CountDownLatch
- CyclicBarrier
- Phaser

### Phase 5: Thread Communication
- wait and notify
- volatile
- Atomic variables
- ThreadLocal
- BlockingQueue
- Producer-consumer pattern
- Concurrent collections

### Phase 6: Advanced Concurrency
- Java Memory Model
- Happens-before relationships
- Memory visibility
- Deadlocks and livelocks
- Starvation
- Lock-free programming
- False sharing

### Phase 7: Virtual Threads
- Creating virtual threads
- Thread-per-task execution
- Virtual thread scheduler
- Carrier threads
- Mounting and unmounting
- Pinning
- Interruption and cancellation
- ThreadLocal considerations
- Resource management
- Best practices

### Phase 8: Modern Java Concurrency
- CompletableFuture
- Structured concurrency
- Scoped values
- Advanced task coordination

### Phase 9: Concurrency Patterns
- Producer-consumer
- Thread-per-task
- Fan-out/fan-in
- Pipeline
- Bounded concurrency

### Phase 10: Real-World Projects
- Concurrent web crawler
- Parallel file processor
- Concurrent banking system
- High-concurrency HTTP server
- Performance benchmarking suite

## Running the Project

Compile:

```bash
mvn clean compile
```

Run tests:

```bash
mvn test
```

Package:

```bash
mvn clean package
```

## Java Version Compatibility

Java 21 is the minimum supported version.

Examples will document their required Java versions.
Features introduced after Java 21 will be clearly identified.

The repository will distinguish between stable Java features
and preview features requiring additional JVM/compiler flags.

## Repository Structure

```text
src/
├── main/java/com/mastery/concurrency/
│   ├── fundamentals/
│   ├── platformthreads/
│   ├── synchronization/
│   ├── communication/
│   ├── executors/
│   ├── virtualthreads/
│   ├── advanced/
│   ├── patterns/
│   └── realworld/
│
└── test/java/com/mastery/concurrency/
```

## Learning Philosophy

Every topic aims to include:

1. Concept explanation.
2. Internal implementation details.
3. Runnable Java examples.
4. Expected output.
5. Common mistakes and pitfalls.
6. When to use it.
7. When not to use it.
8. Practical exercises.
9. Automated tests where applicable.

## Contributing

Contributions, corrections, and improvements are welcome.

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the MIT License.
See [LICENSE](LICENSE).
