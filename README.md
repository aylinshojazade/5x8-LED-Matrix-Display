# Design and Implementation of a 5×8 LED Matrix Display

## Overview

This project implements a 5×8 matrix display using sequential and combinational digital circuits in Multisim.

The design is based on:

* D Flip-Flops
* 4-to-1 Multiplexers
* Shift Register Architecture
* Hierarchical Blocks

The system supports:

* Hold
* Shift Left
* Shift Right
* Parallel Load

Output states are monitored using Logic Probes.

## Software

* NI Multisim

## Project Structure

Each row is implemented as an independent hierarchical block consisting of D flip-flops and multiplexers. The complete matrix is formed by connecting multiple row modules.

## Screenshots

Screenshots of the complete circuit, row structure, multiplexer design, and simulation results are included in the Images directory.

## Author

Aylin Shojazade
