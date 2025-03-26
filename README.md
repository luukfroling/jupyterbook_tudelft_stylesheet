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

## what does it not do? 

- set standard primary and secondary colours of the book
- Badges have not been implemented in JB 2 yet (as far as I know) 
- There is only a single button class
- All elements starting with prf: as well as the exercises are being identified by their id. This is because so far it is not possible to attach custom css classes. 
- grasple is not included
- some originally referenced icons are not available yet
- For prf:proof there is a title difference with the JB1 version 
- custom components (incl solution link)
- make dropdown in menu tudelft blue too.
- versionadded and deprecated not implemented


