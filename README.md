# vl6180x-rs
Rust crate for VL6180X Proximity and ambient light sensing (ALS) module

This is currently a minimum viable implementation to get proximity measurements. The example code is based on a STM32G070 microcontroller. The example can be run using

```bash
cargo run --example oneshot
```

This will build and flash the example using a black magic probe on MacOS. To use it on other platforms or with other jtag probes you should change `bmp.sh`.