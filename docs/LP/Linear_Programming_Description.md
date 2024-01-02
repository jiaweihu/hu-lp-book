# Linear Programming Description

A linear program deals with minimization or a maximization problem depending on whether the objective function is to be minimized or maximized. The constraints can either be inequalities (≤ or ≥) or equalities. Variables might be unrestricted (i.e. they can take positive or negative values) or be restricted (i.e. can only be nonnegative).\

## Mathematical Representation
A general linear program in the decision variables x1, . . . , xn is
therefore of the following form:

Maximize or Minimize
$z = c_0 + c_1x_1 + . . . + c_nx_n$

subject to:

$$
a_{i1}x_1 + a_{i2}x_2 + . . . + a_{in}x_n\quad
\begin{matrix}
  \leq\\
  \geq\\
  =
 \end{matrix}
\quad b_i\quad\quad i=1,...,m
$$

$$
x_i =
  \begin{cases}
    \geq 0\\
    \leq 0
  \end{cases}
\quad\quad j=1,...,n
$$

The problem data in this linear program consists of $c_j (j = 0, . . . , n)$, $b_i (i = 1, . . . , m)$ and $a_{ij}
(i = 1, . . . , m, j = 1, . . . , n)$. $c_j$ is referred to as the objective function coefficient of $x_j$ or, more simply, the cost coefficient of $x_j$ . $b_i$
is known as the right-hand-side (RHS) of equation i. Notice
that the constant term $c_0$ can be omitted without affecting the set of optimal solutions.

## UseCase: The Diet Problem

In the diet model, a list of available foods is given together with the nutrient content and the cost
per unit weight of each food. A certain amount of each nutrient is required per day. For example,
here is the data corresponding to a civilization with just two types of grains (G1 and G2) and three
types of nutrients (starch, proteins, vitamins):

|              |Starch |Proteins |Vitamins |Cost ($/kg)|
|---           | ---   | ---     |   ---   |   ---     |
|G1            |5      |4        |2        |0.6        |
|G2            |7      |2        |1        |0.35       |
|requirement   |8      |15       |3        |           |

Nutrient content and cost per kg of food.

The requirement per day of starch, proteins and vitamins is 8, 15 and 3 respectively. The problem
is to find how much of each food to consume per day so as to get the required amount per day of
each nutrient at minimal cost.

When trying to formulate a problem as a linear program, the first step is to decide which
*decision variables* to use. These variables represent the unknowns in the problem. In the diet
problem, a very natural choice of decision variables is:
- $x_1$: number of units of grain G1 to be consumed per day,
- $x_2$: number of units of grain G2 to be consumed per day.

The next step is to write down the *objective function*. The objective function is the function to be
minimized or maximized. In this case, the objective is to minimize the total cost per day which is
given by $z = 0.6x_1 + 0.35x_2$ (the value of the objective function is often denoted by z).

Finally, we need to describe the different constraints that need to be satisfied by $x_1$ and $x_2$.
* $x_1$ and $x_2$ must certainly satisfy $x_1$ ≥ 0 and $x_2$ ≥ 0. Only nonnegative amounts of food can be eaten! These constraints are referred to as nonnegativity constraints. 
* Moreover, not all possible values for $x_1$ and $x_2$ give
rise to a diet with the required amounts of nutrients per day. The amount of starch in $x_1$ units of
G1 and $x_2$ units of G2 is 5$x_1$ + 7$x_2$ and this amount must be at least 8, the daily requirement of
starch. Therefore, $x_1$ and $x_2$ must satisfy 5$x_1$ + 7$x_2$ ≥ 8. 
* Similarly, the requirements on the amount
of proteins and vitamins imply the constraints 4$x_1$ + 2$x_2$ ≥ 15 and 2$x_1$ + $x_2$ ≥ 3.

This diet problem can therefore be formulated by the following linear program:

Minimize 
$$z = 0.6x_1 + 0.35x_2$$

Subject to:

$$5x_1 + 7x_2 ≥ 8$$
$$4x_1 + 2x_2 ≥ 15$$
$$2x_1 + x_2 ≥ 3$$
$$x_1 ≥ 0$$
$$x_2 ≥ 0$$

A solution x = ($x_1$, $x_2$) is said to be feasible with respect to the above linear program if it satisfies all the above constraints. The set of feasible solutions is called the feasible space or feasible region. A feasible solution is optimal if its objective function value is equal
to the smallest value z can take over the feasible region.

