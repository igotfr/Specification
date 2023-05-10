## Primitive Types

type | name | description | Langs
---- | ---- | ----------- | -----
! | never | The ! type, also called “never” | Rust
never | | The ! type, also called “never” | Typescript

type | name | description | Langs
---- | ---- | ----------- | -----
bool | 	The boolean type. `true` or `false`. | Rust, Zig
char | A character type | Rust

### Unsigned Integers
type | description | Langs
---- | ----------- | -----
u8 | The 8-bit unsigned integer type | Rust, Zig
u16 |	The 16-bit unsigned integer type | Rust, Zig
u32	| The 32-bit unsigned integer type | Rust, Zig
u64	| The 64-bit unsigned integer type | Rust, Zig
u128 | The 128-bit unsigned integer type | Rust, Zig
usize | The pointer-sized unsigned integer type | Rust, Zig

### Signed Integers
type | description | Langs
---- | ----------- | -----
i8 | The 8-bit signed integer type | Rust, Zig
i16 | The 16-bit signed integer type | Rust, Zig
i32 |	The 32-bit signed integer type | Rust, Zig
i64	| The 64-bit signed integer type | Rust, Zig
i128 | The 128-bit signed integer type | Rust, Zig
isize | The pointer-sized signed integer type | Rust, Zig

### Pointers and References
type | name | description | Langs
---- | ---- | ----------- | -----
*const T | immutable pointer | Raw, unsafe pointers, *const T, and *mut T | Rust
*mut T | mutable pointer | Raw, unsafe pointers, *const T, and *mut T | Rust
&T | reference | References, &T and &mut T | Rust
&mut T | mutable reference | References, &T and &mut T | Rust

### Zero Bit Types
type | name | description | Langs
---- | ---- | ----------- | -----
[T; 0] | 0-array | An empty array | Rust
() | unit | The () type, also called “unit” | Rust

### Compound Types
type | name | description | Langs
---- | ---- | ----------- | -----
[T; N] | array | A fixed-size homogeneous array, denoted `[T; N]`, for the element type, `T`, and the non-negative compile-time constant size, `N` | Rust
(T1, T2, ..) | tuple | A finite heterogeneous sequence, `(T, U, ..)` | Rust
[T] | slice | A dynamically-sized view into a contiguous sequence, `[T]`. Contiguous here means that elements are laid out so that every element is the same distance from its neighbors | Rust

