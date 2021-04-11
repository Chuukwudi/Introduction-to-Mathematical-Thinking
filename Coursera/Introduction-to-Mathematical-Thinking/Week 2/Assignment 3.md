# Introduction to Mathematical Thinking
## ASSIGNMENT 3 (for Lecture 3)

Question 1
----------
1.  Let _D_ be  the  statement  “The  dollar  is  strong”, _Y_ the  statement  “The  Yuan  is  strong”  and _T_ the statement “New US–China trade agreement signed”. Express the main content of each of the following (fictitious) newspaper headlines in logical notation. (Remember, logical notation captures truth, but not the many  nuances  and  inferences  of  natural  language.)  As  before, make sure you could justify and defend your answers.
    
**D - The Dollar is strong\
Y - The Yuan is strong\
T - New US–China Trade agreement signed**

(a)  New trade agreement will lead to strong currencies in both countries.

<details>
    <summary> Answer </summary>
        <p> T ⇒ (𝐷 ∧ 𝑌)
        </p>
</details>
(b)  Strong Dollar means a weak Yuan.

<details>
    <summary> Answer </summary>
        <p> 𝐷 ⇒ ¬𝑌 </p>
</details>

(c)  Trade agreement fails on news of weak Dollar.

<details>
    <summary> Answer </summary>
        <p> ¬𝐷 ⇒ ¬T </p>
</details>

(d)  If new trade agreement is signed, Dollar and Yuan can’t both remain strong.

<details>
    <summary> Answer </summary>
        <p> T ⇒ ¬(𝐷 ∧ 𝑌) </p>
</details>

(e)  Dollar weak but Yuan strong, following new trade agreement.

<details>
    <summary> Answer </summary>
        <p> T ⇒ ¬𝐷 ∧ 𝑌 </p>
</details>

(f)  If the trade agreement is signed, a rise in the Yuan will result in a fall in the Dollar.

<details>
    <summary> Answer </summary>
        <p> (T ∧ 𝑌) ⇒ ¬𝐷 </p>
</details>

(g)  New trade agreement means Dollar and Yuan will rise and fall together.

<details>
    <summary> Answer </summary>
        <p> T ⇒ (𝐷 ∧ 𝑌) ∨ (¬𝐷 ∧ ¬𝑌) </p> or
        <p> T ⇒ (𝐷 ⇔ 𝑌) </p> or
        <p>  T ⇒ [(D ⇒ Y) ∧ (Y ⇒ D)]</p>
</details>

(h)  New trade agreement will be good for one side, but no one knows which.

<details>
    <summary> Answer </summary>
        <p> T ⇒ (𝐷 ∧ ¬𝑌) ∨ (¬𝐷 ∧ 𝑌) </p> or
        <p>  T ⇒ [(D ∨ Y) ∧ ¬(D ∧ Y)]</p>
</details>


Question 2
----------

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>¬𝜙</th><th>𝜓</th><th>𝜙 ⇒ 𝜓</th><th>¬𝜙 ∨ 𝜓</th></tr><tr><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>F</td><td>F</td></tr><tr><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td></tr></tbody></table> </p>
</details>

Question 3
----------
<details>
    <summary> Answer </summary>
        <p> (𝜙 ⇒ 𝜓) = (¬𝜙 ∨ 𝜓) </p> 
</details>


Question 4
----------

<details>
    <summary> Answer </summary>
        <p> <table><tbody><tr><th>𝜙</th><th>𝜓</th><th>¬𝜓</th><th>𝜙 ⇒ 𝜓</th><th>𝜙 ⇏ 𝜓</th><th>𝜙 ∧ ¬𝜓</th></tr><tr><td>T</td><td>T</td><td>F</td><td>T</td><td>F</td><td>F</td></tr><tr><td>T</td><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td></tr><tr><td>F</td><td>T</td><td>F</td><td>T</td><td>F</td><td>F</td></tr><tr><td>F</td><td>F</td><td>T</td><td>T</td><td>F</td><td>F</td></tr></tbody></table> </p>
</details>

Question 5
----------
<details>
    <summary> Answer </summary>
        <p> (𝜙 ⇏ 𝜓) = (𝜙 ∧ ¬𝜓) </p>
</details>

