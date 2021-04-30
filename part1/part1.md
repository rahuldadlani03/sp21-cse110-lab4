# Part 1a

## var declaration
1. values added: 20
2. final result: 20

3. values added: 20
4. 'ReferenceError: result is not defined' is returned. This is because 
declaring variables with 'let' means that they have block scope and line 13 
tries to access result which is not in its block scope.

5. For questions 5 and 6, nothing is printed by the console.log statements.
Instead, the error 'TypeError: Assignment to constant variable.' is thrown since
we're trying to reassign a variable that was declared constant
6. See question 5

Part 1b
1. 3 is printed. This is because i is declared as var so it is visible outside
of the for loop. Also, it prints 3 since i will increment until i <
prices.length even though the for loop does not execute on the forth iteration
where i would be equal to 3
2. The discounted price of prices[2] is printed out- 150. No errors are thrown
because discountedPrice is declared as var and var does not adhere to its block
scope
3. Same thing happens as in question 2. 150 is printed out since 300 multiplied
by 0.5 rounded is equal to 150
4. The function returns an array of the prices passed in discounted at 50
percent. [ 50, 100, 150 ]
5. 'ReferenceError: i is not defined' is printed out because declaring a
variable with let means that it has scope so it can not be accessed outside
of the code block it was declared in
6. 'ReferenceError: discountedPrice is not defined'. Same reason as question 5
7. '150' is printed out. finalPrice is declared in the same scope as line 14 so
it can be accessed
8. It will return the same thing as question 4. Var and let act the same outside
of the scope they can be accessed in and when var declarations are processed
9. 'ReferenceError: i is not defined' is printed out because declaring a
variable with let means that it has scope so it can not be accessed outside
10. '3' is printed out since length is just a constant and is declared in the
same scope as line 12
11. '[ 50, 100, 150 ]' is returned. Since 'discounted' is not reassigned, it
works the same as declaring 'discounted' with let instead of const

## data types
12. 
A. student["name"];
B. student["Grad Year"];
C. student["greeting"]();
D. student["Favorite Teacher"]["name"];
E. student["courseLoad"][0];

13.
A. '32' - 2 mapped to '2' and then concatenated with '3'
B. 1 - '3' numerically converted to 3 and then 3 - 1 = 2
C. 3 - null mapped to 0 and then 3 + 0 = 3
D. '3null' - null mapped to 'null' then concatenated with '3'
E. 4 - true mapped to 1, then 1 + 3 = 4
F. 0 - false and null both mapped to 0 then 0 + 0 = 0
G. '3undefined' - undefined mapped to 'undefined' then concatenated with '3'
H. NaN - undefined mapped to numeric undefined which is NaN then the subtraction
is Nan

14.
A. true - '2' mapped to 2 and 2 > 1 is true
B. false - first character of '2' is greater than first character of '12' so '2'
is greater than '12'
C. true - '2' becomes 2 and 2 == 2 is true
D. false - because === is strict equality check and numeric and string are not
equal types so false
E. false - true converted to 1 and 1 == 2 false
F. true - 2 is not 0 hence it is converted to true and true is 1 so 1 == 1 which
is the same as saying true == true

15. == - is a regular equality check and performs type conversion
=== - is a strict equality check and performs type conversion
16. (See part1b-question16.js)

## functions
17. modifyArray returns [2,4,6]. This is because for each element in array, the
result of callback(array[i]) is stored in newArr. Since callback is set to the
function doSomething and it returns the argument passed in multiplied by 2, that
is what is stored in newArr
18. (See part1b-question18.js)
19. This is printed out:
1
4
3
2
