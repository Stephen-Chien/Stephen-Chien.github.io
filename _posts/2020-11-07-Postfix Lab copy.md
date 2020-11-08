---
layout: post
title: PostFix Calculator Lab
subtitle: Second Lab!
tags: [ArtofData]
comments: true
---


## Calculations

The calculations for this lab are, in the order they were in: [6,40,-162,-692,2,-19,93,95,-11,49000,38,84,-100,115,3,142,791,82,-192,-4,143,3060,137,384,11,48,805,11,-2700,190,-96,1715,60,48,-25,-4,-135,-77,663,40,10,-81,-15,-311,1095,1076,1260,-204,91,416,-26,34,-19,-343,11,-110,192,-63,-2,9,13,-33,-223,152,75,54,517,2110,412,10,-571,3432,23,-48,1764,7,240,-2,-936,9,1,5,414,386,128,-115,1,-18,0,-16186,1391,29,233,38,63,1560,591,-36,917,-25]. The number that I got that was the average was **529.91**. 

## Stack in Postfix Notation

The way I visualized the stack in PostFix Notation was:

1. Look at each character in the row
2. If the character is an integer, append it to the stack
3. Assign two of the numbers that are popped
4. If there is an operator, take those two numbers and do the operation, and append it to the stack
5. Return the top element from the stack


## How I did the lab

First, I tried to create the evaluate function. I used Google Docs to try and write down everything that came to mind, even if it was wrong. ![Google Docs File](/assets/img/thoughtprocess.png). This was pretty much my basis for the lab, and it worked out fine. I was able to create my evaluate function nicely, but a major error was that I had a List disguised as a Stack. The error that I got was that I couldn't convert from a Stack to a string, so instead of using Stack, I used a List. I could have done better by using an actual Stack class. What I learned from this lab was using a Stack class in order to apply it to Postfix Expressions. 
    
