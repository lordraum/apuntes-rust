# Apuntes rust

## Ininiar proyecto rust

`cargo` --> Gestor de paquetes de rust.

`cargo new [project]`

`cargo.toml` --> Archivo manifiesto, o índice del proyecto (Algo así como un package.json en nodejs)

## Hello world

```rust
fn main() {
    println!("Hello, world!");
}
```

Ejecutar --> `cargo run en terminal`

## Variables

En rust las variables por defecto son inmutables, se debe usar `(;)` al declarar y asignar valor a una variable. Se recomienda usar `(_)` antes del nombre de la variable.

### Variable con inferencia de tipo

```rust
let _x: i32 = 10;
```

### Variable sin inferencia de tipo

```rust
let _y = 5;
```

### String format

```rust
"texto plano, {variable o dato}, más texto, {otra variable o dato}"
```

### Variable mutables

```rust
let mut _variable_num = 8;
let mut _prueba: i32;
```

### Constantes

```rust
const _PI: f32 = 3.1416;
```

### Shadowing

Es posible cambiar el valor de la variable y el tipado, es decir redefinir la variable.

