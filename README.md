# MVA-PGM-Project

This project repository of the course **Probabilistic Graphical Models** given by *P. Latouche* and *P. A. Mattei* is based on the following article:

Neal, R. M. (2000). Markov chain sampling methods for Dirichlet process mixture models. Journal of computational and graphical statistics, 9(2), 249-265.


## Structure

- [PDF Report](PGM.pdf) : Sampling Methods for Dirichlet Process Mixture Models. **This report is 6 pages, excluding Figures and References**
- [mc_dp_synthetic_dataset.ipynb](mc_dp_synthetic_dataset.ipynb) : Main notebook with implementation algorithms 1,2,4,5,6,7,8 ; DP sampler and experimentation on synthetic data
- [mc_dp_old_faithful.ipynb](mc_dp_old_faithful.ipynb) : Experimentation on the Old Faithful Dataset with Algorithm 5 and $\alpha$ fine tuning.
- faithful.csv : Old Faithful Dataset
- README.md : This present document


## Contribution Statement

All 3 authors, Marius Alonso, Paul Bonin and Théo Communal have equally contributed to the implementation of the algorithms and execution of the experiments, as well as the meticulous preparation and writing of this report, thereby sharing equal for the work presented.


## Abstract    

   In this paper, we review and summarize algorithms from [Neal, 2000]. Dirichlet Process Mixture Models is a probabilistic unsupervised learning technique that assumes that the instances were generated from a mixture of several distributions with unknown parameters. As such, it can be understood as a more general case of Gaussian Mixture Models, as it allows to use different families of distribution. Furthermore, the number of distributions does not need to be specified beforehand. Sparsity of the clustering is enforced by the Dirichet Process "rich get richer" property given by the $\alpha$ parameter. We implemented these algorithms in Python and tested them on synthetic and real data (Old Faithful Dataset). 

