tags: #statement 

## Statement

Let $a$ be a positive number. Then there exists exactly one natural number $b$ such that $b\texttt{++} = a$

## Proof
We induct on $a$.

### Base case
By [[Definition - positive natural numbers]],  $a \neq 0$.

Therefore, the base case must start from the next natural number, $a = 0\texttt{++}$, where, 
$$b\texttt{++} = 0\texttt{++}$$
By [[Axiom - injectivity of successor]], we conclude $b = 0$.
Thus, there exists exactly one $b$ for which the statement holds in the base case.
This proves the base case.
### Induction step
We assume the statement holds for $a$. And so we must prove the statement for $a\texttt{++}$, giving,$$b\texttt{++} = a\texttt{++}$$
By [[Axiom - injectivity of successor]], this gives, 
$$b = a$$
By [[Axiom - principle of mathematical induction]], the induction is closed and the statement is proven.