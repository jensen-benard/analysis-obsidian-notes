tags: #statement 

## Statement

For any natural numbers $a, b, c$, we have $$(a + b) + c = a + (b + c)$$
## Proof
We induct on $a$.

### Base case

We need to prove the base case, $a = 0$.

$$(0 + b) + c = 0 + (b + c)$$
From [[Definition - addition of natural numbers]], this gives LHS and RHS:
$$b + c = b + c$$
since [[Axiom - zero is a natural number]].

### Inductive step

We assume inductively:
$$(a + b) + c = a + (b + c)$$
So we need to prove:
$$(a\texttt{++} + b) + c = a\texttt{++} + (b + c)$$
From [[Definition - addition of natural numbers]] and [[Statement - addition with successor on second term for natural numbers]], we get LHS:
$$(a\texttt{++} + b) + c  = (a + b)\texttt{++} + c = ((a + b) + c)\texttt{++}$$
since from [[Axiom - successor is a natural number]], $a\texttt{++}$ is a natural number.

Similarly, using our inductive assumption, we get RHS:
$$a\texttt{++} + (b + c) = (a + (b + c))\texttt{++} = ((a + b) + c)\texttt{++} $$
Since LHS $=$ RHS, the induction is closed. And we have proven the statement from [[Axiom - principle of mathematical induction]].
