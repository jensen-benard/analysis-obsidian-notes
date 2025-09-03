tags: #statement 

## Statement

Let $a$, $b$ and $c$ be natural numbers.

If $a \geq b$ and $b \geq c$, then $a \geq c$

## Proof

By [[Definition - order of natural numbers]], $a \geq b$ and $b \geq c$ are defined as
$$a = b + n$$
$$b = c + m$$
for some natural numbers $n$ and $m$.

We substitute $b = c + m$ into $a = b + n$ to get
$$a = (c + m) + n$$
By [[Statement - addition is associative]], this is equivalent to,
$$a = c + (m + n)$$
By [[Statement - closure under addition]], $m + n$ is a natural number.

Let $k = m + n$, for some natural number $k$. Then
$$a = c + k$$
which by [[Definition - order of natural numbers]], shows $a \geq c$. And the statement is proven.