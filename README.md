<!-- omit in toc -->
# Awesome RP2040 Rust

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> A curated list of resouces for development in the Rust programming language for the RP2040 microcontroller

<!-- omit in toc -->
## Table of Contents

- [Community](#community)
- [Books, Blogs, and Training Materials](#books-blogs-and-training-materials)
- [Video Courses and Talks](#video-courses-and-talks)
- [Tools](#tools)
- [Templates](#templates)
- [Projects](#projects)
- [License](#license)

## Community

You can usually find community members in the [`#rp-rs:matrix.org` Matrix room](https://matrix.to/#/#rp-rs:matrix.org).

## Books, Blogs, and Training Materials

- [EN] [The examples in rp-hal](https://github.com/rp-rs/rp-hal/tree/main/rp2040-hal/examples)
- [EN] [Getting Started with Rust on a Raspberry Pi Pico (Part 1)](https://reltech.substack.com/p/getting-started-with-rust-on-a-raspberry)
- [EN] [Programing in Rust the XIAO RP2040 board](https://tutoduino.fr/en/tutorials/programing-in-rust-the-xiao-rp2040-board/)

## Video Courses and Talks

- [EN] [Running Rust on the Pico W](https://www.youtube.com/watch?v=vwFWBP0IuRU&pp=ygULcnAyMDQwIHJ1c3Q%3D)
- [EN] [Rust runs on Everything(no operating system, just Rust)](https://www.youtube.com/watch?v=Yi0WRF5WPFw&t=332s&pp=ygULcnAyMDQwIHJ1c3Q%3D)
- [EN] [Introduction to Rust Programming on bare metal hardware](https://www.youtube.com/watch?v=KECu_piSM5s&pp=ygULcnAyMDQwIHJ1c3Q%3D)

## Tools

- [probe-rs](https://probe.rs/) - A flashing and debugging tool for embedded devices
- [elf2uf2](https://github.com/JoNil/elf2uf2-rs) - A tool to convert ELF files to UF2 files. Useful when you have no debugger(or second RP2040 used as a debugger) and want to flash your firmware.

## Templates

- [Project template for rp2040-hal](https://github.com/rp-rs/rp2040-project-template)

## Projects

- [μLA](https://github.com/dotcypress/ula) - A SUMP/OLS compatible Micro Logic analyzer using PIO
- [RMK](https://github.com/HaoboGu/rmk) - A feature-rich Rust keyboard firmware
- [rp2040-sound-card](https://github.com/mgottschlag/rp2040-usb-sound-card) - A USB Audio implementation on the RP2040
- [rp2040-37c3-oled](https://github.com/kpcyrd/rp2040-37c3-oled) - Rust Firmware for displaying the 37C3 Logo animation
- [inputmodule-rs](https://github.com/FrameworkComputer/inputmodule-rs) - A Laptops Input Module Firmware

<!-- omit in toc -->
## Contributing
Any contributions are welcome! If you would like to add a project or resource just open a PR with the changes. If you have any questions, suggestions or want to make a larger contribution please open an issue.

## License

This list is licensed under

- CC0 1.0 Universal License ([LICENSE](LICENSE) or https://creativecommons.org/publicdomain/zero/1.0/legalcode)
