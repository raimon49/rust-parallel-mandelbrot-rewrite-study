# rust-parallel-study

A rewrite of the following implementation with `rayon` crate

* https://github.com/raimon49/rust-parallel-mandelbrot-study

## Build & Run

```bash
$ cargo build --release
$ target/release/mandelbrot-rewrite /tmp/mandel.png 4000x3000 -1.20,0.35 -1,0.20
```

