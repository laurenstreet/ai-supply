---
title: "Neural Networks (NN) Overview"
permalink: /nn-overview/
date: 2023-08-28
---

The following is based on [[1]](https://www.deeplearningbook.org/).

NNs can be seen as sequential function evaluations from one layer to the next.  Consider the example from the image below where the NN is made up of an input layer, two hidden layers, and an output layer.  

![Example Neural Network](https://github.com/laurenstreet/ai-supply/blob/main/assets/images/neutral-nets.png?raw=true "Example Neural Network")

A vector $$\mathbf{y}_\text{in}$$ is passed to the NN at the input layer.  To go from the input layer to the first hidden layer, $$\mathbf{y}_\text{in}$$ is transformed by a function evaluation $$f\left(\mathbf{y}_\text{in}\right)$$ to another vector $$\mathbf{y}_{1}$$.  Then, to go from the first to the second hidden layer, the vector $$\mathbf{y}_{1}$$ is transformed through the function evaluation $$f(\mathbf{y}_{1})$$ to another vector $$\mathbf{y}_{2}$$.  Finally, to go from the second hidden layer to the output layer, the vector is transformed through the function evaluation $$f(\mathbf{y}_{2})$$ to the vector $$\mathbf{y}_\text{out}$$.

More generally, the input to a NN, $\mathbf{y}_{in}$, is related to the output of a NN, $\mathbf{y}_{out}$ as, 
$$ \mathbf{y}_{out} = f_{n}(f_{n-1}(...f_2(f_1(\mathbf{y}_{in})))) $$

where $n$ is the total number of layers.  To go from one layer to the next, there is a set of network values that describe the weights that transform the output from one layer to the input of the next layer.  The total set of network values is commonly denoted $\mathbf{\theta}$ and can be written as $\mathbf{\theta} = \left( \theta_1, ..., \theta_{n} \right)$.

Consider again the example from the image above.  The input vector has three components $\mathbf{y}_{in} = (y_{in,1},y_{in,2},y_{in,3})$, so the input layer has three nodes.  The function evaluation $f(\mathbf{y}_{in})$ gives a vector with four components, $\mathbf{y}_{1}$, so the first hidden layer has four nodes, and so on.   