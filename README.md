# Asm_arithmetics

An assembler functions for arbitrary-precision integer addition, subtraction and multiplication.

### Run
Addition: `nasm -f elf64 add.asm && ld -s -o add add.o && ./add` 

Subtraction: `nasm -f elf64 sub.asm && ld -s -o sub sub.o && ./sub` 

Multiplication: `nasm -f elf64 mul.asm && ld -s -o mul mul.o && ./mul`
