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
 ## Unique number conversion 

 You are given 2 numbers `A` and `B`. You can perform two sets of operations, with the first operation, `O1`, you can `subtract 1 from the current number`. With the second operation, `O2`, you can `multiply the number by 2`. Given A, your task is to derive number B using these 2 sets of operations. Determine the minimum number of steps to convert A to B using these sets of operations.


`Constraints`: 

The first and the only line of the input contains two distinct integers `n and m` (`1 ≤ n, m ≤ 10`<sup>`4`</sup>)


<b>`Sample Input 1`</b>
<pre>

<b>Input</b>: 

A = 4, B = 6

<b>Output</b>: 2
<b>Explanation</b>: Use operation O<sub>1</sub> followed by operation O<sub>2</sub>.

After O<sub>1</sub> we have 3. (Subtracting by one)
After O<sub>2</sub> we have 6. (Multiplying by two)

</pre>


<b>`Sample Input 2`</b>
<pre>

<b>Input</b>: 

A = 10, B = 1

<b>Output</b>: 1
</pre>



