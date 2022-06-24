---
layout: default
nav_order: 1
parent: HashMap
---

# API
## Class Name: HashMap

## Fields

| Name          | Data Type         | Description                         |
|:--------------|:------------------|-------------------------------------|
| arr1          | Array of Integers | Stores keys                         |
| arr2          | Array of Integers | Stores values                       |
| current       | Integer           | Location of top value               |
| length        | Integer           | Length/Size of HashMap              |


## Methods

| Name          | Parameters                     | Return Type      | Description                                               |
|:--------------|:-------------------------------|------------------|-----------------------------------------------------------|
| constructor   | None                           | Object (HashMap) | Creates an instance of class                              |
| put           | Key (Integer), Value (Integer) | Void             | Stores key & its value to map                             |
| get           | Key (Integer)                  | Integer          | Gets corresponding value for key from map                 |
| size          | None                           | Integer          | Returns the size of map                                   |
| isEmpty       | None                           | Boolean          | Checks whether map is empty or not                        |
| isFull        | None                           | Boolean          | Checks whether map is full or not                         |
| clear         | None                           | Void             | Clears the map                                            |
| containsKey   | Key (Integer)                  | Boolean          | Checks whether map contains corresponding key or not      |
| containsValue | Value (Integer)                | Boolean          | Checks whether map contains corresponding value or not    |
| removeKey     | Key (Integer)                  | Boolean          | Removes key & its corresponding value from map if present |
| removeValue   | Value (Integer)                | Boolean          | Removes value & its corresponding key from map if present |
