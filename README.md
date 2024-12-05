This repository demonstrates a common error in Rust: creating multiple mutable borrows of the same variable. The `bug.rs` file contains the erroneous code, which attempts to create two mutable references (`y` and `z`) to the same variable (`x`). This violates Rust's borrowing rules, resulting in a compiler error.  The `bugSolution.rs` file shows how to correctly manage mutable borrows, either by using a single mutable reference or by restructuring the code to avoid the conflict.