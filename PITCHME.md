# Java 8 
## What's new?

+++

- Functional Interfaces
- Lambda Expressions
- Method References |
- Default Methods |
- Stream API |
- Date-Time API |

---

### Functional Interfaces

- java.util.function


---

### Lambda Expressions

- Uses functional interfaces
- Replacement for some anonymous classes |
-   but consider the **scope** | 
- Syntax: `(params) -> code` |

+++

```java
ExecutorService executorService = Executors.newCachedThreadPool();

executorService.submit(new Runnable() {
    @Override
        public void run() {
            out.println("Anonymous is in thread: " + currentThread());
        }
    });

executorService.submit(() -> out.println("Lambda is in thread: " + currentThread()));
```
@[3-8](with anonymous class)
@[10](with lambda)

+++

### Best practices

- **Use @FunctionalInterface** on functional interfaces
- **Avoid** too many default methods
- Use **parameter inference**
- **Omit** parentheses on single arguments
- Keep lambda expressions **short**

+++

### Best practices

- Avoid blocks
- Avoid return statements
- Avoid side effects
- Prefer method references

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




