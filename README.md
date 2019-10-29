# tech-talk-math-opt

Mathematical optimization is a programming technique that turns problems in to simple mathematical expressions, then allows a prebuilt solver to attempt to find the best (or constraint obeying) solution.

Math optimization makes sense when you have many (thousands potentially) simple components working together.


This demo will be done in a Jupyter notebook in julia.

To set up:
Install julia from julialang.org
Run from a julia terminal
```
;add IJulia JuMP GLPK CSV
```
then run
```
using IJulia; notebook()
```
choose to install jupyter.
navigate to the folder that has the s=Sudoko.ipynb and open it
