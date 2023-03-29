This is my personal tracking repo for problematic interactions between the new trait solver in Rust
(`-Ztrait-solver=next`, rust-lang/rust#107374) and HIR typecheck, which relies on specific behaviors
of the old ("-Ztrait-solver=classic") solver such as eager normalization.

I'll use this to track minimal repros for these problematic cases in HIR typeck, and draft commits
that I've stashed in my personal rust fork for demo purposes, early code review, etc.

Mostly using this for the issue tracker since it's a bit easier to keep organized than a HackMD.
I was inspired by [solver-woes](https://github.com/lcnr/solver-woes) for this :heart:.
