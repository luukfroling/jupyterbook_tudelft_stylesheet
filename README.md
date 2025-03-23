# TU Delft stylesheet JB2

A JB2 implementation of the TU Delft stylesheet originally written for JB1 (https://github.com/TeachBooks/Sphinx-TUDelft-theme?tab=readme-ov-file). 

:construction: This is still a work in progress :construction:

Several features have not been implemented yet. 

## What does it do

This extension applies styling changes, being

- particular colours (different colors for light and dark themes) for:
    - admonitions (e.g. hint, note, tip, error, etc.),
    - proofs (e.g. theorem, axiom, lemma, corollary, etc.),
    - exercises,
    - buttons,
    - custom components,
    - $\LaTeX$

## installation 

To use this style, download the .css file and follow the steps described here https://mystmd.org/guide/website-style

## example book and usage

How to use the specific components and styles can be found here (link example book)

## what does it not do (TODO)

- set standard primary and secondary colours of the book
- Badges have not been implemented in JB 2 yet (as far as I know) 
- There is only a single button class
- All elements starting with prf: as well as the exercises are being identified by their id. This is because so far it is not possible to attach custom css classes. 
- grasple is not included
- some originally referenced icons are not available yet
- For prf:proof there is a title difference with the JB1 version 
- custom components (incl solution link)


