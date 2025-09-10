tags: #problems


## A.1.1
What is the negation of 

'either $X$ is true, or $Y$ is true, but not both.'

We need to think 'What conditions of $X$ and $Y$ make that statement false. '

So either $X$ is false and $Y$ is false, or $X$ is true and $Y$ is true

## A.1.2
What is the negation of 

'$X$ is true if and only if $Y$ is true.'

This statement means, that if $X$ is true then $Y$ is also true and vice versa.

So we need to think 'what makes this statement false?'

Either $X$ is false when $Y$ is true, or $Y$ is false when $X$ is true.

## A.1.3
Suppose that you have shown that 
whenever $X$ is true, then $Y$ is true, 
and 
whenever $X$ is false, then $Y$ is false. 

Have you now demonstrated that $X$ and $Y$ are logically equivalent?

Saying $X$ and $Y$ are logically equivalent is the same thing as saying $X$ if and only if $Y$.

The first statement gives us $X \implies Y$.
The second statement is the contra-positive of
whenever $Y$ is true, then $X$ is true, i.e $Y \implies X$.
This is because if $Y$ is true, then $X$ cannot be false as it would cause $Y$ to be false, which contradicts the statement that $Y$ is true. Since a statement can only be either true or false, but not both, $X$ is true when $Y$ is true.

Hence $X$ and $Y$ are logically equivalent.

## A.1.4
Suppose that you have shown that whenever $X$ is true, then $Y$ is true,
and
whenever $Y$ is false, then $X$ is false.
Have you now demonstrated that $X$ is true if and only if $Y$ is true?

No since the second statement is equivalent to the first statement.

Hence, we have only demonstrated that $X \implies Y$


## A.1.5
Suppose you know that $X$ is true if and only if $Y$ is true, 
and
you know that $Y$ is true if and only if $Z$ is true. 

Is this enough to show that $X$, $Y$, $Z$ are all logically equivalent?

Yes, since both statements imply $X$ is true if only if $Z$ is true. 

## A.1.6
Suppose you know that whenever $X$ is true, then $Y$ is true;
that whenever $Y$ is true, then $Z$ is true; 
and whenever $Z$ is true, then $X$ is true.

Is this enough to show that $X$, $Y$, $Z$ are all logically equivalent?

The statements mean that
$X \implies Y$, $Y \implies Z$, and $Z \implies X$.

The third statement implies $Z \implies Y$, due to the first statement.
and so $Z \iff Y$.
The first statement implies $X \implies Z$, due to the second statement.
and so $X \iff Z$.
The second statement implies $Y \implies X$, due to the third statement.
and so $Y \iff X$

Hence, $X$, $Y$ and $Z$ are logically equivalent.
