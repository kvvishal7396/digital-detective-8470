## TASK:
* Understanding how to convert numbers between decimal,binary and hexadecimals.

## 5.1 Converting numbers by hand-

**Convert decimal 13 to binary**

13 ÷ 2 = 6(remainder 1)

6 ÷ 2 = 3(remainder 0)

3 ÷ 2 = 1(remainder 1)

1 ÷ 2 = 0(remainder 1)

**Therefore,The binary representation of 13 is,** 1101

**Convert decimal 25 to binary**

25 ÷ 2 = 12(remainder 1)

12 ÷ 2 = 6(remainder 0)

6 ÷ 2 = 3(remainder 0)

3 ÷ 2 = 1(remainder 1)

1 ÷ 2 = 0(remainder 1)

**Therefore,The binary representation of 25 is,** 11001

**Convert binary 1010 to decimal**

(1 * 8) + (0 * 4) + (1 * 2) + (0 * 1)

=> 8 + 2 = 10

**Therefore,The decimal representation of 1010 is,** 10

**Convert binary 1101 to decimal**

(1 * 8) + (1 * 4) + (0 * 2) + (1 * 1)

=> 8 + 4 + 1 = 13

**Therefore,The decimal representation of 1101 is,** 13

**Convert hexadecimal A to decimal**
* We,know that hexadecimal 'A' is directly equal to 10 in decimal.
**Therefore,The decimal representation of A is,** 10

**Convert hexadecimal 1F to decimal**
(1 * 16) + (F)
* We, know that F in hexadecimal is equal to 15 in decimal
=> 16 + 15 = 31
**Therefore,The decimal representation of 1F is,** 31

**Convert binary 1111 to hexadecimal**
* Binary --> decimal
1111 = (1 * 8) + (1 * 4) + (1 * 2) + (1 * 1) = 15
Decimal --> Hexadecimal
* we,know that 15 in decimal is represented as F in Hexadecimal
**Therefore,The Hexadecimal representation of 1111 is,** A

## 5.2 and 5.3 testing my converter to convert numbers
* i ran my number_converter.py i used 3 test numbers and it gave the follwing results:

|Test number|binary output|hexadecimal output|
| :--- | :--- | :--- |
|13|1101|d|
|25|11001|19|
|31|11111|1f|

## 5.4 Hows text stored?

**ASCII Values**
* The ASCII value for 'A' is 65 and the ASCII value for 'a' is 97.

**Why does computer need encoding to store text**
* Computers only understand numbers (0s and 1s). We need an encoding standard to map specific numbers to specific visual characters so that every computer loads and displays the exact same text characters.

**NON-ASCII Symbol**
* The indian rupee(₹) symbol is a NON-ASCII Symbol.

## commands used-
* python3 - to run my file number_converter.py

* bin() and hex() - conver4ting decimal to binary and hexadecimal numbers.

## Understandings,difficulties faced:
* I understood how to convert numbers between binary,decimal,hexadecimals and learned to run a python file using simple commands.
* I didn't have any difficulties.


##  Evidence / files
* `number_converter.py`
* `mission-05-numbers-data/README.md`

##  Commit details
* **Commit Message:** "Build number converter and practise data representation"



