# Bits of one Ten

Ten has:
- Client side.
- Service side.

## Client side

Client side:
- I: goal is true, but state is false.
- O: goal is false, state is false.
- A: goal is true, state is true.
- E: goal is false, state is true.

User has getter and setter:
- Goal can be set:
  - Setting to I/A, goal is True: ?O.
  - Setting to O/E, goal is False: ?A.
- State can be get:
  - Getting from A/E, state is True: E?.
  - Getting from I/O, state is False: I?.

This, because E and I refer to groups AE and IO, while A and O refer to small steps IA and OE, when written as diagonals, which supports two bits like this.

## Service side

Service side has two sides:
- Short side S.
- Long side L.

Long term corresponds to short term:
- E: $\[L\]S$ - L => S (given L is True, S is True).
- A: $¬\[L\]S$ - L => ¬S (given L is True, S is False).
- O: $\[¬L\]S$ - ¬L => S (given L is False, S is True).
- I: $¬\[¬L\]S$ - ¬L => ¬S (given L is False, S is False).

I use this syntax: \[L=False\]S - this means value of S in environment, where L=False.

Short term corresponds to long term in opposite letters.

L, at this probing moment, is unset.

This type of probing resolves optimization tasks:
- For example, say you optimize value of A to maximum of B, calculated from A.
  - Your combinatoric can hardly combine values of B directly, because they hold if A has given value;
    - Yet you would like to combine it in combinatoric space of A:
      - \[A\]B; here, you can use value of B directly as if A was calculated so.
        - You resolve this multi-end combinatorics problem: you read B as if A was set.
          - Typically it involves simple combinatorics, but it's syntactically a bit tough: kind of slipping away from logic syntax.

