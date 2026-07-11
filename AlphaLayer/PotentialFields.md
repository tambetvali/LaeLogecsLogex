# Potential Field of Logex and Logecs

Laegna Logex is able to track potential fields with this syntax:

```prolog
[StateExtension]StateExpression.
```

Give that you have your logical system with these values set:
- a = True.
- b = False.

Now you can query `[c = True]d`.

In case c is set to true, this expression:
- *Get*: Receives value of d, given that c would be True.
  - Fork: branch the new logic system to new thread.
  - Associate the value only in new thread.
  - Return the result.
  - Garbage Collect the thread.
- *Set*: `(c = True) => d`

c and d do not affect a and b, but static logical system can extend it's state and d can *use* a and b, which are evaluated in it's fork; for example this optimizer could maximize d, given even events which would happen later, and then optimize something what follows a and b.

These two operations, if controller and optimizer master them as well, allow multi-end combinations:
- Paradox of linearization of linear-exponent systems.
- Paradox fo understanding, how value indirectly or directly changes itself.

For example, let's say:
- A => not A.
  - Setting A now set not A.
  - `[A]A = not A` is the general expression.
  - If anythinf is followed / implied by A, it will be part of `A[A]`.
  - Object represented: point acceleration, where:
    - OA values are instantly set.
    - IE values are received.
- Let's check logic of the sentence:
  - `[not A]A`.
    - Whether, in environment where A is set to not A, value of A can be set:
      - A, if it was set to A, would return I, and if set to O, would return E:
        - IA and EO are logical errors we can express and understand.
        - Anything in code and logic could do something based on A (depend on A) and set A to other value (inconsistent A).

Which cases can be seeked:
- Seeking variables which were not set:
  - Seeking variables which were not set, as in previous example, always works.
- In imperative mode:
  - Set A as configuration point, where single value is changed:
    - Each change changes the logical context: set time = time + 1 (see this syntax in ChucK, a strongly-timed music programming language, to see what I mean).
      - time is not logical variable, but logic window.
      - time, thus, needs to be set up as imperative, not logical variable.
      - "time" has then:
        - single definition point.
        - when changed, it affects whole chain of implications.
        - implications of it's old value are lost.
- Global and local
  - Set global logic in way that local values are not set.
  - Local values can query global states, and estimate their assimilation to it.
- Fallback
  - Local script can have variables evaluated, but this evaluation is not decided as it's probing branch of other, deeper order question.
  - It runs the evaluation from it's fallback position:
    - In beginning of code, evaluate what value you give to a, based on later, more complete logic which has a set, without having a yet.
    - Evaluation for example questions:
      
      `[a = True]d` - if it sets a to True, can it expect d?

      Code, later, can calculate d on a. Logical-imperative mix or logical language or symbolic system in imperative, each could follow this logically and make sure a is set if a => d.
      - `State-A => State-D => Goal-A` - if True state of A yields True state of D, True state of A should be Goal.

