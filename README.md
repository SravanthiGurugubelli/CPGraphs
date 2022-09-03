# Generative-Models-and-Learning-Algorithms-for-Core-Periphery-Structured-Graphs
We consider core-periphery structured graphs, which are graphs with a group of densely and sparsely connected nodes, respectively, referred to as core and periphery nodes. The so-called core score of a node is related to the likelihood of it being a core node. In this paper, we focus on learning the core scores of a graph from its node attributes and connectivity structure. To this end, we propose two classes of probabilistic graphical models: affine and nonlinear. First, we describe affine generative models to model the dependence of node attributes on its core scores, which determine the graph structure. Next, we discuss nonlinear generative models in which the partial correlations of node attributes influence the graph structure through latent core scores. We develop algorithms for inferring the model parameters and core scores of a graph when both the graph structure and node attributes are available. When only the node attributes of graphs are available, we jointly learn a core-periphery structured graph and its core scores. We provide results from numerical experiments on several synthetic and real-world datasets to demonstrate the efficacy of the developed models and algorithms. 

Here, we provide the datasets used in the paper and the scripts to implement the core score inference algorithms proposed in the paper. The 'Datasets' folder contains the real-world and syntheic datasets we validate the proposed core scores inference algorithms on. The code snippets to load the datasets are provided within the inference algorithm scripts. The file 'Synthetic_Data.ipynb' contains the code to generate data synthetically using the proposed models, namely, GA-Affine-Real, GA-Affine-Bool, GA-Nonlinear, and AO.
The scripts 'GA-Affine-Real.ipynb','GA-Affine-Bool.ipynb','GA-Nonlinear.ipynb', and 'AO.ipynb' contain implementations of the proposed inference algorithms related to the GA-Affine-Real, GA-Affine-Bool, GA-Nonlinear, and AO models, respectively. 
