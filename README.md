# quiz 4-7 corrections

## quiz 4
11. Open ended response
  1) Correct
  2) 
  ```
function carPool(){
let z = Number(prompt("How many friends will you invite to the movies?"));
let SUVs = Number(prompt("Enter the number of your friends' parents who drive SUVs."))
let SUVneeded = Math.ceil(z/7);
let x = (SUVneeded) - (SUVneeded - SUVs);
let y = Math.ceil((z-(x*7))/4);
console.log(x, "parents who drive SUVs and ", y, "parent(s) who drive sedans are required to transport the ", z, "friends to the movies.");
}
```
## quiz 5
1. The answers to this question were &&, =, and ||. I now realize that these are the correct answers as the question is asking for the logical operators. This would be these correct answer as these operators deal with boolean logic.
2. I had gotten partial credit for this question as I marked = as an answer and did not mark != and !== as correct answers. The question is asking for relational operators which makes these answers, in addition to the answers I marked, correct because these are used to compare equality.
4. The  correct answer to this question was 
```
a < b && a < c
c > a || c > b
```
This is because the logical OR statement completes the bottom IF statement. Both conditions have to be true to make the statement output true, but if one or neither is false, it outputs false.

5. The correct answer to this question was
```
x === y
x !== y
```
However, I answered 
```
x === y
x != y
```
I now understand that the first one is correct because both operators mean it is not equal to but !== compares data and value type, whereas != compares value only.
6. The correct answer was  10, 8, and 20, respectively. This is because 17 and N puts the user into the child and visitors categories, giving the user an admission of 10 with no student discount, while 16 and Y gives the user the child and student categories which first gives the user an admission of 10,  then 10 - (10 * 0.2). This gives the user an admission of 8. Running 24 and N through the code gives the user a status of adult and N, which means that the user is not a child, and has an admission of 20.
7. I got this question partially correct. I did not mark let status = (studentGrade < 88) ? "ND" : "HR"; as a correct answer. However, it is correct because the if-else statements can be replaced by the two ternary operators. This answer is the inverse of the operators I had selected.
9. The correct answer to this question was
```
switch (dayCode)
   case 0: day = "Monday"; break;
   case 1: day = "Tuesday"; break;
   case 2: day = "Wednesday"; break;
   case 3: day = "Thursday"; break;
   case 4: day = "Friday"; break;
   case 5: day = "Saturday"; break;
   case 6: day = "Sunday"; break;
   default: day = "an unknown day"; break;
}
```
However, I did not select this answer as I was unaware that "break" was supposed to be written at the end of each line of code. Also, cases do not use quotations to show the case number.
10. The correct answer was 
```
if (score >= 90) {
    letterGrade = "A";
} else if (score >= 80) {
    letterGrade = "B";
} else if (score >= 70) {
    letterGrade = "C";
} else if (score >= 60) {
    letterGrade = "D";
} else {
    letterGrade = "F";
}
```
This is the correct answer as the answer I chose could accomplish the same task, but it was much more extensive than this answer. This code can achieve the same thing, but in a more efficient manner. If one if-statement is not met, the function will move onto the next else-if.
12. The correct answer to this question was a while loop check its condition before running the loop body, whereas a do...while loop checks its condition after running the loop body. I can understand that the answer I chose was incorrect as it was stating the opposite of the correct answer. 
## quiz 6
1. I marked console.log as a correct answer, in addition to prompt for this question. Prompt is correct. However, console.log is incorrect as it is not designed to return a value.
2. I received partial credit for this answer as I marked console.log and prompt correct. However, I did not mark alert as a correct answer. Alert is correct, though, because it is a built-in function that is designed to accept parameters.
4. My answer was wrong since I put that the function will return undefined. This is incorrect because only the parameters that did not receive arguments will be undefined, not the whole function. 
5. My answer was that the extra argument values will overwrite one or more of the parameters. However, I can understand that if more arguments are passed than there are parameters in the function definition, the extra arguments will be ignored. 
6. This answer would be correct because it accepts the parameters and achieves the goal of the function. The answer I chose is incorrect since the variables do not need to be declared again.
9. I received partial credit for this question. I did not include this answer as correct:
```function multiply(a, b, c, d) {
    if (a !== undefined && b !== undefined && c !== undefined && d !== undefined) {
        return a * b * c * d;
    else if (a !== undefined && b !== undefined && c !== undefined) {
        return a * b * c;
    } else if (a !== undefined && b !== undefined) {
        return a * b;
    } else if (a !== undefined) {
        return a;
    }
}
```
I now understand that this can be included as a correct answer as it achieves the same thing as the other two functions. However, it is simply more extensive.
10. I did not receive partial credit for this question, but I was partially correct as I marked one of the two possible answers correct. I did not include that the function is not designed to accept any parameters as a correct answer, however. I now know that this is correct since the function is not designed to accept any parameters as there is not enough information to determine whether it is true.
12. The correct answer to this question was that 1 and 2 will be printed to the console. This is because y was declared using the keyword var. A reference error would have occurred if var was not used.
13. The answer to this question is true instead of false since the var keyword pushes a variable to the function scope.
14. It is true for variables such as let and const to declare a variable inside of an if statement can only be referenced from within that same scope. This is because variables declared using var are brought to the top of the parent function in which they're declared. This means that no matter where the declaration takes place, the browser will move those declarations to the top of the function definition.
## quiz 7
8. I answer one out of the two answers for this question correct. I did not mark the following correct answer, though:
```
for (let i = 0; i < list.length; i++) {
    console.log(list[i]);
}
```
This is correct since using the name of the array, followed by .length allows us to access the number of elements in the array. It, essentially, tells us how many elements are in the list.
