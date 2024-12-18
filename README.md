# 📥 ChicKernel permalinks
### [**GitHub Releases**](https://github.com/chickendrop89/device_xiaomi_unified-kernel/releases/latest) | [**SourceForge mirror**](https://sourceforge.net/projects/chickernel-xiaomi-tapas-kernel) | [**XDA Forums thread**](https://xdaforums.com/t/kernel-chickernel-a-kernel-optimized-for-smoothness-and-low-memory.4678538) 

# 📝 Note:
This kernel is tuned for these SDM685 (`sm6225-AD`) devices:
- Xiaomi Redmi Note _12_ 4G (`topaz` / `tapas`)
- Xiaomi Redmi Note _13_ 4G (`sapphire` / `sapphiren`)

# 🏗️ Notes (for developers):
**Cloning this source**:
1. *This repo has kernelSU as a git submodule*. This means it has to be cloned with `--recurse-submodules`
2. Since this is default branch, use the `-b` switch to clone a different one (eg. `android13-5.15-lts`)
3. You can use the `--depth=1` argument to make a lighter shallow clone (not recommended)

**Upstreaming kernelSU**:
- Change directory to your source directory and run:
```shell
git submodule update --init --remote
```

**This kernel is built with these configurations:**
- `build.config.gki.aarch64.chickernel`
- `build.config.gki.aarch64.chickernel.ksu`

**This kernel is built with a newer toolchain as defined in `build.config.constants`**
- Ensure you have the correct prebuilt downloaded from [this site](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+/refs/heads/main)

# ⛔ Report Issues
Please [report issues here](https://github.com/chickendrop89/device_xiaomi_unified-recovery/issues), or to my telegram
