 XOR and XNOR Gates - Theory & Truth Tables**

### Concept Overview
XOR (Exclusive OR) and XNOR (Exclusive NOR) are special logic gates used for parity checking, error detection, and data comparison in digital systems.

### Detailed Explanation

#### ✅ XOR Gate (Exclusive OR)
- **Definition:** The XOR gate outputs `1` when the inputs are **different**. If the inputs are the same, the output is `0`.
- **Symbol:** Represented by a standard OR gate symbol with an additional curved line on the input side.
- **Boolean Expression:** `Y = A ⊕ B`
- **Truth Table:**

| A | B | Y (XOR) |
|:-:|:-:|:---------|
| 0 | 0 | 0         |
| 0 | 1 | 1         |
| 1 | 0 | 1         |
| 1 | 1 | 0         |

**Example Application:** Used in data encryption, parity generators, and error detection circuits.

#### ✅ XNOR Gate (Exclusive NOR)
- **Definition:** The XNOR gate is the complement of the XOR gate. It outputs `1` when the inputs are **identical** and `0` otherwise.
- **Symbol:** Represented by an XOR gate symbol with an additional circle at the output.
- **Boolean Expression:** `Y = (A ⊕ B)'`
- **Truth Table:**

| A | B | Y (XNOR) |
|:-:|:-:|:----------|
| 0 | 0 | 1          |
| 0 | 1 | 0          |
| 1 | 0 | 0          |
| 1 | 1 | 1          |

**Example Application:** Used in equality checkers, digital comparators, and identity verification systems.

### Code Explanation
- **`assign` Statements:** Used to define XOR and XNOR logic using the `^` (XOR) and `~` (NOT) operators.
- **`$monitor` Task:** Monitors changes in signals and prints real-time output.
- **Test Cases:** Each input combination is tested to confirm the correctness of XOR and XNOR gate functionality.

### Execution Steps
1. Copy the Verilog code into your simulator (e.g., ModelSim, Xilinx Vivado, etc.).
2. Compile the code and check for errors.
3. Run the simulation and verify the output against the truth tables.

### Real-World Example for Practice
- Design a **4-bit parity checker** using XOR gates to detect errors in transmitted data.

Would you like to proceed with **Day 4: Universal Gates (NAND & NOR) - Theory & Truth Tables** next?

