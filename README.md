# Booth's Algorithm

## Introduction

Booth's multiplication algorithm is a method for multiplying signed or unsigned integers in 2's complement binary representation. It utilizes fewer additions and subtractions than more straightforward multiplication algorithms.

## Objectives

- Provide knowledge on binary multiplications.
- Solve problems using Booth's algorithm.
- Teach the procedure for binary multiplication using Booth's algorithm.

## Advantages

- Performs Signed Multiplications.
- Performs better when negative numbers are involved.
- Reduces the number of operations.

## Disadvantages

- Performance decreases if the quotient (Q) has a repetitive pattern like 01010101010.

## Solutions

- Multiply using the Straightforward Algorithm.
  - Only works for unsigned integers.
- Multiply only magnitudes using the Straightforward Algorithm.
  - If signs are different, negate the answer.

## Booth's Algorithm

- Developed by A.D. Booth in 1950 at Birkbeck College in London.
- Works for signed integers.

## Conclusion

Booth's algorithm is an efficient multiplication algorithm for signed binary numbers that can be easily implemented in software and hardware. It is a valuable tool for computer engineers and programmers who need to perform fast multiplication of signed binary numbers.

## Future Scope

- Signed Multiplication.

## Back to Agenda

- Return to the Agenda for further topics.

## Steps to Follow

1. Convert signed integers into unsigned using 2’s complement.
2. Load the values into registers.

### Example

For the 2's complement of (-5):
- Binary: 0111
- 1's complement: 1000
- + 1
- 2's complement: 1001

## Running the Project

To run this project, you can use the Logisim tool. Open the file `Booth_multiplier.circ` in Logisim and follow the steps mentioned in the tool to simulate and analyze the Booth's Algorithm.

## Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or provide feedback to enhance the functionality and usability of the Booth's Algorithm.

## Reporting Issues

If you encounter any errors or face problems related to this program, please feel free to contact me via jvlpranathi@gmail.com.

