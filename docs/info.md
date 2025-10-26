<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project uses basic logic gates (AND and NOT) to show how digital signals interact. It’s designed for simple demonstrations of input and output behavior, testing the workflow, and viewing the circuit in 3D.

## How to test

OUT0 turns ON only when both IN0 and RST_N are active (AND gate).
OUT1 turns ON only when both IN1 and IN0 are active (AND gate).
OUT2 shows the opposite signal of IN2 (NOT gate).
OUT3 shows the opposite signal of IN3 (NOT gate).
OUT4–OUT7 directly follow IN4–IN7 without changes.

## External hardware

Reset button
8-position DIP switch (for inputs)
LED indicators (for outputs)
