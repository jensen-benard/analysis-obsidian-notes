tags: #statement 

## Statement
Let $a$, $b$ and $c$ be natural numbers.

 If $a \geq b$ and $b \geq a$, then $a = b$ 

## Proof

By [[Definition - order of natural numbers]], $a \geq b$ and $b \geq a$ are defined as
$$a = b + n$$
$$b = a + m$$
respectively, for some natural numbers $n$ and $m$.

Substitute $b = a + m$ into $a = b + n$, giving
$$a = (a + m) + n$$

By [[Statement - addition is associative]], this is equivalent to
$$a = a + (m + n)$$
From [[Statement - cancellation law of addition]], $a = 0$. Hence,
$$0 = m + n$$
And by [[Statement - sum of two natural numbers equating to zero are both zero themselves]], $m = 0$ and $n = 0$.

Therefore, substituting $m = 0$ and $n = 0$ back into $b = a + m$ and $a = b + n$, we get
$$b = a + 0$$
$$a = b + 0$$
respectively.

By [[Statement - adding with zero on the second term leaves the natural number unchanged]], we conclude $b = a$.

