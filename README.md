# Android kernel building script

## Little build system to build Android kernel sources

- Includes GCC and Clang support
- Managed with config files
- Automatic AnyKernel3 packing

## Instructions

- Add a config for your kernel in `configs/` (check the example config in configs/examples/example)
- Add kernel sources in `kernels/`
- `./build config [-c]`

Arguments:

    config - name of the config to use

    -c or --clean - do make clean before building
