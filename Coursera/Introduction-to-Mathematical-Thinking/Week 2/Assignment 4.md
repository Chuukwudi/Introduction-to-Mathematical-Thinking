# Introduction to Mathematical Thinking
## ASSIGNMENT 4 (for Lecture 4)

Question 1
----------
 Build a truth table to prove the claim I made earlier that 𝜙 ⇔ 𝜓 is true if 𝜙 and 𝜓 are both true or both false, and 𝜙 ⇔ 𝜓 is false if exactly one of 𝜙, 𝜓 is true and the other false. (To constitute a  proof,  your  table  should  have  columns  that  show  how  the  entries  for 𝜙 ⇔ 𝜓 are  derived,  one operator at a time.)


<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>𝜙 ⇒ 𝜓</th><th>𝜓 ⇒ 𝜙</th><th>(𝜙 ⇔ 𝜓) = (𝜙 ⇒ 𝜓) ∧ (𝜓 ⇒ 𝜙)</th></tr><tr><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td></tr><tr><td>F</td><td>T</td><td>T</td><td>F</td><td>F</td></tr><tr><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td></tr></tbody></table> </p>
</details>

Question 2
-----------
Build a truth table to show that\
(𝜙 ⇒ 𝜓) ⇔ (¬𝜙 v 𝜓)\
is true for all truth values of 𝜙 and 𝜓. A statement whose truth values are all T is called a logical validity, or sometimes a tautology.

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>¬𝜙</th><th>𝜙 ⇒ 𝜓</th><th>¬𝜙 v 𝜓</th><th>(𝜙 ⇒ 𝜓) ⇒ (¬𝜙 v 𝜓)</th><th>(¬𝜙 v 𝜓) ⇒ (𝜙 ⇒ 𝜓)</th><th>(𝜙 ⇒ 𝜓) ⇒ (¬𝜙 v 𝜓) ∧ (¬𝜙 v 𝜓) ⇒ (𝜙 ⇒ 𝜓)</th></tr><tr><td>T</td><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr></tbody></table> </p>
</details>

Question 3
----------
 Build a truth table to show that\
 (𝜙 ⇏ 𝜓) ⇔ (𝜙 ∧ ¬𝜓)\
 is a tautology.

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>¬𝜓</th><th>𝜙 ⇏ 𝜓</th><th>𝜙 ∧ ¬𝜓</th><th>(𝜙 ⇏ 𝜓) ⇒ (𝜙 ∧ ¬𝜓)</th><th>(𝜙 ∧ ¬𝜓) ⇒ (𝜙 ⇏ 𝜓)</th><th>(𝜙 ⇏ 𝜓) ⇒ (𝜙 ∧ ¬𝜓) ∧ (𝜙 ∧ ¬𝜓) ⇒ (𝜙 ⇏ 𝜓)</th></tr><tr><td>T</td><td>T</td><td>F</td><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>T</td><td>F</td><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>T</td><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td></tr></tbody></table> </p>
</details>


Question 4
----------

The  ancient  Greeks  formulated  a  basic  rule  of  reasoning  for proving  mathematical  statements. Called _modus ponens_, it says that if you know 𝜙 and you know 𝜙 ⇒ 𝜓, then you can conclude 𝜓.\
(a)  Construct a truth table for the logical statement [ 𝜙 ∧ (𝜙 ⇒ ψ)] ⇒ 𝜓


<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>𝜙 ⇒ 𝜓</th><th>𝜙 ∧ (𝜙 ⇒ 𝜓)</th><th>𝜙 ∧ (𝜙 ⇒ 𝜓) ⇒ 𝜓</th></tr><tr><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>F</td><td>T</td></tr><tr><td>F</td><td>T</td><td>T</td><td>F</td><td>T</td></tr><tr><td>F</td><td>F</td><td>T</td><td>F</td><td>T</td></tr></tbody></table> </p>
</details>

(b)  Explain  how  the  truth  table  you  obtain  demonstrates  that modus  ponens is  a  valid  rule  of inference.

<details>
    <summary> Answer </summary>
        <p> Here, I see that if the antecedent is known, and we also know that the antecedent implies the consequent. It is possible to deduce the consequent (Tautology).</p>
</details>


