# Trinkerr Backend Interview

## Party with girlfriend

You are invited to a party at one of the best hotels in the city. But it's a couple entry, so you are not allowed to go alone. So you asked your girlfriend for this party. She agreed to join you but has a condition. She wants both the couple should dress up in the same colour.

You are given an array of colours, and you have to pick up the dress colours such that both you and your girlfriend should have the **same colour** and at the same time, ensure that your girlfriend's dress is selected after yours, i.e **index <sub>your dress</sub> < index <sub> your girlfriend's dress</sub>**

You are a geek, so you decided to count the number of ways to do that. Return the number of ways possible, **Optimally**. 


<br>

`Input`
You are given an array of colours. 

`Sample Input 1`

<pre>
<b>Input</b>: [1,2,3,1,2]

<b>Output</b>: 2

<b>Explanation</b>: 
You can select the colours at index (0, 3) or (1, 4).
</pre>


`Sample Input 2`

<pre>
<b>Input</b>: [1,2,3]

<b>Output</b>: 0

<b>Explanation</b>: 
No pair possible. 
</pre>


`Sample Input 3`

<pre>
<b>Input</b>: [1, 2, 1, 2, 1]

<b>Output</b>: 4

<b>Explanation</b>: 
You can select the colours at index (0, 2) , (0, 4), (2, 4) and (1, 3).
</pre>


---

## Intern

You've recently joined a company as an intern and you were playing around with the database of the company to get some stats asked by your manager. But due to a minor mistake in your script code, the keys of the database table got jumbled, and duplicates were also created for those keys. Now you have to clean this mess before anyone knows.

Now, your task is to group all the (<b>the anagrams</b>) keys.

<p>
<blockquote>
An Anagram is a word or phrase that is made by arranging the letters of another word or phrase in a different order.
</blockquote>
</p>

`Input`:
You are given a sequence of names key names.


`Output`:
You need to return an array of array grouping the anagram keys.


`Sample Input 1`

<pre>
<b>Input</b>: keys = ["idea", "idae", "bsnl", "nsbl", "grasim", "bata"]

<b>Output</b>: [["idea", "idae"], ["bsnl", "nsbl"], ["bata"], ["grasim"]]
</pre>

`Sample Input 2`

<pre>
<b>Input</b>: keys = ["data", "data"]

<b>Output</b>: [ ["data", "data"] ]
</pre>



NOTE: 
1. All the letters are in lowercase. 
2. Keys don't have a spaces in between them. So something like: 
	"GM Birla" stock is not possible
---
