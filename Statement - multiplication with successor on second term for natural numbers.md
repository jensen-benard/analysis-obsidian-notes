tags: #statement 

## Statement

Let $n$ and $m$ be natural numbers. Then
$$ n \times m\texttt{++} = (n \times m) + n$$

## Proof

We induct on $n$.

### Base case

We need to prove the statement is true for $n = 0$, so that
$$0 \times m\texttt{++} = (0 \times m) + 0$$
From [[Definition - multiplication of natural numbers]]. and since [[Axiom - successor is a natural number]], LHS becomes
$$0 \times m\texttt{++} = 0$$
and using [[Statement - addition with zero on second term for natural numbers]], RHS becomes
$$(0 \times m) + 0 = 0 + 0 = 0$$
Hence, we have proven the base case

### Inductive step

Assume the statement is true for $n$. We need to prove the statement for $n\texttt{++}$, so that
$$n\texttt{++} \times m\texttt{++} = (n\texttt{++} \times m) + n\texttt{++}$$
From [[Definition - multiplication of natural numbers]] followed by our assumption, LHS can be expressed as
$$n\texttt{++} \times m\texttt{++} = (n \times m\texttt{++}) + m\texttt{++} = ((n \times m) + n) + m\texttt{++}$$
Since [[Statement - addition is associative for natural numbers]] and given [[Statement - addition with successor on second term for natural numbers]], we get:
$$(n \times m\texttt{++}) + m\texttt{++} = (n \times m) + (n + m\texttt{++}) = (n \times m) + (n + m)\texttt{++}$$
For the RHS, we get
$$(n\texttt{++} \times m) + n\texttt{++} = ((n \times m) + m) + n\texttt{++}$$
And similarly, given [[Statement - addition is commutative for natural numbers]], we get
$$ ((n \times m) + m) + n\texttt{++} = (n \times m) + (m + n\texttt{++}) = (n \times m) + (m + n)\texttt{++} = (n \times m) + (n + m)\texttt{++}$$

We can see LHS = RHS.
Hence, the inductions is closed.

By [[Axiom - principle of mathematical induction]], we have proven the statement for all natural numbers.