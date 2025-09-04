tags: #statement 

## Statement

For any natural numbers $n$ and $m$, 
$$n + (m\texttt{++}) = (n + m)\texttt{++}$$
## Proof

We induct on $n$.

### Base case
Let's consider the base case $n = 0$,
$$ 0 + m\texttt{++} = (0 + m)\texttt{++} $$
We know [[Axiom - zero is a natural number]], and so from [[Definition - addition of natural numbers]], 
the LHS:
$$0 + m\texttt{++} = m\texttt{++}$$
and RHS:
$$(0 + m)\texttt{++} = (m)\texttt{++} = m\texttt{++}$$
Since LHS $=$ RHS then the base case is proven.

### Inductive step
Now assume inductively that 
$$n + (m\texttt{++}) = (n + m)\texttt{++}$$

We must prove:
$$n\texttt{++} + m\texttt{++} = (n\texttt{++} + m)\texttt{++}$$
From [[Definition - addition of natural numbers]] and our inductive assumption, we get LHS:
$$n\texttt{++} + m\texttt{++} = (n + m\texttt{++})\texttt{++} = ((n + m)\texttt{++})\texttt{++}$$
since $n\texttt{++}$ is a natural number from [[Axiom - successor is a natural number]].

Similarly, on RHS:
$$(n\texttt{++} + m)\texttt{++} = ((n + m)\texttt{++})\texttt{++}$$

Therefore, LHS $=$ RHS, hence the induction is closed. And so the statement is proven from [[Axiom - principle of mathematical induction]].