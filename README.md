# 5_decision_making_statements
# Aim:
To write C++ programs using if-else and nested if statements. To use switch case for multiple conditions.

# Objectives:
Learn how to use if-else and nested if in real-life problems. Understand how switch case works and how to use break and exit(0).

# Theory:
If-Else Statement
The if-else statement is used when we want to do know and decide if a condition is true or false.
##### Syntax
```cpp
if (condition) {
    // Code runs if condition is true
}
else {
    // Code runs if condition is false
}
```
# Nested If Statement
When an if is written inside another if, it is called a nested if. Used when there are multiple conditions to check.

Syntax
```cpp
if (condition1) {
    // Code if condition1 is true

    if (condition2) {
        // Code if condition2 is also true
    }
    else {
        // Code if condition2 is false
    }
}
else {
    // Code if condition1 is false
}
 ```
# Switch Case Statement
Used when we have to choose between many options based on one input variable. Helps reduce multiple if-else if lines. Use break to stop the program from checking more cases and overrwritting it. If no case matches, it runs the default statement.

##### Syntax
```cpp
switch (expression) {
    case value1:
        // Code block 
        break;

    case value2:
        // Code block
        break;

    // You can add as many cases as you want.
    default:
        // Code if no case matches
}
```


