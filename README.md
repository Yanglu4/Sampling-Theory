# Summary
The purpose of this project is to estimate the total personal income(dollars) of community in the Integrated Public Use Microdata
Series(IPUMS) dataset,available online at www.ipums.org/usa/ (Ruggles et al., 2004).
<br />
<br />
The dataset used is a self-weighting sample selected from the 1980 Decennial Census sample, selected using the “Small Sample Density”
option in the data extract tool(Lohr, 2010). The data are in file *ipums.csv* and these data are treated as population in this project. And the documentation for the variables are in file *ipums.pdf*. 
<br />
<br />
Several probability sampling techniques are employed to produce estimations for the total personal income: Simple Random Sampling(SRS), Stratified Random Sampling, Ratio/Regression Estimator in SRS, Cluster Sampling, and Two-stage Unequal Probability Sampling. Different inferences yielded from each approach are compared and contrasted in the report.
<br />
<br />
The code is available in file *ipums_data_analysis.rmd*  and outputs/results are available in file *ipums_data_analysis report.rmd*. 

# Reference
Ruggles, S., Sobek, M., Alexander, T., Fitch, C. A., Goeken, R., Hall, P. K., et al. (2004).
Integrated public use microdata series: Version 3.0 [machine-readable database].
Retrieved from www.ipums/org/usa.

Lohr, S. L. (2010). Sampling: Design and analysis. Mason, OH: South-Western Cengage Learning.
