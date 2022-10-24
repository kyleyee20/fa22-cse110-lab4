1. it prints 3 because the i variable is kept throughout the function
2. it prints 150 because it uses the last value it had stored, which was the 300 with the .5 discount
3. it prints 150 because the finalPrice variable is var declared for the scope of the function
4. this doesn't return anything because you are not printing the values
5. it returns an error because we use let, so i is not defined
6. it returns an error because we use let, so discountedPrice is not defined
7. it returns 150 because even though we use let, it is still defined within this scope outside of the loop.
8. it doesnt return anything because we don't call for it to print the values
9. theres an error because we are trying to increment a const value
10. it returns 3 beacuse the length is a const that doesn't change
11. it doesnt return anything because we are not calling a print command
12. a) student.name
    b) student["Grad Year"]
    c) student.greeting()
    d) student["Favorite Teacher"].name
    e) student.courseLoad[0]
13. a) '32' because it added together strings
    b) 1 because it took 3 to be an integer when subtracting
    c) 3 because null is treated as 0
    d) '3null' because null is treated as a string to add
    e) 4 because true is treated as a 1
    f) 0 because both false and null are treated as 0
    g) '3undefined' because they are treated as strings to add together
    h) NaN because when subtracting, undefined is not a proper value
14. a) true because 2 is used as a number
    b) false because they are both strings and 12 is smaller because it starts with a 1
    c) true because the '2' is seen as a number
    d) false because the === checks their exact values
    e) false because true is a 1
    f) true because Boolean with any value returns true
15. the == ignores datatypes while === includes their datatypes
17. the array gets modified to double of each of the values because we used the callback parameter to call the doSomething function on each value in the array
19. 1 4 3 2 but each on a new line because the timeout delays the running of the line, so 1 and 4 would print, then since 3 had a smaller timeout, it would print before 2.
