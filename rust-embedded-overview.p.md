# Rust Embedded Overview
Bart Massey 2026-01-03
Rust Africa Hackathon


## What is "Embedded"?

* Small-systems stuff: often tiny memory
  for programs and data — MCU

* "Realtime" stuff

* Often no or minimal OS / Real-Time Operating System

* Hardware / software focus


## What is special about "Embedded Rust"?

* Usually `no-std` `no-main`: you have just
  the Rust `core` library and often no heap.

* Whole ecosystem in place: https://rust-embedded.org

* Everything is "normal": standard Rust toolchain,
  `crates.io`, *fairly* normal build process


## What can you do with embedded Rust?

* Anything you can do with embedded, only better!

* "Runtime systems" like RTIC and Embassy fill an important
  niche between bare-metal and OS-driven dev.


## What does the Rust embedded stack look like?

* Peripheral Acces Crate (PAC): low-level MCU

* Hardware Abstraction Layer (HAL): higher-level MCU

* Board Support Package (BSP): MCU + onboard peripherals

* Driver crates: mix-and-match attached hardware


## How do you get started?

* https://rust-embedded.github.io/discovery-mb2 is the
  fastpath
  
* There's lots of other paths, too, though. Example: many
  folks like ESP32 hardware


## How do you find people?

* Again, check out https://rust-embedded.org

* Our Matrix chat is very active; meetings are on Tuesdays

* https://rust-edu.org
## Final Thought

* AI is starting to take over everything

* Good reason to get into AI?

* Or embedded. Embedded is where we still
  do stuff by hand
  
* Rust is the future of embedded
