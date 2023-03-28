---
layout: default
title: Workshop
nav_order: 4
has_children: true
has_toc: false
---


# Introduction

## What is a for loop? 
<br/>
For loops allow you to perform an operation ***iteratively*** in R (e.g., instead of repeating lines of code). Most functions you use in R are built using for loops. 
<br/>

---
for (**<span style="color: green">i</span>** in **<span style="color: blue">x</span>**)
{
   
   perform some operation using each value of x

} 

<span style="color: green">i stands for iteration, and is set to each value of x in each iteration of the loop </span>

<span style="color: blue">x could be a vector, list, matrix, or any other sequence of values/objects</span>


---

## What is a conditional statement? 
<br/>
Conditional statements allow you to perform operations based on a logical statement, and can be used alone, or often  more powerfully within a for loop. 

---

if (**<span style="color: green">logical statement</span>**)
{
   
   perform some operation if logical statement is true 

} 

<span style="color: green">This logical statement can be anything with an outcome of true/false.</span> We will go over examples of these in the tutorial. 

