# Rust Ownership and Borrowing Example

This folder contains a Rust program written to understand the core concepts of:

- Ownership
- Borrowing
- Mutable References
- Struct and complex Struct
- impl Functions
- Updating values using `&mut`
- Printing original and updated data together

This program uses a complex structure (`User` and `Address`) and demonstrates how Rust handles memory safely.

---

## 📌 Concepts Covered

### ✔ Ownership
The original struct is stored separately before mutation to preserve initial values.

### ✔ Borrowing
A mutable reference is created using:

```rust
let user_ref = &mut user;
