# Blatt 3

### Exercise 9

#### (a)

- neutrality & anonymity $\nRightarrow$ positive responsiveness

  A SCF that always favors the least voted.

- positive responsiveness & neutrality  $\nRightarrow$ anonymity 

  A SCF that uses asymmetric Borda score but with one user has double the weight.

- positive responsiveness & anonymity  $\nRightarrow$ neutrality 

  A SCF that in a re-election, newcomers have to earn more than 3/5 of the votes to take office.

#### (b)

- IIA, Pareto-optimality, non-dictatorship $\nRightarrow$ transitive rationalizability

  ~~A SCF that favors alternatives with odd votes~~

  A SCF that favors most top voted.

- transitive rationalizability, IIA, Pareto-optimality  $\nRightarrow$ non-dictatorship

  A SCF that always favors voter k's decision.

- non-dictatorship, transitive rationalizability, IIA  $\nRightarrow$ Pareto-optimality

  

- Pareto-optimality, non-dictatorship, transitive rationalizability $\nRightarrow$ IIA

### Exercise 10

#### (a) No anonymous, neutral, and positive responsive SCF is rationalizable by a transitive relation when there are m ⩾ 3 alternatives and n ⩾ 2 voters

Assume an anonymous, neutral and positive responsive SCF $f$ is rationalizable by a transitive relation $R$.

Consider the following profile:

| 1    | 1    |
| ---- | ---- |
| a    | b    |
| b    | c    |
| c    | a    |

Lemma 2 ($S$ is rationalizable iff it is rationalized by its base relation) implies that $R = R_f$

May's theorem (Majority rule is the only SCF on two  alternatives that satisfies anonymity, neutrality, and positive  responsiveness) implies that $R_f = R_M$

In this case, $S(\{ b, c\}) = \{b\}, S(\{a, b, c\})=\{a, b\}, S(\{ b, c\}) \neq S(\{a, b, c\})$, 

$R_M$ can not rationalize $f$.

To account for $m>3$ and $n>2$, we can add  indifferent voters and bottom-ranked alternatives

#### (b)  Assume voters can only report strict preferences (i.e., no indifferences between alternatives are allowed). Show that no anonymous, neutral, and positive responsive SCF is rationalizable if there are m = 4 alternatives and n = 4 voters, but there is such an SCF if there are m = 3 alternatives and n = 4 voters.

- When $m=4$ and $n =4 $

  Assume an anonymous, neutral and positive responsive SCF $f$ is rationalizable by a transitive relation $R$.

  Consider the following profile:
  

  | 1    | 1    | 1    | 1    |
  | ---- | ---- | ---- | ---- |
  | a    | b    | c    | d    |
  | b    | c    | d    | a    |
  | c    | d    | a    | b    |
  | d    | a    | b    | c    |

  Lemma 2  implies that $R = R_f$

  May's theorem implies that $R_f = R_M$

  $R_M$ is cyclic therefore cannot rationalize $f$

$$
a \leftarrow b \\ 
\downarrow \  \ \  \uparrow  \\ 
d \rightarrow c
$$

- When $m=3$ and $n=4$

### Exercise 11

### Exercise 12

**Show that for |U| = m and |N| = n, there is an anonymous, neutral, Pareto-optimal, and resolute SCF for strict preferences if and only if n cannot be divided by any q ∈ N with 2 ⩽ q ⩽ m**

Forward:

Suppose $n$ can be divided by $q$ with $2 \leq q \leq m$. We can divide $n$ voters to $q$ group $G_1, G_2, ..., G_q$, each contains $\frac{n}{q}$ voters. We take $q$ alternatives from $U$: $U_q = \{u_1, u_2, ..., u_q\}$ , we represent the reset alternatives as $U\backslash U_q$, take construct a profile $P$ as below:

| n/q (G1)          | n/q (G2)          | n/q (G3)          | ...  | n/q (Gn)          |
| ----------------- | ----------------- | ----------------- | ---- | ----------------- |
| $u_1$             | $u_2$             | $u_3$             | ...  | $u_q$             |
| $u_2$             | $u_3$             | $u_4$             | ...  | $u_1$             |
| $u_3$             | $u_4$             | $u_5$             | ...  | $u_2$             |
| ...               | ...               | ...               | ...  |                   |
| $u_q$             | $u_1$             | $u_2$             | ...  | $u_{q-1}$         |
| $U\backslash U_q$ | $U\backslash U_q$ | $U\backslash U_q$ | ...  | $U\backslash U_q$ |

Assume $U'_q$ as a permutation of $U_q$, $U' = U_q' + U\backslash U_q$.  $u_i$ in $U$ corresponds to $u_i'$ in $U'$.

By neutrality, $x_i \in f(U)$ implies $x_i' \in f(U')$. By anonymity, $x_i \in f(U)$ implies $x_i \in f(U')$. By Pareto-optimal, $x_i \in U\backslash U_1$ are never selected. This only satisfies when $f(U) = \{u_1, u_2, ..., u_q\}$. Because $q \geq 2$, it can not be resolute.

Backward:

Suppose $n$ can not be divided by $q$. Pair wise majority is  anonymous, neutral, Pareto-optimal, and resolute because we can not fabricate two alternatives with the same high score.

