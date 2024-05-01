1. 3 is printed out in line 12. This is because the variable 'i' is of var type, and it is accessible outside of the 'for' loop since it can be accessed throughout the entire function.

2. For the same reason as above, discountedPrice is stored as a var and the last computed value is 150, and since it has scope throughout the function, 150 is printed on line 13.

3. finalPrice is stored as a var, and has function-scope. Math.round(150 * 100)/100 is 150, and therefore 150 is printed out in line 14.

4. The returned discountPrices array will be the discountPrices post discount being applied, i.e. [50, 100, 150].

5. Line 12 causes an error. This is because the 'let' keyword can't be accessed outside the for-loop.

6. The 'let' keyword assigned to discountPrice has only block scope, and can therefore not be accessed outside the block. Hence, line 13 causes an error.

7. 150 will be printed by line 14. This is because line 14 has scope in the entire function and outside of the for-loop since it is defined outside the for-loop.

8. Similar to 4, the array [50, 100, 150] will be returned.

9. Line 11 causes an error, since the 'let' keyword can't be accessed outside the for-loop.

10. Length is declared using the 'const' keyword, and is non-modifiable. It is initially set to the length of the prices array, which is 3. Therefore, the line 12 will result in 3 being printed.

11. Similar to 4 and 8, the array [50, 100, 150] will be returned.

12. 
a. ```student.name```
b. ```student['Grad Year']```
c. ```greeting()```
d. ```student['Favorite Teacher'].name```
e. ```student.courseLoad(0)```

13.
a. 32
b. 1
c. 3
d. 3null
e. 4
f. 0
g. 3undefined
h. NaN

14.
a. true
b. false
c. true
d. false
e. false
f. true

15. The == operator compares values of two variables post type-conversion. The === operator performs equality check without any form of type-conversion.

16. Please check part2-question16.js

17. [2, 4, 6] is outputted as a result of the above code. This is because the doSomething function is applied to the array, and therefore all the elements of the array are simply multiplied by 2.

18. Please check part2-question18.js

19. The answer is as follows:
```
1 
4
3
2
```

