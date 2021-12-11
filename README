# Minimal reproduction of cargo feature weirdness.

Calling `cargo build` or `cargo test` from the `my-crate` dir succeeds.  
Calling either from `my-crate/tests/helper` fails with:

```
error: failed to select a version for `my-crate`.
    ... required by package `test-helper v0.1.0 (/home/wcarv/Code/dep_ex/my-crate/tests/helper)`
versions that meet the requirements `=0.1.0` are: 0.1.0

the package `test-helper` depends on `my-crate`, with features: `test-helper` but `my-crate` does not have these features.


failed to select a version for `my-crate` which could resolve this conflict
```