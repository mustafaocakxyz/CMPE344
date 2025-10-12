<img width="568" height="64" alt="Screenshot 2025-10-11 at 17 31 00" src="https://github.com/user-attachments/assets/6e09e809-9443-4ee4-be58-3abbc7d9e968" />

<img width="810" height="414" alt="Screenshot 2025-10-11 at 17 33 11" src="https://github.com/user-attachments/assets/545f9907-e00b-412a-93a7-535096714469" />

**Exercise:** What if we do not use registers? What alternative solutions can be implemented?

<img width="785" height="360" alt="Screenshot 2025-10-11 at 17 35 04" src="https://github.com/user-attachments/assets/ec3d239a-2047-448a-943a-2e06b5b5474f" />

**Exercise:** How register file is implemented for RISCV64?
<img width="779" height="377" alt="Screenshot 2025-10-11 at 17 38 36" src="https://github.com/user-attachments/assets/e0c24c58-7ed0-4fec-9f13-7a8fd98ed402" />

**Exercise:** How many bytes can you store in the register file?
<img width="771" height="523" alt="Screenshot 2025-10-11 at 17 39 28" src="https://github.com/user-attachments/assets/9d2aebb5-fddd-400e-9439-64060733cf27" />

RISC-V Register Conventions:
<img width="817" height="461" alt="Screenshot 2025-10-11 at 17 40 04" src="https://github.com/user-attachments/assets/0dd5bfcf-4d12-4e43-aa62-880bdf4dbdd8" />

**Role of Memory**
<img width="809" height="422" alt="Screenshot 2025-10-11 at 17 40 52" src="https://github.com/user-attachments/assets/ab6608d8-f55c-4cd7-9049-8dc818d1ee26" />

**Exercise:** What is Endianness? Find examples of systems with little and big endians? Why does it matter?
<img width="889" height="405" alt="Screenshot 2025-10-11 at 17 43 29" src="https://github.com/user-attachments/assets/b039cdfa-d9b1-4572-bf2f-246f789bf597" />

**Exercise:** Words don't need to be aligned in memory. Investigate the meaning and purpose of word alignment.
<img width="727" height="263" alt="Screenshot 2025-10-11 at 17 44 11" src="https://github.com/user-attachments/assets/ed154e5d-cf42-43ce-a34c-b541851bfbe2" />

Memory Operands Example:
<img width="813" height="406" alt="Screenshot 2025-10-11 at 17 45 50" src="https://github.com/user-attachments/assets/0b003a35-c464-48af-8ef3-6e3ca5cb59b2" />

**Exercise:** What about 64-bit systems?
<img width="609" height="310" alt="Screenshot 2025-10-11 at 17 46 35" src="https://github.com/user-attachments/assets/6db39220-1dce-4f65-b418-083fdf660a2a" />

**Exercise:** Why registers are faster? Why do we need many load & store operations? How should we use registers and memory when writing our programs? How compiler should use them?
<img width="705" height="315" alt="Screenshot 2025-10-11 at 17 48 59" src="https://github.com/user-attachments/assets/5a694787-f9dd-4804-a355-c1b32f23921e" />

**Exercise:** RISC-V requires register use. Investigate systems with alternative solutions.
<img width="692" height="188" alt="Screenshot 2025-10-11 at 17 49 38" src="https://github.com/user-attachments/assets/2e3157dd-a5b7-4ccf-8bb6-9aec25cbcad6" />

Some RISC-V Design Principles (1):
<img width="583" height="241" alt="Screenshot 2025-10-12 at 10 39 11" src="https://github.com/user-attachments/assets/ab0c1bc6-518f-46a7-914b-7ee31c44335d" />

R-Type, I-Type and S-type instruction examples:
<img width="782" height="343" alt="Screenshot 2025-10-12 at 10 42 21" src="https://github.com/user-attachments/assets/8bc07fa8-f09f-4ac7-8a65-57401d0064ae" />

