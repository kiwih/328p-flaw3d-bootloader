# 328p-flaw3d-bootloader

This repository contains a version of the FLAW3D bootloader used in the paper _FLAW3D: A Trojan-based Cyber Attack on the Physical Outcomes of Additive Manufacturing_, which is currently available from [arXiv](https://arxiv.org/abs/2104.09562) (currently under publication review). 

For your convenience, the code which has been edited has been clearly labelled in the comments (Using `/*** DEMO COMPROMISE CODE ***/` blocks). 

Overall, FLAW3D serves as a proof of concept that bootloaders can be designed to interfere with the execution of microcontroller firmware even after the bootloaders are unloaded. In the paper, we use this as a mechanism to reduce the print quality of additively manufactured (3D printed) parts. However, to preserve the anonymity of the devices targeted, in this repository we present only the code for the basic FLAW3D bootloader, and not the complete compromise code.

For a detailed explanation of the source code and its functionality, you can also read the associated [blog post](https://01001000.xyz/2021-04-21-Hiding-a-Trojan-in-an-AVR-Arduino-Bootloader/) which steps through the modifications, has explanation figures, and even a demo video!
