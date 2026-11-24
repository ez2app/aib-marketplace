# AIB Marketplace (`aib-marketplace/v1`)

Official plugin catalog for **AIB 2.0** (`~/.ez2-aib/plugins/<name>/`).

## Rules
- Every listed plugin must point to an immutable release asset (`https://github.com/.../releases/download/...`) with a 64-hex `sha256`.
- AIB verifies `sha256` before installing or running any plugin binary.
