# Expressions and operators

## Assignment operators

- An assignment operator gives a value to its left operand based on the value of its right operand. 
- The simple assignment operator is equal (=). Gives a the value of the right operand to the left operand. ex. x = r()
- Nesting assignments in other expressions can result in surprising behavior. chaining assignments in the same statement is discouraged.

## Comparison operators

- A comparison operator compares its operands and returns a logical value based on whether the comparison is true. 
- ex: var var1 = 3;
      var var2 = 4;

- If the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison.

## examples of comparison operators
- equal: ==
- not equal: !=
- strict equal: ===
- strict not equal: !== 
- greater than: >
- greater than or equal to: >=
- less than <
- less than or equal to <=

# Loops and iteration

## for statement

- A for loop repeats until a specified condition evaluates to false.
- ex: for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
  - initialExpression: is executed
  - conditionExpression: expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates.
  - The statement executes. 
  - Expression incrementExpression is executed.

  ## while statement

  - A while statement executes its statements as long as a specified condition evaluates to true. 
  - ex: let n = 0;
        let x = 0;
        while (n < 3) {
        n++;
        x += n;
        }
- After the first pass: n = 1 and x = 1
- After the second pass: n = 2 and x = 3
- After the third pass: n = 3 and x = 6
- After completing the third pass, the condition n < 3 is no longer true, so the loop terminates.