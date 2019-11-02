# Discovery

I'm a very begginer to arduino and electronics so in here i will be putting my discovery as i go.
Some of this may not make sense since it is meant to be a diary for my learning curcve.

# Components

I have my arduino uno R3 (built by [elegoo](https://www.elegoo.com)) connected to my computer and
was able to run various examples. Here's a list of components we are going to be using for this project:

* [TMC2130](https://www.trinamic.com/fileadmin/assets/Products/ICs_Documents/TMC2130_datasheet.pdf)
* arduino uno R3
* Stepper mottor 28BYJ-48

In terms of resources, here's what i've got so far for the software side of things

* [TMC2130Stepper](https://platformio.org/lib/show/1493/TMC2130Stepper/examples)

# VSCode

I've got myself setup with c++ on vscode so i can try things out before i push things over to
an arduino.

# Wiring

Here's the schematics we are going to start with

![TMC2130][tmc2130Img]

# First challenge

TMC2130 doesn't seem to be the correct driver for 28BYJ-48 because it supports
bipolar motors because they accept 4 connections as opposed to 5 connections.
I've found ways to turn 28BYJ-48 into a bipolar but i don't really know
the ramifications of it. SO i'll have to get the Stepper Motor - Nema 17 Stepper
Motor Bipolar if this doesn't work. Here's an image of my 28BYJ-48 turned into
bipolar

![28BYJ-48][28BYJ48Img]

[tmc2130Img]: https://raw.githubusercontent.com/opposite-bracket/arduino-motor-rotator/master/imgs/tmc2130-schematics.jpg "TMC2130 schematics"
[28BYJ48Img]: https://raw.githubusercontent.com/opposite-bracket/arduino-motor-rotator/master/imgs/28BYJ-48-turned.png "28BYJ48 turned"