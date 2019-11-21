# Project 4: Algorithm implementation and evaluation: Collaborative Filtering

### [Project Description](doc/project4_desc.md)

Term: Fall 2019

+ Team # 1
+ Projec title: Comparing the effect of regularizations
+ Team members
	+ Abrams, Zack
	+ Gao, Zun
	+ Zhang, Qingyu
	+ Zhao, Marshall
	+ Zhou, Zian
+ Project summary: We are assigned to compare the effect of regularizations between 1) Penalty of Magnitudes and 2) Bias and Intercepts + Temporal Dynamics using the algorithm Stochastic Gradient Descent and KNN for post-processing.

+ Matrix Factorizaition Techniques For Recommender Systems (see doc/paper/P1 Recommender-Systems.pdf)
	
	Matrix factorization characterizes both items and users by vectors of factors inferred from item rating patterns.
![matrix_factorization](figs/matrix_factorization.png)

	+ Steps: 
		+ Step 1: Convert Data into **R** matrix 
	
		+ Step 2: Use the algorithm (with regularization term to train the data and get **U** AND **V** 
		
			+ Case 1: No Regularization Term
		
			+ Case 2: Apply Regularization Term **Penalty of Magnitudes** to the algorithm
		
			+ Case 3: Apply Regularization Term **Bias and Intercepts + Temporal Dynamics** to the algorithm
		
+ Post-processing with KNN (see doc/paper/P2 Recommender-Systems.pdf)

	+ Steps: 
		+ Step 1: Define similarity between movies *j* and *j2* as cosine similarity between vectors *vj* and *vj2* obtained from regularized SVD:
	
		+ Step 2: 

		
Case 1: No Regularization Term
	+ RMSE: 
Case 2: Adding Regularization Term **Penalty of Magnitudes** to the algorithm
	+ RMSE:
Case 3: Adding Regularization Term **Bias and Intercepts + Temporal Dynamics** to the algorithm
	+ RMSE:

	
**Contribution statement**: 
	+ Abrams, Zack contributes nothing for this assignment. 
	+ The other four team members contribute equally.
	+ All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
