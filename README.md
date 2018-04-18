![.:.Hex To Decimal..:.](.png)

## CodeWars Challenge- 21


*Description:*
Complete the function which converts hex number (given as a string) to a decimal number.

*Test Case:*


1. hexToDec("1"), 1);
2. hexToDec("a"), 10);
3. ("10"), 16);
4. ("FF"), 255);
5. ("-C"), -12);


## Solved Using:

1. JavaScript

## My Solution:

By using the parseInt method on the string argument being passed in with a specific radix of 16 I can return the hexadecimal number for each string.
