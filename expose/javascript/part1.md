1. Line 9 prints the sum of num1 and num2, for this example it prints: values added: 20
2. Line 13 prints the final result of the sum of num1 and num2, in this example it prints: final result: 20 
3. You shouldn't use var cause it can lead to scoping issues and naming conflicts since var variables are avaliable anywhere in the function. 
4. Line 9 prints valued added:  20, which is the sum of num1 and num2.
5. Line 13 causes an error because result is not defined outside the if statement. Let declares a block scoped local variable. 
6. Line 9 produces an error because result is a const variable thus it can't be reassigned but we reassign it from 0 to the sum of num1 and num2. 
7. Line 13 causes an error because result is not defined outside the if statement since its assigned using const which assigns local variables.

