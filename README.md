# VHDL Counter Overflow Bug
This repository demonstrates a potential overflow issue in a simple VHDL counter. The `bug.vhdl` file contains the buggy code, while `bugSolution.vhdl` provides a corrected version.

## Bug Description
The original code lacks explicit handling for the case when the counter reaches its maximum value. This can lead to unexpected behavior, potentially causing the counter to wrap around incorrectly or produce unpredictable outputs.

## Solution
The solution involves adding a check to ensure the counter does not exceed its defined range. This prevents overflow and ensures correct counter operation.