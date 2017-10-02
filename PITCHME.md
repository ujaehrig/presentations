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
Thread.start(new Runnable() {
    public void run() {
        System.out.println("I'm running in Thread: " + Thread.currentThread());
    }
});

Thread.start(() -> System.out.println("I'm running in Thread: " + Thread.currentThread()));

```
@[1-5]
@[7]

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




