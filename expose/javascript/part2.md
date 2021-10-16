### 1. It prints **3**. **var** variables have no block scope. Because it prints the value of **var i**, which is initialized with value 0 and added by 1 for 3 times.
&nbsp;
### 2. It prints **150**. **var** variables have no block scope. Because it prints the latest value of **var discountedPrice**, which is assigned a value of 300*(1-0.5) = 150 at line 7 in the loop above at the end.
&nbsp;
### 3. It prints **150**. **var** variables have no block scope. Because it prints the latest value of **var finalPrice**, which is assigned a value of (150*100)/100 = 150 at line 8 in the loop above at the end. The **Math.round()** function returns the value of a number rounded to the nearest integer, thus this line will round **var discountedPrice** to 2 decimal places.
&nbsp;
### 4. It returns an array: **[ 50, 100, 150 ]**. **var** variables have no block scope. We declare an empty array at line 3 and keep pushing the value of **var finalPrice** into it during each iteration of the loop. Since the discount is **0.5** and the initial price list is **[ 100, 200, 300 ]**, this function simply returns the new price list (price list for consumer) which is **[ 50, 100, 150 ]**.
&nbsp;
### 5. It returns a reference error. **let i** is declared inside of the for-loop block. **let** variables have block scope, thus it is not defined outside.
&nbsp;
### 6. It returns a reference error. **let discountedPrice** is declared inside of the for-loop block. **let** variables have block scope, thus it is not defined outside.
&nbsp;
### 7. It prints **150**. **let finalPrice** is declared outside of the for-loop block, thus it is defined in the block of the **discountPrices()** function. Thus it prints the latest value of **let finalPrice**, which is assigned a value of (150*100)/100 = 150 at line 8 in the loop above at the end.
&nbsp;
### 8. It returns an array: **[ 50, 100, 150 ]**. We declare an empty array at line 3 and keep pushing the value of **let finalPrice** into it during each iteration of the loop. Since the discount is **0.5** and the initial price list is **[ 100, 200, 300 ]**, this function simply returns the new price list (price list for consumer) which is **[ 50, 100, 150 ]**.
&nbsp;
### 9. It returns a reference error. **let i** is declared inside of the for-loop block. **let** variables have block scope, thus it is not defined outside.
&nbsp;
### 10. It prints **3**. It prints the value of **const length** which is assigned a value of 3 at line 10. Also, since it is a **const** type, its value will never change.
&nbsp;
### 11. It returns an array: **[ 50, 100, 150 ]**. The keyword **const** is a little misleading. It does NOT define a constant array. **It defines a constant reference to an array.** Because of this, we can still change the elements of a constant array. We declare an empty array at line 3 and keep pushing the value of **const discountedPrice** into it during each iteration of the loop.
&nbsp;

### 12.
<ol type="A">
    <li> student.name <b>example:</b> console.log(student.name);
    <li> student['Grad Year'] <b>example:</b> console.log(student['Grad Year']);
    <li> student.greeting();
    <li> student['Favorite Teacher'].name <b>example:</b> console.log(student['Favorite Teacher'].name);
    <li> student.courseLoad[0] <b>example:</b> console.log(student.courseLoad[0]);</ol>

### 13.
<ol type="A">
    <li> '32'
    <li> 1
    <li> 3
    <li> '3null'
    <li> 4
    <li> 0
    <li> '3undefined'
    <li> NaN
    </ol>

&nbsp;
### 14.
<ol type="A">
    <li> true
    <li> false
    <li> true
    <li> false
    <li> false
    <li> true
    </ol>

&nbsp;
### 15. When comparing values of different types, regular quality operator **==** converts the values(operands) to numbers, while the strict equality operator **===** checks the equality without type conversion. In other words, if a and b are of different types, then a **===** b immediately returns false without an attempt to convert them.
&nbsp;
### 16. The answer is in [**part2-question16.js**](part2-question16.js). 
&nbsp;
### 17. It will return an array: [2, 4, 6]. Here we are passing in an array: **[1, 2, 3]** and a fucntion **doSomething()** as parameters of **modifyArray()**. Then we pass each element of the given array as a parameter of **doSomething()** and push each return value into a new array. The **doSomething()** function can double the input value and return it, thus each element in the new array is twice as large as the original one. Hence we have **[2, 4, 6]**.
&nbsp;
### 18. The answer is in [**part2-question18.js**](part2-question18.js). 
&nbsp;
### 19. <br>1<br>4<br>3<br>2



