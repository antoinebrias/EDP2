# EDP2

****** Empirical dynamic programming for model-free ecosystem based management ******

Steve Munch & Antoine Brias

1/ Quantitative ecosystem-based management typically relies on hypothetical ecosystem models that are difficult to validate for all but the best-studied systems. 
2/ Here we develop a management scheme that is based on predictive models driven by the observed dynamics.  
3/ We show that near-optimal management policies can be constructed from time series data by merging empirical dynamic modeling and stochastic dynamic programming.  The Empirical Dynamic Programming approach performs well in cases we examined and outperformed a commonly used single-species alternative.  
4/ We expect model-free ecosystem based management to be of use wherever ecosystem dynamics are uncertain or observations of the system do not cover all relevant species.

The MATLAB file *comparison_GPDP2d_reduxYd_log_q.m* gathers dynamic programming code for near-optimal policies computation for 4 different models. It compares: 1/ the result of the optimal control algorithm given : 1.1/ the true model, 1.2/ approximation of the dynamics based on time-series, plus the the result of the approximated dynamic programming algorithm (temporal difference learning) given 2.1. the true model, and 2.2/ time-series.

The MATLAB file *yield_ratio_violin.m* handles the creation of LaTeX tables and violin plots, by using data in *july_res_par.mat*
