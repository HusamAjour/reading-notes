[Back to Home](README.md)

# Read 08

## Decisions & Loops

### Comparison Operators:

Comparison operators are used in conditional statements. They are used to determine wehter the condition is true or false and that decides which block of code to execute next. The table below shows a set of comparison operators and the difference between them and how to use each one of them.

|Operator Sign| Operator Name | What it does | Example |
|---|---|---|---|
| `==` | is equal to| compares two valuesto see if they are the same | `'hello == 'hello'` returns true |
| `!=`| is not equal to | compares two values to see if they're not the same | `'hello !== 'hello'` returns false |
| `===` | strict equal to | compares twp values to check that both data type and value are the same | `'3' === 3` returns false |
| `!==` | strict not equal otl | compares twp values to check that both data type and value are not the same | `'3' === 3` returns true |
| `>` | greater than | compares if the number on the left is greater than the number on the right | `4 > 3` returns true |
| `<` | less than | compares if the number on the left is less than the number on the right | `6 < 10` returns false |
| `>=` | greater than or equal to | compares if the number on the left is greater than or equal to the number on the right | `4 >= 4` returns true |
| `<=` | less than or equal to | compares if the number on the left is less than or equal the number on the right | `5 <= 3` returns false |

### Logical Operators

Logical operaors are used when the need is to compare the results of more than one comparison operator.

|Logical operator | Name | Use|
|---|---|---|
| `&&` | Logial AND | tests more than one condition |
| `!` | Logial NOT | inverts a single boolean value |
| `\|\|` | Logical OR | tests at least one condition |

### Loops

Loops are used when the need is to repeat the execution of block of code couple of times based on a condition. There are 3 types of loops: `For Loop`, `While Loop`, and `Do While Loop`.

For Loop is used when you need to repeat of a piece of code a specific number of times.

Example:

```
for (var i = 0; i <10; i++){
    document.write(i);
}
```

While Loop is used when you don't know the how many times the code should run.

Example:

```
while(i<10){
  document.write(i);
  i++;
}
```

Do While Loop is very similar to the While Loop but has only one difference which is that the code will run at least once.

Example:

```
do{
  document.write(i);
  i++;
}
while(i<10);
```

[Back to Home](README.md)
