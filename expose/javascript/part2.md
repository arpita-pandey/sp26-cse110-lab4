1. Line 12 prints 3, the size of prices. Since i is initialized a a global var it is avaliable anywhere in the function. 

2. Line 13 prints the discounted price which is 150 in this case. Since discountedPrice is initialized with var it can be used outside the scope of the for loop. 

3. Line 14 prints the finalPrice 150, which is defined in the same scope.

4. The function returns an array called discounted which is the prices inputed into the function after they are discounted using the discount parameter. 

5. Line 12 causes an error because i is defined using let so it is local to the for loop and hasn't been inititalized outside of it so it will cause an error. 

6. Line 13 causes an error because discountedPrice is only defined inside the for loop since it is initialized using let. 

7. Line 14 will successfully print the value of finalPrice because the variable was declared using let at the function level. Since the line is still within the same block where the variable was defined, it remains accessible after the loop finishes.

8. The function will return the array [50, 100, 150]. This occurs because the loop correctly calculates the discounted values and pushes them into the discounted array, which is then returned by the function.

9. An error will occur because i is declared with let inside the for loop header, giving it block scope. Consequently, i is not defined outside of the loop's curly braces, making it inaccessible at line 11.

10. This line will result in an error or not be reached because const was used to declare variables that the code attempts to reassign. Even if the reassignment didn't fail, any variable like length declared with const or let inside a block cannot be accessed from outside that block.

11. The function will return an error rather than a value. This is because the code attempts to reassign a value to a const variable within the loop, which is a prohibited operation in JavaScript and triggers a TypeError.

12.
A. student.name;
B. student['Grad Year'];
C. student.greeting();
D. student['Favorite Teacher'].name
C. student.courseLoad[0]

13. 
A. '32' , numbers map to the exact string representation.
B. 1 , numbers map to the exact string representation and - only works with numbers.
C. 3, null = 0. 
D. '3null' , ints map to their exact string represenation and an operand is a string which triggers string concatenation. 
E. 4, true = 1 and 1 + 3 = 4.
F. 0, false = 0 and null = 0 so 0+0 = 0. 
G. '3undefined' because the presence of a string and the + causes string concatenation. 
H. 'Nan' because the - operand requires numbers and one is a string and the other is undefined. 

14. 
A. true , when comparing a string to number using > the '2' is converted to a 2. 
B. false, comparing 2 strings is done in unicode order.
C. true, loose equality convers the string to number since the types are different. 
D. false, strict equality checks value and type. 
E. false, comparing boolean to a number true = 1. 
F. true, any non-zero number = true in javascript so true === true. 

15. == : Compares two values for equality after converting both values to a common type.
===: Compares both the value and the data type without doing any conversion. It only returns true if both operands are the same type and have the same value.

17. The result is [2,4,6]. Function modifyArray takes an array and feeds every element to the doSomething function which multiplies each element by 2 and then pushes this modified element into a new array and returns the new array. 

19. The output will be:
1
4
3
2