# Formula Calculations in C

This repository contains a C program that takes user input for multiple values and applies the following mathematical formulas:

### Formulas Implemented:
1. **Formula 1:** `a + (b - c / d) + ++num`
2. **Formula 2:** `num1 + num2 / num3 + num + num2++`
3. **Formula 3:** `(m + n) / (p + amount)`

### How to Use:
1. Compile the program using a C compiler (e.g., `gcc`).
2. Run the executable file.
3. Enter values when prompted.
4. The program will display the results of each formula.

### Compilation Command:
```sh
gcc formula_calculations.c -o formula_calculations
```

### Execution Command:
```sh
./formula_calculations
```

### Note:
- Formula 3 handles division by zero by checking if the denominator is zero before performing the operation.
- Ensure valid inputs to avoid unexpected behavior.
