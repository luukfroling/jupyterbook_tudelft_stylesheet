# Jyputer Book 2 stylesheet: TUDelft theme

:construction: This is still a work in progress :construction:

A JB2 implementation of the TU Delft stylesheet originally written as a sphinx extension which can be found <a href="https://github.com/TeachBooks/Sphinx-TUDelft-theme?tab=readme-ov-file"> here </a>. It is important to note this stylesheet can be used, however as jupyter book 2 is still in early development some features originally included in the extension have not been implemented yet.

## What does it do? 

This extension applies styling changes, being

- particular colours (different colors for light and dark themes) for:
    - admonitions (e.g. hint, note, tip, error, etc.),
    - proofs (e.g. theorem, axiom, lemma, corollary, etc.),
    - exercises,
    - buttons,
    - custom components,
    - $\LaTeX$

## installation 

To use this style, download the .css file and follow the steps described in the JB2 documentation <a href="https://mystmd.org/guide/website-style"> here </a>

## example book and usage

How to use the specific components and styles can be found <a href="https://luukfroling.github.io/jupyterbook_tudelft_stylesheet/"> here </a>

### Admonitions: 

Admonitions can by styled by applying the class of the chosen style 

```text
::::::{admonition} The one with the custom titles
:class: admonition
It's got a certain charm to it. (admonition)
::::::
```

### Button

The button works as normal

```text
{button}`MyST-MD GitHub <example.com>`
```

### Exercise and solution

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

### Proofs (prf:)

All of these subcomponents can be used similar to the exercise and solution, by the use of a label. The first part of the label specifies which component style must be applied while the second part is a unique identifier. e.g. 'proposition-1', 'corollary-7392'. 

```text
::::::{prf:proposition}
:label: proposition-1
This is a dummy proposition directive.
::::::
```



## what does it not do? 
- apply TUDelft logo
- Badges have not been implemented in JB 2 yet (as far as I know) 
- There is only a single button class
- All elements starting with prf: as well as the exercises are being identified by their id. This is because so far it is not possible to attach custom css classes. 
- grasple is not included
- some originally referenced icons are not available yet
- For prf:proof there is a title difference with the JB1 version 
- custom components (incl solution link)
- make dropdown in menu tudelft blue too.
- versionadded and deprecated not implemented


