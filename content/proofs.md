# Proofs

## observation 

::::::{prf:observation}
:class: doesthisclasswork
:label: observation-1
This is a dummy observation directive.
::::::


## property 

::::::{prf:property}
:class: doesthisclasswork
:label: property-1
This is a dummy property to illustrate the directive.
::::::


## example 

::::::{prf:example}
:class: pleasework
:label: example-1
Next, we shut down randomness in demand and assume that the demand shock
$\nu_t$ follows a deterministic path:


```{math}
\nu_t = \alpha + \rho \nu_{t-1}
```

Again, we’ll compute and display outcomes in some figures

```python
ex2 = SmoothingExample(C2=[[0], [0]])

x0 = [0, 1, 0]
ex2.simulate(x0)
```
::::::

## prf:proof

:::{prf:proof}
:class: proof
:label: proof-1

We'll omit the full proof.

But we will prove sufficiency of the asserted conditions.

To this end, let $y \in \mathbb R^n$ and let $S$ be a linear subspace of $\mathbb R^n$.

Let $\hat y$ be a vector in $\mathbb R^n$ such that $\hat y \in S$ and $y - \hat y \perp S$.

Let $z$ be any other point in $S$ and use the fact that $S$ is a linear subspace to deduce

```{math}
\| y - z \|^2
= \| (y - \hat y) + (\hat y - z) \|^2
= \| y - \hat y \|^2  + \| \hat y - z  \|^2
```

Hence $\| y - z \| \geq \| y - \hat y \|$, which completes the proof.
:::

##  prf:definition

::::::{prf:definition}
:class: customClass
:label: definition-1
The *economical expansion problem* (EEP) for
$(A,B)$ is to find a semi-positive $n$-vector $p>0$
and a number $\beta\in\mathbb{R}$, such that

$$
&\min_{\beta} \hspace{2mm} \beta \\
&\text{s.t. }\hspace{2mm}Bp \leq \beta Ap
$$
::::::

## prf:axiom

::::::{prf:axiom} Completeness of $\mathbb{R}$
:label: axiom-1
Every Cauchy sequence on the real line is convergent.
::::::

## prf:conjecture

::::::{prf:conjecture} Fake $\gamma$ conjecture
:label: conjecture-1
This is a dummy conjecture to illustrate that one can use math in titles.
::::::

## assumption

::::::{prf:assumption}
:label: assumption-1
This is a dummy assumption directive.
::::::