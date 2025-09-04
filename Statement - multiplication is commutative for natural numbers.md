tags: #statement 

## Statement

Let $n$ and $m$ be natural numbers. Then 
$$n \times m = m \times n$$

## Proof

We induct on $n$.

### Base case

We need to prove the statement for $n = 0$, so that
$$0 \times m = m \times 0$$
From [[Definition - multiplication of natural numbers]] and [[Statement - multiplication with zero on second term for natural numbers]], we get
$$ 0 = 0 $$
Hence, the base case is proven.

## Inductive step

Assume the statement is true for $n$. We need to prove the statement for $n\texttt{++}$, so that
$$n\texttt{++} \times m = m \times n\texttt{++}$$
From [[Definition - multiplication of natural numbers]] and [[Statement - multiplication with successor on second term for natural numbers]], we get
$$(n \times m) + m = (m \times n) + m$$
From our assumption, $n \times m = m \times n$. And so we get
$$(n \times m) + m = (n \times m) + m$$

This closes the induction.

By [[Axiom - principle of mathematical induction]], we have proven the statement for all natural numbers.