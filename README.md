# NOS: A Tiny OS in Rust

NOS is a minimalist operating system written in Rust, designed as a foundational OS that demonstrates low-level programming concepts and bare-metal development in Rust.

## Features

- Minimalist OS structure
- Basic bootloader setup
- Kernel written entirely in Rust
- Demonstrates memory management, basic system calls, and other essential OS components

## Dependencies

Before running this project, ensure the following dependencies are installed:

- **[QEMU](https://www.qemu.org/):** An open-source emulator that simulates a computer processor via dynamic binary translation. QEMU provides various hardware and device models, enabling it to run various guest operating systems.
  
- **[Cargo](https://doc.rust-lang.org/cargo/):** Rust's package manager, which handles dependencies, compiles packages, and facilitates sharing within the Rust community through [crates.io](https://crates.io/).

## How to Use

To get started with NOS, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Venomxd27/NOS.git
   ```
2. **Build and run the project:**
  ```bash
  cd NOS
  cargo run
  ```
