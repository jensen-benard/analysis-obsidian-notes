tags: #statement #todo

## Statement

For any natural numbers $a$, $b$ and $c$, we have
$$a(b + c) = ab + ac$$
and 
$$(b + c)a = ba + ca$$

## Proof

Since [[Statement - multiplication is commutative for natural numbers]], we only need to show $$a(b + c) = ab + ac$$
We induct on $c$.

### Base case
Let $c = 0$. This gives
$$a(b + 0) = ab + a(0)$$
From [[Statement - multiplication with zero on second term for natural numbers]] and [[Statement - addition with zero on second term for natural numbers]], RHS becomes
$$ ab + a(0) = ab + 0 = ab$$
and LHS becomes
$$a(b + 0) = a(b) = ab$$

Since LHS $=$ RHS, the base case is done.

### Inductive step

Assume the statement is true for $c$. We prove for $c\texttt{++}$. This gives
$$a(b + c\texttt{++}) = ab + a(c\texttt{++})$$
From [[Statement - multiplication with successor on second term for natural numbers]] and our assumption, RHS becomes
$$ab + a(c\texttt{++}) = ab + ac + a = a(b + c) + a = a\times((b+c)\texttt{++})$$
From [[Statement - addition with successor on second term for natural numbers]], LHS becomes
$$a(b + c\texttt{++}) = a((b + c)\texttt{++})$$

Since LHS $=$ RHS, the induction is closed.

By [[Axiom - principle of mathematical induction]], the statement is proven.