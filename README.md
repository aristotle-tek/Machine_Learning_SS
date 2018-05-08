# Machine Learning for Social Science #
### Applying machine learning with examples and concerns of social scientists, focusing on causal inference, estimating uncertainty, robustness and policy applications. ##


## Instructor ##

[Andrew Peterson](http://www.andrewjerelpeterson.com/ "Andrew Peterson") (Postdoctoral Researcher, University of Geneva)

## Course Description
This course is designed with social scientists in mind, by which it is meant simply that it assumes an interest in certain concerns that are not always common among computer scientists and others who do machine learning. While I hope the course may be useful more broadly, it will be of particular interest to social scientists due to a focus on the following areas:
1. **Assumptions and Research Design** We will compare the approach and assumptions of machine learning to the econometric approach more familiar to political scientists and economists.
2. **Causal Inference** We will also approach the use of machine learning with the causal inference framework in mind, and think about how machine learning may add additional problems, or help in analyzing data with testing theories and examining relationships that may be plagued by selection bias.
3. **Applications** The examples used and applications examined will be drawn from social science research.


## Prerequisites ##

This course assumes basic familiarity with machine learning approaches and algorithms as well as econometrics (although these are reviewed in Part 1). Alternatively, you may review the following:

### Econometrics ###
You should be familiar with the following:
- hypothesis testing, multiple regression, the Gauss-Markov theorem, 
- heteroskedasticity, clustered and auto-correlated errors
- binary outcome models
- commonly-used approaches such as how to code categorical variables, interpret interaction effects, partialling out, etc.

### Machine Learning ###
If you are not already familiar with machine learning, I suggest the following readings from [The Elements of Statistical Learning, 2nd Ed](https://web.stanford.edu/~hastie/ElemStatLearn/) as most essential to the material:

1. Fundamentals of Machine Learning (Chs 2, 7)
- the curse of dimensionality
- machine learning as function approximation
- bias-variance tradeoff
- regularization
- cross-validation
- model selection

2. Linear Methods for Regression (Ch 3)
- Subset selection, Lasso, ridge regression


3. Additive Models, Boosting, Trees and Forests (Chs 9, 10, 15)

4. Model Inferece
- Bootstrap
- Maximuml Likelihood
- EM
- Bagging

5. Unsupervised learning (Ch 14)
- Focus on PCA (14.5) and Multidimensional Scaling (14.8)

## Course Outline

|   |  Content                                | Materials |
|---|-----------------------------------------|-----------|
| 1 | Fundamentals, Assumptions               | [Slides](https://github.com/aristotle-tek/Machine_Learning_SS/blob/master/slides/ML_SS_slides_01_handout.pdf) |
| 2 | Comparing ML and Econometric Approaches | [Slides](https://github.com/aristotle-tek/Machine_Learning_SS/blob/master/slides/ML_SS_slides_02_handout.pdf) |
| 3 | ML for Causal Inference I: Identification, double robustness in high-dimensions               |           |
| 4 | ML for Causal Inference II: IV, effect heterogeneity,  treatment assignment             |           |
| 5 | Applied Example 1: ML and Measuring Polarization |  |
| 6 | Applied Example 2: Deep Learning and Texts |  |
| 7 | Applied Examples: Various | |

---
## Additional Resources

My introduction to causal inference in general was through Cyrus Samii's PhD level course in 2012, for which the updated version of [slides and other resources are available here](http://cyrussamii.com/?page_id=2580). Bruce Hansen kindly makes his regularly updated Econometrics text [available online free here](https://www.ssc.wisc.edu/~bhansen/econometrics/). Athey and Imbens taught a course on machine learning and econometrics for which [materials are available here (scroll down)](https://www.aeaweb.org/conference/cont-ed/2018-webcasts).



