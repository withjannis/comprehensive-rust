---
minutes: 15
---

# Exercise: Fibonacci

The Fibonacci sequence begins with `[0,1]`. For n>1, the n'th Fibonacci number
is calculated recursively as the sum of the n-1'th and n-2'th Fibonacci numbers.

Write a function `fib(n)` that calculates the n'th Fibonacci number. When will
this function panic?

```rust,editable,should_panic
{{#include exercise.rs:fib}}
    if n < 2 {
        // The base case.
        todo!("Implement this")
    } else {
        // The recursive case.
        todo!("Implement this")
    }
}

{{#include exercise.rs:main}}
```

<details>

The Fibonacci sequence is described in more detail [here][1]. The first and
second cases are defined, after which it is calculated recursively.

</details>

[1]: https://oeis.org/A000045