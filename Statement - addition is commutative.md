tags: #statement 

## Statement

For any natural numbers $n$ and $m$, 
$$n + m = m + n$$
## Proof

We induct on $n$.


### Base case
We need to prove the base case:
$$0 + m = m + 0$$
From [[Definition - addition]], we get LHS:
$$0 + m = m$$
since [[Axiom - zero is a natural number]].

And from [[Statement - adding with zero on the second term leaves the natural number unchanged]], we get RHS:
$$m + 0 = m$$
Since LHS $=$ RHS, the base case is proven.


### Inductive step
We assume inductively that:
$$n + m = m + n$$
And so we need to prove:
$$n\texttt{++} + m = m + n\texttt{++}$$
From [[Definition - addition]], we get LHS:
$$n\texttt{++} + m = (n + m)\texttt{++}$$
since [[Axiom - successor is a natural number]], hence $n\texttt{++}$ is a natural number.

Similarly, from [[Statement - addition with successor on second term equals successor of the sum]] and our inductive assumption, we get RHS:
$$m + n\texttt{++} = (m + n)\texttt{++} = (n + m)\texttt{++}$$
Since LHS $=$ RHS, we have closed the induction. And the statement is proven from [[Axiom - principle of mathematical induction]].
