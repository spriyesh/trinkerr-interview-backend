# Trinkerr Backend Interview


## English Assignment

Conan has recently joined an English speaking class. He is a french native and has limited proficiency in English. On the very first day, the teacher gave him an assignment. The task is to get the longest prefix which is common in every word. He came up with a trick to complete the assignment. He converted the alphabets into numbers and then find the longest common prefix. Help him get the prefix.

<br>

`Input`
You are given a list of numbers in <b>string format</b>. 


`Sample Input 1`
<pre>
<b>Input</b>: words_as_numbers = ["11232","121232","11111"]
<b>Output</b>: "1"
</pre>


`Sample Input 2`
<pre>
<b>Input</b>: words_as_numbers = ["11232","1123123213","11232", "112333913", "1123122"]
<b>Output</b>: "1123"
</pre>



---
## Designing File system

You are a computer architect who is designing the file system for your operating system. The basic constraint for designing the file system is handling names in the directory. You cannot allow the same name for two files. Design a program to ensure the unique name of files. If there is already a file with the given name, add a number, i, surrounded by brackets to ensure uniqueness, such that this i is the smallest positive number, and the new name obtained is also unique.


`Input`: 

You are given a sequence of names. Name at i<sup>th</sup> position is served first, and then only you can move on to the next name.



`Sample Input 1`
<pre>
<b>Input</b>: file-names = ["Valorant","GTA5","Fortnite","Valorant(2019)"]
<b>Output</b>: ["Valorant","GTA5","Fortnite","Valorant(2019)"]
<b>Explanation</b>: 
"Valorant" -- not assigned before, remains "Valorant"
"GTA5" -- not assigned before, remains "GTA5"
"Fortnite" -- not assigned before, remains "Fortnite"
"Valorant(2019)" -- not assigned before, remains "Valorant(2019)"
</pre>

`Sample Input 2`
<pre>
<b>Input</b>: file-names = ["Valorant","Valorant(1)","Valorant","Valorant(2019)"]
<b>Output</b>: ["Valorant","Valorant(1)","Valorant(2)","Valorant(2019)"]
<b>Explanation</b>: 
"Valorant" -- not assigned before, remains "Valorant"
"Valorant(1)" -- not assigned before, remains "Valorant(1)"
"Valorant" -- assigned before, so add a (i) suffix, with smallest positive valid i. Valorant(1) is already taken, so Valorant(2)
"Valorant(2019)" -- not assigned before, remains "Valorant(2019)"
</pre>


`Sample Input 3`
<pre>
<b>Input</b>: file-names = ["naruto","naruto(1)","naruto(2)","naruto(3)", "naruto"]
<b>Output</b>: ["naruto","naruto(1)","naruto(2)","naruto(3)", "naruto(4)"]
<b>Explanation</b>: 
"naruto" -- not assigned before, remains "naruto"
"naruto(1)" -- not assigned before, remains "naruto(1)"
"naruto(2)" -- not assigned before, remains "naruto(2)"
"naruto" -- assigned before, so add a (i) suffix, with smallest positive valid i, which happens to be 3. So "naruto(3)"
</pre>


---
