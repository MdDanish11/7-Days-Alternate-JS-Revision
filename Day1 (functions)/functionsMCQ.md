1. What will be the output of the following code?

function greet(name = "Guest") {
    return `Hello, ${name}`;
}
console.log(greet());

A) Hello, Guest
B) Hello, undefined
C) Hello,
D) Hello, name

Ans. A
-------------------------------------------------------------------
2. Which statement about the return keyword is correct?

A) The return statement can only return primitive values.
B) After a return statement is executed, no further code in the function is executed.
C) A function with a return statement cannot be assigned to a variable.
D) The return statement must be at the end of the function.

Ans. B
----------------------------------------------------------
3. What will be logged when the following code is executed?

function calculateTotal(...prices) {
    return prices;
}
console.log(calculateTotal(10, 20, 30));

A) 10, 20, 30
B) [10, 20, 30]
C) 30
D) undefined

Ans. A
-----------------------------------------------------------------------------------------------
4. ** What will be the output of the following code?

function add(a, b) {
    return a + b;
}
const result = add(3);
console.log(result);

A) NaN
B) 3
C) undefined
D) error

Ans. A 
-----------------------------------------------------------------------------------------

5. Which of the following is the correct way to handle an object as a function parameter?

A) function handleObject(object) {}
B) function handleObject(object = {}) {}
C) function handleObject(anyObject) {}
D) All of the above

Ans. D
--------------------------------------------------------------------------------------------

6. What will be the output of the following code?

function checkName(name) {
    if (name === undefined) {
        return "Please provide a name.";
    }
    return `Hello, ${name}`;
}
console.log(checkName());

A) Hello, undefined
B) Please provide a name.
C) Hello,
D) undefined

Ans. B
---------------------------------------------------------------------------------------------

7. What happens when a function does not return anything?

A) It returns undefined by default.
B) It throws an error.
C) It returns null.
D) It returns an empty string.

Ans. A
------------------------------------------------------------------------------------------------
8. Question 8:
Which of the following is true about default parameters in functions?

A) Default parameters must always be passed explicitly.
B) Default parameters are used only if no argument is provided for the parameter.
C) Default parameters can only be strings.
D) Default parameters are ignored if an argument is passed.

Ans. B
---------------------------------------------------------------------------------------------
9. What will be the value of val2 and num1 in the following function call?

function calculateCart(val1, val2, ...num1) {
    return val1, val2, num1;
}
console.log(calculateCart(200, 400, 500, 2000));

A) val1 = 200, val2 = 400, num1 = [500, 2000]
B) val1 = 200, val2 = 400, num1 = 500
C) val1 = 200, val2 = 500, num1 = 2000
D) val1 = 400, val2 = 500, num1 = [200, 2000]

Ans. A
-------------------------------------------------------------------------------------------
10. What is the result of calling the following function?

function loginUserMessage(username = "sam") {
    if (!username) {
        console.log("Please enter a username.");
        return;
    }
    return `${username} just logged in.`;
}
console.log(loginUserMessage());
console.log(loginUserMessage("Danish"));

A) Please enter a username. and sam just logged in.
B) sam just logged in. and Danish just logged in.
C) Please enter a username. and Please enter a username.
D) Danish just logged in. and sam just logged in.

Ans. B