# libkagami

Standalone ASS subtitle parsing and manipulation library extracted from `pandora-toolchain`.

The crate re-exports the extracted modules at the crate root:

```rust
use libkagami::core::SubstationAlpha;
```

For compatibility with the original in-tree module paths, the nested module is also available:

```rust
use libkagami::libkagami::core::SubstationAlpha;
```
