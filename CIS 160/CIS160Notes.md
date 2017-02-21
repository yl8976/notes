A bit of arithmetic

## Definition 1.1
An integer n

is even when
n = 2k for some integer k

and is odd when
n = 2k + 1 for some integer k

The positive integer m> 0 is n
divisor (or factor) of an integer n when

n = m * k  for some integer k

m | n => n divides m

An integer p is prime when p > 1
and p has exactly two divisors:

1 and p

Here are the first few primes:
2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43

An integer n > 1 that is not prime is called _composite_



## Proposition 1.2
An integer p > 1 is prime iff (short for "if and only if") for all positive integers r and s, if p = r * s, then r = 1 or s = 1.

## Proposition 1.3
An integer p > 1 is composite iff p = r * s for some integers r > 1 and s > 1

P iff Q
Is the same as
P => Q
and
Q => P
"=>" means "implies".

# Proofs
For now, we rely on our innate logical intuition for some simple proofs.

## Example 1.4
If the sum of two integers is even then so is their difference.

Solution: Slightly more formally:
let m and n be any two integers. If m + n is even then m - n is even.


m + n = 2k for some integer k
m = 2k - n
m - n = 2k - n - n
= 2(k - n)
Therefore m - n is also even.

Each step implies the next

## Example 1.5
Prove the following: For all integers x, if x > 1, then x^3 + 1 is composite

x^3 + 1 = (x + 1)(x^2 - x + 1)

### WTS (What To Show)
x + 1 > 1 (obvious)
and
x^2 - x + 1 > 1 (always positive; x =/= 1 so inequality is true)


## Example 1.6
Prove or disprove the following: Let x be an integer. If x > 1, then x^2 - x + 1 is a prime.

x = 2 => x^2 - x + 1 = 3
x = 3 => 7
x = 4 => 13
x = 5 => 21 (not a prime)

x = 5 is a _counterexample_.

# Sets
You already know that a set is an unordered collection of distinct elements.
We review some notation: elements of a set (**membership in a set**), set **inclusion, subset, proper (strict) subset**: standard sets of numbers: **reals, rationals, integers, and natural numbers**.

Ø => the empty set

x ∈ A  e.g. {a, e, i, o, u}
A ⊆ B  e.g. {e, i, o, a, u}
A ⊂ B (strict subset)

0 is a natural number.

## Definition 1.7
The set-builder or comprehension notation:
{x | P(x)}
{x ∈ A | P(x)}
{x | x ∈ A and P(x)}

For example,
Z+ = {x ∈ Z | x >= 1}

and

Q = {r | there exists x ∈ Z and there exists y ∈ z+ s.t. r = x/y}

Example 1.1 revisited:
n = 2k where k ∈ Z

## Definition 1.8
The **powerset** of set A, notation 2^A

2^A = {X | X ⊆ A}

e.g. if A = {q, 2} then

2^A = {{q, 2}, {q}, {2}, Ø}


## Definition 1.9
The cardinality of a finite set A, notation |A|
i.e. the number of elements in a set

|{q, 2, N^2}| = 3
|R| = ?
