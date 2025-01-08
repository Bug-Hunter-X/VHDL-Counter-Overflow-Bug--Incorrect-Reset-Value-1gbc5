# VHDL Counter Overflow Bug

This repository demonstrates a subtle bug in a VHDL counter implementation. The bug involves an incorrect assignment when the counter reaches its maximum value, causing unexpected behavior.

## Bug Description
The `buggy_counter.vhdl` file contains a counter that is supposed to count from 0 to 15 and then wrap around. However, due to a typo in the overflow condition, the counter does not reset correctly, leading to unintended behavior.

## Solution
The corrected code is provided in `fixed_counter.vhdl`.  The solution simply fixes the typo in the overflow condition.