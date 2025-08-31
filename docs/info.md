<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This FIFO is designed to transfer data asynchronously between different clock domains. It supports storage of up to 32 entries, each 4 bits wide, for a total capacity of 16 bytes. The design uses separate read and write pointers with full and empty control signals, ensuring data is written only when space is available and read only when valid data is present. By synchronizing pointers across clock domains, it enables reliable and lossless data transfer.

## How to test

Explain how to use your project

