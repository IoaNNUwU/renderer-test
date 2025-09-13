### List of all languages

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
