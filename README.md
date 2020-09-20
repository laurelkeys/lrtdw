# rust-playground

Trying out this Rust thing... let's see how it goes 🦀

## book[`/`](book/)
Notes on [_the_ book](https://doc.rust-lang.org/book/) "The Rust Programming Language", together with code examples.

```bash
.
│
├── ch02-guessing-game/...
├── ch03-fibonacci/...
├── ch08-mean-median-mode/...
├── ch08-pig-latin/...
├── ch12-grep/...
├── ch14-add/...
├── ch14-art/...
├── ch15-cons-list/...
├── ch15-mock-object/...
├── ch15-weak-ref-tree/...
├── ch16-concurrency/...
├── ch17-blog/...
├── ch17-gui/...
├── ch19-hello-macro/...
├── ch19-pancakes/...
├── ch20-hello/...
│
└── notes.md            # complete book notes
```

## crust[`/`](crust/)
Coding along [Jon Gjengset](https://github.com/jonhoo)'s "[Crust of Rust](https://www.youtube.com/playlist?list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa)" video series.

```bash
.
├── strsplit/
│   └── src/lib.rs      # "Crust of Rust: Lifetime Annotations"
│
├── vecmac/
│   └── src/lib.rs      # "Crust of Rust: Declarative Macros"
│
├── iterators/
│   └── src/lib.rs      # "Crust of Rust: Iterators"
│
├── pointers/
│   └── src/            # "Crust of Rust: Smart Pointers and Interior Mutability"
│       ├── lib.rs
│       ├── cell.rs     # a mutable memory location
│       ├── refcell.rs  # a mutable memory location with dynamically checked borrow rules
│       └── rc.rs       # a single-threaded reference-counting pointer
│
└── panama/
    └── src/lib.rs      # "Crust of Rust: Channels"
```

## lrtdw[`/`](lrtdw/)
Following [Cliff L. Biffle](http://cliffle.com/about/)'s `unsafe`-first approach to "[Learn Rust the Dangerous Way](http://cliffle.com/p/dangerust/)" (LRtDW) series of articles.

```bash
.
├── nbody-c/
│   └── main.c          # reference C code, unchanged
│
├── nbody-rs/
│   ├── src/
│   │   └── main.rs     # Rust code, following LRtDW
│   └── Cargo.toml
│
└ make.py               # build script
```

## lrwetmll[`/`](lrwetmll/)
Following "[Learn Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/)" chapters.

```bash
.
└── lists/
    ├── src/
    │   ├── first.rs    # ch. 2, a bad singly-linked stack
    │   ├── second.rs   # ch. 3, an ok singly-linked stack
    │   ├── third.rs    # ch. 4, a persistent singly-linked stack
    │   ├── fourth.rs   # ch. 5, a bad but safe doubly-linked deque
    │   ├── fifth.rs    # ch. 6, an unsafe singly-linked queue
    │   └── lib.rs
    └── Cargo.toml
```
