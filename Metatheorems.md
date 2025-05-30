# Metatheorems

### What is a Metatheorem?

A **metatheorem** is a theorem *about* a formal system itself, rather than about the objects within the system. It describes properties of the system's syntax, semantics, or inference rules.

In this section, we will use two important metatheorems.

---

## Deduction Metatheorem

The following metatheorem simplifies the amount of formal proof required.

**Definition:**  
Let Γ be a non-empty set of premises. If  
\[
Γ, P ⊨ Q
\]  
then  
\[
Γ ⊨ P ⟹ Q
\]

> **Note:** I understand this definition may be difficult to grasp at first. I recommend the book *"Lógica y Matemáticas Discretas en la Informática: El Estilo Calculatorio"* by **Jaime Alejandro Bohórquez Villamizar**.  
> It provides a clearer explanation and includes a formal proof of this metatheorem.

Meanwhile, let’s explore a simple example to make the idea more accessible.

---

## Proving the Theorem Using the Deduction Metatheorem:

### **(P ∧ Q) ⟹ (P ≡ Q)**

**Proof:**  
By the Deduction Metatheorem, it is enough to prove:

<p align="center"><code>P, Q ⊨ P ≡ Q</code></p>

*(Here, we assume all statements before the implication are true.)*

We adapt the use of the test format in the following way:

<p align="center">

P  
≡  (*by hypothesis: P; since any statement is equivalent to itself,* **P ≡ True**)  
True  
≡  (*by hypothesis: Q; so now P ≡ Q is equivalent to True*)  
Q  

</p>

∎
