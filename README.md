# vendr
## Purpose
The aim of this project is to build a vending machine controller which will be used to retrofit an old snack vanding machine. The machine will be in use in a makerspace to allow members to buy hardware and other items (microcontrollers, sensors, common components like buck/boost converters, also things like usb drives, microsd cards) at aliexpress prices but with on-demand convenience. It may also dispense snacks.

A limited version of this project will also be submitted as the final project for the Classpert "Making Embedded Systems" Red Jellies cohort.

## System Overview
This system is going to be built around the STM32F469I Discovery board, which has a 4" 800x480 touchscreen. This screen will be the main interface for the user. Item and price changes will be applied remotely through a network connection.

The complete project will require the development of a servo driver board, an LED driver board, and integration of a coin and bill acceptor. Planned upgrades beyond the current scope include integrating a wifi module to avoid having to run ethernet to the machine, and integration of an nfc reader to allow electronic payments.

The limited version for the course project will have control logic implemented, rudimentary screens, and may have additional peripherals added in order to meet the course requirements.

## Block Diagram
![block diagram drawio](https://user-images.githubusercontent.com/3228604/142719461-882f1765-44da-4bac-84b3-bdb4cd84e5f4.png)
