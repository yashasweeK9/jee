---
type : 
subject : 
branch :
chapter :
type : Concept
subject : Mathematics
branch : Algebra
chapter : Permutations and Combinations
date created: Saturday, May 21st 2022, 12:09:08 am
date modified: Saturday, May 21st 2022, 12:10:08 am
title: Problem Solving Methods for Permutations and Combinations
---
[[Permuations and Combinations MOC]]
# 0.0.0.0.0.1 Problem Solving Methods for Permutations and Combinations
## 1 Gap Method
>[!conc] Concept of Gap Method
>![](https://i.imgur.com/oziTQpl.png)


***
## 2 Block Method
>[!conc] Concept of Block Method
>![](https://i.imgur.com/T5YASqL.png)
***
## 3 Dearrangement
Dearrangement of $n$ distinct objects is a kind of arrangement in which no object occupies its original place and this can be done in
>[!ltex] Mathematical Illustration
>![](https://i.imgur.com/1gIhQIB.png)

>[!ques] Question on Dearrangement and selection
>![](https://i.imgur.com/Qg1jLi0.png)

***
## 4 Distribution of identical objects
1. Number of ways of distributing $n$ identical objects among $r$ persons , if any guy can get any number of objects is $^{n+r–1}C_{r–1}$
2. Also, known as Begger’s Method, it is used in finding <mark class="hltr-cyan">non-neagtive integral solutions</mark> of equations.

>[!conc] Concept of Distribution of identical objects
>![](https://i.imgur.com/OeciSeo.png)

>[!ques] Question on Distribution of identical objects
>![](https://i.imgur.com/4In37ku.png)

***

## 5 Distribution of distinct objects

>[!conc] Concept
>![](https://i.imgur.com/4Fl7xHK.png)

>[!ques] Question
>![](https://i.imgur.com/gFwGVOc.png)


***


## 6 Group Formation

### 6.1 Equal division of distinct objects into groups
>[!ques] Question
>![](https://i.imgur.com/BsLHjT0.png)


### 6.2 Unequal division of distinct objects into groups
>[!ques] Question
>![](https://i.imgur.com/w7ACrH8.png)


***
## 7 Circular Arrangements
### 7.1 Arrangements around Table
>[!conc] Concept of Arrangements around Table
>![](https://i.imgur.com/wiMwsjs.png)


>[!ex] An Example on Arrangements around a Table
>![](https://i.imgur.com/4PG4yQ3.png)



### 7.2 Arrangements around a Necklace
>[!conc] Concept
>![](https://i.imgur.com/W0WzsJJ.png)

>[!ex] An Example on Arrangements around a Necklace
>![](https://i.imgur.com/RoX9ssn.png)


***
## 8 Geometrical Results
1. >[!conc] Concept
>![](https://i.imgur.com/inKB1Lo.png)

2. >[!conc] Concept
>![](https://i.imgur.com/6Dxxmh0.png)

3. >[!conc] Concept
>![](https://i.imgur.com/GOVj4Mv.png)


***

## 9 Sum of Divisiors and No. of Divisor
1. For Number of Divisiors
>[!conc] Concept
>![](https://i.imgur.com/I04t94Y.png)


2. For Sum of Divisiors
>[!ltex] Mathematical Illustration
>![](https://i.imgur.com/L5x9Ozw.png)

>[!ques] Question
>![](https://i.imgur.com/O2oHtXj.png)

***
## 10 Exponent of Prime
>[!conc] Concept
>![](https://i.imgur.com/ZV5k8xz.png)


***

## 11 Rank
### No Repetition Case
1. Write the word for which you have to find rank in the dictionary.
2. Label each letter with natural numbers alphabettically.
3. Write down beneath each letter the number of letters that have the index lower than the current letter under which you are writing.
4. Multiply index so obtained from back with a factoial of a whole number starting from 0 backwards.
5. Sum the Products so Obtained
6. Add one to the Sum (Its a Serial Number)
7. Number So Obtained is the rank of that particular word in the dictionary.

>[!conc] Concept of trick
>![](https://i.imgur.com/MaKGQcD.png)


### Repetion Case
1. >[!conc] Concept
>![](https://i.imgur.com/t95Pc2s.png)
>1. In first case A was fixed that’s why its permuations were not divided by $2!$
>2. Also in $2^{nd}$ case A was not taken again as it was already covered in the first case.



2. >[!conc] Concept
>![](https://i.imgur.com/Rrr738H.png)
>1. Write the word for which you have to find rank in the dictionary.
>2. Label each letter with natural numbers alphabettically. (same letters get same numbers irrespective of position in the word)
>3. Write down beneath each letter the number of letters that have the index <mark class="hltr-blue">strictly lower than</mark> i.e. neither equal nor larger the current letter under which you are writing.
>4. Write doen the factorial of whole numbers beneath each index starting from 0 all the way to the start
>5. Now Strating from the 1st Position from front,  normally divide the written factorials by the facotial of repeating pair of elements. (if an element from the reapeating pair has been passed, count its next occurence as disitnct element as its no longer in our scope)
>6. Add one to the Sum (as it is a Serial Number)
>7. Number So Obtained is the rank of that particular word in the dictionary.


***