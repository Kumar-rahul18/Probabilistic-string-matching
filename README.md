# Probabilistic-string-matching

Problem Summary:
We have 
𝑛
n point objects in a one-dimensional, gravity-free universe. Each object has:

A mass 
𝑚
𝑖
m 
i
​
 
An initial position 
𝑥
𝑖
x 
i
​
 
An initial velocity 
𝑣
𝑖
v 
i
​
 
The objects are numbered from left to right, so 
𝑥
0
<
𝑥
1
<
…
<
𝑥
𝑛
−
1
x 
0
​
 <x 
1
​
 <…<x 
n−1
​
 .

Key Points:
Elastic Collisions: When two objects collide, the collision is elastic, meaning both momentum and kinetic energy are conserved.

Collision Representation: A collision between objects 
𝑖
i and 
𝑖
+
1
i+1 is represented as a tuple 
(
𝑡
,
𝑖
,
𝑥
)
(t,i,x), where:

𝑡
t is the time of the collision.
𝑖
i is the index of the left object in the collision.
𝑥
x is the position at which the collision occurs.
Order of Collisions: Collisions need to be listed in chronological order. If multiple collisions happen at the same time, they are ordered from left to right (i.e., smaller index first).
