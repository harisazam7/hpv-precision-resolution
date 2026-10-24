# Precision–Resolution Hierarchies for Scientific Data

Course project for **High Performance and Visualization**, University of Bremen.

## Overview

Large scientific datasets (e.g. simulation outputs, volumetric scans) are often too big to store,
transfer, or visualize at full fidelity. Two common ways to reduce data size are:

- **Resolution reduction** – representing a scalar field with fewer spatial samples
- **Precision reduction** – representing each value with fewer bits

This project studies the **precision–resolution tree** proposed by Hoang et al., a hierarchical
data layout that combines both kinds of reduction. It allows a dataset to be decoded progressively,
with a flexible trade-off between quality, memory use, and data movement.

## Reference

D. Hoang, B. Summa, H. Bhatia, P. Lindstrom, P. Klacansky, W. Usher, P.-T. Bremer, V. Pascucci,
*Efficient and Flexible Hierarchical Data Layouts for a Unified Encoding of Scalar Field Precision and Resolution*,
IEEE Transactions on Visualization and Computer Graphics.

## Topics

- Scalar fields and regular grids
- Multiresolution and wavelet hierarchies
- Bit-plane (precision) encoding
- Precision–resolution trees and valid cuts
- Progressive decoding and random access
- Error vs. data-size trade-offs

## Status

🚧 Work in progress – notes, code, and experiments will be added here.

## Author

Haris Azam – MSc Mathematics, University of Bremen
