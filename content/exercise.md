# exercise 

``{exercise}
:label: my-exercise

Recall that $n!$ is read as "$n$ factorial" and defined as
$n! = n \times (n - 1) \times \cdots \times 2 \times 1$.

There are functions to compute this in various modules, but let's
write our own version as an exercise.

In particular, write a function `factorial` such that `factorial(n)` returns $n!$
for any positive integer $n$.
```

:::{exercise}
:label: my-definition

The *economical expansion problem* (EEP) for
$(A,B)$ is to find a semi-positive $n$-vector $p>0$
and a number $\beta\in\mathbb{R}$, such that

$$
\begin{align*}
&\min_{\beta} \hspace{2mm} \beta \\
&\text{s.t. }\hspace{2mm}Bp \leq \beta Ap
\end{align*}
$$
:::