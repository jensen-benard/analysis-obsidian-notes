tags: #statement 

## Statement

if $a$ is positive and $b$ is a natural number, then $a + b$ is positive (and hence $b+a$ is also positive).

## Proof

We use induction on $b$.

### Base case

We need to prove the base case, $b = 0$.
Hence, from [[Statement - addition with zero on second term for natural numbers]] we have:
$$a + 0 = a$$
since $a$ is positive then the base case is proven.

### Inductive step

We assume the statement inductively. And so we need to prove the case for $b\texttt{++}$.
From [[Statement - addition with successor on second term for natural numbers]], this gives:
$$ a + b\texttt{++} = (a + b)\texttt{++}$$

From our inductive assumption, $a + b$ is positive. We know $(a + b)\texttt{++}$ is a at least a natural number since [[Axiom - successor is a natural number]]. However, since [[Axiom - zero is not a successor of a natural number]] then, $$(a + b)\texttt{++} \neq 0$$
Hence by [[Definition - positive natural numbers]], $(a + b)\texttt{++}$ is a positive number and the induction is closed.

This proves our statement from [[Axiom - principle of mathematical induction]].