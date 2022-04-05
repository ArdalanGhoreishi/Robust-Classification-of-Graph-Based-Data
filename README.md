# Robust-Classification-of-Graph-Based-Data
An implementation for paper: [Robust Classification of Graph-Based Data](https://arxiv.org/abs/1612.07141)

This is a project for Big Data Analytics course (AUT, Winter 2021) which is done in collaboration with my classmate [mjzohrabi](https://github.com/mjzohrabi). We have implemented the main functions, RobustGC, PF-RobustGC, pred_x, d_x and kernel_calc based on the paper details. 

The results are tested based on three datasets from the original paper including: Karate_club, polbooks, and USPS (only 4 and 9 digits, for the sake of binary classification). We also performed a binary classification test based on Coat and T-shirt classes from MNIST dataset. 
The out of sample extension is tested based on 4,9 digits from USPS dataset like what is done in the paper. 

The implementation details and results can be observed from ipynb files. Note that the results can be slightly different because of random selection and the hyper-parameters' values. 
