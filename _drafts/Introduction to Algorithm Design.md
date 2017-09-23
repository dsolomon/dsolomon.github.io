#Introduction to Algorithm Design
notes from Skiena's The Algorithm Design Manual & Lecture Slides

Crafting the correct algorithm is a joyful art!

###Algorithm Correctness
For any algorithm, we must prove that it always returns the
desired output for all legal instances of the problem.
For sorting, this means even if:

(1) the input is already sorted or (2) it contains repeated elements.

###Disproving Algorithm Correctness Quickly
Searching for counterexamples is the best way to disprove the
correctness of a heuristic.
* Think about all small examples.
* Think about examples with ties on your decision criteria
(e.g. pick the nearest point)
* Think about examples with extremes of big and small

###Further Proving Algorithm Correctness
Mathematical induction is a very useful method for proving
the correctness of recursive algorithms.
Recursion and induction are the same basic idea: (1) basis
case, (2) general assumption, (3) general case.

###Reasoning about an Algorithm

Create a careful description of steps to be performed in English then code. An algorithm is an idea - you need to be able to describe it.

1. English
2. Real code.

Create singular goals. 
