---
keywords: fastai
title: "AP Collegeboard Practice 66Q Exam Reflection"
toc: true
branch: master
badges: true
comments: true
author: Shreya Ahuja
categories: [fastpages, notes, collegeboard]
nb_path: _notebooks/2023-01-22-multiple-choice-blog.ipynb
layout: notebook
---
## Collegeboard Score: 60/66 (91%)

## General Reflection 
My final score was 60/66 which I was pretty happy with. This would be in range for the 5 on the AP Exam, but I do need to get better with my timing. For the actual AP Exam, I will need to answer questions at a must faster pace, which might my score lower if I do not practice with a time restriction. I thought that this test helped me in better understanding DeMorgans Laws, as there were many questions on that. I found these types of problems and some other ones challenging as I had to look at each answer option to make sure I was choosing the correct one, but I think I will get faster with more practice. Overall, this exam helped me get exposed to many types of problems, but I could work on my pacing and making sure to look at the question carefully. 

## AP College Board 66 MC Test Corrections

- Question 19
    - In the answer choice that I chose, the expressions are not equivalent when a has the value 4, b has the value 3, c has the value 2, and d has the value 1. After looking at the problem more carefully, I realized that c < d for the code segment to work. If c is greater than or equal to then this statement wouldn't be equivalent to the one given. Therefore, my answer would be wrong and A would be correct.


- Question 35
   - My answer was incorrect because the original code segment prints 10. The option that I chose causes the code segment to result in 11. The loop executes the same number of times as in the original code segment, but the initial value of count is 1. This would mean that D.



- Question 43
   - When I was doing the test, I thought that both implementations worked as intended, but the only different could be that  the first one would allow the result to come faster. However, once I looked at the problem again I realized that the implementation doesn’t work because it would cause an out of bounds exception (sum[j-1] in the first iteration would be sum[-1] which is not right. This would then mean that in order for the code segment to work, D would be the correct answer.



- Question 58
   - My answer was incorrect because pos should be equal j because each iteration you don't want the index to be reset back to 0. In other words, it would not make sense for the position to be reset to the 0th index every time the sorting method takes place. I did not think about this when I was first taking the test, but with this knowledge, the correct answer would be B. 


- Question 64
    - In Code Segments 1, the code does not print the array elements in order from left to right using an enhanced for loop. Code segment I uses elements as indices. The first element of arr is 1, and arr[1] is 2; the second element is 2, and arr[2] is 4; the third element is 4, and arr[4] is 3; etc. Option 3 is the only one that allows the given code segment to print the array elements in order from left to right using an enhanced for loop



