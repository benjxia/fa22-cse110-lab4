1. 3, the loop terminates after 3 iterations (length of the input), and
   i is the incrementer variable and has function scope. 
2. 150, it is the value of discountedPrice after the loop terminates since the variable has function scope. 
3. 150, it is the value of finalPrice after the loop terminates since the
   variable has function scope. 
4. A list containing [50, 100, 150], discountPrices applies the discount 
   all elements to its first parameter array to a copy list that is returned.
5. Error, i is only defined within the for loop, and is not defined at the scope of console.log
6. Error, discountedPrice is only defined within the for loop, and is not defined at the scope of console.log
7. 150, it is set to the discounted price of the last index of prices in the final iteration. 
8. A list containing [50, 100, 150], discountPrices applies the discount 
   all elements to its first parameter array to a copy list that is returned.
9. Error, i is only defined within the for loop, and is not defined at the scope of console.log
10. 3, length is set to 3 at the beginning of the function.
11. A list containing [50, 100, 150], while the list itself is being updated, there's never an attempt to reassign what discounted is referencing. 
12. 
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. 
    1. '32', 2 gets converted into a string
    2. 1, 3 gets converted into a number. 
    3. 3, null gets converted to a 0. 
    4. 3null, null gets converted to a string. 
    5. 4, true maps to 1. 
    6. 0, both map to 0. 
    7. 3undefined, undefined gets converted to a string
    8. NaN, undefined -> NaN if not converted to string. 
14. 
    1. true, '2' is converted to a number
    2. false, string comparison -> 12 comes before 2.
    3. true, '2' is converted to string
    4. False, '2' and 2 are different types and values
    5. False, true gets converted to a 1
    6. True, boolean(2) is converted to true since 2 is nonzero. 
15. == allows for type conversion, === is strict equality and type and value must both match. 
16. See `part2-question16.js`
17. [2,4,6]. Walking through the functions, we first call modifyArray while passing doSomething as a callback. We iterate through the passed array [1,2,3] and push the callback output to newArr, and return newArr. The callback returns the double of the parameter, so we basically just double each element in the original array and return the new array.
18. See `part2-question18.js`
19. 
```
1
4
3
2
```