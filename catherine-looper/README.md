# 1-ES6-practice

## Feature Tasks

Follow these instructions carefully and in order.

1. Open the HTML file in the browser to ensure that it works.
2. Turn all `var` variable declarations into `let`.
3. After you do, there will be one error. Find that line in the code, delete that line and respond to the adjacent TODO item.
4. Return to the browser to ensure that the code works again.
5. **Save the code, and do a Git "add" and "commit".**
6. Now, in the code, convert all `let` variable declarations into `const`.
7. Bugs will erupt everywhere. Debug by using the error messages in the browser console, turning `const` declarations back into `let` where necessary. Expect there to be some back-and-forth between your code editor and your browser.
8. When you think you have things working, clear local storage and reload the page to ensure that the code still works when starting from a totally clean state.
9. **Save the code, and do a Git "add" and "commit".**
10. Now find all concatenations in the code and convert them into template literal notation.
11. Reload the browser to ensure that the code works as expected.
12. **Save the code, and do a Git "add" and "commit".**
13. Answer the following questions:

---

##### Investigate how `let` and `const` are now used in the code. Where did you need to convert `const` into `let` to make the code work? Can you identify any patterns/similarities?

I used const in the code when the variable did not need to be reassigned or redeclared. Initially, I changed all of the let variables to const, which threw a lot of errors. I had to change the const variables in the for loops back to let variables, since i increments each time, it is reassigning the variable each time, so const does not work in that environment. Additionally, the empty arrays need to use a let vs const, because they are also getting reassigned, as is the total clicks counter variable.

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

It is pretty sweet. It is much cleaner to use back-ticks at the beginning and ending of the code rather than using quotations throughout. I also like that spaces in the code are actually counted as spaces. It makes using template literal notation more intuitive. I definitely think I will continue using template literal notation rather than concatenation moving forward. 
