## Miel

> Java, but a bit sweeter.

Miel is a Java compiler plugin that augments Java syntax with opinionated improvements.

Here's the full list of changes:

- `boolean` -> `bool`
- `byte` -> `i8`
- `short` -> `i16`
- `int` -> `i32`
- `long` -> `i64`
- `float` -> `f32`
- `double` -> `f64`
- `final var myVar` -> `var myVar`
- `var myVar` -> `mut var myVar`
- `final class MyClass` -> `class MyClass`
- `class MyClass` -> `open class MyClass`
- `new MyClass()` -> `MyClass()`
- `x instanceof X` -> `x is X`