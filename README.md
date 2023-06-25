<h1 align="center">Predict long-term Default Rates.</h1>
<p align="center">Project Description</p>
This project has the main objective to iterate thru different models for predicting theoretic default rates in the lending business. It is based on the `PyMC`-framework for probabilistic programming.

## Content of the project
* 1. `predict_default_rates_short.ipynb`: baseline
* 2. `predict_default_rates_230622.ipynb`: 
    - increased sample size for calculating likelihood
    - assume beta distribution for prior and gamma distribution for likelihood

## Conclusions
* the larger the sample size, the more stable the convergence (see posterior predictive check) - duh!
* note how changed distributions for prior and likelihood functions improved convergence and the posterior predictive checks

## Next steps
- [ ] iterate thru different priors (currently, distribution of data is `uniform`, but prior is assumed to be `beta`)
- [ ] dockerize

## Author

**Carlos Pumar-Frohberg**

- [Profile](https://github.com/cpumarfrohberg)
- [Email](mailto:cpumarfrohberg@gmail.com?subject=Hi "Hi!")


## 🤝 Support

Comments, questions and/or feedback are welcome!
