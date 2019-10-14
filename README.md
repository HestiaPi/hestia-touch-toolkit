# hestia-touch-toolkit
Files for optional tools we have used to make manufacturing and testing easier

# Demo
https://www.youtube.com/watch?v=gRcRINqT31g

# Soldering jig
3D design that holds all components in place from the bottom side of the PCB for hands-free soldering.
File format: 3D STL

# Testing jig
Continuity test with SMD LEDs for all GPIO pins solder points using Pogo Pins (P100-B). 
A female header with all pins shorted needs to be inserted on the Pi header.
File format: PCB Gerber

# Quick release 
Quick release mechanism with Pogo Pins (P100-Q2) for terminal block. 
An additional PCB is attached to provide power (either 100-240V AC or 24V AC) to HestiaPi and illuminate mains light bulbs. A script needs to run in the Pi to trigger sequentially all 4 relays.
File format: 3D STL and PCB Gerber
