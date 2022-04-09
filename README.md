# Trinkerr Backend Interview

## Steps to make a number Special

Given a number, determine the number of steps to reduce the number into 1,  when we repeatedly do the sum of the squares of their digits. Return -1 if it's not possible at all. 

<br>

`Input`
You are given a number

`Sample Input 1`

<pre>
<b>Input</b>: 13

<b>Output</b>: 2

<b>Explanation</b>: 
1*1 + 3*3 = 10
1*1 + 0*0 = 1
</pre>


`Sample Input 2`

<pre>
<b>Input</b>: 2

<b>Output</b>: -1

<b>Explanation</b>: 
You can't acheive 1 after doing these operation.
</pre>


`Sample Input 3`

<pre>
<b>Input</b>: 28

<b>Output</b>: 3

<b>Explanation</b>: 
2*2 + 8*8 = 68
6*6 + 8*8 = 100
1*1 + 0*0 + 0*0 = 1
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
<b>Input</b>: keys = ["idea", "idae", "bsnl", "nsbl", "GRASIM", "bata"]

<b>Output</b>: [["idea", "idae"], ["bsnl", "nsbl"], ["bata"], ["GRASIM"]]
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