Question 5
----------
[This question has a long set-up. The question itself is the very last sentence. TAKE YOUR TIME.]\
One way to prove that ¬(𝜙 ∧ 𝜓) and (¬𝜙) ∨ (¬𝜓) are equivalent is to show they have the same truth table:

<table><tbody><tr><th>𝜙</th><th>𝜓</th><th>𝜙 ∧ 𝜓</th><th>¬(𝜙 ∧ 𝜓)*</th><th>¬𝜙</th><th>¬𝜓</th><th>(¬𝜙) ∨ (¬𝜓)*</th></tr><tr><td>T</td><td>T</td><td>T</td><td>F</td><td>F</td><td>F</td><td>F</td></tr><tr><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td></tr><tr><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td><td>F</td><td>T</td></tr><tr><td>F</td><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td></tr></tbody></table>

Since the two columns marked * are identical, we know that the two expressions are equivalent. Thus, negation has the affect that it changes ∨ into ∧ and changes ∧ into ∨. An alternative approach way to prove this is to argue directly with the meaning of the first statement:
1. 𝜙 ∧ 𝜓 means both φ and ψ are true.
2. Thus ¬(𝜙 ∧ 𝜓) means it is not the case that both 𝜙 and 𝜓 are true.
3.  If they are not both true, then at least one of 𝜙, 𝜓 must be false.
4. This is clearly the same as saying that at least one of ¬𝜙 and ¬𝜓 is true. (By the definition of negation).
5. By the meaning of _or_, this can be expressed as (¬𝜙) ∨ (¬𝜓). 
   
Provide an analogous logical argument to show that ¬(𝜙 ∨ 𝜓) and  (¬𝜙) ∧ (¬𝜓) are equivalent.


<details>
    <summary> Answer </summary>
        <p> 1. (𝜙 ∨ 𝜓) means all else is true except when 𝜙 and 𝜓 are both false. </p>
        <p>2. ¬(𝜙 ∨ 𝜓) means all else is False except when 𝜙 and 𝜓 are both False. </p>
        <p>3. This is that False and False should be True and everything else False. So (¬𝜙) ∧ (¬𝜓) is correct. </p>
</details>


Question 6
----------

By a _denial_ of a statement φ we mean any statement equivalent to ¬φ. Give a useful (and hence natural sounding) denial of each of the following statements.\

(a)  34,159 is a prime number.

<details>
    <summary> Answer </summary>
        <p> 34,159 is not a prime number. </p>
</details>

(b)  Roses are red or violets are blue.

<details>
    <summary> Answer </summary>
        <p> Roses are not red or violets are  not blue. </p>
</details>

(c)  If there are no hamburgers, I’ll have a hot dog.

<details>
    <summary> Answer </summary>
        <p> There are no hamburgers but I’ll not have a hot dog. </p>
</details>

(d)  Fred will go but he will not play.

<details>
    <summary> Answer </summary>
        <p> Fred will not go or he will play. </p>
</details>

(e)  The number _x_ is either negative or greater than 10.

<details>
    <summary> Answer </summary>
        <p> The number _x_ is neither negative nor greater than 10. </p>
</details>

(f)  We will win the first game or the second.

<details>
    <summary> Answer </summary>
        <p> We will not win the first game and the second. </p>
</details>


Question 7
----------

Show that φ ⇔ ψ is equivalent to (¬φ) ⇔ (¬ψ).

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>¬𝜙</th><th>𝜓</th><th>¬𝜓</th><th>𝜙 ⇒ 𝜓</th><th>𝜓 ⇒ 𝜙</th><th>¬𝜙 ⇒ ¬𝜓</th><th>¬𝜓 ⇒ ¬𝜙</th><th>(¬𝜙)⇔(¬𝜓) = (¬𝜙 ⇒ ¬𝜓) ∧ (¬𝜓 ⇒ ¬𝜙)</th><th>𝜙⇔𝜓 = (𝜙 ⇒ 𝜓) ∧ (𝜓 ⇒ 𝜙)</th></tr><tr><td>T</td><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td><td>F</td><td>F</td><td>F</td></tr><tr><td>F</td><td>T</td><td>T</td><td>F</td><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td><td>F</td></tr><tr><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr></tbody></table> </p>
</details>

Question 8
----------

