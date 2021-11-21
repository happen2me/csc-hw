# CSC Assignment 4

Hui Zheng 		03736480

Qianyun Li		03736115

Yuanchun Shen 	03745935

## Exercise 13

#### (a) 

**Which groups are decisive? Are there any weak dictators? Is there an oligarchy? Is there a collegium?**

- Five permanent members and any other two members form a decisive group.
- There is not any weak dictator or oligarchy.
- Five permanent members form a collegium.

#### (b)

**Which groups are decisive? Are there any weak dictators? Is there an oligarchy? Is there a collegium?**

> Reference: *Positive Political Theory I: Collective Preference* Page 41

Suppose we have $r$ alternatives $\{x_1, x_2, ..., x_r\}$ such that $x_1 P x_2, x_2 P x_3, ..., x_{r-1} P x_r$. Since there are only 6 other members, one permanent member must strictly prefer $x_1$ over $x_2$. We assume this member to be $1$. $1$ must weakly prefer $x_j$ to $x_{j+1}$ for $j=2,3,...,r-1$ to allow $x_2 P x_3, x_3 P x_4, ..., x_{r-1} P x_r$. By transitivity, $1$ must strictly prefer $x_1$ over $x_r$. Because $1$ is a permanent member, the final relationship does not allow $x_r P x_1$. This implies that the base relation is acyclic.

## Exercise 14

#### (a)

**Provide a profile where $f_{narrow}$ and $f_{broad}$ differ**

Consider the following profile, where $A = \{a, b\}$

| 1    | 1    | 1    |
| ---- | ---- | ---- |
| a    | c    | c    |
| c    | d    | d    |
| d    | b    | b    |
| b    | a    | a    |

In this case, $f_{narrow}=b$, $f_{broad}=a$

#### (b)

**Does $f_{narrow}$ satisfy Pareto-optimality? IIA? Transitive rationalizability?**

- $f_{narrow}$ satisfies Pareto-optimality.

  Assume $a P_i b$ for all $i \in N$, $a,b \in A$. Then $s(a, A) - s(b, A) \geq N$, $b$ cannot be in $f_{narrow}$

- $f_{narrow}$ satisfies IIA

  For two profiles that $R_{i|A}=R'_{i|A}, \forall i \in N$, $\forall a \in A, s(a,A)$ are the same. Therefore, $f_{narrow}(R_N, A) = f_{narrow}(R'_N, A)$.

- $f_{narrow}$ does not  satisfy transitive rationalizability

  It does not satisfy strong expansion:

  Consider the following profile:

  | 1    | 1    | 1    |
  | ---- | ---- | ---- |
  | a    | c    | c    |
  | c    | b    | b    |
  | b    | a    | a    |
  |      |      |      |

  $A = \{a, b, c, d\}, B=\{a, b\}$.

  $s(a, A) = 3, s(b, A) = 2, f_{narrow}(A) = {}$

  - Contraction

    Assume $B \subseteq A$ and $f_{narrow}(R, A) \cap B \neq \emptyset$. Let $x \in f_{narrow}(R, A) \cap B$. 

    Because $x \in f_{narrow}(R, A)$, $s(x, A) \geq s(b, A), \forall b \in A\backslash \{x\}$. Because $B \subseteq A$, 

    $s(x, A) = s(x, B) + s(x, A\backslash B)$

    $s(x, A\backslash B) = \sum_{i\in N} |\{y\in A\backslash B, y P_i x\}|$

    $s(b, A\backslash B) = \sum_{i\in N} |\{y\in A\backslash B, y P_i b\}|$

    

  - Stronger expansion

    

    

#### (c)

**Does $f_{broad}$ satisfy Pareto-optimality? IIA? Transitive rationalizability?**

- $f_{broad}$ satisfies Pareto-optimality

  Assume $a P_i b$ for all $i \in N$, $a,b \in A$. Then $s(a, A) - s(b, A) \geq N$, $b$ cannot be in $f_{broad}$

- $f_{broad}$ does not satisfy IIA

  Consider the profile $P_1$

  | 1    | 1    | 1    |
  | ---- | ---- | ---- |
  | a    | c    | c    |
  | c    | d    | d    |
  | d    | b    | b    |
  | b    | a    | a    |

  And the profile $P_2$

  | 1    | 1    | 1    |
  | ---- | ---- | ---- |
  | c    | c    | c    |
  | d    | d    | d    |
  | a    | b    | b    |
  | b    | a    | a    |

  Where $A=\{a, b\}$, $P_1 and P_2$ only differs in infeasible alternatives, but $f(P_1) = \{a\}$, $f(P_2) = \{b\}$. This shows that it does not  satisfy IIA.

## Exercise 15

### (a) 

An alternative x is extremal in a preference profile $R_N$ implies

x P_i y for all y ∈ U\\{x} and i ∈ N, or

y P_i x for all y ∈ U\\{x} and i ∈ N

Because f satisfies Pareto-optimality: 

for all R_N, x, and y: x P_i y implies x P y.

So x is extremal in $R_N$ implies (x P y) or (y P x), for all y ∈ U\\{x}.

Then x is extremal in a binary relation R.

### (b)





 
