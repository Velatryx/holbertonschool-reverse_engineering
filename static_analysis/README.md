

For this project, we expect you to look at these concepts:

    Static Analysis

Introduction

"You cannot defend what you do not understand. Static analysis is the art of understanding a program without ever running it and that changes everything."

Every piece of malware, every compiled exploit, every suspicious binary that arrives in a security investigation is just a file. Static analysis is the discipline of reading that file - its structure, its strings, its assembly code, its imports and extracting meaning before a single instruction executes.

In practice this matters in three critical scenarios. In malware analysis, you cannot safely run an unknown binary, so you must understand it statically first. In security auditing, you may not have source code but still need to verify behavior. In CTF challenges, exactly what this module's tasks simulate - the flag is always hidden somewhere in the binary, and the only way to find it is to read what the compiler left behind.

Tools like Ghidra, Radare2, and IDA Pro exist because disassembly and decompilation turn incomprehensible machine code into something a human can reason about. This module teaches that fundamental skill and connects directly to every security topic involving binaries, exploits, or malware.
Resources
Read or watch:

    Ghidra Beginner’s Guide:
    System Security
    Exponentiation by Squaring
    Modular Arithmetic
    Introduction to Cryptography
    Introduction to Assembly Language for Reverse Engineering
    GDB Tutorial: Stepping Through Assembly
    Reversing with Ghidra: A Beginner's Guide
    Understanding x86/x64 Assembly

Tools

    Ghidra
    Radare2
    IDA Pro
    GDB (GNU Debugger)
    Objdump

Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

    What is static analysis in reverse engineering?
    Why is static analysis important for malware analysis, security auditing, and software debugging?
    How does disassembly and decompilation aid in understanding a program’s code?
    What are the key differences between executable formats like PE (Windows), ELF (Linux), and Mach-O (macOS)?
    What tools are commonly used for static analysis, such as IDA Pro, Ghidra, and Radare2?
    How do control flow graphs (CFGs) assist in mapping out the execution flow of a program?
    What techniques are used to identify vulnerabilities and bugs in binary code through pattern recognition and signature matching?
    How does header analysis contribute to understanding the structure of binary files?
    What role does cross-referencing play in identifying critical functions and code paths?
    What are the steps in a typical static analysis workflow, from initial inspection to documentation?

Requirements
General

    Allowed tools: IDA Pro, Ghidra, Radare2,Hex-Rays Decompiler, Binwalk, Strings, Binary Ninja, Cutter.
    All analyses should be conducted in a controlled environment, like a VM or sandbox.
    Ensure that all files are backed up regularly during the analysis process.
    All your scripts must be executable and runnable on Kali Linux.
    You should avoid using hardcoded values for paths; utilize relative paths instead.
    Make sure to validate the integrity of the binaries before analyzing them.
    All analysis findings should be organized and clearly formatted for easy reference.
    For this project, your focus will be on the target target_binary
    You are not allowed to use online tools or services for your analysis; everything must be done locally.

