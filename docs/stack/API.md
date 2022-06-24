---
layout: default
nav_order: 1
parent: Stack
---

# API
## Fields

| Name          | Data Type          | Description                                         |
|:--------------|:-------------------|-----------------------------------------------------|
| arr           | ArraysString class | Stores corresponding values of stack                |
| top           | Integer            | Returns the position of value last pushed to stack  |

## Methods

| Name          | Parameters                       | Return Type      | Description                                               |
|:--------------|:---------------------------------|------------------|-----------------------------------------------------------|
| constructor   | size (Integer)                   | Object (Stack)   | Creates an instance of class Stack                        |
| push          | value (Integer)                  | Void             | Pushes a value to the corresponding stack                 |
| pop           | None                             | Integer          | Pops a value from the corresponding stack                 |
| isEmpty       | None                             | Boolean          | Checks whether the stack is empty or not                  |
| size          | None                             | Integer          | Returns size of corresponding stack                       |
| peek          | None                             | Integer          | Returns value at top of stack                             |
| isFull        | None                             | Boolean          | Checks whether the stack is full or not                   |
