# Operators and Loops

**_Comparisons_**  
_There are different way to make a comparison in a loop_
_Here are a few examples_  
1. == is equal to
2. != is not equal to 
3. === strict equal to
4. !== strict not equal to  
5. .    > greater than  

*ignore period above before the greater than*  

6. < less than  
7. . >= greater than or equal to
8. <= less than or equal to 
9. && logical and
10. || logical or
11. ! logical not

*Some examples of logical and / or
const a = 3;
const b = -2;*

*console.log(a > 0 && b > 0);
// expected output: false*

*console.log(a > 0 || b > 0);
// expected output: true*

*console.log(!(a > 0 || b > 0));*  

**_Loops_**

**for loop**  
_for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}_  

**while**  
_let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}_

