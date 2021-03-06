# ACO-FS
ACO Feature Selection

Ant Colony Optimisation for feature selection

------------------------------------------------------------------------------
READ ME - Instructions on how to run the code.  
------------------------------------------------------------------------------
To run the MATLAB code
Step 1: Run the aco.m file

You can replace the dataset and SVM classifier with those of your choice. 

Please e-mail us if you find bugs.  
Sadegh Salesi
sadegh.salesi@my.ntu.ac.uk

Dr Georgina Cosma
georgina.cosma@ntu.ac.uk


Reference: S. Salesi and G. Cosma, "A novel extended binary cuckoo search algorithm for feature selection," 2017 2nd International Conference on Knowledge Engineering and Applications (ICKEA), London, 2017, pp. 6-12.
doi: 10.1109/ICKEA.2017.8169893

keywords: {feature selection;optimisation;pattern classification;random processes;search problems;support vector machines;pseudobinary mutation neighbourhood search procedure;extended binary cuckoo search algorithm;feature selection;classification accuracy;cuckoo birds;Lévy flight random walk;search space;Lévy flight mechanism;extended binary cuckoo search optimisation;cuckoo search strategy;support vector machine classifier;Optimization;Search problems;Feature extraction;Birds;Algorithm design and analysis;Space exploration;Convergence;feature selection;classification;cuckoo search;metaheuristic optimisation;nature-inspired algorithms},
URL: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8169893&isnumber=8169886

Abstract:
Cuckoo Search is a recent nature-inspired metaheuristic algorithm, inspired by the cuckoo birds' aggressive strategy to breeding. 
The Cuckoo Search algorithm iteratively uses a Lévy flight random walk to explore a search space. 
The Lévy flight mechanism takes sudden turns of 90 degrees and consequently the Cuckoo's Search strategy does not carefully 
search around the cuckoos' nest, and hence it suffers from slow convergence and low optimisation accuracy. 
In order to improve the weaknesses of the Cuckoo Search algorithm, this paper proposes a pseudobinary mutation 
neighbourhood search procedure embedded in a new binary version of the Cuckoo Search algorithm. The proposed Extended Binary Cuckoo 
Search algorithm has been designed for the task of feature selection, and thus aims to minimise the number of selected features 
(such that only the best features are retained in the subset) whilst maximising the classification accuracy. Based on these criteria, 
a new objective function is proposed which considers the number of features in the subset as well as the classification accuracy 
when searching for the best subset of features. To measure the classification accuracy when using a set of candidate features, the 
Support Vector Machine classifier is utilised. Experiments were conducted with the proposed Extended Binary Cuckoo Search optimisation applied to biomedical datasets and the 
results demonstrated the superiority of the proposed algorithm against three other nature-inspired algorithms, namely 
the Binary Ant Colony Optimisation, Binary Genetic Algorithm, and Binary Particle Swarm Optimisation. Moreover, the experiments 
revealed that when using the proposed function, higher classification accuracy is achieved using a fewer number of features, as 
opposed to using the standard classification accuracy function which needed more features to achieve comparable accuracy.

@INPROCEEDINGS{Salesi2017, 
author={S. Salesi and G. Cosma}, 
booktitle={2017 2nd International Conference on Knowledge Engineering and Applications (ICKEA)}, 
title={A novel extended binary cuckoo search algorithm for feature selection}, 
year={2017}, 
volume={}, 
number={}, 
pages={6-12}, 
keywords={feature selection;optimisation;pattern classification;random processes;search problems;support vector machines;pseudobinary mutation neighbourhood search procedure;extended binary cuckoo search algorithm;feature selection;classification accuracy;cuckoo birds;Lévy flight random walk;search space;Lévy flight mechanism;extended binary cuckoo search optimisation;cuckoo search strategy;support vector machine classifier;Optimization;Search problems;Feature extraction;Birds;Algorithm design and analysis;Space exploration;Convergence;feature selection;classification;cuckoo search;metaheuristic optimisation;nature-inspired algorithms}, 
doi={10.1109/ICKEA.2017.8169893}, 
ISSN={}, 
month={Oct},}
