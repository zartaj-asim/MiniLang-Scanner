# MiniLang-Scanner
Design and implement a scanner for MiniLang using C++ or python.



### Test Cases 
- Case 1: Testing IF-Else Code
Tested the scanner's ability to tokenize a basic if-else code structure in MiniLang.
- Case 2: Testing != (not equal to) operator
Tested the scanner's handling of the != (not equal) operator within an if statement. 
- Case 3: Testing Boolean Expression
Tested the scanner's ability to handle Boolean expressions within an if statement. 
- Case 4: Testing Lexical Error
Tested the scanner's ability to detect and report lexical errors in the MiniLang code.

### Edge Cases 
- Edge Case 1: Empty File
  - Input: An empty file.
  - Expected Output: No tokens. 
- Edge Case 2: File with Only Whitespace
  - Input: File with only whitespace characters.
  - Expected Output: No tokens. 
- Edge Case 3: File with Comments Only
  - Input: File with only comments.
  - Expected Output: No tokens. 
- Edge Case 4: Long Identifier File
   - Input: File with a long identifier.
   - Expected Output:
Identifier: a1234567890123456789012345678901234567890
Operator: =
Integer Literal: 42
 
