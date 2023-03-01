# PLONK Arithmetisation Assignment

Calculate polynomials used in PLONK Arithmetisation. Fill in the values in this markdown to complete the assignment

The polynomial used in this assignment is: $$x^3 + x == 2$$

**Note: You can use the code from your `Lagrange Polynomial Assignment` to complete this**

## Gates

Complete the gates below, the first one is completed for you

### Gate 1

$$x_1 * x_1 = x_2$$

### Gate 2

### Gate 3

### Gate 4

## Assignments
Complete the assignment vectors, let $x_1 = 1$

$$\vec{a} = [1,?,?,?]$$

$$\vec{b} = [1,?,?,?]$$

$$\vec{c} = [1,?,?,?]$$

## Selectors

Fill in the below table for the values of $q_L$, $q_R$, $q_O$, $q_M$ and $q_C$, satisfying the equation: 

$$q_L * a + q_R * b + q_O * c + q_M * a*b + q_C = 0$$


|$q_L$|$q_R$|$q_O$|$q_M$|$q_C$|
|-----|-----|-----|-----|-----|
|  ?  |  ?  |  ?  |  ?  |  ?  |
|  ?  |  ?  |  ?  |  ?  |  ?  |
|  ?  |  ?  |  ?  |  ?  |  ?  |
|  ?  |  ?  |  ?  |  ?  |  ?  |

## Domain

We will use the base field of $\mathbb{F_{17}}$ and the domain consisting of roots of unity

Fourth roots of unity in $\mathbb{F_{17}}$:
$$H: {1, 4, 16, 13}$$

## Cosets

$$k_1 = 2$$

$$k_2 = 3$$

$$k_{1}H: {?, ?, ?, ?}$$

$$k_{2}H: {?, ?, ?, ?}$$

## Interpolating Polynomials

$$f_a(x) = ?x^3 + ?x^2 + ?x + ?$$

$$f_b(x) = ?x^3 + ?x^2 + ?x + ?$$

$$f_c(x) = ?x^3 + ?x^2 + ?x + ?$$

$$q_{L}(x) = ?x^3 + ?x^2 + ?x + ?$$

$$q_{R}(x) = ?x^3 + ?x^2 + ?x + ?$$

$$q_{O}(x) = ?x^3 + ?x^2 + ?x + ?$$

$$q_{M}(x) = ?x^3 + ?x^2 + ?x + ?$$

$$q_{c}(x) = ?x^3 + ?x^2 + ?x + ?$$

## Copy Constraints

| LHS | RHS | Domain of LHS | Domain of RHS |
|-----|-----|---------------|---------------|
|$a_1$|  ?  |       ?       |       ?       |
|$a_2$|  ?  |       ?       |       ?       |
|$a_3$|  ?  |       ?       |       ?       |
|$a_4$|  ?  |       ?       |       ?       |
|$b_1$|  ?  |       ?       |       ?       |
|$b_2$|  ?  |       ?       |       ?       |
|$b_3$|  ?  |       ?       |       ?       |
|$b_4$|  ?  |       ?       |       ?       |
|$c_1$|  ?  |       ?       |       ?       |
|$c_2$|  ?  |       ?       |       ?       |
|$c_3$|  ?  |       ?       |       ?       |
|$c_4$|  ?  |       ?       |       ?       |

## Copy Constraints Polynomials

$$S_{{\sigma}_1} = ?x^3 + ?x^2 + ?x + ?$$

$$S_{{\sigma}_2} = ?x^3 + ?x^2 + ?x + ?$$

$$S_{{\sigma}_3} = ?x^3 + ?x^2 + ?x + ?$$

## Evaluation

-   Clone this repo.

    ```
    git clone CLONE_URL
    ```

-   Create a new branch with your name. You can use the following command

    ```
    git checkout -b my-name
    ```

-   Fill in the values in this file with your solution

-   Create a pull request from your branch to the main branch of the repo

-   Since this assignment is manually evaluated we will provide feedback on your solution in form of pull request comments
