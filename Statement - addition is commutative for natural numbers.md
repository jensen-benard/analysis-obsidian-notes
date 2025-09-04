tags: #statement 

## Statement

For any natural numbers $n$ and $m$, 
$$n + m = m + n$$
## Proof

We induct on $n$.


### Base case
We need to prove the base case:
$$0 + m = m + 0$$
From [[Definition - addition of natural numbers]], we get LHS:
$$0 + m = m$$
since [[Axiom - zero is a natural number]].

And from [[Statement - addition with zero on second term for natural numbers]], we get RHS:
$$m + 0 = m$$
Since LHS $=$ RHS, the base case is proven.


### Inductive step
We assume inductively that:
$$n + m = m + n$$
And so we need to prove:
$$n\texttt{++} + m = m + n\texttt{++}$$
From [[Definition - addition of natural numbers]], we get LHS:
$$n\texttt{++} + m = (n + m)\texttt{++}$$
since [[Axiom - successor is a natural number]], hence $n\texttt{++}$ is a natural number.

Similarly, from [[Statement - addition with successor on second term for natural numbers]] and our inductive assumption, we get RHS:
$$m + n\texttt{++} = (m + n)\texttt{++} = (n + m)\texttt{++}$$
Since LHS $=$ RHS, we have closed the induction. And the statement is proven from [[Axiom - principle of mathematical induction]].
