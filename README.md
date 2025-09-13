### List of all languages

#### `Cucumber`:
```Cucumber
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `abap`:
```abap
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `ada`:
```ada
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `ahk`:
```ahk
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `apacheconf`:
```apacheconf
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `applescript`:
```applescript
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `as`:
```as
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `as3`:
```as3
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `asy`:
```asy
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `bash`:
```bash
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `bat`:
```bat
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `befunge`:
```befunge
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `blitzmax`:
```blitzmax
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `boo`:
```boo
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `brainfuck`:
```brainfuck
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `c`:
```c
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `cfm`:
```cfm
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `cheetah`:
```cheetah
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `cl`:
```cl
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `clojure`:
```clojure
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `cmake`:
```cmake
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `coffeescript`:
```coffeescript
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `console`:
```console
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `control`:
```control
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `('control')`:
```('control')
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `cpp`:
```cpp
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `csharp`:
```csharp
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `css`:
```css
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `cython`:
```cython
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `d`:
```d
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `delphi`:
```delphi
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `diff`:
```diff
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `dpatch`:
```dpatch
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `duel`:
```duel
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `dylan`:
```dylan
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `erb`:
```erb
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `erl`:
```erl
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `erlang`:
```erlang
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `evoque`:
```evoque
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `factor`:
```factor
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `felix`:
```felix
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `fortran`:
```fortran
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `gas`:
```gas
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `genshi`:
```genshi
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `gitignore`:
```gitignore
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `glsl`:
```glsl
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `gnuplot`:
```gnuplot
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `go`:
```go
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `groff`:
```groff
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `haml`:
```haml
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `haskell`:
```haskell
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `html`:
```html
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `hx`:
```hx
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `hybris`:
```hybris
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `ini`:
```ini
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `io`:
```io
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `ioke`:
```ioke
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `irc`:
```irc
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `jade`:
```jade
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `java`:
```java
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `js`:
```js
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `jsp`:
```jsp
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `lhs`:
```lhs
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `llvm`:
```llvm
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `logtalk`:
```logtalk
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `lua`:
```lua
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `make`:
```make
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `'Makefile',`:
```'Makefile',
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `'makefile',`:
```'makefile',
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `'GNUmakefile')`:
```'GNUmakefile')
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `mako`:
```mako
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `maql`:
```maql
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `mason`:
```mason
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `'autohandler',`:
```'autohandler',
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `'dhandler')`:
```'dhandler')
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `markdown`:
```markdown
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `modelica`:
```modelica
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `modula2`:
```modula2
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `moocode`:
```moocode
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `mupad`:
```mupad
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `mxml`:
```mxml
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `myghty`:
```myghty
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `'autodelegate')`:
```'autodelegate')
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `nasm`:
```nasm
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `newspeak`:
```newspeak
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `objdump`:
```objdump
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `objectivec`:
```objectivec
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `objectivej`:
```objectivej
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `ocaml`:
```ocaml
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `ooc`:
```ooc
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `perl`:
```perl
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `php`:
```php
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `postscript`:
```postscript
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `pot`:
```pot
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `pov`:
```pov
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `prolog`:
```prolog
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `properties`:
```properties
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `protobuf`:
```protobuf
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `py3tb`:
```py3tb
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `pytb`:
```pytb
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `python`:
```python
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `'SConstruct',`:
```'SConstruct',
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `'SConscript',`:
```'SConscript',
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `r`:
```r
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `rb`:
```rb
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `'Rakefile',`:
```'Rakefile',
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `rconsole`:
```rconsole
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `rebol`:
```rebol
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `redcode`:
```redcode
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `rhtml`:
```rhtml
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `rst`:
```rst
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `sass`:
```sass
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `scala`:
```scala
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `scaml`:
```scaml
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `scheme`:
```scheme
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `scss`:
```scss
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `smalltalk`:
```smalltalk
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `smarty`:
```smarty
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `sourceslist`:
```sourceslist
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `splus`:
```splus
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `sql`:
```sql
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `sqlite3`:
```sqlite3
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `squidconf`:
```squidconf
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `ssp`:
```ssp
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `tcl`:
```tcl
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `tcsh`:
```tcsh
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `tex`:
```tex
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `text`:
```text
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `v`:
```v
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `vala`:
```vala
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `vbnet`:
```vbnet
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `velocity`:
```velocity
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `vim`:
```vim
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `xml`:
```xml
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `xquery`:
```xquery
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `xslt`:
```xslt
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```

#### `yaml`:
```yaml
error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound
note: `'b` differs between the trait and impl
   --> src/lib.rs:7:17
    |
5   | impl<'a> std::str::FromStr for Keyword<'a> {
    | ------------------------------------------ in this impl...
6   |     type Err = InvalidKeyword;
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^  -- this lifetime bound makes `'b` early-bound
    |                 |
    |                 `'b` is early-bound
    |
   ::: /playground/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/src/rust/library/core/src/str/traits.rs:816:1
    |
816 | pub trait FromStr: Sized {
    | ------------------------ in this trait...
...
841 |     fn from_str(s: &str) -> Result<Self, Self::Err>;
    |                    ^ `'_` is late-bound

error[E0195]: lifetime parameters do not match the trait definition
   --> src/lib.rs:7:17
    |
7   |     fn from_str<'b: 'a>(s: &'b str) -> Result<Self, Self::Err> {
    |                 ^^
    |
    = note: lifetime parameters differ in whether they are early- or late-bound

error: could not compile `playground` (lib) due to 1 previous error
```
