# Trinkerr Backend Interview

## Stranger's Call

You are stuck in the maze and have no idea of how to get outside it. You received an anonymous call from someone, offering to help you. You don't know that person but you agreed to accept his help since you were desperate to get out of the maze. 

The person gave you a set of directions to follow, to get you out of the maze. Let **"N"** denote **north** side movement, **"E"** denote **eastward** movement, **"W"** denote **west** and **"S"** denote movement in the **south**. Distance travelled will be the same in each direction, i.e 1m. 

But deep down, you still don't trust the person, that's why you decided to verify his instructions. You decided to calculate where you'll reach after following the instructions. **Determine whether you will remain in the same position after following the instructions or not.**


<br>

`Constraints:`
Length of the string is <= 10<sup>5</sup>

`Input`
Given a string, containing only "N", "S", "W", and "E" characters.

`Sample Input 1`

<pre>
<b>Input</b>: "NWE"

<b>Output</b>: false

<b>Explanation</b>: 
After following the instructions, you won't be at the same place
</pre>


`Sample Input 2`

<pre>
<b>Input</b>: "NWSE"

<b>Output</b>: true

<b>Explanation</b>: 
You will end up in the same position as in the beginning
</pre>



---

## Deadliest Weapons 


You are the supreme commander of the army, and you must ensure that the weapons you have in your artillery are deadly. Each weapon has a rating denoting how leathal the weapon is when used alone called the **deadly score**. You have a bunch of weapons and it's your duty to use the weapons in such sync that their deadly score is at their best. Determine the **highest deadly score of the weapons possible**.

The deadly score of two weapons is calculated by appending the deadly score of individual weapons. Eg. let's say weapon A has a deadly score of 23 and Weapon B has a deadly score of 46. So the possible deadly scores of A and B can be 2346 or 4623.


`Input`:
You are given an array of numbers denoting the deadly score of individual weapon.


`Output`:
Return the maximum deadly score possible (In string) since this number can be huge.

`Sample Input 1`

<pre>
<b>Input</b>: [9, 2, 4]

<b>Output</b>: "942"
</pre>

`Sample Input 2`

<pre>
<b>Input</b>: [3,30,9]

<b>Output</b>: "9330"
</pre>


---
