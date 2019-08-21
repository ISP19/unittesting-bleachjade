## Unit Testing Assignment

by Bill Gates.


## Test Cases for unique


| Test case              |  Expected Result    |
|------------------------|---------------------|
| empty list             |  empty list         |
| one item               |  list with 1 item   |
| one item many times    |  list with 1 item   |
| 2 items, many times, many orders | 2 item list, items in same order  |
| input not a list  |  raise TypeError       |
| boolean in list  |  return that boolean as normal value


## Test Cases for Fraction


| Test case              |  Expected Result    |
|------------------------|---------------------|
| init method            | initial fraction    |
| str method             | shows fraction in the string form |
| add method             | the sum of two fractions as a new fraction. |
| sub method             | the minus result of two fractions as a new fraction. |
| mul method             | the multiplication of two fractions as a new fraction. |
| eq method              | Two fractions are equal if they have the same value.Fractions are stored in proper form so the internal representation is unique. |
| gcd method             | the Greatest Common Divisor of numerator and denominator. |