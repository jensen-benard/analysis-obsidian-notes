tags: #statement 

## Statement
Let $a$ and $b$ be natural numbers.

$a \lt b$ if and only if $a\texttt{++} \leq b$

## Proof

### Proving the forward direction

Suppose $a \lt b$.

By [[Definition - order of natural numbers]], this is equivalent to $a \leq b$ where $a \neq b$. Hence, can be written as
$$b = a + n$$
for some natural number $n \neq 0$, since otherwise $b = a$ from [[Statement - addition of identity on second term]].

By [[Definition - positive natural numbers]], this means $n$ is a positive number.

Hence, since [[Statement - every positive number has a unique predecessor]], there exists a natural number $m$, where
$$m\texttt{++} = n$$
We can substitute this into $b = a + n$ and maintain $a \lt b$, giving
$$b = a + m\texttt{++}$$
By [[Statement - addition with successor on second term]],
$$ b = a + m\texttt{++} = (a + m)\texttt{++} = a\texttt{++} + m$$
Hence, by [[Definition - order of natural numbers]],
$$b \geq a\texttt{++}$$


### Proving the reverse direction
Suppose $b \geq a\texttt{++}$.

By [[Definition - order of natural numbers]], this is equivalent to
$$b = a\texttt{++} + k$$
for some natural number $k$.

By [[Definition - addition]] and [[Statement - addition with successor on second term]],
$$b = a\texttt{++} + k = (a + k)\texttt{++} = a + k\texttt{++}$$
Since [[Statement - every positive number has a unique predecessor]], there exists a positive number $j$ where $k$ is its predecessor such that,
$$k\texttt{++} = j$$
Substituting $j$ into $b = a + k\texttt{++}$, we get
$$b = a + j$$
By [[Definition - positive natural numbers]], $j \neq 0$. 

By [[Definition - addition]], this means $b \neq a$ and so $b = a + j$ is equivalent to 
$$ b \gt a$$
from the [[Definition - order of natural numbers]].

Since we have proven both directions, the statement is proven.