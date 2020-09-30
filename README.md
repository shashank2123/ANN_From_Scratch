#                                                             Building Artifical Neural Networks step by step from scratch
### Introduction :- 
If u wondering how ANN works or what are the steps to build it then this repository will help to gain insight of ANN.It start from building small one node ANN or 
Logistic Regression to building multi layer ANN binary classifier.I used Cat and Non Cat image datasets to train model and build it.<br>

### Datasets:-
> test_catvnoncat.h5 <br>
> train_catvnoncat.h5

### Outline :-
- Building one node ANN or Logistic Regression 
- Building one hidden layer ANN
- Building  ANN

##    Building one node ANN or Logistic Regression step by step from scratch :-
> The basic unit of computation in a neural network is the neuron, often called a node or unit. It receives input from some other nodes, or from an external source and computes an output. Each input has an associated weight (w), which is assigned on the basis of its relative importance to other inputs. The node applies a function f (defined below) to the weighted sum of its inputs as shown in Figure below:

![Working-of-node-in-ANN](https://user-images.githubusercontent.com/44959680/94657209-bb3a6280-031e-11eb-8184-7e15c4f3a955.png)


Further explained in notebook [Logistic Regression or one node ANN.ipynb](Logistic%20Regression%20or%20one%20node%20ANN.ipynb) 

##    Building one hidden layer ANN step by step from scratch :-
> The feedforward neural network was the first and simplest type of artificial neural network devised.It contains multiple neurons (nodes) arranged in layers. Nodes from adjacent layers have connections or edges between them. All these connections have weights associated with them. Building ANN with one hidden layer will help you to make smoother transition to build complete ANN with multiple hidden layer 

![The-simple-ANN-structure-with-one-hidden-layer](https://user-images.githubusercontent.com/44959680/94656831-35b6b280-031e-11eb-890f-d0ef24eccbca.png)

Further explained in notebook [ANN_with_one_hidden_layer.ipynb](ANN_with_one_hidden_layer.ipynb) 

## Building  ANN step by step from scratch :-
> A feedforward neural network can consist of three types of nodes:

> - **Input Nodes –** The Input nodes provide information from the outside world to the network and are together referred to as the “Input Layer”. No computation is performed in   any of the Input nodes – they just pass on the information to the hidden nodes.

> - **Hidden Nodes –** The Hidden nodes have no direct connection with the outside world (hence the name “hidden”). They perform computations and transfer information from the  input nodes to the output nodes. A collection of hidden nodes forms a “Hidden Layer”. While a feedforward network will only have a single input layer and a single output layer, it can have zero or multiple Hidden Layers.

> - **Output Nodes** – The Output nodes are collectively referred to as the “Output Layer” and are responsible for computations and transferring information from the network to the outside world.

![download (2)](https://user-images.githubusercontent.com/44959680/94657924-c6da5900-031f-11eb-8dde-f458501cbf37.png)

Further explained in notebook [ANN.ipynb](ANN.ipynb)
