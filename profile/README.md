# DebugOS
### TL;DR
A toy project dedicated to writing an OS in Rust that can load and run appications made for Windows, Linux, and Mac.
### What
This project aims to emulate each of these OSes core parts (like libc) with the ability to disect the code using a (hopefully built-in) dissasembler. Mainly gearing for virus and malware simulation. 
### Why
Why not? Also, making code that should never interact togeter sounds fun! This is a toy project so all involved can have fun learning Kernel/OS development.

## Goals
- Run viruses and malware in a "safer" way
- Software should belive it is being ran on the official OS it was ment for
- Run in near real-time, other than hitting breackponts.
- Using a fake OS, we hope to be able to detect when the virus/malware infects the honeypot kernel-space and be able to track down the exploit
