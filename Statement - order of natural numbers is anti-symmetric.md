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

By [[Statement - addition is associative for natural numbers]], this is equivalent to
$$a = a + (m + n)$$
From [[Statement - cancellation law of addition for natural numbers]], $a = 0$. Hence,
$$0 = m + n$$
And by [[Statement - uniqueness of zero under addition for natural numbers]], $m = 0$ and $n = 0$.

Therefore, substituting $m = 0$ and $n = 0$ back into $b = a + m$ and $a = b + n$, we get
$$b = a + 0$$
$$a = b + 0$$
respectively.

By [[Statement - addition with zero on second term for natural numbers]], we conclude $b = a$.

