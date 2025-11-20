### $\text{Exercise 1.}$

Let's proceed by direct proof.

Suppose $n$ has $k$ digits, so $n = \sum_{i=0}^k a_i \times 10^i$.

If the sum of the digits of $n$ is divided by $9$, so:
$$
\sum_{i=0}^k a_i = 9l
$$
An obvious lemma:
$$
\begin{aligned}
9 &\mid (10^i-1)
\end{aligned}
$$
So,
$$
\sum_{i=0}^k a_i \times (10^i - 1) = \sum_{i=0}^k a_i \times 9 \times t_i = 9 \times \sum_{i=0}^k a_i \times t_i
$$
Then,
$$
\sum_{i=0}^k a_i \times 10^i = \sum_{i=0}^k a_i \times (10^i-1) + \sum_{i=0}^k a_i = 9\times (l + \sum_{i=0}^k a_i \times t_i)
$$
It means $n$ is divided by $9$

### $\text{Exercise 2.}$

Let's proceed by contraposition.

Suppose $a$ is odd, so:
$$
a = 2k+1 \quad k\in \mathbb{Z}
$$
and,
$$
a^2 = 4k^2 + 4k + 1 = 2(2k^2 + 2k) + 1
$$
So $a^2$ is odd.

And this means if $a^2$ is even then $a$ is even.