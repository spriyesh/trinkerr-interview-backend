# Trinkerr Backend Interview

## Newbie Programmer

You have recently joined the college where you were introduced to programming in general. In one of your Strings classes, you learned that string addition is also possible in programming.

You tried to do similar addition in numbers (concatenation) and noticed that new numbers formed can be really big. You got interested in the task and decided to calculate the sum of all those numbers formed by the transformations. Return the sum **Optimally!!**. 

String addition of two strings is :  `"a" + "b" = "ab"`.

**Note:** `a + b` and `b + a`  are treated differently in the transformation. **Transformation is concatenation of 2 values**.

<br>

`Constraints:`
length of the array <= 10<sup>5</sup>

`Input`
You are given an array of numbers. 

`Sample Input 1`

<pre>
<b>Input</b>: [10, 11]

<b>Output</b>: 4242

<b>Explanation</b>: 
T<sub>1</sub>: 10 + 10 = 1010 (Index 0, Index 0)
T<sub>2</sub>: 11 + 10 = 1110 (Index 1, Index 0)
T<sub>3</sub>: 10 + 11 = 1011 (Index 0, Index 1)
T<sub>4</sub>: 11 + 11 = 1111 (Index 1, Index 1)
</pre>


`Sample Input 2`

<pre>
<b>Input</b>: nums = [8, 10, 12]

<b>Output</b>: 6390

<b>Explanation</b>: 
Numbers formed are: 88, 810, 812, 108, 1010, 1012, 128, 1210, 1212
</pre>



---

## Mirror Image


Given a string, determine its mirror image. 
A mirror image of a string is a string in which all the alphabets are reversed. All other characters are untouched. 


`Input`:
You are given a string.


`Output`:
Return the mirror image of the string

`Sample Input 1`

<pre>
<b>Input</b>: "ab-cd"

<b>Output</b>: "dc-ba"
</pre>

`Sample Input 2`

<pre>
<b>Input</b>: "a-bC-dEf-ghIj"

<b>Output</b>: "j-Ih-gfE-dCba"
</pre>



NOTE: 
1. input consists of characters with ASCII values in the range [33, 122].
2. input does not contain `'\"' or '\\'`.

---
