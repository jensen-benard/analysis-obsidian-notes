tags: #statement  #todo 

## Statement

For any natural numbers $a$, $b$, $c$, we have
$$(a \times b) \times c = a \times (b \times c)$$

## Proof

We induct on $c$

### Base case

Let $c = 0$, 
$$(a \times b) \times 0 = a \times (b \times 0)$$
From [[Statement - multiplication with successor on second term for natural numbers]], LHS becomes
$$(a \times b) \times 0 = 0$$
and RHS becomes
$$a \times (b \times 0) = a \times 0 = 0$$

Hence, base case is proven.

### Inductive step

Assume statement is true for $c$. We prove for $c\texttt{++}$,
$$(a \times b) \times c\texttt{++} = a \times (b \times c\texttt{++})$$
From [[Statement - multiplication with successor on second term for natural numbers]], LHS becomes
$$(a \times b) \times c\texttt{++} = ((a \times b) \times c) + (a \times b)$$
and RHS becomes
$$a \times (b \times c\texttt{++}) = a \times ((b \times c) + b)$$
