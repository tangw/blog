---
title: "Solving Cryptarithms"
categories: [Math]
tags: [Puzzle, Cryptarithm]
date: 2024-01-20 23:06:24
mathjax: true
toc: true
---

# Introduction #

**Cryptarithm**, also known as **alphametic**, is a mathematical
puzzle where the digits of numbers in a mathematical equation are
replaced by letters of the alphabet. The mathematical equation in a
cryptarithm is commonly a basic arithmetic calculation such as <span
style="color:red">addition</span>, <span
style="color:blue">subtraction</span>, <span
style="color:green">multiplication</span>, or <span
style="color:orange">division</span>. The objective is to recover the
original equation by identifying the value of each letter that
satisfies the equation.

In a standard cryptarithm, **each letter must represent a unique
digit** whenever it occurs in the equation, and **the leading digit
must not equal zero** unless stated otherwise. A good puzzle should
have a unique solution, and the letters should make up a phrase.

# Examples #

Solving a cryptoarithm puzzle by hand usually requires a mix of
logical reasoning, simple arithmetic, and exhaustive testing of
possibilities. In this post, let us solve some cryptarithms in each
category of the arithmetic operations. For the convenience of our
discussion, columns in equations are numbered from the right to the
left, starting from one as a convention.

## Addition ##

Our first example in <span style="color:red">addition</span> was
created by Henry Dudeney in 1924.[^1]

### SEND + MORE = MONEY ###

The arithematic equation of this puzzle is given below, where there is
only one letter $M$ in column 5.

<span style="color:red">
$$
\begin{matrix}
  & & \text{S} & \text{E} & \text{N} & \text{D} \\
+ & & \text{M} & \text{O} & \text{R} & \text{E} \\
\hline
& \text{M} & \text{O} & \text{N} & \text{E} & \text{Y}
\end{matrix}
$$
</span>

One possible solution to the above puzzle is laid out in details with the
following steps:

1. From column 5, we know that <span style="color:red">**M =
   1**</span> since it is the only carry-over possible from the sum of
   two single digits in column 4;
2. In column 4, since $S + M$ generates a carry, $O$ must be less than
     $M$. Therefore, <span style="color:red">**O = 0**</span>;
3. Since $O = 0$, either $S = 8$ or $S = 9$, depending on whether
   there is a carry from column 3. If there was a carry from column 3,
   $N$ must be less than zero, which is impossible since $O =
   0$. Therefore, there is no carry from column 3, and hence <span
   style="color:red">**S = 9**</span>;
4. In column 3, $E \ne N$ must be true as they represent different
   digits. Since $O = 0$, there must be a carry from column 2. So $E +
   1 = N$;
5. In column 2, if there was no carry from column 1, $N + R = 10 +
   E$. From the previous step, we know that $E + 1 = N$. So we have
   $E + 1 + R = 10 + E$, or $R = 9$, which is impossible since $S =
   9$. Therefore, there must be a carry from column 1. So <span
   style="color:red">**R = 8**</span>;
6. To produce a carry from column 1, we must have $D + E = 10 + Y$;
7. Because either $Y \ne 0$ or $Y \ne 1$, $Y \geq 2$, and $D + E \geq
   12$. The possible pair of choice could be either $(5, 7)$ or $(6,
   7)$. So either $D = 7$ or $E = 7$. If $E = 7$, $N = 8$ must be true
   since $E + 1 = N$, which is impossible. So <span
   style="color:red">**D = 7**</span>;
8. Since $D = 7$, $E \ne 6$ because otherwise $N = E + 1$ would be
   seven, which is impossible. Therefore, <span style="color:red">**E
   = 5**</span> and <span style="color:red">**N = 6**</span>;
9. Finally, from $D + E = Y + 10$, we know that <span
   style="color:red">**Y = 2**</span>.

### KYOTO + OSAKA = TOKYO ###

<span style="color:red">
$$
\begin{matrix}
  & \text{K} & \text{Y} & \text{O} & \text{T} & \text{O} \\
+ & \text{O} & \text{S} & \text{A} & \text{K} & \text{A} \\
\hline
& \text{T} & \text{O} & \text{K} & \text{Y} & \text{O}
\end{matrix}
$$
</span>

### WATER + BOTTLE = THROAT ###

<span style="color:red">
$$
\begin{matrix}
  & & \text{W} & \text{A} & \text{T} & \text{E} & \text{R} \\
+ & \text{B} & \text{O} & \text{T} & \text{T} & \text{L} & \text{E} \\
\hline
& \text{T} & \text{H} & \text{R} & \text{O} & \text{A} & \text{T}
\end{matrix}
$$
</span>

### CROSS + ROADS = DANGER ###

### ADJUST + NAUSEA = SENTRY ###

[^1]: H. E. Dudeney, in Strand Magazine vol. 68 (July 1924), pp. 97
    and 214.
