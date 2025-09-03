tags: #statement 

## Statement
Let $a$, $b$ and $c$ be natural numbers.

 $a \geq b$ if and only if $a + c \geq b + c$

## Proof

### Proving the forward direction
Suppose $a \geq  b$.

By [[Definition - order of natural numbers]], $a \geq b$ is equivalent to
$$a = b + n$$
for some natural number $n$.

By [[Definition - addition]], we can add $c$ to both sides to give
$$a + c = (b + n) + c$$
By [[Statement - addition is associative]] and [[Statement - addition is commutative]], we get
$$a + c = b + (n + c) = b + (c + n) = (b + c) + n$$
Hence, by [[Definition - order of natural numbers]], this is equivalent to
$$a + c \geq b + c$$

### Proving the reverse direction
Now suppose $a + c \geq b + c$.

By [[Definition - order of natural numbers]], this is equivalent to
$$a + c = (b + c) + m$$
for some natural number $m$.

By [[Statement - addition is associative]] and [[Statement - addition is commutative]], we have
$$(b + c) + m = b + (c + m) = b + (m + c) = (b + m) + c$$
Hence,
$$a + c = (b + m) + c$$
By [[Statement - cancellation law of addition]], this gives
$$a = b + m$$
Again, by [[Definition - order of natural numbers]], this is equivalent to 
$$ a \geq b $$

Since we have proven both directions, the statement is proven.
