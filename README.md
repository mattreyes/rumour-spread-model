# graph-SIR: A Graph-Based Stochastic Rumour Spread Model for Social Networks

Simulating the spread of a rumour in a social network with Python.

The spreading of rumours across a population bear many similarities to epidemics. Variants of the [SIR model](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SIR_model) used in epidemiology have also been used to model rumour spread. However, this model contains the unrealistic assumption that the network is fully connected. That is, any person can contact anyone else inside of it.

Our stochastic and agent-based approach removes this assumption, incorporating information about the social network for a more realistic model.

![](sir_visualization.gif)

More details can be found in *section 3* of the project writeup, included in this repository.

## Getting started

Follow [these instructions](https://git.skewed.de/count0/graph-tool/wikis/installation-instructions#installing-using-docker) to install the graph-tool library with Docker.