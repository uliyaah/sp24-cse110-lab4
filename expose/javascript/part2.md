# Part 2 Solutions
1. "3" will be printed because the value of i after running the for loop will be the length of the prices array, which is 3.
2. "150" will be printed because the last value held in discountedPrice would be the last element of the array with the discount applied to it which results in 150.
3. "150" will be printed because the last value held in finalPrice would be the last element of the array with the discount and rounding applied to it which results in 150.
4. It will return an array containing [50, 100, 150] which is the discounted prices of the orginal prices passed to the function.
5. The code will cause an error because i is declared as a let variable so it is only defined within that for loop not outside of it.
6. The code will cause an error because discountedPrice is declared as a let variable so it is only defined within that for loop.
7. "150" will print because finalPrice is declared at the beginning of the function, outside of the for loop, so it is defined anywhere in the function and can be used anywhere inside the function.
8. It will return an array containing [50, 100, 150] which is the discounted prices of the orginal prices passed to the function.
9. The code will cause an error because i is declared as a let variable so it is only defined within that for loop not outside of it.
10. "3" will be printed because the value of length is set to the length of the received array of prices, which in this case is 3.
11. It will return an array containing [50, 100, 150] which is the discounted prices of the orginal prices passed to the function.
12.  
    - A) student.name
    - B) student['Grade Year']
    - C) student.greeting()
    - D) student['Favorite Teacher'].name
    - E) student.courseLoad[0]

13. - A) Output: 32 because the + operator functions for both addition and concatenation, since 3 is a string data type, it was concatenated to 2 reuslting in 32
    - B) Output: 1 because the - operator only works for subtraction, since 3 is a string data type it is just converted to a number and then 2 is subtracted from it resulting in 1
    - C) Output: 3 since 3 is a number, null is just converted to a 0 and then added to 3 resulting in 3
    - D) Output: 3null because null is converted to a string, and concatenation is performed as in the same logic as part A, resulting in 3null
    - E) Output: 4 because true is converted to a 1 and added to 3 resulting in 4
    - F) Output: 0 because both values are converted to 0 and added resulting in 0
    - G) Output: 3undefined because of the same logic as part A and D
    - H) Output: NaN because undefined can't be converted to a number
14. 
    - A) Output: True, because both operands are converted to numbers, so this is 2 > 1, which is true
    - B) Output: True, because both operands are converted to numbers, so this is 2 < 12, which is true
    - C) Output: True, because == operator performs type coercion, so this is 2 == 2
    - D) Output: Fakse, because === operator does not perform type coercion, so this is 2 === '2'
    - E) Output: True, because boolean true is coerced to 1, so this is 1 == 2, which is false
    - F) Output: True, because Boolean(2) is true, so this is true === true
15. == tries to convert the data types to be the same and then compares while === is a strict equality and compares the values as is, considering data types and all.
16. [Link to JS file](./part2-question16.js)
    ``` 
    for(let prop in statistics){
        if(prop[0] === 'r' || statistics[prop] % 2 !== 0){
            console.log(statistics[prop]);
        }
    }
    ```
17. For the particular function call in the example, the result will be [2,4,6]. When modifyArray is called, the array that is passed as an input is iterated through the for loop where callback will be applied, in this case callback is equal to doSomething which will multiply each element from the array by 2. The values of each modified element is stored in newArray which is returned after exiting the for loop  
18. [Link to JS file](./part2-question18.js)
     ```
    function printTime() {
        let d = new Date();
        let time = d.toLocaleTimeString();
        console.log(time);
    }
    setInterval(printTime, 1000);
    ```
19. 1 4 3 2 in this order





