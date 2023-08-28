---
title: "Neural Networks (NN) Overview"
permalink: /nn-overview/
date: 2023-08-28
---

The following is based on [[1]](https://www.deeplearningbook.org/).

NNs can be seen as sequential function evaluations from one layer to the next.  Consider the example from the image below where the NN is made up of an input layer, two hidden layers, and an output layer.  

![Example Neural Network](https://github.com/laurenstreet/ai-supply/blob/main/assets/images/neutral-nets.png?raw=true "Example Neural Network")

A vector $$\text{ }\mathbf{y}_\text{in}\text{ }$$ is passed to the NN at the input layer.  To go from the input layer to the first hidden layer, $$\text{ }\mathbf{y}_\text{in}\text{ }$$ is transformed by a function evaluation $$\text{ }f\left(\mathbf{y}_\text{in}\right)\text{ }$$ to another vector $$\text{ }\mathbf{y}_{1}\text{ }$$.  Then, to go from the first to the second hidden layer, the vector $$\text{ }\mathbf{y}_{1}\text{ }$$ is transformed through the function evaluation $$\text{ }f(\mathbf{y}_{1})\text{ }$$ to another vector $$\text{ }\mathbf{y}_{2}\text{ }$$.  Finally, to go from the second hidden layer to the output layer, the vector is transformed through the function evaluation $$\text{ }f(\mathbf{y}_{2})\text{ }$$ to the vector $$\text{ }\mathbf{y}_\text{out}\text{ }$$.

More generally, the input to a NN, $$\text{ }\mathbf{y}_{in}\text{ }$$, is related to the output of a NN, $$\text{ }\mathbf{y}_\text{out}\text{ }$$ as, 
$$ \mathbf{y}_\text{out} = f_{n}(f_{n-1}(...f_2(f_1(\mathbf{y}_\text{in})))) $$
where $$\text{ }n\text{ }$$ is the total number of layers.  To go from one layer to the next, there is a set of network values that describe the weights that transform the output from one layer to the input of the next layer.  The total set of network values is commonly denoted $$\text{ }\mathbf{\theta}\text{ }$$ and can be written as $$\text{ }\mathbf{\theta} = \left( \theta_1, ..., \theta_{n} \right)\text{ }$$.

Consider again the example from the image above.  The input vector has three components $$\text{ }\mathbf{y}_\text{in} = (y_{in,1},y_{in,2},y_{in,3})\text{ }$, so the input layer has three nodes.  The function evaluation $$\text{ }f(\mathbf{y}_\text{in})\text{ }$$ gives a vector with four components, $$\text{ }\mathbf{y}_{1}\text{ }$$, so the first hidden layer has four nodes, and so on.   