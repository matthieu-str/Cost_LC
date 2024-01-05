# Semester project rep: key energy technologies cost learning curves

The following notebooks are contained in the `notebook` folder:
- `data_distributions.ipynb`: fit every yearly cost triplet (5th percentile, average value, 95th percentile) or (20th percentile, average value, 80th percentile) with a given PDF. This is done for all triplet between 2010 and 2020, for all available technologies, for the triangular, PERT, Weibull, and generalized gamma distributions. 
- `data_distributions_search.ipynb`: functions of PDFs and CDFs of all distributions cited before. Research of the better way to solve the numerical system to be used in the previous notebook. 
- `graph_LR_vs_t.ipynb`: plots the learning rates for all technologies for all learning curve over time (2020-2050). 
- `graph_multi_LC.ipynb`: plots the learning curves for all technologies (investment cost as a function of the installed capacity). 
- `historical_graph_V2.ipynb`: plots the investment cost trend of technologies over time (and also the one of NG for comparison).
- `learning_curves_graph_V2.ipynb`: plots all technologies chosen learning curve within one single graph.
- `percentiles_prospective.ipynb`: replicates the learning curves fitting for the 5th and 95th percentiles. 
- `regressions.ipynb`: original fitting of average cost values with various learning curves functions. 
- `Train_Test_LC.ipynb`: test the performance of the different learning curve functions by training on a sub-set of historical points. 
- `traing_param_prospective.ipynb`: computed the triangular distribution parameters a and b for the prospective cost in 2050. 
- `uncertainty_cost.ipynb`: fitting the percentiles values with various PDFs. 
- `varying_learning_rates`: plots the learning curves for the varying LR learning curve functions. 