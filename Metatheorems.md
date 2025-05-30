# Metatheorems
### What is a Metatheorem?
A **metatheorem** is a theorem about a formal system itself, rather than about objects within the system. It concerns properties of the system's syntax, semantics, or proof rules.
We are going to use two of them.
## Deducion Metatheorems
The following theorem simplifies the amount of formal proof needed.
Defenition.
Let Γ a set of premises and noempty. If Γ, P ⊨ Q then Γ ⊨ P ⟹ Q.

I know this definition could be some hard to understand. I recommend you to read "Lógica y Matemáticas discretas en la informatica, El estilo calculatorio. By Jaime Alejandro Bohórquez Villamizar". In that book it is explaim better and you can find a proof of this Metatheorem. 
Temporarily, I will give you an example to understand better.
## Prove with Deducion Metatheorems this Theorem: ** (P ∧ Q) ⟹ (P ≡ Q) **
**proof:**
For Deducion Metatheorems just prove, 
<p align="center">
P,Q ⊨ P ≡ Q
</p>
(Here, we take all of things before the conditional and we suppos that its true.)

To do this, we adapt the use of the test format in the following way.
<p align="center">
P
  
≡ < hypothesis: P, P equivalent to P ≡ True >

True

≡  < hypothesis: Q, P equivalent to Q ≡ True >

Q

</p>
∎

