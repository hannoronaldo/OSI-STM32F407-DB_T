# System Requirement description for the OSI-STM32F407-DB_T

<i> =============== SysRS start ============== </i>

## Table of contents
 - [Project goals](#project-goals)
 - [System description](#system-description)
 - [Hardware prerequisit](#hardware-prerequisit)
 - [Hardware Blocks](#hardware-blocks)
 - [Software Function Blocks](#software-function-blocks)

## Project goals

OSI-STM32F407-DB_T project is the preview design to test the communication between the BeagleBone Black as master controller with the STM32 drive modules.
This implementation should be define the resources for a later break this design in a small BlackPill like implementation.    

## System description

xxxx  

## Hardware prerequisit

![Hardware Board usage Overview](images/board_overview.png)

There are 5 PCB's are involved:
### 1x BeagleBone Black C1.2
We will use this board in the latest step of the implementation with the CAN communication between the BBB and the STM32 dev board, in earliert stages we will implement also the CAN communication with loopback and extern devices
### 1x STM32F407 Discovery Board
this board will use as a development platform to define funktion blocks for motor/steering/distance measurement and CAN communication.
Also to see what amount of flash and RAM usage consumtion is needed to implement later a module based on the BlackPill dev board.
### 1x MCP2515 CAN controller board
this MCP2515 board will connect with the STM32 disco boad to establish the CAN communication.
### 1x TJA1050 CAN transceiver board
this TJA1050 transceiver board will connect with the BBB to establish the CAN communication. It's can be a modified MCP2515 board

## Hardware Blocks

In the picture below you se a rough wiring between the boards.

![Hardware Board wiring Overview](images/hardware_connection.png)

## Software Function Blocks

xxx
 


### NOTES
In case of any requirement update we will update the document and inform you.  

### Contacts
You contact detail goes here  

<i> =============== SysRS End ============== </i>


