## Part 2: A Little More of a Challenge... ##
1. The code will print out 3 since that is the ending condition of the loop.
2. The code will print out 150 since that is the last price that get calculated to find its discounted value. 
3. The code will print out 150 since at the last iteration of the loop, `discountedPrice` gets assigned with 150 and `finalPrice` gets assigned with the rounding value of `discountedPrice`, which is still 150. 
4. This function will return [50,100,150] because through each itertaion of the loop, the element in the array `price` get multiplied with the discount 0.5 and as a result, every price get divided by 2. Since at lien 8, every discount price getsn pushed into the output array, the output array is indeed the same as the input array except every element gets divided by half. 
5. The causes an error because the scope of variable `i` is restricted within the loop. Once we reach the back curly bracket, the variable `i` is no longer defined. 
6. The causes an error because the scope of variable `discountedPrice` is restricted within the loop. Once we reach the back curly bracket, the variable `discountedPrice` is no longer defined. 
7. The code will print out 150 since that is the last price that get calculated to find its discounted value. And the reason `let` works under this context is that the scope of `finalPrice` is the whole function block since it is defined outside of the loop. Therefore, the value of finalPrice is remembered and modified through the loop and records the value of last discount price. 
8. This function will return [50,100,150] because through each itertaion of the loop, the element in the array `price` get multiplied with the discount 0.5 and as a result, every price get divided by 2. Since at lien 8, every discount price getsn pushed into the output array, the output array is indeed the same as the input array except every element gets divided by half. The reason why `let` works is because the scope of the variable `discounted` is the whole function and therefore still accessible outside the block of the loop. 
9. The causes an error because the scope of variable `i` is restricted within the loop. Once we reach the back curly bracket, the variable `i` is no longer defined. 
10. The code wil print out 3 since that is the length of the input array `prices` as defined. 
11. This function will return [50,100,150] because through each itertaion of the loop, the element in the array `price` get multiplied with the discount 0.5 and as a result, every price get divided by 2. Since at lien 8, every discount price getsn pushed into the output array, the output array is indeed the same as the input array except every element gets divided by half. The reason why `const` works is because the scope of the variable `discounted` is the whole function, therefore still accessible outside the block of the loop and also `const` only prevents from assigning a new array to the variable directly but still mutatble to `push`. 
12. - A. `student.name`
    - B. `student["Grad Year"]`
    - C. `student.greeting()`
    - D. `student["Favorite Teacher"].name`
    - E. `student.courseLoad[0]`
13. - A. The output is **32** since integers map to their exact string representation and string concatenations take place. 
    - B. The output is **1** since strings amp to their exact integers representation and math calculations take place.
    - C. The output is **3** since null is treated as zero when converted into number and math calculations take place.
    - D. The output is **3null** since null maps to its exact string representation and string concatenations take place. 
    - E. The output is **4** since true is treated as one when converted into number and math calculations take place. 
    - F. The output is **0** since both null and false are treated as zero when converted into numeric values and math calculations take place. 
    - G. The output is **3undefined** since undefined maps to its exact string representation and string concatenations take place.
    - H. The output is **NaN** since undefined is treated as NaN when converted into its numeric values, making the result also NaN. 
14. - A. The output is **true** since '2' maps to 2 when being evaluated and 2 is indeed greater than 1. 
    - B. The output is **false** since when comparing two strings in js, the method is bitwise comparison and since '2' > '1', the result is indeed false. 
    - C. The output is **true** since '2' maps to 2 when being evaluated and 2 is equal to 2 itself. 
    - D. The output is **false** since === does not do any type conversion and therefore a number and string are clearly not equal to each other.
    - E. The output is **false** since true maps only to 1 and clearly 2 is not equal to 1 numerically. 
    - F. The output is **true** since under Boolean conversion, 2 is mapped to true and true is indeed equal to true. 
15. When using == as operator, the type conversion happens automatically while when using === as operator, it checks the equality without type conversion. 
17. The output would be [2 4 6] since within each iteration of the loop, the function doSomething is called with the value passed from the input array and within the function doSomething the input number is doubled, therefore pushing the result of the function doSomething to the output array would just double everything in the input array. 
19. the output should be 1 4 3 2 since setTimeout delays the function within the parenthesis and since `console.log(1)` and `console.log(4)` are not within the function, they get executed first. As 0 delay time means execute the code immediately in the next event cycle, `console.log(3)` get executed immediately after `console.log(4)`. And since `console.log(3)` get delayed by 1 second, the 3 gets printed out last. 