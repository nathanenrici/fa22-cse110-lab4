1. 20
2. 20
3. 20
4. The code returns an error. This is because the "let" keyword creates the result variable in the "if" block while this return takes place outside of that block.
5. The code returns an error before anything is printed. This is because result is a const, so reassigning its value is not allowed.
6. Same as in part 5. If line 9 cannot print due to error it never makes it to line 13.