Every step is strictly ordered 

# Rust Core basics:
1. Setup with `Cargo` and ` rustc`; `Hello world!` 
2. Primitive data types, operators and `static Types`
3. Mutability
4. `References` Rust
5. `String`, `&str`
   1. `Heap` and `Stack` and basic model of computer memory 
6. `Struct`'s and `enum`'s
7. `Result` and `Optional`
8. First look at functions
    1. Introduction to functions
    2. Take a look at `encapsulation` and `abstraction` concepts
    3. Passing by `value` or `reference`
9. Conditionals, `match` and boolean
10. Loops
11. Slices
12. First look at `collections`
    1. Introduction of basic methods of `HashMap`, `HashSet` and `Vec`
13. `Traits`
    1. `Traits`
    2. Concept of `Interface` in OOP and `Traits` as implementation of it.  
    3. (and maybe `Traits` as type class from FP)


# Rust Core advanced:
1. `Default`, `Clone` and `Copy`
2. `Move semantic` 
3. `Smart pointers` 
4. `From/Into` traits 
5. `Error handling` and `?` in Rust
    1. Error propagation 
6. Advanced `Traits`
    1. Implementation rule 
    2. Trait bounds and `Where` keyword 
    3. Default Implementations and associated `type`'s 
    4. `impl` keyword; trait in return types and argument as trait
    5. Take a look at `GATs`
7. `Polymorphism` and `Dispatch` in Rust
    1. What is `Polymorphism` and how to use it
    2. What is `static` and `dynamic` dispatch
    3. `dyn` keyword and usage examples
    4. `Polymorphism` in Rust (https://www.brandons.me/blog/polymorphism-in-rust)
8. `lifetime`'s
9. `type safety pattern`
10. `generics IN type OUT`
11. `exhaustivity pattern`
12. Advanced functions: `Fn`'s traits
    1. `Fn`, `FnOnce`, `FnMut` traits
    2. What is `HOF`
13. `Closure`'s
14. Advanced `collections`
    1. `Big O`
    2. Usage of each collection; tips and tricks 
    3. Implementations of `Map`, `Set` and `List`
    4. Maybe implementation of collection with Rust as h/w
15. `Iterators`

# Rust main tools pool:
1. `Testing`
   1. Unit testing, Integration testing
   2. `Mocking` 
2. `Macro` and how to use it in Rust
   1. Procedural and/vs Declarative
   2. `Function-like` macros
   3. `Attribute` macros
   4. `Derive` macros
3. `anyhow` and `thiserror`
4. `Serde` and serialization and deserialization
5. `Loging`, `CLI args` and `env vars` 
    1. `log` crate, and `tracing`; Log levels
    2. `dot_env` crate
    3. `clap` crate  
6. `Async` concept and `tokio`


# Frameworks basics:
1. `Http` core principals and `API` design
   1. `MVC` architecture pattern; `DAO` and `DTO`
   2. `Axum` and/or `Actix`
   3. `Reqwest`
   4. Basics of `auth` - cookies and sessions
2. `SQL` and relational `DB`'s core principals
   1. What is `ORM`
   2. `DieselORM`, `SeaORM`
    