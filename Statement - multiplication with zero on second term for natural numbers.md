tags: #statement 

## Statement

Let $m$ be a natural number. Then
$$ m \times 0 = 0$$

## Proof

We induct on $m$.

### Base case

We need to prove the statement for $m = 0$, so that
$$0 \times 0 = 0$$
From [[Definition - multiplication of natural numbers]] and [[Axiom - zero is a natural number]], this gives $0 = 0$. Hence the base case is proven.

## Inductive step

Assuming the statement is true for $m$, we need to prove the statement for $m\texttt{++}$, so that
$$m\texttt{++} \times 0 = 0$$
From [[Definition - multiplication of natural numbers]] and since [[Axiom - successor is a natural number]], then
$$m\texttt{++} \times 0 = (m \times 0) + 0$$
From our assumption, $m \times 0 = 0$ and [[Definition - addition of natural numbers]]  RHS becomes
$$(m \times 0) + 0 = 0 + 0 = 0$$
This closes the induction.

By [[Axiom - principle of mathematical induction]], the statement is proven for all natural numbers.