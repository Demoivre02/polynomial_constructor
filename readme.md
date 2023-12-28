# Polynomial Root Finder

This Python script provides a set of functions for finding the polynomial equation with given roots and displaying it in a user-friendly format. The main functions include:

1. `Poly(terms)`: Takes a list of coefficients as input and returns the polynomial equation in string form. It displays the equation with the standard mathematical notation, e.g., `ax^n + bx^(n-1) + ... + c = 0`.

2. `PolyRoot(roots)`: Takes a list of roots (in decimal or fraction form) as input and returns the corresponding polynomial equation. It internally calls the `Poly` function.

3. `GCD(num, denom)`: Calculates the greatest common divisor of two numbers using the Euclidean algorithm.

4. `DecToFrac(decimal)`: Converts a decimal number to a simplified fraction. If the decimal is recurring, it handles recurring decimals and converts them to fractions.

5. `FracToTuple(frac)`: Converts a fraction in the form "numerator/denominator" to a tuple `(numerator, denominator)`.

6. `MultiplyRoots(roots, multiplier)`: Multiplies each root by a given multiplier.

7. `RootsToTuples(roots)`: Converts a list of roots (in decimal or fraction form) to a list of tuples.

# Examples

```python
print(PolyRoot(['-3/2', '0']))
print(PolyRoot(['1.0(54)', '3/1']))
print(PolyRoot(['0.(8)', '-0.75', '-3/6', '-5', '4/2']))
print(PolyRoot(['-5.(9)', '114/19', '4.0', '-131/95', '0', '25/200', '-391/23']))
```

These examples demonstrate how to use the script to find polynomial equations from given roots. The roots can be provided as fractions or decimals (including recurring decimals). The resulting polynomial equations are displayed in a readable format.