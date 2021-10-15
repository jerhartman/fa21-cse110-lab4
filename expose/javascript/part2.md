1. 3 is printed as i has function scope and was set to 3 at the end of the for loop
2. 150 is printed as discountedPrice has function scope and was set to 150 in the last iteration of the for loop
3. 150 is printed as finalPrice has function scope and was set to 150 in the last iteration of the for loop
4. [50, 100, 150] is returned as the function runs as intended since all the variables are in scope 
5. error: i is out of scope
6. error: discountedPrice is out of scope
7. 150 is printed since finalPrice is declaired in the same block and is set to 150 at the end of the for loop
8. [50, 100, 150] is returned as the function runs as intended with no scope errors
9. error: i is out of scope
10. 3 is printed since length is declaired in the same scope and no const variables are updated, so the program doesn't crash
11. [50, 100, 150] is returned as the function runs as intended with no scope errors and no const variables are updated
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseload[0]
13. A. '3' + 2 = '32' since 2 gets mapped to a string and concatenated
    B. '3' - 2 = 1 since '3' gets mapped to an integer and is decreased by 2
    C. 3 + null = 3 since null gets mapped to 0 and added to 3
    D. '3' + null = '3null' since null gets mapped to a string and concatenated
    E. true + 3 = 4 since true gets mapped to 1 and added to 3
    F. false + null = 0 since false and null both map to 0 and are added
    G. '3' + undefined = '3undefined' since undefined gets mapped to a string and concatenated
    H. '3' - undefined = NaN since '3' is mapped to 3 and undefined is mapped to NaN the result in NaN
14. A. '2' > 1 is true since '2' is mapped to 2 which is greater than 1
    B. '2' < '12 is false since we perform a string comparison where '2' comes after '1'
    C. 2 == '2' is true since the string '2' maps to the integer 2
    D. 2 === '2' is false since === is strict equality and checks for same type without converting 
    E. true == 2 is false since true is mapped to 1 which is not equal to 2
    F. true === Boolean(2) is true since Boolean(2) returns true
15. == will check if variables are equal when mapped to the same type, where as === does not convert types
16. see part2-question16.js
17. [2, 4, 6] is returned by modifyArray since we loop through the input array and call doSomething on each value, storing the result in newArr
18. see part2-question18.js
19. 1
    4
    3
    2


