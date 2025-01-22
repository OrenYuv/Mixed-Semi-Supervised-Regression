# Mixed-Semi-Supervised-Regression
This repository is related to the paper 'Mixed Semi-Supervised Generalized-Linear-Regression with Applications to Deep-Learning and Interpolators' by Yuval and Rosset (2024), https://doi.org/10.48550/arXiv.2302.09526.

The repository includes simulation code, facilitating the replication of the empirical study detailed in the paper.


Every code file within the directories 'OLS', 'GLM', and 'Linear interpolator' produces the corresponding figure featured in the paper (Figure 1 to 6).



Refer to the guidelines at the start of the 'Nose-X Prediction' code file to create Figure 7. To produce Figure 7, you must have access to the CelebA dataset, which can be found at https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html. 


The datasets used for Figures 8 and 9 are located in the folder named 'Interpolating NNs'. The file "Netflix_X_Vote.csv" holds the ratings from 12,931 users for the movie "Miss Congeniality" and encompasses 184 movies with the fewest missing values across the entire Netflix dataset. The file "Netflix_y.csv" provides the ratings for the movie "Miss Congeniality" by the same users. The complete Netflix dataset can be accessed at https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data. Execute the code file 'Netflix ratings prediction' and save the output data. Subsequently, execute the relevant code for Figures 8 and 9 respectively.