RISC-V Design Principles (2):
<img width="787" height="324" alt="Screenshot 2025-10-12 at 10 43 58" src="https://github.com/user-attachments/assets/c2e51d98-6eca-4557-ad80-65704cda42c1" />

**Exercise:** What could be other costs of similarity among instruction formats?
<img width="583" height="83" alt="Screenshot 2025-10-12 at 10 46 44" src="https://github.com/user-attachments/assets/a3a683f0-91c8-4406-8264-b32ea610ef8b" />


**Exercise:** Find examples where similarity principle wasn't applied.
<img width="593" height="138" alt="Screenshot 2025-10-12 at 10 46 59" src="https://github.com/user-attachments/assets/13ce5e7a-fd38-4f5b-a43f-14a77799ab57" />

Pseudo-Instructions
<img width="654" height="239" alt="Screenshot 2025-10-12 at 10 49 17" src="https://github.com/user-attachments/assets/f98bcf24-13b4-442b-aeb1-8ffafe356775" />

**Exercise:** Translate the no-operation (nop) pseudo-instruction.
<img width="604" height="357" alt="Screenshot 2025-10-12 at 10 49 55" src="https://github.com/user-attachments/assets/f308bc7c-3aaa-405c-ac4e-f49ad21d99f3" />

**Exercise:** What is exactly a LABEL in the assembly code?
<img width="581" height="305" alt="Screenshot 2025-10-12 at 10 52 05" src="https://github.com/user-attachments/assets/be409de7-069c-4a76-aa87-ddf7e000cda8" />

**Exercise:** What is PC-relative addressing? Why address is PC-relative? Why multiples of 2?
<img width="585" height="721" alt="Screenshot 2025-10-12 at 11 05 57" src="https://github.com/user-attachments/assets/673e377d-e50c-414c-b2ef-6aaa52dcd516" />

**Exercise:** What does the operation link mean and what is the role of rd?
<img width="599" height="594" alt="Screenshot 2025-10-12 at 11 08 45" src="https://github.com/user-attachments/assets/acedb97d-eb14-4b15-a833-1e2eb215ff3c" />

## RISC-V Addressing Modes & Summary:

Immediate Addressing
<img width="589" height="335" alt="Screenshot 2025-10-12 at 11 12 50" src="https://github.com/user-attachments/assets/a9561603-3c12-4628-a06c-15c7db54d238" />

Register Addressing
<img width="597" height="345" alt="Screenshot 2025-10-12 at 11 13 18" src="https://github.com/user-attachments/assets/4493649e-89fa-42ac-8781-245f60999122" />

Base Addressing
<img width="591" height="365" alt="Screenshot 2025-10-12 at 11 13 55" src="https://github.com/user-attachments/assets/f9e6fef7-e080-471a-ad4c-3d90c64c00e2" />

PC-relative Addressing
<img width="598" height="334" alt="Screenshot 2025-10-12 at 11 14 21" src="https://github.com/user-attachments/assets/3d636c58-107b-49b1-ac6b-d7ffa90e9ab6" />

## RISC-V Instruction Formats & Summary:
<img width="790" height="402" alt="Screenshot 2025-10-12 at 11 15 09" src="https://github.com/user-attachments/assets/35791f03-54a5-4726-80cc-8d2fb0253b28" />

# Procedures
Leaf procedure example (stack allocation)
<img width="557" height="418" alt="Screenshot 2025-10-12 at 11 21 04" src="https://github.com/user-attachments/assets/2d478e3f-b49c-48d2-b598-5b178d883a24" />

Stack status:
<img width="829" height="399" alt="Screenshot 2025-10-12 at 11 21 37" src="https://github.com/user-attachments/assets/5dc0e13b-4106-4a48-95c5-d7acb90d82d4" />

Register conventions for stack usage:
<img width="315" height="217" alt="Screenshot 2025-10-12 at 11 21 59" src="https://github.com/user-attachments/assets/1a9a95ab-4956-4d20-a5d9-f9ce98ebd376" />

