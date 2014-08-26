# Continuous 1D Cellular Automata Tutorial #

In a continuous cellular automaton, each cell has a gray level between [0,1] as its state. 

In the cellular automaton shown, the transition function f computes the state of the cell *s*, at evolution step *t*+1, as the fractional part of the mean of its neighborhood's gray levels at evolution step *t* plus a constant *k*.

This rule is described on [page 159 of Wolfram's NKS](http://www.wolframscience.com/nksonline/page-159)

See Mathematica notebook for more details and demo. 

![zerodot0081_500steps.png](https://bitbucket.org/repo/yoAnAE/images/2436032968-zerodot0081_500steps.png)
*k = 0.009, t = 500, initial condition = "one cell"*

![zerodot0081_500steps_randomIC.png](https://bitbucket.org/repo/yoAnAE/images/2042167240-zerodot0081_500steps_randomIC.png)
*k = 0.009, t = 500, initial condition = "random"*