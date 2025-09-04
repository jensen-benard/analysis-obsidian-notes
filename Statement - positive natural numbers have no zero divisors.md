tags: #statement #todo

## Statement

Let $n$ and $m$ be natural numbers.
$$ n \times m = 0$$if and only if at least one of $n$, $m$ is equal to $0$. 

In particular, if $n$ and $m$ are both positive, then $nm$ is also positive.

## Proof

Let us first prove that 

- if $n$ and $m$ are both positive, then $nm$ is also positive. 

Notice that this statement is the negation of 

- $n \times m = 0$ if and only if at least one of $n, m$ is equal to $0$.


Suppose that $n$ and $m$ are positive.

We know [[Statement - every positive natural number has a unique natural number predecessor]]. And so
$$n \times m = (a\texttt{++}) \times (b\texttt{++})$$
where $a$ and $b$ are natural numbers.

By [[Definition - multiplication of natural numbers]] and [[Statement - addition is associative for natural numbers]], RHS becomes
$$(a \times b\texttt{++}) + b\texttt{++} = ((a \times b) + a) + b = (a \times b) + a + b + 1$$
Since [[Statement - addition preserves positiveness of natural numbers]], this result is positive and therefore $nm$ is positive.




