# drive-vla-wheels

Built wheels referenced by drive-vla's `uv.lock` through `find-links` for
platforms PyPI does not cover. Each release tag names the package set and the
build target. Wheels are built on the target machine (see
`scripts/slurm/build_spconv.sh` in drive-vla) and uploaded as release assets.

| Release | Contents | Built on |
|---|---|---|
| `aarch64-cu126-sm90-v1` | `cumm-0.7.13`, `spconv-2.3.8` (AOT, sm_90) for CPython 3.12, linked against CUDA 12.6 / GCC 13.3 | JSC JUPITER login node, 2026-10-08 |
