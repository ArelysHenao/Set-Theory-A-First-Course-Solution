## 📘 Definition

Let \( A \) and \( B \) be sets:

1. \( \neg(a \in A) \equiv a \notin A \)
2. \( a \in A \setminus B \equiv a \in A \land a \notin B \)
3. \( a \in A \cup B \equiv a \in A \lor a \in B \)
4. \( a \in A \cap B \equiv a \in A \land a \in B \)

---

# 🧠 EXERCISE 1.1

Let \( A, B, C \) be sets.

### 1. If \( a \notin A \setminus B \) and \( a \in A \), show that \( a \in B \)

> 💡 *Note: First, write it using calculative logic.*

<div align="center">

**\( a \notin A \setminus B \land a \in A \Rightarrow a \in B \)**

<br>

We proceed from left to right:

<br>

\[
\begin{aligned}
& a \notin A \setminus B \land a \in A \\
& \equiv && \text{(Definition of } \notin \text{)} \\
& \neg(a \in A \setminus B) \land a \in A \\
& \equiv && \text{(Definition of } \setminus \text{)} \\
& \neg(a \in A \land a \notin B) \land a \in A \\
& \equiv && \text{(De Morgan's Laws)} \\
& (\neg(a \in A) \lor \neg(a \notin B)) \land a \in A \\
& \equiv && \text{(Definition of } \notin \text{)} \\
& (\neg(a \in A) \lor \neg(\neg(a \in B))) \land a \in A \\
& \equiv && \text{(Double Negation)} \\
& (\neg(a \in A) \lor a \in B) \land a \in A \\
& \equiv && \text{(Distributive Law)} \\
& (\neg(a \in A) \land a \in A) \lor (a \in B \land a \in A) \\
& \equiv && \text{(Contradiction)} \\
& \text{false} \lor (a \in B \land a \in A) \\
& \equiv && \text{(Identity Law)} \\
& a \in B \land a \in A \\
& \Rightarrow && \text{(Weakening)} \\
& a \in B
\end{aligned}
\]

</div>

<p align="right">∎</p>
