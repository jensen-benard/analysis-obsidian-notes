tags: #statement 

## Statement

Let $a$ and $b$ be natural numbers. 

Then exactly one of the following statements is true:
$$a \lt b$$
$$a = b$$
$$a \gt b$$
## Proof

### Proving only one statement can hold
First we show that we cannot have more than one statement holding at the same time.

Suppose $a \lt b$. 
Then by [[Definition - order of natural numbers]], $b \neq a$.

Similarly, suppose $a \gt b$.
Then by the same definition $b \neq a$

Suppose $a >b$ and $a \lt b$.
Then since [[Statement - a natural number is less than another if and only if the second can be written as the first plus a positive number]], we have
$$a = b + e$$
and
$$b = a + f$$
respectively, where $e$ and $f$ are positive numbers.

If we substitute $b$ into $a = b + e$ and [[Statement - addition is associative]], we get
$$a = (a + f) + e = a + (f + e)$$
By [[Statement - cancellation law of addition]] and
$$a = a + 0$$then
$$f + e = 0$$
But since $f$ and $e$ are positive and [[Statement - addition preserves positiveness of natural numbers]], this is a contradiction and $a \gt b$ and $b \lt a$ cannot hold at the same time.

Thus, no more than one statement is true at a time.


### Proving at least one of the statements is true
Finally we show that at least one of the statements is true.

We induct on $a$.
#### Base case

We need to prove the case where $a =0$. 
Substitute $a = 0$ into the three statements gives
$$0 \lt b$$
$$0 = b$$
$$0 \gt b$$
For $0 > b$ case, by [[Definition - order of natural numbers]], this gives
$$0 = b + n$$
for some natural number $n$. 
Since [[Statement - sum of two natural numbers equating to zero are both zero themselves]],  both $b = 0$ and $n = 0$.
By [[Definition - order of natural numbers]], this is a contradiction to $0 > b$.

Similarly, for the case $0 \lt b$, this gives
$$b = 0 + n$$
Then we let $b = n$, hence by [[Definition - addition]],
$$ b = 0 + b$$
And so we have proven one instance where $0 \lt b$.

Therefore, either $0 \lt b$ or $0 = b$.
Hence, by [[Definition - order of natural numbers]],
$$0 \leq b$$
This proves the base case where at least one of the statements is true.

#### Inductive step

Assume that at least one of the statements is true for $a$.

We need to prove at least one of the statements is true for $a\texttt{++}$.

There are three cases.


Let's assume $a \lt b$ is the case that is true from our assumption. Then since [[Statement - a natural number is less than another if and only its successor is less than or equal to the other]], we have
$$a\texttt{++} \leq b$$
Hence, either $a\texttt{++} \lt b$ or $a\texttt{++} = b$. Therefore at least one of the statements is true in this case.


Let's assume $a =b$ instead. 
We know
$$a\texttt{++} \geq a\texttt{++}$$
Since [[Statement - a natural number is less than another if and only its successor is less than or equal to the other]], then
$$a\texttt{++} \gt a$$
Since $a = b$, then
$$a\texttt{++} \gt b$$
And so we have at least one statement that is true for this case.


Finally, let's assume $a \gt b$. By [[Definition - order of natural numbers]], we can say
$$a \geq b$$
where $a \neq b$.

Since [[Statement - addition preserves order of natural numbers]],
$$a\texttt{++} \geq b\texttt{++}$$
Hence, since [[Statement - a natural number is less than another if and only its successor is less than or equal to the other]], then
$$a\texttt{++} \gt b$$
And so we have at least one statement that is true for this case.


We have show that in each case, at least one statement for $a\texttt{++}$.

Hence, the induction is closed.
