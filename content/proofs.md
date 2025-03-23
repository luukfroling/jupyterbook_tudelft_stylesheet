# Proofs

## prf:theorem

::::::{prf:theorem} Orthogonal-Projection-Theorem
:label: theorem-1
Given $y \in \mathbb R^n$ and linear subspace $S \subset \mathbb R^n$,
there exists a unique solution to the minimization problem

```{math}
\hat y := \arg\min_{z \in S} \|y - z\|
```

The minimizer $\hat y$ is the unique vector in $\mathbb R^n$ that satisfies

* $\hat y \in S$

* $y - \hat y \perp S$


The vector $\hat y$ is called the **orthogonal projection** of $y$ onto $S$.
::::::

## prf: criterion

::::::{prf:criterion} Weyl's criterion
:label: criterion-1
Weyl's criterion states that the sequence $a_n$ is equidistributed modulo $1$ if
and only if for all non-zero integers $m$,

```{math}
\lim_{n \rightarrow \infty} \frac{1}{n} \sum_{j=1}^{n} \exp^{2 \pi i m a_j} = 0
```
::::::

## prf:lemma

::::::{prf:lemma}
:label: lemma-1
If $\hat P$ is the fixed point of the map $\mathcal B \circ \mathcal D$ and $\hat F$ is the robust policy as given in [(7)](https://python-advanced.quantecon.org/robustness.html#equation-rb-oc-ih), then

```{math}
:label: rb_kft

K(\hat F, \theta) = (\theta I - C'\hat P C)^{-1} C' \hat P  (A - B \hat F)
```
::::::

## prf:proposition

::::::{prf:proposition}
:label: proposition-1
This is a dummy proposition directive.
::::::

## prf:corollary

::::::{prf:corollary}
:label: corollary-1
If $A$ is a convergent matrix, then there exists a matrix norm such
that $\vert \vert A \vert \vert < 1$.
::::::

## prf:observation 

::::::{prf:observation}
:class: doesthisclasswork
:label: observation-1
This is a dummy observation directive.
::::::


## prf:property 

::::::{prf:property}
:class: doesthisclasswork
:label: property-1
This is a dummy property to illustrate the directive.
::::::


## prf:example 

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

## prf:assumption

::::::{prf:assumption}
:label: assumption-1
This is a dummy assumption directive.
::::::