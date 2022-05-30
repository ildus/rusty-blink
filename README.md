Blinky on Rust for STM32F407 Discovery board
----------------

Installation

```
cargo install cargo-flash
cargo build
cargo flash --chip stm32f407VGTx
```

Using BSP (specific board support):

```
[dependencies.stm32f407g-disc]
version = "0.4.1"
git = "https://github.com/stm32-rs/stm32f407g-disc"
```
