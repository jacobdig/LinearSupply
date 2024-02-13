## Members
Jacob Di Girolamo, Computer Engineer, jacobdig@vt.edu

## Mentor
MENTOR NAME HERE

## Current Status
IN PROGRESS

## Project Overview

The goal of this project is to design a lab bench power supply which can provide at least 28V at 4A. The supply should be controlled through a microcontroller, and eventually should be able to be controlled through a serial connection. Over voltage and over current protection will be implemented, and a buck converter will be used prior to the linear stage to improve overall efficiency.

The foundation for this design is derived from the LT Journal of Analog Innovation V24N2, page 12 (https://www.analog.com/media/en/technical-documentation/lt-journal-article/LTJournal-V24N2-2014-07.pdf), which describes a linear bench supply able to provide 24V at 3A with OV and OC protection, but is manually controlled with potentiometers. For this project, I would like to use an LM2678 as the buck stage and an LM338 as the linear stage, incorperating a microcontroller to adjust the voltage and current, display the actual voltage and current, and to control the supply over serial communication with a computer. The LM2678 and LM338 were chosen to have higher voltage and current capabilities while also being lower cost than the ICs mentioned in the above article. 

## Educational Value Added

As a computer engineer, I haven't taken a power class, but have always been interested in designing power supplies for my other projects. This project will give me an opportunity to design both a buck converter and a linear supply, learning about power supply PCB design along the way. I will learn about the noise and thermal considerations when designing power supplies and will also learn to implement PID and serial control through a microcontroller, with the final product being a versitile and useful peice of lab equipment.

## Tasks

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Design Decisions

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Design Misc

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Steps for Documenting Your Design Process

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## BOM + Component Cost

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Timeline

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Useful Links

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Log

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->
