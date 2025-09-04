tags: #statement 

## Statement

For a natural number $n$,
$$1 \times n = n$$
hence,
$$n \times 1 = n$$

## Proof

We induct on $m$.

### Base case

Let $n$ = 0.
Hence, by [[Definition - multiplication of natural numbers]], LHS becomes
$$1 \times 0 = 0$$
this equates to the RHS of $0$.

And the statement is proven for the base case.

### Inductive step

Assume the statement is true for $n$. 
We now prove the statement for $n\texttt{++}$. 

Using [[Statement - multiplication with successor on second term for natural numbers]], this gives LHS
$$1 \times n\texttt{++} = (1 \times n) + 1$$
Using our assumption, this evaluates to
$$(1 \times n) + 1 = n + 1 = n\texttt{++}$$
This is equal to the RHS of $n\texttt{++}$.

Hence, the induction is closed. 

By [[Axiom - principle of mathematical induction]] and [[Statement - multiplication is commutative for natural numbers]], we have proven the statement.