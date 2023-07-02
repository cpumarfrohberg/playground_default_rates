<h1 align="center">Predict long-term Default Rates.</h1>
<p align="center">Project Description</p>
This project has the main objective to iterate thru different models for predicting theoretic default rates in the lending business with the objective to find optimal model assumptions in order to then predict the **distribution** of named rates. It is based on the `PyMC`-framework for probabilistic programming.

## Content of the project
* see main vs. feature branches in order to compare iterations over different model specs

## Conclusions
* the larger the sample size, the more stable the convergence (see posterior predictive check) - duh!
* most realistic assumption for distribution of data is `lognormal` (probability that a large, unexpected default rate materializes is non-zero)

## Next steps
- [ ] iterate thru different priors (based on intuition as well as selected papers, it seems reasonable to assume a `binomial`, if not `bernouilli` - see papers)
- [ ] iterate thru different likelihood distributions with longer tails (currently likelihood is assumed to be `gamma` (see papers), but it seems reasonable to assume a `beta` and/or `binomial` distributions)
- [ ] fit a `Logistic Regression` - model for predicting probability of default of individual loan applicants (separate project)
- [ ] dockerize

## Author

**Carlos Pumar-Frohberg**

- [Profile](https://github.com/cpumarfrohberg)
- [Email](mailto:cpumarfrohberg@gmail.com?subject=Hi "Hi!")
- [papers](https://kiefer.economics.cornell.edu/ProbabilityApproachWP.pdf)

## 🤝 Support

Comments, questions and/or feedback are welcome!
