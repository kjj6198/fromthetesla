# fromthetesla

Inspired from [fromthetransistor](https://github.com/geohot/fromthetransistor) and adding my suggestion


## Introduction

## 0. Electricity

First we need to know how electricity is made, we can't run program without electricity.

- Electromagnetic induction
- How to convert AC to DC

## 1. Transistor -> logic gate

- Knowing how transistor works, buy cheapest transistor (e.g: 2N2222) and learn to make OR, AND, NOT, XOR logic gates.
- Build full adder, multiplexer, shift and some advanced circuit

## 2. Hardware language

- Learn verilog and write some simple circuit
- Pick up some hardware communication protocols like UART, I2C. (UART would be easier)

## 3. Build a simple CPU

## 5. AVR Programming

Easiest way to learn how hardware, firmware works without OS overhead

- Learn GPIO, SRAM, flash, EEPROM, timer, interrupt
- Write simple program like HID device, I2C communication
- (optional: learn how USB works, it might be harder than you think)

**NOTE: don’t use arduino or any library if you really want to learn how it works**

## 6. Programming Language (AVR)

You might know `malloc` and how compiler compiles your code into avr assembly, now let’s build one. AVR is 8-bit controller, might be eaiser to build than an ARM 32bit controller.

- Build a C compiler: can compile C program into AVR assembly. (without any optimization, only basic syntax support is OK)
- Build a linker / libc: integrate the most important functions
    - io-avr, timer, math, malloc, interrupt
    - stdlib
    - string: like memcpy, strcpy, strlen
- (optional: try build a scripting programming languages)

## 7. Operating System

- Build an operating system in `QMENU`
- Program some peripherals protocols like SD, USB, UART
- File system: FAT

## 8. Build the Browser

[https://browser.engineering/](https://browser.engineering/)

- Start from networking. (TCP, HTTP/HTTPS, DNS resolution)
- HTML, CSS parsing and rendering (without JavaScript parsing)
    - Learn how to parse the syntax and layout the style

## 9. Hardware world

*Learn hardware in order to appreciate the software*

- Design your own schematic with Kicad
- Do PCB layout for it
- Send to JLCPCB or any other PCB manufacturer
- Assemble your PCB and demostrate the functionality
- (optional: learn HDMI signal)
