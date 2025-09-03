tags: #statement 

## Statement

For all natural numbers $n$, $m$, the sum $n + m$ is a natural number 
## Proof

We induct on $n$.

### Base case

We must prove the statement for the case $n = 0$, where
$$0 + m$$
By [[Definition - addition]], this gives
$$0 + m = m$$
Hence, $0 +m$ is a natural number.

### Inductive step

Assume the statement is true for $n$. We must prove the statement for $n\texttt{++}$, where
$$n\texttt{++} + m$$
By [[Definition - addition]],
$$n\texttt{++} + m = (n + m)\texttt{++}$$
Since we assumed the statement is true for $n$, then $n+m$ is a natural number.

Hence, by [[Axiom - successor is a natural number]], $(n + m)\texttt{++}$ is also a natural number.

By [[Axiom - principle of mathematical induction]], the induction is closed. And the statement is proven.

