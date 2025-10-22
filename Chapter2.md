RISC-V Instruction format:

![WhatsApp Image 2025-09-30 at 21 56 43](https://github.com/user-attachments/assets/d03b08be-4ad4-4dc7-a330-2fe60e6cd782)

Difference between R-type, I-type and S-type instruction formats:

![WhatsApp Image 2025-09-30 at 21 59 03](https://github.com/user-attachments/assets/e02b662a-5d6b-446b-bae6-2595da63b709)

Basic operations and their corresponding instruction formats:

<img width="738" height="289" alt="Screenshot 2025-09-30 at 22 02 17" src="https://github.com/user-attachments/assets/3bfd22d7-7549-4554-bb08-4494ef4e76d9" />

More detailed instructions with example commands:

<img width="774" height="295" alt="Screenshot 2025-09-30 at 22 06 16" src="https://github.com/user-attachments/assets/f70f2b63-4ffc-4c3e-9558-14d85eaf1031" />

Logical operations in RISC-V

<img width="721" height="241" alt="Screenshot 2025-10-01 at 20 59 04" src="https://github.com/user-attachments/assets/aea6589a-b852-4ce4-8343-5d36b16c6dce" />

Branching with if conditions (branch if equal , branch if not equal)

<img width="731" height="279" alt="Screenshot 2025-09-30 at 22 59 47" src="https://github.com/user-attachments/assets/d9cee3f2-f4f1-4d6c-8e3c-885f0f68edda" />

Fancy question:

<img width="430" height="135" alt="Screenshot 2025-10-01 at 21 07 41" src="https://github.com/user-attachments/assets/6fe47723-2da1-4675-93c3-16c42752c9b3" />

The answer is: both of them.

You can adjust a specific binary number and make it AND with your word. The AND operation will turn everything other than your desired field to zero and your field will prevail.

Also, you can shift left your field to the leftmost position in your binary number to clear all left-side elements. And then shift right the field to the right-most position, clearing all right-side elements. Now, there is only your field and zeros everywhere else.

Here is a note of converting C code into assembly using branches:

![WhatsApp Image 2025-10-01 at 21 27 41](https://github.com/user-attachments/assets/007254b3-72f4-42d2-bb98-1cc76c2c2c26)

RISC-V convention for register usage:

<img width="683" height="167" alt="Screenshot 2025-10-01 at 21 35 43" src="https://github.com/user-attachments/assets/9db063a2-20ee-4b8e-83e9-c7ea188dc4f8" />

Example usage for jal and jalr instructions:

```assembly
# === Caller (main program) ===
main:
    li   a0, 5           # Load 5 into a0 (argument)
    jal  ra, double_num   # Call the procedure
    nop                  # (placeholder for next instructions)
    
# === Callee (procedure) ===
double_num:
    add  a0, a0, a0      # a0 = a0 + a0
    jalr x0, 0(ra)       # Return to the address in ra
```

**IMPORTANT NOTE:** Main purpose of stack usage is storing the old values of registers in the stack, using those registers temporarily in a procedure, and when we are done with the registers, restoring their old values into them so caller can safely use them.


## Recursive fact() Function in Assembly
### Code
![WhatsApp Image 2025-10-22 at 09 08 28](https://github.com/user-attachments/assets/67c20649-1e05-43b7-8e87-474e54622fda)

### Stack & Registers
![WhatsApp Image 2025-10-22 at 09 08 50](https://github.com/user-attachments/assets/f588cd3b-c372-4e7c-930b-920dd9b553fd)
