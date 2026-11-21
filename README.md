# RAD-V

Radiation Aware Design (RAD)-V is a RISC-V core designed to implement the full
RV32I ISA and be radiation resiliant. It is currently a work in progress.

# Pipeline structure

1. Fetch

Fetch the instruction from memory

2. Decode

Derive the operation and operands

3. Execute

Based on the instruction values, carry it out

4. Memory Access

Data memory is accessed if the instruction requires it

5. Writeback

Results are written back to the register file (if there are any)

# Instructions to support

The goal of the CPU core is to support the complete RV32I ISA

## I Type
- [ ] lb
- [ ] lh
- [ ] lw
- [ ] lbu
- [ ] lhu
- [ ] addi
- [ ] slli
- [ ] slti
- [ ] sltiu
- [ ] xori
- [ ] srli
- [ ] srai
- [ ] ori
- [ ] andi
- [ ] jalr

## U Type
- [ ] auipc
- [ ] lui

## S Type
- [ ] sb
- [ ] sh
- [ ] sw

## R Type
- [ ] add
- [ ] sub
- [ ] sll
- [ ] slt
- [ ] sltu
- [ ] xor
- [ ] srl
- [ ] sra
- [ ] or
- [ ] and

## B Type
- [ ] beq
- [ ] bne
- [ ] blt
- [ ] bge
- [ ] bltu
- [ ] bgeu

## J Type
- [ ] jal
