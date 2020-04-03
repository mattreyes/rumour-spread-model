# graph-SIR: a Social Network Rumour Spread Model

Simulating the spread of a rumour in a social network with Python.

The spreading of rumours across a population bear many similarities to epidemics - variants of the [SIR model](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SIR_model) from epidemiology have been used to model rumour spread. However, this model contains the unrealistic assumption that the social network is fully connected. That is, a person can directly contact anyone else inside of it.

To improve on this, our stochastic and agent-based approach incorporates information about the social network for a more realistic model.

![](sirs_visualization.gif)

More details can be found in section 3 of the project writeup, included in this repository.

## Getting started

Run `docker run -p 8888:8888 -p 6006:6006 -it -u user -w /app -v "$(pwd):/app" tiagopeixoto/graph-tool jupyter notebook --ip 0.0.0.0` to run the graph-tool library with Docker in a Python notebook. More installation info [here](https://git.skewed.de/count0/graph-tool/wikis/installation-instructions#installing-using-docker) 