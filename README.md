Concept Overview
Digital logic is the foundation of digital electronics. It involves the use of binary values (0 and 1) to represent and manipulate data. The key elements in digital logic include logic gates, combinational circuits, and sequential circuits.

Key Topics Covered
✅ Binary System (0 and 1)
✅ Logic Levels (HIGH/LOW or TRUE/FALSE)
✅ Basic Logic Gates Overview (AND, OR, NOT)
✅ Truth Tables for Basic Gates
✅ Real-World Applications of Digital Logic

 Introduction to Digital Logic**

### Concept Overview
Digital logic is the foundation of digital electronics. It involves the use of binary values (0 and 1) to represent and manipulate data. The key elements in digital logic include logic gates, combinational circuits, and sequential circuits.

### Detailed Explanation of Concepts

#### ✅ Binary System (0 and 1)
- The binary number system is a base-2 system where numbers are represented using only two digits: **0** and **1**.
- In digital logic, these values correspond to:
  - **0** → Low voltage or OFF state
  - **1** → High voltage or ON state

#### ✅ Logic Levels (HIGH/LOW or TRUE/FALSE)
- Digital circuits operate using two voltage levels:
  - **HIGH** (logic 1) – Represents **True** or **On**
  - **LOW** (logic 0) – Represents **False** or **Off**

#### ✅ Basic Logic Gates Overview (AND, OR, NOT)
- **AND Gate:** Produces an output of `1` only if **both** inputs are `1`. Otherwise, the output is `0`.
- **OR Gate:** Produces an output of `1` if **any** of the inputs is `1`.
- **NOT Gate (Inverter):** Produces the **opposite** of the input. A `1` becomes `0` and vice versa.

#### ✅ Truth Tables for Basic Gates
Truth tables define the behavior of logic gates by listing all possible input combinations and their corresponding output values.

| Input A | Input B | AND | OR | NOT A |
|:--------|:--------|:----|:---|:------|
| 0        | 0        |  0  | 0  |  1    |
| 0        | 1        |  0  | 1  |  1    |
| 1        | 0        |  0  | 1  |  0    |
| 1        | 1        |  1  | 1  |  0    |

#### ✅ Real-World Applications of Digital Logic
- **AND Gates**: Used in circuits that require multiple conditions to be true (e.g., security systems).
- **OR Gates**: Used in alarm systems where multiple conditions can trigger an alert.
- **NOT Gates**: Often used in signal inversion circuits or as part of larger logic combinations.

### Detailed Code Explanation
- **`assign` Statements**: These are continuous assignments in Verilog that are used for combinational logic design.
- **`$monitor`**: A system task in Verilog that tracks changes in specified variables and prints their values.
- **Test Cases**: The testbench applies all combinations of input values to validate the behavior of the AND, OR, and NOT gates.

### Execution Steps
1. Copy the Verilog code into your preferred simulator (e.g., ModelSim, Xilinx Vivado, etc.).
2. Compile the code to check for syntax errors.
3. Run the simulation and observe the truth table results in the simulation output.
4. Verify the outputs match the expected logic gate behavior.



