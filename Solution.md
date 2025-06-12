## Definition:
Let A and B be sets.
1. ¬(a ∈ A) ≡ a ∉ A
2. a ∈ A\B ≡ a ∈ A  ∧  a ∉ B
3. a ∈ A∪B ≡ a ∈ A  ∨  a ∈ B
4. a ∈ A∩B ≡ a ∈ A  ∧  a ∈ B



# EXERCISE 1.1
Let A,B and C be sets.
###  1.  If a ∉ A\B and a ∈ A, show that a ∈ B.
Note: first, I recommend you writing it in calculative logic.
<div align="center">
  
**a ∉ A\B ∧ a ∈ A ⟹ a ∈ B**<br>
</div>
we do it for transit to left to right,

<div align="center">
a ∉ A\B ∧ a ∈ A <br>
≡ < definition of ∉ ><br>
¬(a ∈ A\B) ∧ a ∈ A<br>
≡ < definition of \ ><br>
¬(a ∈ A  ∧  a ∉ B) ∧ a ∈ A<br>
≡ < Morgan's Laws ><br>
(¬(a ∈ A) ∨ ¬(a ∉ B)) ∧ a ∈ A<br>
≡ < definition of ∉ ><br>
(¬(a ∈ A) ∨ ¬(¬(a ∈ B))) ∧ a ∈ A<br>
≡ < DNL> <br>
(¬(a ∈ A) ∨ a ∈ B) ∧ a ∈ A<br>
≡ < Distributive Laws > <br>
(¬(a ∈ A) ∧ a ∈ A) ∨ (a ∈ B ∧ a ∈ A)<br>
≡ < Contradiction for ∧ > <br>
false ∨ (a ∈ B ∧ a ∈ A)<br>
≡ < Neutral element for ∨><br>
(a ∈ B ∧ a ∈ A)<br>
⟹ < Debilitation ><br>
a ∈ B<br>
</div>
<p align="right">∎</p>
