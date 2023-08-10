# test_VCregression
Testing variance component regression model for prediction of protein epistasis 

I wanted to evaluate the effectiveness of a recently published pipeline by Zhou et al. for using variance component regression to predict higher order epistasis in protein multi-mutants: https://www.pnas.org/doi/full/10.1073/pnas.2204233119

In particular, I used the GB1 dataset published by Wu et al.: https://elifesciences.org/articles/16965

The vcregression folder contains code that was written by Zhou et al., which I modified as necessary for my project. The data folder contains some file pre-processing, while the GB1 folder contains my analysis of the results, including comparison of fitness predictions and diagnosis of Monte Carlo sampler chain mixing. Additionally, I also coded a simple linear regression model on one-hot encoded sequences, to use as a baseline. 
