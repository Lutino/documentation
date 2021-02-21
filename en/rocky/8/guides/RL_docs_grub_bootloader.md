# Understanding Grub: The boot managera for Rocky Linux.

Have you ever wondered how your computer starts the Rocky Linux operating system ? Read on to learn about it.

## Requirements
To successfully follow along, you'll need:
* Rocky Linux bootable disk (USB or CD/DVD)
* Knowledge of the command-line
* A working personal Computer
  While this guide is meant to get you a basic understanding and to get you started, here is a more [complete guide](www.gnu.org/software/grub/manual/grub/grub.html).

## The BIOS in ROM goes to RAM to run the POST ... Pheeww!!!
Once you push the power button on your personal computer, a small program located on a chip soldered to your computer's motherboard, called ROM (Read-Only Memory,) is run. The program, called BIOS (Basic Input Output System,) is loaded into your computer's memory or RAM (Random Access Memory) to execute a self-test process. Upon completion, it looks into the first sectors of your hard drive for the next program to run: that is where it finds the boot loader. 

## What is a Boot loader ?

## Grub: A boot loader with a purpose

## Grub Installation

## Confuguring Grub to serve you well

## Passing parameters to the kernel

## Boooting into specific Run Levels

## Selecting the default kernel: starting your preferred OS
