tags: #statement 

## Statement

If $A$, $B$ and $C$ are sets, then 
$$(A \cup B) \cup C = A \cup (B \cup C)$$

## Proof

By [[Definition - equality of sets]], it is sufficient to prove
$$x \in (A \cup B) \cup C \iff x \in A \cup (B \cup C)$$
for every object $x$.

By [[Axiom - union of sets]], evaluating $x \in (A \cup B) \cup C$, gives
$$x \in A \cup B \ \text{or}\ x \in C$$ which is equivalent to
$$x \in A \ \text{or}\ x \in B \ \text{or}\ x \in C$$
Similarly, evaluating $x \in A \cup (B \cup C)$, gives
$$x \in A\ \text{or}\ x \in B \cup C$$
which is equivalent to 
$$x \in A \ \text{or}\ x \in B \ \text{or}\ x \in C$$
Since
$$x \in A \ \text{or}\ x \in B \ \text{or}\ x \in C \iff x \in A \ \text{or}\ x \in B \ \text{or}\ x \in C$$
then
$$x \in (A \cup B) \cup C \iff x \in A \cup (B \cup C)$$
