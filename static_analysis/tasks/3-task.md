
3. Reverse Engineering an Obfuscated Flag

This challenge will push your reverse engineering skills to the limit. You are given a binary that verifies a flag, but the flag has been obfuscated using complex mathematical operations.

Due to the nature of this obfuscation, the algorithm creates collisions, meaning multiple possible outputs could appear valid.

Your goal is to reverse the obfuscation process, determine the correct flag, and complete the challenge.

Important Notes About the Obfuscation

    The algorithm creates collisions at odd positions in the flag.
    Some characters may have alternative representations due to the way the obfuscation works.
    The only way to get the exact flag is through brute force, as the obfuscation involves multiplication, making it non-reversible.
    he expected flag format is:
        Holberton{XXXXX?} (where X is a lowercase letter or an underscore ("_"), and the final character is a symbol ).
    Be mindful of these constraints when deriving the final flag.

Objective

    Reverse engineer the binary to understand how it verifies the flag.

    Unravel the mathematical obfuscation used to hide the flag.

    Submit the correct flag after successfully reversing the operations.

Steps

1- Download the Binary: Obtain the binary containing the flag verification mechanism.

2- Analyze the Binary: Use reverse engineering tools to disassemble and inspect the verification logic.

3- Decode the Obfuscation: Determine how the mathematical operations transform the original flag.

4- Infer or Brute Force the Correct Flag: Due to obfuscation collisions, you may need to test different variations.

5- Verify the Flag: Once you derive a potential flag, input it into the binary to confirm correctness.

Tools

    Ghidra

    IDA Pro

    radare2

    Hex Editors

Download your target file from here
