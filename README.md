This repository serves as a public archive for the decompiled flattened device tree (fdt) for the Motorola Moto G6 (motorola-ali).

The flattened device tree blob was retrieved from the downstream kernel by booting the device into TWRP, and running `adb pull /sys/firmware/fdt` to extract the running, flattened device tree blob.

The device tree compiler (DTC) was then used to decompile the fdt blob into a human-readable device tree source (dts) file. The exact command was `dtc -I dtb -O dts ./fdt -o fdt.dts`

