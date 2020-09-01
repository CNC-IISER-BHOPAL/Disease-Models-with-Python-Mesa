# Disease-Models-with-Python-Mesa
This repository is meant as a facilitator for all those who want to learn agent based disease modelling using the mesa framework in python. When I started out, there were too few examples for this on the net. Thankful to the community helping me learn, here I will share some of my insights.


Mesa is a agent based modelling platform. The models I have created are Based on the SIR models in Epidimiology. 
All our agents reside in a square grid. Each cell in this grid can host people and is analogous to proximities and neighbourhoods.
The agents are rule based actors and work according to the step function defined in the Person class.
Every period, they randomly choose a cell in their neighbourhood and move.
If a agent is infected, he can infect each of the other agents in his cell with some probability called transmission probability. 
In most of my models, i have hardcoded it to 0.4, but you can change it and experiment.
As we explore various models and complexities, the rules and restrictions on the agents become more complex.
As deaths are introduced, each day a sick agent faces death with some probability.

Finally, I have briefly introduced some of the economics aspects of epidemic with wages and disease costs.
These are very basic rudimentaries. I am in the process of deveoping a lockdown model for the same and will post more.


Have fun creating your own pandemic.

Original Creator
Ayush Mathur (18065)
