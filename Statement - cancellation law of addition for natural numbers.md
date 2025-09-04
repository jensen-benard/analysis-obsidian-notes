tags: #statement 

## Statement

Let $a, b, c$ be natural numbers such that,
$$a + b = a + c$$

Then we have $b = c$.

## Proof

We induct on $a$.

### Base case

We must prove the base case for $a = 0$, where:
$$0 + b = 0 + c$$
From [[Definition - addition of natural numbers]], we get:
$$ b = c $$
since [[Axiom - zero is a natural number]].

Hence we have proved the base case.

### Inductive step

We assume inductively that $a + b = a + c$, hence we must prove:
$$a\texttt{++} + b = a\texttt{++} + c$$
From [[Definition - addition of natural numbers]], we get LHS:
$$a\texttt{++} + b = (a + b)\texttt{++}$$
since from [[Axiom - successor is a natural number]], $a\texttt{++}$.

Similarly, using our inductive assumption, we get RHS:
$$a\texttt{++} + c = (a + c)\texttt{++} = (b + c)\texttt{++}$$
Since LHS $=$ RHS, the induction is closed. And so the statement is proven from [[Axiom - principle of mathematical induction]].
