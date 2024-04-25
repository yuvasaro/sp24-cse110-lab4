1. Line 12 will print the variable `i`, which is at that point the length of the `prices` list. This is because `i` is declared with the `var` keyword, meaning it has function scope, and is used as the index variable in the for loop that executes before line 12. After the for loop is completed, `i` contains the length of `prices`.

2. Line 13 will print the last calculated discounted price from the for loop because the `discountedPrice` variable is declared with `var` so it has function scope. After the last iteration of the for loop, `discountedPrice` contains the last calculated discounted price.

3. Line 14 will print the last calculated final price from the for loop because the `finalPrice` variable is declared with `var` so it has function scope. After the last iteration of the for loop, `finalPrice` contains the last calculated final price.

4. This function will return the list of discounted prices, containing a discounted version of each price in the `prices` list using the discount specified by the `discount` parameter. The variable `discounted` has function scope because it is declared with the `var` keyword.

5. Line 12 will cause an error because it tries to access the variable `i` which was declared with `let` in the for loop. `i` has block scope due to the `let` keyword, and its block is the for loop, so it cannot be accessed outside of the loop.

6. Line 13 will cause an error because it tries to access the variable `discountedPrice` which was declared with `let` in the for loop. `discountedPrice` has block scope due to the `let` keyword, and its block is the for loop, so it cannot be accessed outside of the loop.

7. Line 14 will print the last calculated final price from the for loop because even though the `finalPrice` variable is declared with `let`, its block scope corresponds to the entire function since it is declared inside the function scope (and not in any other inner scope). After the last iteration of the for loop, `finalPrice` contains the last calculated final price.

8. This function will return the list of discounted prices, containing a discounted version of each price in the `prices` list using the discount specified by the `discount` parameter. Even though the variable `discounted` is declared with the `let` keyword, it is declared inside the function scope (and not in any other inner scope).

9.  Line 11 will cause an error because it tries to access the variable `i` which was declared with `let` in the for loop. `i` has block scope due to the `let` keyword, and its block is the for loop, so it cannot be accessed outside of the loop.

10. Line 12 will print the length of the `prices` list stored in the constant `length`. No errors occur because the code does not attempt to reassign the constant.

11. This function will return the list of discounted prices, containing a discounted version of each price in the `prices` list using the discount specified by the `discount` parameter. Even though the variable `discounted` is declared with the `const` keyword, it is declared inside the function scope (and not in any other inner scope), and the code never attempts to reassign it; it is only mutated with methods called on it.

12.  
- A. `student.name`
- B. `student["Grad Year"]`
- C. `student.greeting()`
- D. `student["Favorite Teacher"].name`
- E. `student.courseLoad[0]`

13. 
- A. `'32'`
- B. `1`
- C. `3`
- D. `'3null'`
- E. `4`
- F. `0`
- G. `'3undefined'`
- H. `NaN`

14. 
- A. `true`
- B. `false`
- C. `true`
- D. `false`
- E. `false`
- F. `true`

15. `==` first does type conversion so that the two items being compared are the same type, then checks for equality. `===` doesn't do type conversion, so it returns false if the two values are different data types or have different values, and only returns true if they are of the same data type and have the same value.

17. First the array `newArr` is created. Then in the for loop, for each element in the input array `[1, 2, 3]`, the function `doSomething` is called on the element and the result is appended to `newArr`. The function `doSomething(num)` multiplies `num` by 2 and returns it. At the end of the for loop, the results of `1*2`, `2*2`, and `3*2` are pushed to `newArr` and then `newArr` is returned at the end of the function. The result is `[2, 4, 6]`.

18. The code first prints `1` with no delay, then prints `2` after 1 second, then prints `3` and then `4` with no delay.
