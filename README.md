![CleanShot 2023-04-21 at 10 52 38](https://user-images.githubusercontent.com/31207828/233592202-f4c307db-3951-4fa4-9b38-c565499cd00b.gif)

# Base 5 Modulo 12510 3-Digit Counter Design

This project involves a completed design of a base 5 modulo 12510 3-digit counter using Logisim. The counter is designed to count upwards and downwards, and it can react to button presses to change the direction of counting.

## Project Description

The final project is a fully functional base 5 modulo 12510 3-digit counter. The counter counts from 000B=5 to 444B=5 in a loop and displays the count on 7-segment displays. The most significant digit is displayed on Disp2, and the least significant one on Disp0. Each bit of the encoding of each digit is displayed on a corresponding LED on the template.

The counter is designed to count upwards while a button on the template is pressed and count downwards while it is released. Upon reset, the state is 130B=5, and the counter starts counting upwards.

The functionality of the counter has been extended so that a brief press of the button schedules a change in the direction of counting for the clock cycle immediately after the next transition to the value 423B=5. The system is designed to react to arbitrarily short button presses.

The project was completed using Logisim version 3.7.2 and 3.8.0, based on the provided template file tp34.circ. The top-level module of the file is named TP34.

## Features

Upward and downward counting
Display of count on 7-segment displays
Reaction to button presses to change counting direction
Reset functionality
Tools Used

```
Logisim version 3.7.2 and 3.8.0
Template file tp34.circ
```
