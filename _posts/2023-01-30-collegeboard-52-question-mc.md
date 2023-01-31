---
keywords: fastai
title: "AP Collegeboard Practice 52 Question Exam Reflection"
toc: true
branch: master
badges: true
comments: true
author: Shreya Ahuja
categories: [fastpages, notes, collegeboard]
nb_path: _notebooks/2023-01-22-collegeboard-52-question-mc.ipynb
layout: notebook
---
## Collegeboard Score: 46/52 (88.4%)

## General Reflection 
My final score was 46/52 which I was pretty happy with, even though it was lower than last time. Although I got a good score, I believe that I need to get better with my timing on these assessments. I have been taking too much time trying to understand the questions and find the correct answer, but I will not have this much time on the AP Exam. I found some of these problems more challenging than the previous tests, which may have been why I got a lower score. I think I need to practice more of these concepts more thoroughly before the AP Exam. 

## AP College Board 52 Question Test Corrections

- Question 7
    - The correct answer choice would be B. The combine method compares corresponding substrings of length 1 from input strings one and two. If the substrings are the same, the substring is appended to res; otherwise, "0" is appended to res. The first and second characters of res are "0" because the characters in position 0 and the characters in position 1 of one and two differ. The third character of res is "1" because the characters in position 2 of one and two are both "1". The fourth character in res is "0" because the characters in position 3 of one and two differ. The fifth character in res is "0" because the last characters of one and two are both "0". Therefore, the value of 00100 is returned rather than the 00101 that I had chosen. 

- Question 19
   - In this question, the for loop assigns values to k from 0 to the last possible position in str at which check could appear, inclusive. In the body of the loop, the String a is assigned a substring of check that starts at position k and has the same length as check. If the substring a and check are the same, num is assigned k. When the for loop ends, num has the last value of k at which a match between the substring a and check was found or the index of the last occurrence of check in str. This would mean that the correct answer is C instead of B.



- Question 31
   - My answer was incorrect because code segment uses k, an element of the two-dimensional array, as an index in a one-dimensional array. The correct answer would have been D because it correctly shows that the outer for loop stores each row of the two-dimensional array in j, a one-dimensional array. The inner for loop stores each element of j in k and prints k.


- Question 33
    - The answer to the question is A, but I chose B. A is the correct answer because the outer for loop iterates over every row of numbers and assigns each row to the array row.  The inner loop iterates over the array row accessing each element and assigning it to n. Then n is printed to the screen. In the first iteration of the outer loop, row is equal to {1, 2, 3}, and the inner loop will assign each successive value in row to n and print it to the screen, meaning 123 will be printed. For the second iteration of the outer loop, row is equal to {4, 5, 6}, and the inner loop will assign each successive value in row to n and print it to the screen, meaning 456 will be printed after 123, giving us the output 123456. In the other one, there is no element at Row 3, so it would not work. 

- Question 42
    - The code segment that I chose was wrong. After executing the values mystery (values), the list should have the values of [0,4,2,5,3]. But, the answer I chose said that it would include [4,2,5,3] which is not correct.I missed something in the code, but understand why the answer should be D now.

- Question 44
    - The method assigns the shortest string that occurs in any element of arr between arr[n] and arr[arr.length - 1], inclusive, to result[n]. The shortest string found between arr[0] and arr[3] is "of", so result[0] is assigned the value "of". The shortest string found between arr[1] and arr[3] is also "of", so result[1] is also assigned the value "of". The same is true for the part of the array that begins at index 2 and ends at index 3, so result[2] is also assigned the value "of". In the last iteration of the outer for loop, there are no values to consider after arr[3], so result[3] is assigned the value "spring". This would mean the answer should be D, but I chose C which would be wrong.


