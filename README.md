![image](https://github.com/user-attachments/assets/172c3907-f531-4f41-8c38-2b4055034a34)# ICISS-2024
Code for the ICISS-2024 paper

# Multiplicative Cyclic Group Example

This project demonstrates the creation and manipulation of a multiplicative cyclic group of integers modulo a prime number using Python. The code includes examples of generating random elements from the group and performing arithmetic operations.

## Overview

The code defines a prime number `p` and creates a finite field `Fp` of order `p`. It then demonstrates how to find a generator for the multiplicative group and perform operations like exponentiation and inversion within the group.

## Prerequisites

To run this code, you'll need to have the following installed:

- Python (version 3.x recommended)
- SageMath (as it provides classes like `GF` and `ZZ` for finite field arithmetic)

## Installation

1. **Install SageMath**:
   Follow the [SageMath installation guide](https://doc.sagemath.org/html/en/installation/index.html) to install it on your system.

2. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>

**Usage**

    **Run the Code:** To execute the code, use SageMath's Python environment:
    sage <your-script-name>.sage

   ** Modify the Prime Number:** The prime number p can be changed to suit your needs. Ensure it remains a prime number for accurate group operations.

    **Understanding the Output:**
        Ride Request and Ride Offer sections show the generated random elements and their corresponding cryptographic computations.

**Example**

To experiment with different prime numbers or generators, simply modify the p and generator variables at the beginning of the script.

**Notes**

    Ensure p is a prime number to guarantee the correct behavior of the finite field operations.
    The generator might need to be adjusted if the default choice does not satisfy the group's order requirements.

This code is compiled in the sagemath environment.

The output of this code is mentioned below.

>>>>>>>>>>>>>
Multiplicative cyclic group of prime order: 11
A generator of the: 2
------- Ride Request ------
Alpha 1: 8
Beta 1: 0
r1: 2
r2: 6
c1: 4
c2: 9
c4: 4
Mp: 7
------- Ride Offer ------
Alpha 11: 3
Beta 11: 6
r11: 3
r21: 8
c11: 8
c21: 3
c41: 4
Md: 10
<<<<<<<<<<<<<<<<<
