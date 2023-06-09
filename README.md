# Thyristor Control Board (TCB) Project
By Jordan Harris-Toovy for internal and shared projects.
This repo contains the design files and accocated C/c++ code for a custom RP2040-powered dual thyristor control module. It is intended to be used to drive either two large SCRs as part of a SCR bridge rectifier, or a single large TriAC as the code of a larger power supply. Via an onboard current sensor, current measurements can be used in a feedback system if desired. Additionally, the I/O on the low-voltage side of the isolation barrier will allow for CNC integration for novel applications.

Currently, the board is in production of the first test batch, with an estimated arrival date of 2023-06-16. Code for the onboard Seeed XIAO RP2040 is also being developed, however, it is not yet ready. I will update this repo with the code and documentation as it is developed.
