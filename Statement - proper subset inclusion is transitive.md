tags: #statement 

## Statement

Let $A$, $B$, $C$ be sets.

If $A \subsetneq B$ and $B \subsetneq C$ then $A \subsetneq C$.

## Proof

By [[Definition - subset]],
$$x \in A \implies x \in B$$
for every object $x$, where $A \neq B$.

Similarly,
$$x \in B \implies x \in C$$
for every object $x$, where $B \neq C$.

So, for an arbitrary object $x$, we have $x \in A$, hence $x \in B$. However this also means, $x \in C$.
And so we have
$$x \in A \implies x \in C$$
But we must prove $A \neq C$.

For the sake of contradiction, let us assume $A = C$.
Hence, $B \subsetneq C$ becomes
$$B \subsetneq A$$
So now we have, $A \subsetneq B$ and $B \subsetneq A$. 

By [[Definition - equality of sets]], this implies $A = B$, since every element of $A$ is in $B$ and vice versa. This contradicts $A \neq B$.

Hence, $A \neq C$.

Therefore, by [[Definition - subset]],
$$A \subsetneq C$$
