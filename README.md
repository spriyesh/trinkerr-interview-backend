# Trinkerr Backend Interview

## Watering plants

Chunnu has recently joined as a gardener. On the very first day of his job, he was given the task to configure the range of sprinklers. To ensure that all the plants get sufficient water, all the plants should be within the range of the sprinkler's radius. 

He is completely unaware of how to solve this problem, so he calls you to help him. Help him in finding the minimum radius of the sprinklers so that all the plants are getting sufficient water. 

You are given the coordinates of both, plants and sprinklers which are installed on a straight line, in the form of 2 arrays. 



`Constraints`: 

1 <= `plants.length, sprinklers.length` <=  10 <sup>5</sup> 

1 <= ```plants[i], sprinklers[i]``` <= 10 <sup>9</sup> 



`Sample Input 1`
<pre>
<b>Input</b>: plants = [1,2,3], sprinklers = [2]
<b>Output</b>: 1
<b>Explanation</b>: The only sprinklers was placed in the position 2, and if we use the radius 1 standard, then all the plants can be warmed.
</pre>


`Sample Input 2`

<pre>
<b>Input</b>: plants = [1,2,3,4], sprinklers = [1,4]
<b>Output</b>: 1
<b>Explanation</b>: The two sprinklers was placed in the position 1 and 4. We need to use radius 1 standard, then all the plants can be warmed.
</pre>


`Sample Input 3`
<pre>

<b>Input</b>: 

plants = [282475249,622650073,984943658,144108930,470211272,101027544,457850878,458777923],

sprinklers = [823564440,115438165,784484492,74243042,114807987,137522503,441282327,16531729,823378840,143542612]

<b>Output</b>: 161834419
</pre>

---

## Sorting the Characters

Suppose you are given a string with 2 characters only. `a` and `c`. Your task is to output the result such that all the a's are on left side and all the c's are on the right side.

`Sample Input 1`
```text
Input:

const str = "accacaca";

Output: 

aaaacccc
```

`Note`: You will be given the string with a's and c's only and all of them will be in lower case characters. But you need to make sure that you need to do the task as efficiently as possible. You are not allowed to use sorting as sorting will take `O(nlogn)` time,  where `n` corresponds to the length of the string. 