Construct truth tables to illustrate the following:\
(a) 𝜙 ⇔ 𝜓

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>𝜙 ⇒ 𝜓</th><th>𝜓 ⇒ 𝜙</th><th>𝜙⇔𝜓 = (𝜙 ⇒ 𝜓) ∧ (𝜓 ⇒ 𝜙)</th></tr><tr><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>T</td><td>T</td></tr><tr><td>F</td><td>T</td><td>T</td><td>F</td><td>F</td></tr><tr><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td></tr></tbody></table> </p>
</details>


(b) 𝜙 ⇒ (𝜓 ∨ θ)

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>θ</th><th>𝜓 ∨ θ</th><th>𝜙 ⇒ (𝜓 ∨ θ)</th></tr><tr><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>T</td><td>F</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>F</td><td>F</td></tr><tr><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>F</td><td>F</td><td>T</td></tr></tbody></table> </p>
</details>


Question 9
----------

Use truth tables to prove that the following are equivalent:\
𝜙 ⇒ (𝜓 ∧ θ) and (𝜙 ⇒ 𝜓) ∧ (𝜙 ⇒ θ)

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>θ</th><th>𝜓 ∧ θ</th><th>𝜙 ⇒ 𝜓</th><th>𝜙 ⇒ θ</th><th>𝜙 ⇒ (𝜓 ∧ θ)</th><th>(𝜙 ⇒ 𝜓) ∧ (𝜙 ⇒ θ)</th></tr><tr><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td><td>F</td><td>F</td></tr><tr><td>T</td><td>F</td><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td><td>F</td></tr><tr><td>T</td><td>F</td><td>F</td><td>F</td><td>F</td><td>F</td><td>F</td><td>F</td></tr><tr><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>T</td><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td></tr></tbody></table> </p>
</details>


Question 10
-----------
Verify the equivalence in the previous question by means of a logical argument. (So, you must show that assuming φ and deducing 𝜓 ∧ θ is the same as both deducing 𝜓 from 𝜙 and θ from 𝜙.)


<details>
    <summary> Answer </summary>
        <p> 1. If 𝜙 ⇒ (𝜓 ∧ θ) is true, and assuming 𝜙 is true, then (𝜓 ∧ θ) is also true. </p>
        <p> 2. If (𝜓 ∧ θ) is true, then 𝜓 and θ are both true.</p>

On the other hand,
        <p>3. For equivalence,  (𝜙 ⇒ 𝜓) ∧ (𝜙 ⇒ θ) must be true. </p>
        <p>4. This follows that (𝜙 ⇒ 𝜓) is true and  (𝜙 ⇒ θ) is also true</p>

Substituting the earlier assumed and deduced values of 𝜙 (True) and  𝜓(True) and θ(True) into expression 4 above, Both statements are equivalent.

</details>

Question 11
-----------
Use truth tables to prove the equivalence of 𝜙 ⇒ 𝜓 and (¬𝜓) ⇒ (¬𝜙).\
(¬𝜓) ⇒ (¬𝜙) is called the contrapositive of 𝜙 ⇒ 𝜓. The logical equivalence of a conditional and its contrapositive means that one way to prove an implication it is to verify the contrapositive. This is a common form of proof in mathematics that we’ll encounter later.

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>¬𝜙</th><th>¬𝜓</th><th>𝜙 ⇒ 𝜓</th><th>¬𝜓 ⇒ ¬𝜙</th></tr><tr><td>T</td><td>T</td><td>F</td><td>F</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td><td>F</td></tr><tr><td>F</td><td>T</td><td>T</td><td>F</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td></tr></tbody></table> </p>
</details>

Question 12
-----------
Write down the contrapositives of the following statements:\
(a)  If two rectangles are congruent, they have the same area.\

<details>
    <summary> Answer </summary>
        <p> If two rectangles do not have the same area, they are not congruent </p>
</details>

(b)  If a triangle with sides _a, b, c (c_ largest) is right-angled, then _a² + b² = c²_.\

<details>
    <summary> Answer </summary>
        <p> If a² + b² ≠ c² then the triangle with sides a, b, c (c largest) is not right-angled </p>
</details>

(c)  If 2n−1 is prime, then _n_ is prime.\

<details>
    <summary> Answer </summary>
        <p> If n is not prime, then 2^n -1 is not prime. </p>
