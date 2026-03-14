# java-test-0001-final-14953-akash
Final Project Assignment - This repository contains the complete final project code and documentation.

## Problem Statement
This program demonstrates the use of **Java nested loops, spacing control, and pattern construction** to generate a hollow diamond star pattern.

The goal is to print the pattern exactly as specified using proper alignment and formatting.

## Expected Output

    *
   * *
  *   *
 *     *
*       *
 *     *
  *   *
   * *
    *

---

# Approach

1. **Define the size of the diamond**
   - Use a variable `n` to represent the number of rows in the upper half of the diamond.

2. **Print the upper half of the diamond**
   - Use a loop from `1` to `n`.
   - Print leading spaces to align the stars in the center.
   - Print stars `*` only at the **first and last positions** of each row.
   - Print spaces between them to maintain the **hollow structure**.

3. **Print the lower half of the diamond**
   - Use another loop from `n-1` down to `1`.
   - Print leading spaces similar to the upper half but in reverse order.
   - Print stars at the **first and last positions** with spaces in between.

4. **Use nested loops**
   - The outer loop controls the rows.
   - Inner loops control the printing of spaces and stars.

5. **Maintain symmetry**
   - The lower half mirrors the upper half to complete the diamond pattern.

---

# Time Complexity

O(N^2)

# Space Complexity

O(1)