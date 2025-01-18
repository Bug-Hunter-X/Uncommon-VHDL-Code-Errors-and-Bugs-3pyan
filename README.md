# Uncommon VHDL Code Errors and Bugs

This repository contains examples of uncommon errors and bugs that can occur in VHDL code, along with their solutions.  The focus is on issues beyond basic syntax errors, covering more subtle problems related to signal assignments, type handling, and concurrency.

## Bugs

* **bug.vhdl**: Demonstrates incorrect signal assignments within a process, leading to potential simulation issues.
* **bugSolution.vhdl**: Shows the corrected version with proper signal assignment and wait statements.

## How to Use

1. Clone this repository.
2. Open the VHDL files using a VHDL simulator (e.g., ModelSim, GHDL).
3. Compile and simulate the buggy code (`bug.vhdl`) to observe the problematic behavior.
4. Then, compile and simulate the corrected code (`bugSolution.vhdl`) to see the solution. 

## Contributing

Contributions are welcome!  If you encounter other uncommon VHDL bugs, feel free to submit a pull request with example code and solutions.