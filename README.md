# ATM-MACHINE-OPERATION-
This problem deals with incrementing a large number that is represented using a one-dimensional array. Each element of the array stores a single digit of the number in left-to-right order. Since the number can be very large, it cannot be directly stored in standard numeric data types.

The task is to add one to the number by processing the digits from the last index and handling carry operations wherever required. If a digit is less than 9, it is incremented by one and the process stops. If a digit is 9, it is changed to 0 and the carry is passed to the next digit on the left. If all digits are 9, a new digit 1 is added at the beginning of the array.

The final output is the updated array of digits representing the incremented number without any leading zeros.
