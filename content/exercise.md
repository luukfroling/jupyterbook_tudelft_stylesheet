# exercise 


## usage

The exercises are identified by their id, so label every exercise starting with "exercise-" followed by a unique identifier

```text
::::::{exercise} exercise 1
:label: exercise-1
Proof 1 + 1
::::::
```

The solution works in a similar manner 

```text
::::::{solution} exercise 1
:label: solution-1
I should have picked an easier example exercise...
:::
```

## examples


:::{exercise} exercise 1
:label: exercise-1

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

::::::{solution} exercise 1
:label: solution-1
Here's one solution.

```{code-block} python
def factorial(n):
    k = 1
    for i in range(n):
        k = k * (i + 1)
    return k

factorial(4)
```
::::::