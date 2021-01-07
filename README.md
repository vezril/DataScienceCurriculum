* # DataScienceCurriculum

Based off this article: https://towardsdatascience.com/a-complete-52-week-curriculum-to-become-a-data-scientist-in-2021-2b5fc77bd160

## Introduction
If you want to be a data scientist but haven’t yet made the commitment, now is the time.

Last year, I made a commitment to learn something new about data science every week for 52 weeks, and I think that was one of the best decisions I’ve ever made. You’d be surprised at how far you can get in a year.

And so, I’m presenting to you a complete 52 weeks curriculum that you can do in 2021 as a new years resolution! It is crammed and it will be a grind, but it will be worth it.
Immediately, you’ll notice that this guide does not start with machine learning, and I have good reasons for that. If you want to learn more about why machine learning comes in the later weeks, check out my [article](https://towardsdatascience.com/want-to-be-a-data-scientist-dont-learn-machine-learning-28e418d9af2f).

A couple of notes before we dive into it:
* _This will not cover everything that you need to know to be a fully equipped data scientist. That being said, this will cover what I believe are the most fundamental skills of a data scientist._
* _This assumes that you already know differential calculus since we all learned it in high school_
* _This curriculum will not include anything related to deep learning. Deep learning deserves its own 52 weeks on its own — it would be a disservice if I tried to squeeze it in!_

With that said, let’s dive into it!

## Course Structure
* Statistics and Probability (Week 1 to Week 6)
* Mathematics (Week 7 to 12)
* SQL (Week 13 to Week 21)
* Python and Programming (Week 22 to Week 28)
* Pandas (Week 29 to Week 33)
* Visualizing Data (Week 34 to Week 35)
* Data Exploration and Preparation (Week 36 to Week 39)
* Machine Learning (Week 40 to Week 51)
* Data Science Project (Week 52)

## Statistics & Probability
Why Statistics and Probability?

Data science and machine learning are essentially a modern version of statistics. By learning statistics first, you’ll have a much easier time when it comes to learning machine learning concepts and algorithms! Even though it may seem like you’re not getting anything tangible out of the first few weeks, it will be worth it in the later weeks.

### Week 1: Descriptive Statistics
* [*] [Intro to Descriptive Statistics](https://towardsdatascience.com/descriptive-statistics-f2beeaf7a8df)
* [*] [Another Intro to Descriptive Statistics](https://towardsdatascience.com/intro-to-descriptive-statistics-252e9c464ac9)

### Week 2: Probability
* [ ] [Theoretical probability](https://www.khanacademy.org/math/statistics-probability/probability-library/basic-theoretical-probability/v/basic-probability)
* [ ] [Sample spaces](https://www.khanacademy.org/math/statistics-probability/probability-library/probability-sample-spaces/v/events-and-outcomes-3)
* [ ] [Set operations](https://www.khanacademy.org/math/statistics-probability/probability-library/basic-set-ops/v/intersection-and-union-of-sets)
* [ ] [Addition rule](https://www.khanacademy.org/math/statistics-probability/probability-library/addition-rule-lib/v/probability-with-playing-cards-and-venn-diagrams)
* [ ] [Multiplication rule for independent events](https://www.khanacademy.org/math/statistics-probability/probability-library/multiplication-rule-independent/v/compound-sample-spaces)
* [ ] [Multiplication rule for dependent events](https://www.khanacademy.org/math/statistics-probability/probability-library/multiplication-rule-dependent/v/introduction-to-dependent-probability)
* [ ] [Conditional probability and independence](https://www.khanacademy.org/math/statistics-probability/probability-library/conditional-probability-independence/v/calculating-conditional-probability)

### Week 3: Combinations and Permutations
* [ ] [Counting principle and factorial](https://www.khanacademy.org/math/statistics-probability/counting-permutations-and-combinations/counting-principle-factorial/v/tree-diagram-to-count-outcomes)
* [ ] [Permutations](https://www.khanacademy.org/math/statistics-probability/counting-permutations-and-combinations/permutation-lib/v/permutation-formula)
* [ ] [Combinations](https://www.khanacademy.org/math/statistics-probability/counting-permutations-and-combinations/combinations-lib/v/introduction-to-combinations)
* [ ] [Combinatorics](https://www.khanacademy.org/math/statistics-probability/counting-permutations-and-combinations/combinatorics-probability/v/probability-using-combinations)

### Week 4: Normal Distribution and Sampling Distributions
* [ ] [Normal distribution and the Empirical rule](https://www.khanacademy.org/math/statistics-probability/modeling-distributions-of-data/normal-distributions-library/v/ck12-org-normal-distribution-problems-qualitative-sense-of-normal-distributions)
* [ ] [Introduction to Sampling Distributions](https://www.khanacademy.org/math/statistics-probability/sampling-distributions-library/what-is-a-sampling-distribution/v/introduction-to-sampling-distributions)
* [ ] [Sampling distribution of a sample proportion](https://www.khanacademy.org/math/statistics-probability/sampling-distributions-library/sample-proportions/v/sampling-distribution-of-sample-proportion-part-1)
* [ ] [Sampling distribution of a sample mean](https://www.khanacademy.org/math/statistics-probability/sampling-distributions-library/sample-means/v/statistics-sample-vs-population-mean)

### Week 5: Confidence Intervals
* [ ] [Introduction to Confidence Intervals](https://www.khanacademy.org/math/statistics-probability/confidence-intervals-one-sample/introduction-to-confidence-intervals/v/confidence-intervals-and-margin-of-error)
* [ ] [Estimating Sample Proportions](https://www.khanacademy.org/math/statistics-probability/confidence-intervals-one-sample/estimating-population-proportion/v/confidence-interval-example)
* [ ] [Estimating Sample Means](https://www.khanacademy.org/math/statistics-probability/confidence-intervals-one-sample/estimating-population-mean/v/introduction-to-t-statistics)

### Week 6: Hypothesis Testing
* [ ] [Introduction to Hypothesis Testing](https://www.khanacademy.org/math/statistics-probability/significance-tests-one-sample/idea-of-significance-tests/v/simple-hypothesis-testing)
* [ ] [Error probabilities and power](https://www.khanacademy.org/math/statistics-probability/significance-tests-one-sample/error-probabilities-and-power/v/introduction-to-type-i-and-type-ii-errors)
* [ ] [Tests about a population proportion](https://www.khanacademy.org/math/statistics-probability/significance-tests-one-sample/tests-about-population-proportion/v/constructing-hypotheses-for-a-significance-test)
* [ ] [Tests about a population mean](https://www.khanacademy.org/math/statistics-probability/significance-tests-one-sample/tests-about-population-mean/v/writing-hypotheses-for-significance-test-about-means)
* [ ] [More videos](https://www.khanacademy.org/math/statistics-probability/significance-tests-one-sample/more-significance-testing-videos/v/hypothesis-testing-and-p-values)

## Mathematics
### Why Mathematics?
Like statistics, many data science concepts build on fundamental mathematical concepts.

In order to understand cost functions, you need to know differential calculus. In order to understand hypothesis testing, you need to understand integration. And to give more one more example, linear algebra is essential to learning deep learning concepts, recommendation systems, and principal component analysis.

### Week 7: Vectors and Spaces
* [ ] [Vectors](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/vector-introduction-linear-algebra)
* [ ] [Linear Combinations and Spans](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/linear-combinations/v/linear-combinations-and-span)
* [ ] [Linear Dependence and Independence](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/linear-independence/v/linear-algebra-introduction-to-linear-independence)
* [ ] [Subspaces and the basis for a subspace](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/subspace-basis/v/linear-subspaces)

### Week 8: Dot Product and Matrix Transformations pt. 1
* [ ] [Vector dot and cross products](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/dot-cross-products/v/vector-dot-product-and-vector-length)
* [ ] [Functions and Linear Transformations](https://www.khanacademy.org/math/linear-algebra/matrix-transformations/linear-transformations/v/a-more-formal-understanding-of-functions)
* [ ] [Transformations and Matrix Multiplications](https://www.khanacademy.org/math/linear-algebra/matrix-transformations/composition-of-transformations/v/compositions-of-linear-transformations-1)

### Week 9: Matrix Transformations pt. 2
* [ ] [Inverse Functions and Transformations](https://www.khanacademy.org/math/linear-algebra/matrix-transformations/inverse-transformations/v/linear-algebra-introduction-to-the-inverse-of-a-function)
* [ ] [Inverses and Determinants](https://www.khanacademy.org/math/linear-algebra/matrix-transformations/inverse-of-matrices/v/linear-algebra-deriving-a-method-for-determining-inverses)
* [ ] [Transpose of a Matrix](https://www.khanacademy.org/math/linear-algebra/matrix-transformations/matrix-transpose/v/linear-algebra-transpose-of-a-matrix)

### Week 10: Eigenvalues and Eigenvectors
* [ ] [Eigenvalues and Eigenvectors](https://www.mathsisfun.com/algebra/eigenvalue.html)
* [ ] _Anything that you couldn’t finish in the past few weeks!_

### Week 11: Integrals
* [ ] [Approximation with Riemann Sums](https://www.khanacademy.org/math/integral-calculus/ic-integration/ic-riemann-sums/v/simple-riemann-approximation-using-rectangles)
* [ ] [Definite Integrals with Riemann Sums](https://www.khanacademy.org/math/integral-calculus/ic-integration/ic-definite-integral-definition/v/riemann-sums-and-integrals)
* [ ] [The Fundamental Theorem of Calculus and Accumulation Functions](The Fundamental Theorem of Calculus and Accumulation Functions)
* [ ] [Properties of Definite Integrals](https://www.khanacademy.org/math/integral-calculus/ic-integration/ic-integral-prop/v/negative-definite-integrals)

### Week 12: Integrals Part 2!
* [ ] [The Fundamental Theorem of Calculus and Definite Integrals](https://www.khanacademy.org/math/integral-calculus/ic-integration/ic-ftc-part-2/v/connecting-the-first-and-second-fundamental-theorems-of-calculus)
* [ ] [Reverse Power Rule](https://www.khanacademy.org/math/integral-calculus/ic-integration/ic-reverse-power-rule/v/indefinite-integrals-of-x-raised-to-a-power)
* [ ] [Indefinite Integrals of Common Functions](https://www.khanacademy.org/math/integral-calculus/ic-integration/ic-common-indefinite-integrals/v/antiderivative-of-x-1)
* [ ] [Definite Integrals of Common Functions](https://www.khanacademy.org/math/integral-calculus/ic-integration/ic-common-definite-integrals/v/reverse-power-rule-for-definite-integrals)

## SQL
### Why SQL?
SQL is arguably the most important skill to learn across any type of data-related profession, whether you’re a data scientist, data engineer, data analyst, business analyst, the list goes on.

At its core, SQL is used to extract (or query) specific data from a database, so that you can do things like analyze the data, visualize the data, model the data, etc. Therefore, developing strong SQL skills will allow you to take your analyses, visualizations, and modeling to the next level because you will be able to extract and manipulate the data in advanced ways.

I came across [Mode’s curriculum](https://mode.com/sql-tutorial/) a while back and it is fantastic! So I would first get familiar with [using SQL in Mode](https://mode.com/sql-tutorial/sql-in-mode/) and then you’ll be able to go through the topics below!

### Week 13: Basic SQL
* [ ] [Introduction to SQL](https://towardsdatascience.com/learn-beginner-sql-in-5-steps-in-5-minutes-c44c47fa39a1)
* [ ] [SELECT FROM statement](https://mode.com/sql-tutorial/sql-select-statement/)
* [ ] [WHERE statement](https://mode.com/sql-tutorial/sql-where/)
* [ ] [ORDER BY statement](https://mode.com/sql-tutorial/sql-order-by/)
* [ ] [LIMIT statement](https://mode.com/sql-tutorial/sql-limit/)

### Week 14: LOGICAL and COMPARISON Operators
* [ ] [Logical Operators](https://mode.com/sql-tutorial/sql-logical-operators/)
* [ ] [Comparison Operators](https://mode.com/sql-tutorial/sql-operators/)

### Week 15: AGGREGATES
* [ ] [Aggregate Functions](https://mode.com/sql-tutorial/sql-aggregate-functions/) (COUNT, SUM, MIN/MAX, AVG)
* [ ] [GROUP BY](https://mode.com/sql-tutorial/sql-group-by/) clause
* [ ] [HAVING](https://mode.com/sql-tutorial/sql-having/) clause

### Week 16: DISTINCT, CASE WHEN
* [ ] [DISTINCT](https://mode.com/sql-tutorial/sql-distinct/)
* [ ] [CASE WHEN](https://mode.com/sql-tutorial/sql-case/)

### Week 17: JOINS and UNIONS
* [ ] [JOINs](https://mode.com/sql-tutorial/sql-joins/)
* [ ] [UNIONs](https://mode.com/sql-tutorial/sql-union/)

### Week 18: Subqueries and Common Table Expressions
* [ ] [Subqueries](https://mode.com/sql-tutorial/sql-sub-queries/)
* [ ] [Common Table Expressions](https://learnsql.com/blog/when-to-use-cte/) (CTEs)

### Week 19: String Manipulations
* [ ] [String Functions in SQL](https://mode.com/sql-tutorial/sql-string-functions-for-cleaning/) (LEFT/RIGHT, TRIM, STRPOS, SUBSTR, CONCAT, UPPER/LOWER, etc…)

### Week 20: Date-time manipulation
* [ ] [EXTRACT](https://www.w3schools.com/sql/func_mysql_extract.asp)
* [ ] [DATE_ADD()](https://www.w3schools.com/sql/func_mysql_date_add.asp)
* [ ] [DATE_SUB()](https://www.w3schools.com/sql/func_mysql_date_sub.asp)
* [ ] [DATE_DIFF()](https://www.w3schools.com/sql/func_mysql_datediff.asp)
* [ ] _See [here](https://www.w3schools.com/sql/func_mysql_adddate.asp) for more functions (on the left of the webpage)_

### Week 21: Windows Functions
* [ ] [Windows Functions](https://mode.com/sql-tutorial/sql-window-functions/) (ROW_NUMBER(), RANK(), DENSE_RANK(), LAG, LEAD, SUM, COUNT, AVG)
* [ ] See [here](https://www.postgresql.org/docs/8.4/functions-window.html) for advanced window functions.

## Python and Programming
### Why Python?
I started with Python, and I’ll probably stick with Python for the rest of my life. It’s so far ahead in terms of open source contributions, and it’s straightforward to learn. Feel free to go with R if you want, but I have no opinions or advice to provide regarding R.

### Week 22: Introduction to Python
* [ ] [Video: (0:00 to 1:03:10)](https://www.youtube.com/watch?v=rfscVS0vtbw&feature=youtu.be)

### Week 23: List, Tuples, Functions, Conditional Statements, Comparisons
* [ ] [Video: (1:03:10 to 2:00:37)](https://www.youtube.com/watch?v=rfscVS0vtbw&feature=youtu.be)

### Week 24: Dictionaries, Loops, Comments
* [ ] [Video: (2:00:37 to 3:04:17)](https://www.youtube.com/watch?v=rfscVS0vtbw&feature=youtu.be)

### Week 25: Try/Except, Reading & Writing files, Classes and Objects
* [ ] [Video: (3:04:17 to 4:20:43)](https://www.youtube.com/watch?v=rfscVS0vtbw&feature=youtu.be)

### Week 26: Recursion
* [ ] [Video explanation of recursion](https://www.youtube.com/watch?v=KEEKn7Me-ms)
* [ ] [Course on recursion](https://leetcode.com/explore/learn/card/recursion-i/)

### Week 27: Binary Trees
* [ ] [Course on Binary Trees](https://leetcode.com/explore/learn/card/data-structure-tree/)

### Week 28: APIs and Anaconda
* [ ] [APIs for beginners](https://www.youtube.com/watch?v=GZvSYJDk-us)
* [ ] [Getting Anaconda setup on your computer](https://www.mrdbourke.com/get-your-computer-ready-for-machine-learning-using-anaconda-miniconda-and-conda/)

## Pandas
### Why Pandas?
Arguably the most important library to know in Python is Pandas, which is specifically meant for data manipulation and analysis.

### Week 29: Getting and Knowing your data
* [ ] [Follow along and learn — YouTube video](https://www.youtube.com/watch?v=_jCSK4cMcVw&feature=youtu.be)
* [ ] [Practice problem set #1](https://github.com/guipsamora/pandas_exercises/blob/master/01_Getting_%26_Knowing_Your_Data/Chipotle/Exercise_with_Solutions.ipynb)
* [ ] [Practice problem set #2](https://github.com/guipsamora/pandas_exercises/blob/master/01_Getting_%26_Knowing_Your_Data/Occupation/Exercise_with_Solution.ipynb)

### Week 30: Filtering and Sorting
* [ ] [Follow along and learn — YouTube video](https://www.youtube.com/watch?v=ZZPiWZpdekA&feature=youtu.be)
* [ ] [Practice problem set #1](https://github.com/guipsamora/pandas_exercises/blob/master/02_Filtering_%26_Sorting/Euro12/Exercises_with_Solutions.ipynb)
* [ ] [Practice problem set #2](https://github.com/guipsamora/pandas_exercises/blob/master/02_Filtering_%26_Sorting/Fictional%20Army/Exercise_with_solutions.ipynb)

### Week 31: Grouping
* [ ] [Follow along and learn — YouTube video](https://www.youtube.com/watch?v=az67CMdmS6s&feature=youtu.be)
* [ ] [Practice problem set #1](https://github.com/guipsamora/pandas_exercises/blob/master/03_Grouping/Occupation/Exercises_with_solutions.ipynb)
* [ ] [Practice problem set #2](https://github.com/guipsamora/pandas_exercises/blob/master/03_Grouping/Regiment/Exercises_solutions.ipynb)

### Week 32: Apply
* [ ] [Follow along and learn — YouTube video](https://www.youtube.com/watch?v=46lmk1JvcWA&feature=youtu.be)
* [ ] [Practice problem set #1](https://github.com/guipsamora/pandas_exercises/blob/master/04_Apply/Students_Alcohol_Consumption/Exercises_with_solutions.ipynb)

### Week 33: Merge
* [ ] [Follow along and learn — YouTube video](https://www.youtube.com/watch?v=6DbgcHBiOqo&feature=youtu.be)
* [ ] [Practice problem set #1](https://github.com/guipsamora/pandas_exercises/blob/master/05_Merge/Auto_MPG/Exercises_with_solutions.ipynb)
* [ ] [Practice problem set #2](https://github.com/guipsamora/pandas_exercises/blob/master/05_Merge/Housing%20Market/Exercises_with_solutions.ipynb)

## Visualizing Data
### Why Data Visualizations?
The ability to visualize data and insights is so important because it’s the easiest way to communicate intricate information and a lot of information at once. As a data scientist, you’re always selling yourself and your ideas, whether your pitching a new project or convincing others why your model should be productionalized — data visualizations are a great tool to help you with that.

There are dozens of data visualization libraries out there, but I’m going to focus on two: Matplotlib and Plotly.

### Week 34: Data Visualizations with Matplotlib
* [ ] [Introduction to Matplotlib](https://www.datacamp.com/community/tutorials/matplotlib-tutorial-python)
* [ ] [3-D Visualizations in Matplotlib](https://www.datacamp.com/community/tutorials/matplotlib-3d-volumetric-data)
* [ ] [Types of Data Visualizations in Matplotlib](https://towardsdatascience.com/data-visualization-using-matplotlib-16f1aae5ce70)
* [ ] [Cheatsheet](https://www.datacamp.com/community/blog/python-matplotlib-cheat-sheet)

### Week 35: Data Visualizations with Plotly
* [ ] [Types of Visualizations in Plotly (beginner)](https://towardsdatascience.com/interactive-visualizations-with-plotly-ea3f8feb87d1)
* [ ] [Types of Visualizations in Plotly (beginner and advanced)](https://towardsdatascience.com/the-next-level-of-data-visualization-in-python-dd6e99039d5e)

## Data Exploration and Preparation
### Why Data Exploration and Preparation?

> “Garbage in, garbage out”

The models that you create can only be as good as the data that you feed into it. To understand what the state of your data is in, i.e. whether it’s “good” or not, you have to explore the data and prepare the data. Therefore, for the next four weeks, I’m going to provide several amazing resources for you to go through and get a better understanding of what data exploration and preparation entails.

### Week 36: Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) can be difficult because there’s no one set way of doing it — but that’s also what keeps it exciting. Generally, you want to…

* [ ] Derive descriptive statistics (eg. central tendency)
* [ ] Perform uni-variable analysis (distributions and spread)
* [ ] Perform multi-variable analysis (scatterplots, correlation matrix, predictive power score, etc…)
* [ ] Check for missing data and check for outliers

Check out a beginner’s guide to EDA [here](https://towardsdatascience.com/exploratory-data-analysis-dcb5e7189c4e).

### Week 37: Data Preparation: Feature Imputation and Normalization
* [ ] [What is Feature Imputation?](https://en.wikipedia.org/wiki/Imputation_(statistics)#:~:text=In%20statistics%2C%20imputation%20is%20the,known%20as%20%22item%20imputation%22.)
* [ ] [6 ways to impute missing data](https://towardsdatascience.com/6-different-ways-to-compensate-for-missing-values-data-imputation-with-examples-6022d9ca0779)
* [ ] [Normalization vs Standardization](https://stats.stackexchange.com/questions/10289/whats-the-difference-between-normalization-and-standardization)
* [ ] [Example of implementing normalization vs standardization](https://www.analyticsvidhya.com/blog/2020/04/feature-scaling-machine-learning-normalization-standardization/)

### Week 38: Feature Engineering and Feature Selection
* [ ] [Feature Engineering Mini Course](https://www.kaggle.com/learn/feature-engineering)
* [ ] [Feature Encoding](https://medium.com/analytics-vidhya/different-type-of-feature-engineering-encoding-techniques-for-categorical-variable-encoding-214363a016fb)
* [ ] [An Introduction to Feature Selection](https://machinelearningmastery.com/an-introduction-to-feature-selection/)

### Week 39: Imbalanced Datasets
* [ ] [An Introduction to Imbalanced Classification Problems](https://medium.com/analytics-vidhya/different-type-of-feature-engineering-encoding-techniques-for-categorical-variable-encoding-214363a016fb)
* [ ] [The Right Way to Oversample in Predictive Modeling](https://beckernick.github.io/oversampling-modeling/)

## Machine Learning
### Why Machine Learning?
Everything that you’ve learned has led up to this point! Not only is machine learning interesting and exciting, but it is also a skill that all data scientists have. It’s true that modeling makes up a small portion of a data scientist’s time, but it doesn’t take away from its importance.

Later in your career, you might notice that I left out some machine learning algorithms, like K Nearest-Neighbors, Gradient Boost, and CatBoost. This is completely intentional — if you can understand the following machine learning concepts, you’ll have the skills to learn any other machine learning algorithms in the future.

### Week 40: Introduction to Machine Learning
* [ ] [Supervised vs Unsupervised, Continuous vs Discrete](https://towardsdatascience.com/supervised-vs-unsupervised-learning-14f68e32ea8d)
* [ ] [Bias-variance tradeoff](https://towardsdatascience.com/understanding-the-bias-variance-tradeoff-165e6942b229)

### Week 41: Linear Regression
* [ ] [Linear Models: Linear Regression](https://www.youtube.com/watch?v=nk2CQITm_eo)
* [ ] [Linear Models: Multiple Regression](https://www.youtube.com/watch?v=zITIFTsivN8)
* [ ] [Mathematics behind linear regression](https://www2.isye.gatech.edu/~sman/courses/6739/SimpleLinearRegression.pdf)

### Week 42: Logistic Regression
* [ ] [Introduction to Logistic Regression](https://www.youtube.com/watch?v=yIYKR4sgzI8&t=448s)
* [ ] [Part 1: Coefficients](https://www.youtube.com/watch?v=vN5cNN2-HWE&t=776s)
* [ ] [Part 2: Maximum likelihood](https://www.youtube.com/watch?v=BfKanl1aSG0&t=1s)
* [ ] [Part 3: R-squared and P-value](https://www.youtube.com/watch?v=xxFYro8QuXA&t=24s)

### Week 43: Regularization
* [ ] [Ridge Regression (L2)](https://www.youtube.com/watch?v=Q81RR3yKn30)
* [ ] [Lasso Regression (L1)](Lasso Regression (L1))
* [ ] [Elastic Net Regression](Elastic Net Regression)

### Week 44: Decision Trees
* [ ] [Decision Trees Introduction](https://www.youtube.com/watch?v=7VeUPuFGJHk&t=345s)
* [ ] [Feature Selection and Missing Date](https://www.youtube.com/watch?v=wpNl-JwwplA)
* [ ] [Implementing a Decision Tree in Python](https://www.youtube.com/watch?v=q90UDEgYqeI)

### Week 45: Naïve Bayes
* [ ] [A Mathematical Explanation of Naïve Bayes](https://towardsdatascience.com/a-mathematical-explanation-of-naive-bayes-in-5-minutes-44adebcdb5f8)
* [ ] [Naïve Bayes (StatQuest)](https://www.youtube.com/results?search_query=naive+bayes+statquest)

### Week 46: Support Vector Machines
* [ ] [Intuition of Support Vector Machines](https://www.youtube.com/watch?v=efR1C6CvhmE)
* [ ] [Support Vector Machines in Python](https://www.youtube.com/watch?v=N1vOgolbjSc&t=207s)
* [ ] [A mathematical explanation of Support Vector Machines](https://www.youtube.com/watch?v=_PwhiWxHK8o)

### Week 47: Clustering
* [ ] [K-means clustering](https://www.youtube.com/watch?v=4b5d3muPQmA&t=1s)
* [ ] [Hierarchical clustering](https://www.youtube.com/watch?v=7xHsRkOdVwo&t=1s)

### Week 48: Principal Component Analysis
* [ ] [Principal Component Analysis (PCA) step-by-step](https://www.youtube.com/watch?v=FgakZw6K1QQ&t=36s)
* [ ] [Another detailed explanation by Luis Serrano (I highly suggest you watch both)](https://www.youtube.com/watch?v=g-Hb26agBFg)
* [ ] [Mathematical explanation of PCA](https://www.youtube.com/watch?v=fkf4IBRSeEc)

### Week 49: Bootstrap Sampling, Bagging, and Boosting
* [ ] [Bootstrap Sampling](https://towardsdatascience.com/what-is-bootstrap-sampling-in-machine-learning-and-why-is-it-important-a5bb90cbd89a)
* [ ] [Ensemble learning, Bagging, Boosting](https://towardsdatascience.com/ensemble-learning-bagging-and-boosting-explained-in-3-minutes-2e6d2240ae21)

### Week 50: Random Forests and Other Boosted Trees
* [ ] [Random Forests pt.1](https://www.youtube.com/watch?v=J4Wdy0Wc_xQ)
* [ ] [Random Forests pt.2](https://www.youtube.com/watch?v=sQ870aTKqiM)
* [ ] [XGBoost — Regression](https://www.youtube.com/watch?v=OtD8wVaFm6E&t=3s)
* [ ] [XGBoost — Classification](https://www.youtube.com/watch?v=8b1JEDvenQU)
* [ ] [XGBoost — Mathematical Details](https://www.youtube.com/watch?v=ZVFeW798-2I&t=11s)
* [ ] [XGBoost in Python](https://www.youtube.com/watch?v=GrJP9FLV3FE)

### Week 51: Model Evaluation Metrics
* [ ] [Evaluation Metrics with Python Code](https://towardsdatascience.com/how-to-evaluate-your-machine-learning-models-with-python-code-5f8d2d8d945b)
* [ ] [Understanding the confusion matrix and how to implement it in Python](https://towardsdatascience.com/understanding-the-confusion-matrix-and-how-to-implement-it-in-python-319202e0fe4d)

## Week 52: Data Science Project
If you feel comfortable with the materials above, you’re definitely ready to start your own data science project! Just in case, I’ve provided three ideas that you can use as inspiration to get started, but feel free to do whatever you like.

### Idea 1: SQL Case Study
[Link to the case.](https://mode.com/sql-tutorial/a-drop-in-user-engagement/)

The objective of this case is to determine the cause for a drop in user engagement for a social network called Yammer. Before diving into the data, you should read the overview of what Yammer does [here](https://mode.com/sql-tutorial/sql-business-analytics-training/). There are 4 tables that you should work with.

The link to the case above will provide you with much more detail pertaining to the problem, the data, and the questions that should be answered.

Check out how I approached this case study [here](https://towardsdatascience.com/sql-case-study-investigating-a-drop-in-user-engagement-510b27d0cbcc?source=friends_link&sk=49cdc679e66cae75257b955db51f4fe5) if you’d like guidance.

_Skills You’ll Develop_
* _SQL_
* _Data Analysis_
* _Data Visualization if you choose to visualize your insights._

### Idea 2: Trustpilot Webscraper

Learning how to webscrape data is simple to learn and extremely useful, especially when it comes to collecting data for personal projects. Scraping a customer review website, like Trustpilot, is valuable for a company as it allows them to understand review trends (getting better or worse) and see what customers are saying via NLP.

First I would get familiar with how Trustpilot is organized, and decide upon which kinds of businesses to analyze. Then I would take a look at this walkthrough of [how to scrape Trustpilot reviews](https://towardsdatascience.com/customer-reviews-identify-your-strengths-and-weaknesses-with-the-help-of-web-scraping-data-b87a3636ef55).

_Skills You’ll Develop_
* _Writing Python Scripts_
* _Data Wrangling_
* _BeautifulSoup/Selenium (webscraping libraries)_
* _Data Analysis_
* _Take it further and apply NLP to extract insights from reviews._

### Idea 3: Titanic Machine Learning Competition
In my opinion, there’s no better way of showing that you’re ready for a data science job than to showcase your code through competitions. Kaggle hosts a variety of competitions that involves building a model to optimize a certain metric, one of them being the [Titanic Machine Learning Competition](https://www.kaggle.com/c/titanic).

If you want to get some inspiration and guidance, check out [this step-by-step walkthrough](https://www.kaggle.com/yassineghouzam/titanic-top-4-with-ensemble-modeling) of one of the solutions.

_Skills You’ll Develop_
* _Data Exploration and Cleaning with Pandas_
* _Feature Engineering_
* _Machine Learning Modelling_

## Thanks for Reading!
I hope you found this useful! If you managed to get through this, you should have a strong understanding of the fundamentals in Statistics, Mathematics, SQL, Python/Pandas, and several machine learning algorithms!

I hope this inspired you to continue learning too — there are so many things that you can continue to explore like more advanced models (eg. CatBoost), deep learning, experimental design, Bayesian modeling, cloud architecture, and the list goes on.

If you like this and want to see future content, be sure to give me a follow on Medium. And as always, I wish you the best in your data science endeavors.
