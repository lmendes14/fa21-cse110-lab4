1. 3 will be printed. This is because the for loop exits when i equals prices' length, which is 3. We're able to access i outside of the for loop since the 'var' keyword gives i global scope.
2. 150 will be printed. This is because discountedPrice is reassigned the value of prices[2] * (1 - 0.5) = 300*0.5 = 150. We're able to access discountedPrice outside of the for loop since the 'var' keyword gives discountedPrice global scope.
3. 150 will be printed. This is because finalPrice is reassigned the value of Math.round(discountedPrice * 100) / 100 = Math.round(150 * 100) / 100 = 15000 / 100 = 150. We're able to access finalPrice since the 'var' keyword gives finalPrice global scope.
4. The function will return [ 50, 100, 150 ]. This is because the function takes all of the values in prices and applies the discount to each. Since the discount is 0.5, it divides all of the values in prices by 2 and returns the new container.
5. The code causes an error because the 'let' keyword give i block scope within the for loop. When we try to access i outside of the loop, it's out of scope, and an error is thrown.
6. The code causes an error because the 'let' keyword give discountedPrice block scope within the for loop. When we try to access discountedPrice outside of the loop, it's out of scope, and an error is thrown.
7. 150 will be printed. This is because finalPrice is reassigned the value of Math.round(discountedPrice * 100) / 100 = Math.round(150 * 100) / 100 = 15000 / 100 = 150. We're able to access finalPrice since the 'let' keyword gives finalPrice block scope within the function, which is where we're accessing it.
8. The function will return [ 50, 100, 150 ]. This is because the function takes all of the values in prices and applies the discount to each. Since the discount is 0.5, it divides all of the values in prices by 2 and returns the new container.
9. The code causes an error because the 'let' keyword give i block scope within the for loop. When we try to access i outside of the loop, it's out of scope, and an error is thrown.
10. 3 will be printed. This is because we never reassign length and we're within scope.
11. The function will return [ 50, 100, 150 ]. This is because the function takes all of the values in prices and applies the discount to each. Since the discount is 0.5, it divides all of the values in prices by 2 and returns the new container.
12. 
    - A. student.name
    - B. student['Grad Year']
    - C. student.greeting()
    - D. student['Favorite Teacher'].name
    - E. student.courseLoad[0]
13. 
    - A. '32'. Here the 2 gets converted to a string, and the + concatenates the two strings.
    - B. 1. Here the '3' gets converted to a number, and the - subtracts the two numbers.
    - C. 3. Here the null gets treated as a 0, and the + adds the two numbers.
    - D. 3null. Here the null gets converted to a string, and the + concatenates the two strings.
    - E. 4. Here the true gets converted to a 1, and the + adds the two numbers
    - F. 0. Here the false and null get converted to a 0, and the + adds the two numbers.
    - G. 3undefined. Here the undefined gets converted to a string, and the + concatenates the two strings.
    - H. NaN. Here the undefined gets converted to NaN, and any number minus NaN is NaN.
14. 
    A. true. Here the '2' gets converted to its numeric value, and 2 is greater than 1.
    B. false. Here javascript performs string comparison, and 2 is in later lexicographic order than 12.
    C. true. Here '2' gets converted to its numewric value, and 2 equals 2.
    D. false. Here javascript performs strict equality, meaning '2' does not get converted to a number, and a number does not equal a string.
    E. false. Here true gets converted to 1, and 1 does not equal 2.
    F. true. Here Boolean(2) returns true, and true is strictly equal to true.
15. The difference between == and === is that === is a strict equality operator, meaning that no conversions of datatypes occur, whereas == allows for datatype conversion.
17. When we call modifyArray, we perform our callback on each element in the argument array and push that result onto a new array. Since our callback returns 2 times the argument element, we effectively return a new array containing 2 times all of the elements in the passed in array. Thus, the result will be [ 2, 4, 6 ].
19. 1
    4
    3
    2
