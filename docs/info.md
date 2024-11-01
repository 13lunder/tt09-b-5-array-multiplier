<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A 4x4 array multiplier takes in two 4-bit binary numbers, m and q, and creates partial products by multiplying each bit of q with every bit of m, resulting in a total of four partial products. These partial products are added together using a full adder module to create the final product.

![array-multiplier-block-diagram-1024x689](https://github.com/user-attachments/assets/7fe1b2ac-338f-483e-b9b2-2beae6ae9329)


## How to test

5 test cases are included in this project. In each test case, 4-bit binary numbers are assigned to m and q, and their expected product is listed. If the result from the array multiplier matches the expected output, then that test case is considered a success. Multiple test cases are included to ensure functionality.

## External hardware

N/A
