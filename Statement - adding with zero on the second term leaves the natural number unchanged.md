tags: #statement

## Statement

For any natural number $n$, 
$$n + 0 = n$$

## Proof

We induct on $n$.


### Base case
We need to prove the base case where $n = 0$, so that $$0 + 0 = 0$$
Since [[Axiom - zero is a natural number]], and from [[Definition - addition]], this gives $0 = 0$ which is true. So the base case is true.


### Inductive step
Suppose inductively that $n + 0 = n$. So now we need to prove $n\texttt{++} + 0 = n\texttt{++}$.

Since [[Axiom - successor is a natural number]], using [[Definition - addition]], we get $n\texttt{++} + 0 = (n + 0)\texttt{++}$.

Since inductively $n + 0 = n$, then $(n + 0)\texttt{++} = (n)\texttt{++} = n\texttt{++}$.

This closes the induction. And so the statement is proven from [[Axiom - principle of mathematical induction]].