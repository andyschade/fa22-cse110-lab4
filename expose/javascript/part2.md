1) In line 12, the number of i will be printed at the end of the function after the for loop has run thorugh all of its iterations(trhough the length of prices). Line 12 prints 3 because the length of prices is 3. Therefore i = 3.
2) In line 13, 150 will be printed because the last var discountedPrices to be aved in the for loop is (300)x(0.5) which is 150 thus the print of discountedPrice after the end of the for loop results in 150.
3) In line 14, similar to last problem the last var used in the during runtime of the for loop is in the var discountedPrice, the var finalPrice is discountedPrice rounded. In this case 150 rounded is still 150. So line 14 prints 150.
4) Function returns a list of the prices list with the discount applied. In this case the function returns [50, 100, 150]. This is because 100,200, and 300 with the 0.5 discount applied is 50, 100, and 150.
5) At line 12 there is an error because i is not defined outside of the for-loop.
6) At line 13 there is an error because discountedPrice is not defined outside of the for-loop.
7) In line 14, similar to problem 2) the last let used in the during runtime of the for loop is in the let discountedPrice, the finalPrice variable is untaggedand it just is let discountedPrice rounded. In this case 150 rounded is still 150. So line 14 prints 150.
8) Function discountedPrices returns a list of the prices list with the discount applied. In this case the function returns [50, 100, 150]. This is because 100,200, and 300 with the 0.5 discount applied is 50, 100, and 150.
9) At line 11 there is an error because let i is not defined outside of the for-loop.
10) At line 12 the length of this list is printed which is just the value 3. This is beacuse the variable length is inscope and unchnage since it is instantiaded at line 4.
11) Function discountedPrices returns a list of the prices list with the discount applied. In this case the function returns [50, 100, 150]. This is because 100,200, and 300 with the 0.5 discount applied is 50, 100, and 150.
12) - A) student.name
    - B) student['Grad Year']
    - C) student.greeting()
    - D) student['Favorite Teacher'].name
    - E) student.courseLoad[0]
13) - A) 32  -> 3 and 2 are added together as strings
    - B) 1   -> 3 and 2 are subtracted as numbers
    - C) 3   -> 3 is added to null or 0 so = 3
    - D) 3null -> 3 and null are added together as strings
    - E) 4    -> true acts as a 1 to make 3+1 =4
    - F) 0    -> false and null act as 0 to make 0+0=0
    - G) 3undefined -> undefined changes type to sting to concat with 3
    - H) NaN -> undefined is uncomputable so NAN is returned
14) - A) true ->true because string '2' is type casted to int 2 and greater than 1
    - B) false -> false because string '2' is greater than string '12' because it looks at first chararcter in string.
    - C) true -> true because '2' is type casted to 2
    - D) false -> false because 2 and '2' are not the same type
    - E) false -> false because true is == to int value 1
    - F) true -> true because Boolean of 2 is non empty and therefor equal to the type boolean value of true.
15) The == operator is a regular equality check that cannot differentiate between values like 0 and false. And === is a strict equality check that checks the equality without doing any sort of "type conversion".
17) The result is the array [1, 2, 3] is modified by the doSomething function. Each of the values in the array are individually called into the doSomething function which multiplies them by 2. Then the resulting value is pushed to a new array called newArr. thus a new array newArr is created holding the values [2, 4, 6] in this particular case.
