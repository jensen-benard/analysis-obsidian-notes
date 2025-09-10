tags: #statement 

## Statement

if $A$, $B$ and $A'$ are sets, and $A = A'$, then
$$A \cup B = A' \cup B$$

## Proof

By [[Axiom - union of sets]], to prove $A \cup B = A' \cup B$, it is sufficient to prove
$$x \in A \cup B \iff x \in A' \cup B$$
for every object $x$.

By [[Axiom - union of sets]], $A \cup B$ is equivalent to $x \in A$ or $x \in B$.

Suppose there is an object $x \in A$.

By [[Definition - equality of sets]], since $A = A'$, 
$$x \in A'$$
Hence, by [[Axiom - union of sets]], since $x \in A'$ or $x \in B$, it is also true that
$$x \in A' \cup B$$

The reverse direction, $A' \cup B \implies A \cup B$,  is identical, using the same axioms and definitions.

Hence, this gives
$$A \cup B = A' \cup B$$