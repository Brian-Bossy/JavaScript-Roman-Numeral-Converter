# JavaScript-Roman-Numeral-Converter
Project of converting Numbers to Roman Numerals

The function first initializes an empty string called romanNumeral and a map called romanNumeralMap that contains the Roman numeral equivalents of each number from 1 to 1000.

It then loops through each key in the romanNumeralMap object. For each key, it checks if the given number num is greater than or equal to the corresponding value in the map. If so, it appends the Roman numeral equivalent of the value to the romanNumeral string, and subtracts the value from num. It continues doing this until num is less than the value.

Finally, the function returns the romanNumeral string.
