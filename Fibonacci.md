# About Fibonacci sequence

## What is fibonacci sequence?

- The fibonacci sequence is the series of numbers
> - for example : 0, 1, 1, 2, 3, 5, 8,...
- The next number is found by adding up the two numbers before it

## The rule
- The Rule is xn = xn−1 + xn−2

## The code on python
> def fib(n):
>   _curr, _next = 0, 1
>    for _ in range(n):
>        _curr, _next = _next, _curr + _next
>    return _curr
