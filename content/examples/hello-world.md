---
title: "hello world"
date: 2023-06-22T12:00:00-06:00
draft: false
---

the `use` keyword imports a dependency into scope

```rust {.codebox}
use debug::PrintTrait;

fn main() {
    'Hello, world!'.print();
}
```

now, run the tests with `cairo-run hello_world.cairo`

```bash
[DEBUG] Hello, world!                   (raw: 5735816763073854953388147237921)

Run completed successfully, returning []
```