# Miel

> Java, but a bit sweeter.

Miel is a Java compiler plugin that augments Java syntax with opinionated improvements.

## Changes

### Primitives

- `boolean` -> `bool`
- `byte` -> `i8`
- `short` -> `i16`
- `int` -> `i32`
- `long` -> `i64`
- `float` -> `f32`
- `double` -> `f64`

### Mutability

- `final var myVar` -> `var myVar`
- `var myVar` -> `mut var myVar`

### Extensibility

- `final class MyClass` -> `class MyClass`
- `class MyClass` -> `open class MyClass`

### Access

- `private` -> `(default)`
- `(default)` -> `internal`
- `public` -> `pub`

### Misc

- `new MyClass()` -> `MyClass()`
- `x instanceof X` -> `x is X`
- `while (true)` -> `loop`