</details>

(d)  If the Yuan rises, the Dollar will fall.

<details>
    <summary> Answer </summary>
        <p> If the Dollar does not fall, Yuan will not rise. </p>
</details>

Question 13
-----------
It is important not to confuse the contrapositive of a conditional 𝜙 ⇒ 𝜓 with its converse 𝜓 ⇒ 𝜙.Use truth tables to show that the contrapositive and the converse of 𝜙 ⇒ 𝜓 are not equivalent.

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>𝜙 ⇒ 𝜓</th><th>𝜓 ⇒ 𝜙</th></tr><tr><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>T</td></tr><tr><td>F</td><td>T</td><td>T</td><td>F</td></tr><tr><td>F</td><td>F</td><td>T</td><td>T</td></tr></tbody></table> </p>
</details>


Question 14
-----------
Write down the converses of the four statements in question 12.

<details>
    <summary> Answer </summary>
        <p> (a) If two rectangles have the same area, they are congruent. </p>
        <p>(b) If a² + b² = c², then a triangle with sides a, b, c (c the largest) is right angled.</p>
        <p>(c) If n is a prime, then 2^n-1 is a prime.</p>
        <p>(d) If the Dollar falls, the Yuan will rise.</p>
</details>



# OPTIONAL PROBLEMS

Question 1
----------

Express the combinator\
𝜙 unless 𝜓 \
in terms of the standard logical combinators.


<details>
    <summary> Answer </summary>
        <p> ¬𝜓 ⇒ 𝜙 </p>
</details>

Question 2
----------
Let  ̇∨ denote the ‘exclusive or’ that corresponds to the English expression “either one or the other but not both”. Construct a truth table for this connective.

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>𝜙  ̇∨ 𝜓</th></tr><tr><td>T</td><td>T</td><td>F</td></tr><tr><td>T</td><td>F</td><td>T</td></tr><tr><td>F</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>F</td></tr></tbody></table> </p>
</details>

Question 3
----------
Express 𝜙  ̇∨ 𝜓 in terms of the basic combinators ∧, ∨, ¬.


<details>
    <summary> Answer </summary>
        <p> (𝜙  ̇∨ 𝜓) = (𝜙 ∧ ¬𝜓) ∨ (¬𝜙 ∧ 𝜓) </p>
</details>


Question 4
----------
Give, if possible, an example (one example in each case) of a true conditional sentence for which\
(a)  the converse is true.

<details>
    <summary> Answer </summary>
        <p> If a triangle with sides a, b, c (c largest) is right angled, then a² + b² = c². </p>
</details>

(b)  the converse is false.

<details>
    <summary> Answer </summary>
        <p> If 2^n-1 is a prime, n is prime. </p>
</details>

(c)  the contrapositive is true.

<details>
    <summary> Answer </summary>
        <p> If two rectangles are congruent, they have thes ame area. </p>
</details>

(d)  the contrapositive is false.

<details>
    <summary> Answer </summary>
        <p> The contrapositive is not false if the conditional statement is true </p>
</details>


Question 5
---------

_Mod-2 arithmetic_ has just the two numbers 0 and 1 and follows the usual rules of arithmetic together with the additional rule 1 + 1 = 0. (It is the arithmetic that takes place in a single bit location in a digital computer.) Complete the following table:


<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>M</th><th>N</th><th>M × N</th><th>M + N</th></tr><tr><td>1</td><td>1</td><td>1</td><td>0</td></tr><tr><td>1</td><td>0</td><td>0</td><td>1</td></tr><tr><td>0</td><td>1</td><td>0</td><td>1</td></tr><tr><td>0</td><td>0</td><td>0</td><td>0</td></tr></tbody></table> </p>
</details>

Question 6
----------
In  the  table  you  obtained  in  the  above  exercise,  interpret  1  as  T  and  0  as  F  and  view M, N as denoting statements.
(a)  Which of the logical combinators ∧, ∨ corresponds to × ?

<details>
    <summary> Answer </summary>
        <p> ∧ </p>
</details>

(b)  Which logical combinator corresponds to + ?

<details>
    <summary> Answer </summary>
        <p> ̇∨ (xor) </p>
</details>

(c)  Does ¬ correspond to − (minus)?

