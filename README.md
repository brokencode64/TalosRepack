# TalosRepack
A repack of the talos vmware ova with some compatibility fixes.

---
## Workflow

This repository simply repackages vmware ovas from [siderolabs/talos](https://github.com/siderolabs/talos) and replaces the `VMXNET3` network adapter with `E1000e` for compatibility. New releases are built upon a new tag push.
