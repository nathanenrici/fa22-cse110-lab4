1. It prints 3 because i was declared with var and is useable in the entire function. i's last value is 3 going through the for loop.
2. It prints 150 because discountedPriceis available in that scope because var was used and it is in the same function and would have the value of 150 from the last assignment.
3. It prints 150 because finalPrice is available in that scope because var was used and it is in the same block and would have the value of 150 from the last assignment.
4. It returns the array [50,100,150] (discounted). This is because it just pushes the result of prices[i]*(1-discount) to the discounted array, which is later returned.
5. It will error because i is only declared in the for loop which the log is not in.
6. It will error because discountedPrice is only declared in the for loop which the log is not in.
7. It will print 150 because finalPrice was declared in the same block the log is in, so it is still accessible.
8. It returns the discounted array, which in this case contains [50,100,150]. This is because all other variables still serve their purpose without the console logs and the discounted array is in scope being declared in the same block as the return statement.
9. It will error because i was declared with "let" and is therefore only useable in its loop, which the console log is not in.
10. It will print 3 to the console as the const length was declared in the same block as the console.log(), and no constants are reassigned.
11. It returns the array discounted = [50,100,150] because the push function does not change the original array reference, which is what is actually stored by the array discounted. This means that the elements of the array are not constant, only the reference, and the code still works as intended.
12. a. student.name
    b. student["Grad Year"]
    c. student.greeting()
    d. student["favorite teacher"].name
    e. student.courseLoad[0]
13. a.'32' because 2 is mapped to its string representation. Those strings are then concatenated.
    b. 1 because subtracting does nothing to strings it treats them as integers instead
    c. 3 because null becomes 0 as an integer.
    d. '3null' because null becomes the string "null" for string conversion.
    e. 4 because true is 1 as an integer.
    f. 0 because both become 0 as an integer.
    g. '3undefined' because undefined is simply represented as 'undefined' as a string.
    h. NaN because undefined becomes NaN when it is converted to a number.
14. a. true because in comparisons different types become converted to numbers, and 2 > 1.
    b. false because comparing strings is based on the first character as it works similar to alphabetical order and 2 > 1.
    c. true as the are converted to numbers as different types.
    d. false because === does not convert types.
    e. false because true is converted to 1 as a number.
    f. true because numbers that are not 0 converted to a boolean convert to true and true === true.
15. == checks equality with type conversion, while === does not convert types, so values with different types will not return true with === while they can with ==.
16. See part2-question16.js
17. the modifyArray call will return [2,4,6]. doSomething just returns the number times 2, so the modifyArray function just uses that on each element of the array passed to it in the same order.
18. See part2-question18.js
19. 1432