<details>
    <summary> Answer </summary>
        <p> No </p>
</details>

Question 7
----------

Repeat the above exercise, but interpret 0 as T and 1 as F. What conclusions can you draw?

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>M</th><th>N</th><th>M × N</th><th>M + N</th></tr><tr><td>T</td><td>T</td><td>T</td><td>F</td></tr><tr><td>T</td><td>F</td><td>F</td><td>T</td></tr><tr><td>F</td><td>T</td><td>F</td><td>T</td></tr><tr><td>F</td><td>F</td><td>F</td><td>F</td></tr></tbody></table> </p>
        <P> When T and F are replaced with 1 and 0 respectively, '×' acts like 'and' and + like XOR</P>
</details>

Question 8
----------
The following puzzle was introduced by the psychologist Peter Wason in 1966, and is one of the most famous subject tests in the psychology of reasoning. Most people get it wrong. (So you have been warned!)

Four cards are placed on the table in front of you. You are told (truthfully) that each has a letter printed on one side and a digit on the other, but of course you can only see one face of each. What you see is:

<div align="center">B E 4 7 </div>

You are now told that the cards you are looking at were chosen to follow the rule “If there is a vowel on one side, then there is an odd number on the other side.” What is the least number of cards you have to turn over to verify this rule, and which cards do you in fact have to turn over?

<details>
    <summary> Answer </summary>
        <p> I will turn two cards, E and 4. If there is an odd number behind E and a consonant behind 4, then I have confirmed the rules. </p>
</details>


Question 9
----------
Let m, n denote any two natural numbers. Prove that mn is odd iff m and n are odd.
<details>
    <summary> Answer </summary>
        <p> mn can be odd iff mn has only positional implication and does not mean multiplication. On the other hand, if by mn, m x n is implied, then it follows that, from the definition of odd numbers, an odd number should only be divisible by itself and 1. but mn is divisible by itself, by m, by n and by mn. so mn is odd iff either m or n is 1. </p>
</details>

Question 10
-----------

With reference to the previous question, is it true that mn is even iff m and n are even? Prove your answer.

<details>
    <summary> Answer </summary>
        <p> All two even numbers multiply to give an even number but a number mn is even iff one of its factors is 2</p>
</details>

Question 11
----------

 You are in charge of a party where there are young people. Some are drinking alcohol, others soft drinks. Some are old enough to drink alcohol legally, others are under age. You are responsible for ensuring that the drinking laws are not broken, so you have asked each person to put his or her photo ID on the table. At one table are four young people. One person has a beer, another has a Coke, but their IDs happen to be face down so you cannot see their ages. You can, however, see the IDs of the other two people. One is under the drinking age, the other is above it. Unfortunately,you are not sure if they are drinking Seven-up or vodka and tonic. Which IDs and/or drinks do you need to check to make sure that no one is breaking the law?


<details>
    <summary> Answer </summary>
        <p> I have to check the drink of the confirmed underage guy and the ID of the one drinking beer. </p>
</details>

Question 12
-----------

Compare the logical structure of the previous question with Wason’s problem (Optional Problem 8above). Comment on your answers to those two questions. In particular, identify any logical rules you used in solving each problem, say which one was easier, and why you felt it was easier.

<details>
    <summary> Answer </summary>
        <p> Both of the answers had two conditions to be met to be eligible.The first one had an implication. We would have to emphasize the antecedent for finding the least number of turns.In this case, it was “If there is a vowel on one side”. So the statement would have the possibility of being false only if there were a vowel on top, or there were an even number on top. The 7 was an odd number,so no matter what was on the other side, it would be true. And the B already wasn’t a vowel, so it was automatically true. In the second case, it was a conjunction. Both conditions were equally important, order didn’t matter. If one was broken,the whole conjunction was false.I found the second one easier, I didn’t have to carefully see if the antecedent was false. Just having one condition tobe false was enough. </p>
</details>


The 7 was an odd number,so no matter what was on the other side, it would be true. And the B already wasn’t a vowel, so it was automatically true. In the second case, it was a conjunction. Both conditions were equally important, order didn’t matter. If one was broken,the whole conjunction was false.I found the second one easier, I didn’t have to carefully see if the antecedent was false. Just having one condition tobe false was enough.