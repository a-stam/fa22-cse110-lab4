1. 3 is printed
   - variable i is global and i = 3 because loop breaks at i = prices.length
2. 150 is printed
   - because the last element in prices is 300, 300 * (1 - 0.5) = 150 (global variable)
3. 150 is printed
   - finalPrice = round(discountedPrice * 100) / 100
4. [ 50, 100, 150 ]
   - it returns the array of discounted prices, every element in prices array is processed using discount and pushed to the discount array
5. ReferenceError - i is defined using let and it only belongs to the for loop scope
6. ReferenceError - discountedPrice is defined using let and it only belongs to the for loop scope
7. 150 is printed
   - finalPrice = round(discountedPrice * 100) / 100 -> correct scope
8. [ 50, 100, 150 ]
   - it returns the array of discounted prices, every element in prices array is processed using discount and pushed to the discount array
9. ReferenceError - i is defined using let and it only belongs to the for loop scope
10. 3
    - it is the length of the prices array and defined in the scope

11. [ 50, 100, 150 ]
    - it returns the array of discounted prices, every element in prices array is processed using discount and pushed to the discount array
  
12. Answers:
    - A. student.name
    - B. student['Grad Year']
    - C. student.greeting()
    - D. student['Favorite Teacher'].name
    - E. student.courseLoad\[0]

13. Answers:
    - A. '32' -> 2 is converted to a string
    - B. 1 -> 3 is converted to a number
    - C. 3 -> null is converted to 0
    - D. '3null' -> null is converted to a 'null' string and they are concatenated
    - E. 4 -> true is converted to 1
    - F. 0 -> false and null have value of 0 in number
    - G. '3undefined' -> undefined to 'undefined' string

14. Answers:
    - A. true converts string to number
    - B. false lower alphabetcial value
    - C. true string to number conversion
    - D. false string is not equal to number
    - E. false because number value of true is 1
    - F. true since 2 is converted to true boolean

15. == compares two values of variables after type conversion
    === compares the variables without conversion (two different types will never be equal)

17. [ 2, 4, 6 ]
    - the array and doSomething function are return to modifyArray. Since modify array loops through array and adds value processed by doSomething to a new array. Since doSomething returns the double value of the parameter, the array will have all double values of the parameter array.

19. Answer:\
1\
4\
3\
2  