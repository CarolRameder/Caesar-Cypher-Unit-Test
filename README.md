# Caesar-Cypher-Unit-Test

Task Description

The goal of this project is to develop a Python function that identifies rot-equivalent strings. Rot-equivalence is determined by the ability to rotate one string into another by shifting its letters through the alphabet by a certain number of positions, wrapping around the end of the alphabet if necessary. This concept originates from the Caesar cipher, an ancient encryption technique.

The primary function to implement is find_rot_equivalence_classes, which will accept a list of uppercase strings and output a list of lists, where each sublist contains strings that are rot-equivalent to each other.

Example: 

input: ['HELLO', 'IFMMP', 'WORLD', 'URYUB', 'ASVPH', 'SUN']

func(input): [['HELLO', 'IFMMP', 'URYUB'], ['WORLD', 'ASVPH'], ['SUN']]

Requirements:

Implement the find_rot_equivalence_classes function.

Strive for computational efficiency and include the complexity analysis in comments.

Develop a comprehensive test suite using unittest to cover various edge cases.

Read and parse input from STDIN.

Add comments and type description as for a code review.
