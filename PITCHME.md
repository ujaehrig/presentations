# Java 8 
## What's new?

+++

- Lambda Expressions
- Method References |
- Default Methods |
- Stream API |
- Date-Time API |

---

### Lambda Expressions

- Instead of anonymous class
- Syntax: `(params) -> code`

+++

```java
final ExecutorService executorService = Executors.newCachedThreadPool();

executorService.submit(new Runnable() {
    @Override
        public void run() {
            System.out.println("Anonymous is in thread: " + currentThread());
        }
    });

executorService.submit(() -> System.out.println("Lambda is in thread: " + currentThread()));
```
@[3-8]
@[10]

---

### Method References

- Instead of Lambda

+++

```

```


---

### Default Methods

---

### Stream API

---

### Data-Time API




