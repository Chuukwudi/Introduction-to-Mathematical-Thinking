# Introduction to Mathematical Thinking
## ASSIGNMENT 2 (for Lecture 2)

Question 1
----------

 1. Simplify the following symbolic statements as much as you can, leaving your answer in the standardsymbolic form.  (In case you are not familiar with the notation, I’ll answer the first one for you.)
    1. (π > 0) ∧ (π < 10) &nbsp; [Answer: 0 < π < 10.]
    2. (p ≥ 7) ∧ (p < 12) &nbsp; &nbsp;[Answer: 7 ≤ p < 12.]
    3. (x > 5) ∧ (x < 7) &nbsp; &nbsp; &nbsp;[Answer: 5 < x < 7.]
    4. (x < 4) ∧ (x < 6) &nbsp; &nbsp; &nbsp;[Answer: x < 4.]
    5. (y < 4) ∧ (y² < 9) &nbsp; &nbsp; [Answer: y < 3.]
    6. (x ≥ 0) ∧ (x ≤ 0) &nbsp; &nbsp; &nbsp;[Answer: x = 0 ]
    
Question 2
---------
2. Express each of your simplified statements from question 1 in natural English. \
   1. Pie lies between 0 and 10.
   2. p can be 7 and above but is less than 12.
   3. x is between 5 and 7.
   4. x is less than 4.
   5. y is less than 3. 
   6. x is 0
    
Question 3
---------
3.  What strategy would you adopt to show that the conjunction φ1 ∧ φ2 ∧ ... ∧ φn is true?

    Answer: I will simply check that no conjunct from φ1 to φn is false.

Question 4
---------
4. What strategy would you adopt to show that the conjunction φ1 ∧ φ2 ∧ . . . ∧ φn is false?

    Answer: I will ensure that at least one conjunct is false.

Question 5
---------
5.  Simplify the following symbolic statements as much as you can, leaving your answer in a standard symbolic form (assuming you are familiar with the notation): 
    1. (π > 3) ∨ (π > 10) &nbsp; [Answer: π > 3]
    2. (x < 0) ∨ (x > 0) &nbsp; &nbsp; &nbsp; [Answer: x ≠ 0]
    3. (x = 0) ∨ (x > 0) &nbsp; &nbsp; &nbsp; [Answer: x ≥ 0]
    4. (x > 0) ∨ (x ≥ 0) &nbsp; &nbsp; &nbsp; [Answer: x ≥ 0]
    5. (x > 3) ∨ (x² > 9) &nbsp; &nbsp; &nbsp;[Answer: x > 3]
   
 Question 6
---------
6.  Express each of your simplified statements from question 5 in natural English.
    1. Pie is greater than 3
    2. x is not equal to 0
    3. x is 0 or more
    4. x is zero or more
    5. x is greater than 3.
    
Question 7
---------
7.  What strategy would you adopt to show that the disjunction φ1 ∨ φ2 ∨ ... ∨ φn is true? 
    
    Answer: I will check that at least one of the disjuncts is true.

Question 8
---------
8.  What strategy would you adopt to show that the disjunction φ1 ∨ φ2 ∨ ... ∨ φn is false? 
    
    Answer: I will check that all the disjuncts are false.

Question 9
---------
9.  Simplify the following symbolic statements as much as you can, leaving your answer in a standard symbolic form (assuming you are familiar with the notation):
    1. ¬(π > 3.2) &nbsp; [Answer: π ≤ 3]
    2. ¬(x < 0) &nbsp; &nbsp; &nbsp; [Answer: x ≥ 0]
    3. ¬(x² > 0) &nbsp; &nbsp; &nbsp;[Answer: x = 0]
    4. ¬(x = 1) &nbsp; &nbsp; &nbsp; [Answer: x ≠ 1]
    5. ¬¬ψ &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [Answer: ψ]

Question 10
---------
10.  Express each of your simplified statements from question 9 in natural English. 
     1. Pie can be 3 or less.
     2. x is a positive number
     3. x is 0
     4. x is not 1
     5. ψ

Question 11
---------
11.  Let D be  the  statement  “The  dollar  is  strong”, Y the  statement  “The  Yuan  is  strong”  and T the statement “New US–China trade agreement signed”.  Express the main content of each of the following (fictitious) newspaper headlines in logical notation.  (Note that logical notation captures truth, but not the many nuances and inferences of natural language.)  How would you justify and defend your answers?
        1. Dollar and Yuan both strong [Answer: D ∧ Y]
        2. Yuan weak despite new trade agreement, but Dollar remains strong [Answer: ¬Y ∧ T ∧ D]
        3. Dollar and Yuan can’t both be strong at same time. [Answer: (D ∧ ¬Y) ∨ (¬D ∧ Y)]

        4. New trade agreement does not prevent fall in Dollar and Yuan. [Answer: T ∧ ¬D ∧ ¬Y]
        5. US–China trade agreement fails but both currencies remain strong. [Answer: ¬T ∧ D ∧ Y]


## TWO TO THINK ABOUT AND DISCUSS WITH OTHER STUDENTS
Q: In US law, a trial verdict of “Not guilty” is given when the prosecution fails to prove guilt. This, of course, does not mean the defendant is, as a matter of actual fact, innocent. Is this state of affairs captured accurately when we use “not” in the mathematical sense? (i.e., Do “Not guilty” and “¬guilty” mean the same?) What if we change the question to ask if “Not proven” and “¬ proven” mean the same?

A: I think that 'not' and '¬' have the same meaning but our interpretations for "guilty" and "proven" might make a difference in the meaning, whether we mean them literally(going by the law), or in a technical sense(going by the truth). Ideally, they should mean the same however, in real world, ideality is hypothetical.


Q: The truth table for ¬¬φ is clearly the same as that for φ itself, so the two expressions make identical truth assertions. This is not necessarily true for negation in everyday life. For example, you might find yourself saying “I was not displeased with the movie.” In terms of formal negation, this has the form ¬(¬ pleased), but your statement clearly does not mean that you were pleased with the movie. Indeed, it means something considerably less positive. How would you capture this kind of use of language in the formal framework we have been looking at?

A: Nagation works better with things that have opposites. The opposite of "Pleased" is "Displeased" however there are also different states between such as "In different", etc. To keep things formal we'd probably need to introduce some quantification for our degree pleasure, as, e.g., a number from 1 to 10, a number of stars, etc. 
