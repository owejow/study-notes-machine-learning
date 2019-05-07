# Statistics and Probability

- [Statistics and Probability](#statistics-and-probability)
  - [Displaying and describing quantitative data](#displaying-and-describing-quantitative-data)
    - [Frequency Table and Dot plots](#frequency-table-and-dot-plots)
    - [Histogram](#histogram)
    - [Stem and Leaf Plot](#stem-and-leaf-plot)
    - [Classifying shapes of distributions](#classifying-shapes-of-distributions)
      - [Describing a distribution](#describing-a-distribution)
  - [Categorical Data](#categorical-data)
    - [Marginal and conditional distributions](#marginal-and-conditional-distributions)
  - [Probability](#probability)
    - [Statistical Significance of Experiment](#statistical-significance-of-experiment)
    - [Addition Rule for Probability](#addition-rule-for-probability)
    - [Multiplication Rule for Probability](#multiplication-rule-for-probability)
    - [Probability of at least one success](#probability-of-at-least-one-success)
    - [Conditional probability and Independence](#conditional-probability-and-independence)
    - [Conditional probability formula](#conditional-probability-formula)
  - [Statistics Intro: Mean, median and Mode](#statistics-intro-mean-median-and-mode)
    - [Sample Variance](#sample-variance)
    - [Why divide by n-1 for unbiased sample variance](#why-divide-by-n-1-for-unbiased-sample-variance)
    - [Box and Whisker Plots](#box-and-whisker-plots)
    - [Outliers](#outliers)
  - [Study Design](#study-design)
    - [Sampling and observational Studies](#sampling-and-observational-studies)
    - [Techniques for Simple Random Sample](#techniques-for-simple-random-sample)
    - [Types of Statistical Studies](#types-of-statistical-studies)
  - [Making and describing scatter plots](#making-and-describing-scatter-plots)
    - [Correlation coefficient](#correlation-coefficient)
    - [Residuals](#residuals)
      - [R-squared intuition](#r-squared-intuition)
      - [R-squared or coefficient of determinination](#r-squared-or-coefficient-of-determinination)
      - [Standard deviation of residuals or root mean squared deviation (RMSD)](#standard-deviation-of-residuals-or-root-mean-squared-deviation-rmsd)
      - [Impact of removing outliers on regression lines](#impact-of-removing-outliers-on-regression-lines)
  - [Modeling Data Distributions](#modeling-data-distributions)
    - [How parameters change as data is shifted and scaled](#how-parameters-change-as-data-is-shifted-and-scaled)
    - [Density Curves](#density-curves)
      - [What can we glean from density curves](#what-can-we-glean-from-density-curves)
  - [Random Variables](#random-variables)
    - [Binomial Variables](#binomial-variables)
      - [binomial probability problem formula](#binomial-probability-problem-formula)
      - [Expected Value and Variance of a binomial variable](#expected-value-and-variance-of-a-binomial-variable)
    - [Geometric Random Variables](#geometric-random-variables)
      - [Proof Geometric Random Variables](#proof-geometric-random-variables)
    - [Continuous Random Variables](#continuous-random-variables)
      - [Sums and Differences of Random Variables](#sums-and-differences-of-random-variables)
      - [Combining Random Variables](#combining-random-variables)
  - [Combining Random Variables](#combining-random-variables-1)
  - [Outcomes, Events, and Probability](#outcomes-events-and-probability)
  - [Central Limit Theorem](#central-limit-theorem)
    - [Useful hints](#useful-hints)
  - [Sampling Distributions](#sampling-distributions)
    - [Sampling Distribution and Sample Proportion](#sampling-distribution-and-sample-proportion)
    - [Finding the mean and standard deviation of the sampling distribution](#finding-the-mean-and-standard-deviation-of-the-sampling-distribution)
    - [Sampling distribution of a sample mean](#sampling-distribution-of-a-sample-mean)
  - [Confidence Interval](#confidence-interval)
    - [Assumptions about confidence intervals](#assumptions-about-confidence-intervals)
    - [Conditions for Inference on a proportion](#conditions-for-inference-on-a-proportion)
    - [t-statistic](#t-statistic)
      - [Confidence for inference on mean](#confidence-for-inference-on-mean)
        - [random condition**](#random-condition)
        - [**the normal condition**](#the-normal-condition)
      - [**The independence condition**](#the-independence-condition)
      - [**Summary**](#summary)
      - [Confidence interval for Mean](#confidence-interval-for-mean)
      - [Interpreting a confidence interval for a mean](#interpreting-a-confidence-interval-for-a-mean)
      - [Sample size for a given margin of error for a mean](#sample-size-for-a-given-margin-of-error-for-a-mean)
    - [Chebyshev's inequality](#chebyshevs-inequality)
      - [Making a t-interval for paired data](#making-a-t-interval-for-paired-data)
      - [Formula for test statistic](#formula-for-test-statistic)
      - [General Definition](#general-definition)
  - [Significant Tests](#significant-tests)
    - [The idea of significance tests](#the-idea-of-significance-tests)
      - [Significance Levels](#significance-levels)
      - [Type I errors and Type II errors](#type-i-errors-and-type-ii-errors)
        - [Power in Significance Test](#power-in-significance-test)
        - [Consequences of errors and significance](#consequences-of-errors-and-significance)
      - [Testing hypothesis about a proportion](#testing-hypothesis-about-a-proportion)
        - [The random condition](#the-random-condition)
        - [The Normal Condition](#the-normal-condition)
        - [The independence condition](#the-independence-condition)
        - [Calculating a z-statistic in a test about proportion](#calculating-a-z-statistic-in-a-test-about-proportion)
      - [Condition for t test about a mean](#condition-for-t-test-about-a-mean)
      - [When to use the z or t statistic in significance tests](#when-to-use-the-z-or-t-statistic-in-significance-tests)
    - [Comparing Two Populations](#comparing-two-populations)
      - [Confidence intervals for difference between two proportions](#confidence-intervals-for-difference-between-two-proportions)
    - [P-value in a two-sample z test for difference of proportions](#p-value-in-a-two-sample-z-test-for-difference-of-proportions)
    - [Confidence Interval for Difference Between Two Means](#confidence-interval-for-difference-between-two-means)
      - [Formula for the test statistic](#formula-for-the-test-statistic)
      - [Hypotheses for two-sample t-test](#hypotheses-for-two-sample-t-test)
    - [Making conclusions about the difference of means](#making-conclusions-about-the-difference-of-means)
      - [Reject vs. fail to reject $H_0$](#reject-vs-fail-to-reject-h0)
      - [Using a confidence interval to test a difference](#using-a-confidence-interval-to-test-a-difference)

## Displaying and describing quantitative data

### Frequency Table and Dot plots

**frequency table** create a table that contains each distinct value and the frequency of its occurence

Age | # at age
---------|----------
 5 | 2
 6 | 1
 7 | 4

**dot plot** create graph with values on the X and one dot at each x value (incrementally increases).

**questions**  can be made

- what is the range?
- how many 7 year olds

### Histogram

Create buckets of values into categories and create a histogram.

**interpreting a histogram** what can be determined?

- total number of counts can be determined
- number of counts greater than a certain value

### Stem and Leaf Plot

Stems contains all other digits other than the right most digits typically.


Stem | Leaf
---------|------
 0 | 0 0 2 4 7 7 9
 1 | 1 1 3 8
 2 | 0

**how to interpret** can more easily see values.

### Classifying shapes of distributions

**symmetric** draw line in the center the look the same on both sides of split

**left skewed** high points on the right tail on the left

**right skewed** high points on the left tail on the right

**bimodal** have two peaks

**uniform** almost the same value throughout

#### Describing a distribution

Four things to comment:

- shape of distribution
- center of distribution: mean, median
- spread: range, interquartile range, standard deviation, mean average deviation
- outlier


## Categorical Data

**individuals** do not have to refer to people can be things.

**identifier** how ot identify the individual

**categorical variable** can take up a set number of values.

**quantitative variables** many non-categorial variables

### Marginal and conditional distributions

**marginal distribution** data has two be bivariate (two variables). We are only interested in variables that appear in the "margins"

**conditional distribution** is where we are only interested in a particular subpopulation of our entire data set. In rolling dice it could be in terms of rolling a 6 or rolling a two.

## Probability

**large of large numbers** experimental probability is more likely to converge to the theoretical value with more trials


### Statistical Significance of Experiment

**control group** vs **treatment group** what is the probability that the control group and treatment group have differnt means?

- use simulator to re-randomize the result into two new groups and measure the difference between the means of the new groups

### Addition Rule for Probability

additional rule **general formula**

$P(A \cup B) = P(A) + P(B) - P(A \cap B)$

addition rule **mutually exclusive**

$P(A \cup B) = P(A) + P(B)$

### Multiplication Rule for Probability

When we calculate probabilities involving one event AND another event occurring, we multiply their probabilities. When the first event happening does not impact the probability of the seconds. We call these **independent events**. When two events are independent, we can say that:

- $P(A \cap B) = P(A) \cdot P(B)$

In some cases, the first event happening impacts the probability of the second event. We call these **dependent events**. The vertical bar in parenthesis means "given," so this could also be read as "the probability that $B$ occurs given that $A$ has has occurred." This is a general rule for probabilities.

- $P(A \cap B) = P(A) \cdot P(B \mid A)$

NOTE: for indenpendent events:

- $P(B \mid A) = P(B)$

### Probability of at least one success

The following formulas can be used:

- P(at least 1 successes) $=$ 1 - P(all failures)
- P(at least 1 failure) $=$ 1 - P(all successes)

### Conditional probability and Independence

Two events $A$ and $B$ are independent if:

$P(A \mid B) = P(A)\ \cap P(B)$

and

$P(B \mid A) = P(B)$

NOTE: $\mid$ means "given. $P(A \mid B)$ can be read as "the probability that Event $A$ occurs Given Event $B$ has occured."

Use independence with probabilities. Look at experimental results to see if independence holds. We test our assumption and assume that the events are independent if probabilities are significantly different. The measure of significantly different should be quantified statistically. Even though two events are dependent it does NOT mean that there is a causal relationship between the two.

### Conditional probability formula

$P(A \mid B) = \frac{P(A \cap B)}{P(B)}$


## Statistics Intro: Mean, median and Mode

**descriptive** describe population with a small set of numbers

**inferential** make judgements about the population based on samples in population

**average** give me a typical or middle of values find the central tendency

- arithmetic mean sum of all numbers divided by number of data points
- median is looking for the middle of a series of numbers. If even number of numbers divide the arithmetic average of the two middle numbers. If odd it is the middle number. More robust to extreme values
- mode the most common number of a data set. If the most typical number have the most. 

**mean** the total distance from the mean to the data points below the mean is equal to the total distance from the mean to the data points above the mean

**Impact of median and mean making the outlier much farther away** median does not get impacted. The mean is impacted more directly.

**Impact of median and mean by removing outlier** removing low outlier will increase the mean; low outlier will decrease the mean. The median will likely increase by removing small outlier and decrease if removing a large outlier.

**left skewed distribution** mean will be to the left of the median

**right skewed distribution** mean will be to the right of the median

**symmetric distribution** the mean and median will be close to one another

**Interquartile Range** first figure out the median. Then find the middle of the first half and the middle of the second half. The interquartile range is the delta between the two middle points calculated.

NOTE: if there are an even number of points for the median. The points used to calculated in the median will be used in calculating the right and left side of the IQR.

### Sample Variance

**unbiased sample variance** calculate the delta from the sample mean squared; divide by 1 less than the total number of samples.

$S = \sqrt{\sigma_{i=1}^n(\frac{x_i - \bar{x})^2}{(n-1)}}$

Taking the square root of the unbiased sample variance does not give an unbiased estimate for the sample standard deviation. The sqrt function is not non-linear.

$\sigma = \sqrt{\sigma^2}$

### Why divide by n-1 for unbiased sample variance

**parameter** when we compute mean (etc) for the population

- mean for population 
  - $\mu = \frac{\Sigma_{i=1}^N X_i}{N}$
- variance for population 
  - $\sigma^2 = \frac{\Sigma_{i=1}^N (x_i -\mu)^2}{N}$ 

**statistic** when the calculation is done for the mean (etc) of the sample

- mean for sample
  - $\bar{x} = \frac{\Sigma_{i=1}^n x_i}{n}$

- biased sample variance
  - $S_n^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n}$

- unbiased sample variance
  - $S_{n-1}^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}$


Why is dividing by n biased and n-1 is not? The mean could be outside of the samples. With N you are underestimating and with N-2 tend to over-estimate. On average N-1 works best.

### Box and Whisker Plots

1. first order the numbers to figure out the range
1. whiskers for largest and smallest numbers
1. middle line is the median value
1. the median of the numbers of the bottom half is the first quartile
1. the median of the numbers in the top half is the top of the second quartile

### Outliers

Statistical convention is to use the interquatile range to determine outlisers:

- outlier $< Q_1 - 1.5 \times IQR$
- outlier $> Q_3 + 1.5 \times IQR$

## Study Design

### Sampling and observational Studies

- Response bias: Response bias is when people are systematically dishonest when answering a question.
- undercoverage: undercoverage is when the researcher excludes members of the population from being in the sample.
- voluntary response sampling: respondents that voluntarily respond are not indicative of the overall population
- convenience sampling: when you sample the subpopulation who are easy to reach out to
- Nonresponse is when people chosen for the sample cannot be reached or refuse to participate
- Undercoverage is when the researcher systematically excludes members of the population from being in the sample.
- Biased wording of survey questions can cause people to favor certain responses over others.

**random digit table** used to create samples. Print out digits and walk the digits.

### Techniques for Simple Random Sample

- simple random sample: every member of population has same probability of being selected
- stratified sample: take population and stratify it by subgroups then sample within each of the subgroups.
- cluster sample: select all members of certain subgroups of a population
- voluntary: has an excellent chance of bias
- convenience: take samples of those who are most convenient to sample
- bias wording could cause a bias
- response bias: people do not want to respond at all

### Types of Statistical Studies

**Sample Study** estimate the parameter population based on randomly sampling people from the population. 

**Observational Study** understand if two parameters in a population are related to one another. Do those two variables move together? This does not indicate causality. There could be a lurking variable or a confounding variable that results in the correlation.

- In an observational study, we measure or survey members of a sample without trying to affect them.

**Experiment** basis of the scientific method. They establish causality. select samples, randomly assign the people to control and treatment. Then measure affect on individuals. Want to randomly distribute the confounding variable in the control and treatment groups.

- In a controlled experiment, we assign people or things to groups and apply some treatment to one of the groups, while the other group does not receive the treatment.

- A comparative experiment involves one group receiving a treatment (the insoles) and another group that doesn't receive the treatment. The group that doesn't receive the treatment is called the control group.

**explanatory variable** variable that causes something to change.

**response variable** the thing that might get changed by the explanatory variable

**randomized block design**, the experimenter divides subjects into subgroups called blocks, such that the variability within blocks is less than the variability between blocks. Then, subjects within each block are randomly assigned to treatment conditions. Compared to a completely randomized design, this design reduces variability within treatment conditions and potential confounding, producing a better estimate of treatment effects.

**double blind** and **blind** and **triple blind** experiments. blind the people don't know. double blind the people who administer don't know. triple blind the people who are analyzing the experiments don't know.

**treatment** is the specific level of the explanatory variable given to individuals in an experiment. If there are multiple explanatory variables, a treatment is a combination of specific levels from each explanatory variable.

**experimental** unit is who or what we are assigning to a treatment.

**Key idea:** If a sample isn't randomly selected, it may not be representative of the larger population.

 "" | Random sampling | Not Random Sampling
---------|-----------------|---------
 Random Assignment | Can determine causal relationship in population. This design is relatively rare in the real world. | Can determine causal relationship in that sample only. This design is where most experiments would fit.
 No random assignment | Can detect relationships in population, but cannot determine causality. This design is where many surveys and observational studies would fit.| Can detect relationships in that sample only, but cannot determine causality. This design is where many unscientific surveys and polls would fit.

**matched pair design** control and treatment groups get swapped over time to see what happens. Everyone is both in the control and treatment to reduce affect of lurking variables.

- matched pairs design is a special case of a randomized block design. It can be used when the experiment has only two treatment conditions; and subjects can be grouped into pairs, based on some blocking variable. Then, within each pair, subjects are randomly assigned to different treatments.


## Making and describing scatter plots

**scatterplots** darawn to see relationships between variables. Used to determine if two variables have positive or negative relationship.

**bivariate** plot a relationship between two variables.

- describe the relationship as linearity and strength, and direction
  - negative, strong, linear relationship
  - positive, weak, linear relationship
  - negative, strong, non-linear relationship

Describe a relationship in terms of:

- form: is the association linear or nonlinear
- direction: is the association positive or negative
- strength: does the association appear to be strong, moderately strong, or weak
- outliers: do there appear to be any data points that are unusually far away from the general pattern

### Correlation coefficient

**correlation coefficient** formula is the foollowing

- $r = \frac{1}{(n-1)} \sum_{i=1}^{n}(\frac{x_i-\bar{x}}{s_x})\frac{(y_i-\bar{y})}{s_y}%$
- $-1 \le r \le 1$

- linear regression line goes through the mean of x and the y

**Pearson correlation** coefficient is the measure of linear correlation between +1 and -1.

- Cauchy-Schwartz inequality the value is bounded by -1 and +1

### Residuals

**linear regression** fit a line to minimize the square distance to the points.

- residual = actual - estimated
- $y - \hat{y}$
- residuals can be positive or negative

**least squares regression** tries to minimize the distance between the data points and the regression line.

- $\hat{y} = m{x} + b$
- $m = r\frac{S_y}{S_x}$
- the line goes through the mean

**slope interpretation** on average how much does the dependent variable increase for each increment of the independent variable

**bias interpretation** what is the base dependent variable value if the independent variable is 0

**residual plot** gives a sense of how good a fit the line is for the data. There should be no visible trend for the residuals for a good fit. If the plot is not evenly scattered and has a pattern a more non-linear.

first calculate the residuals:

- residual =  actual - expected

#### R-squared intuition

**r-squared** measures how much prediction herror is eliminated when we use least squares regression.

- without regression would use the average of y values to predict the corresponding x value.
- the sum of square of the residuals gives a sense of how good a fit the line is
- $R^2$ tells us what percent of the prediction error in the y variable is eliminated when we use least-squares regression on the x-variable
- $R^2$ is called the coefficient of determination
- $R^2$ tells us what percentage of the variability in the y variable is accounted for by the regression on the x variable.

#### R-squared or coefficient of determinination

- what percent of the variation in y is described by the variation in x?

- $1 - \frac{SE_{line}}{SE_{\bar{y}}}$
- its called $R^2$ or coefficient of determination

total variation in y:

- $SE_{\bar{y}} = (y_1 - \bar{y})^2 + (y_2 - \bar{y})^2 + ... + (y_n - \bar{y})^2$

how much of the variation is not described by the line

- $SE_{line} = (y_1 - (mx_1 -b))^2 + (y_2 - (mx_2 -b))^2 + ... + (y_n - (mx_n -b))^2$

#### Standard deviation of residuals or root mean squared deviation (RMSD)

**standard deviation of residuals** are a measure of how well a regression line fits the data. It is also known as the root mean square deviation or root mean square error

- $RMSD = \sqrt{\frac{\sum (residuals)^2}{n-2}}$
- The RMSD units are whatever they are for the y-axis (average prediction area)
- approximate size of the average error

- $\hat{y} = mx + b$
- $Constant gives b$
- $coefficient on x gives slope$
- $S$ is the standard deviation of residuals
- slope will tell if $R^2$ is positive or negative


Predictor     | Coef | SE Coef | T       | P
--------------|-------|---------|--------|--------
Constant      | 2.544 | 0.134   | 18.955 | 0.000
Caffein (mg)  | 0.163 | 0.057   |  2.862 | 0.005

S=1.532 R-Sq = 60.032$\%$ R-Sq(adj) = 58.621$\%/$

- equation for the regression line
  - $\hat{y} = 2.544 + 0.164x$ where x represents caffeine intake and y represents hours spent studying

- The standard deviation of the residuals, or $S$, measures the size of a typical prediction error in y variable. so the units of $S$ match the units on the y-variable, which is hours in this context.

- what percentage of the variation in study time can be explained by the regression caffeine intake?
- the coefficient of determination or $R^2$ measures what percentag eof the variation of y variable can be explained by the regression on the x variable.

Even with moderately strong positive relationship, we cannot say that caffeine is the cause of the longer study times. 

Another variable -- like a student needing to pass this course to graduate -- might be the cause of both increased study time and caffeine consumption.

Reverse causation is also possible. instead of caffeine causing longer study times, maybe its the need to study longer that caused increased caffeine intake.

**Association does not necessarily imply causation** important to remmeber

#### Impact of removing outliers on regression lines



## Modeling Data Distributions

**percentile rank** two ways of calculating

1. percentage of the data that is below amount in question
2. percentage of the data that is at or below the amount in question

**cumulative relative frequency graph** x shows the variable and y the cumulative relative frequency. The maximum value will have a y value 1.0. 

- The median would be the **cumulative relative frequency** of 0.5
- IQR can be calculated by subracting the 25th percentile from the 75th percentile

**z-score** is the number of standard deviations for a particular data point away from the mean. Gives us a quick measure of how far away from the mean a given data is.

- $z = \frac{x - \mu}{\sigma}$

### How parameters change as data is shifted and scaled

**median** and **mean** are affected as follows:

- if A is added to every value the mean and median will increase by A
- if A is multipled by every value the mean and median will be multiplied by A

**StdDev** and **IQR** is affected should be as follows

- if A is added to every value the standard deviation does not change
- if A is multiplied by every value both IQR and stddev are scaled

### Density Curves

**density curve** area under density curve sums to 1. Values are continuous and bins are infinitely small.

- density curve is that the probability of a precise value is zero. The area under the curve is zero for a single point

#### What can we glean from density curves

**median** for symmetric distribution is the mid point for a density curve. Mean and median are the same

- for non-symmetric regions the line has to divide the area in two equal 50 percent distributions

**skewed** distribution are those that the mean and median are not the same. The mean to the right of the median is called a right-skewed distribution. The mean to the left of a median is called a left-skewed distribution.

**normal distribution** probabilities

- $\mu \pm 1\sigma = 68\%$
- $\mu \pm 2\sigma = 95\%$
- $\mu \pm 3\sigma = 99.7\%$

## Random Variables

### Binomial Variables

- **definition**
  - The outcome of each trial can be classified as either a success or failure
  - each trial is independent of the others
  - there is a fixed number of trials
  - the probability $p$ of success on each trial remains constant

- **assuming independence between trials**
  - $sample \le 10\%$ rule of population can treat it as normal or binomial

  - $\binom{n}{k} = \frac{n!}{k!(n-k)!}$
  - P(exactly k scores in n attempts)
    - $\binom{n}{k} f^k (1-f)^k$
    - $f$ is probability of success

- **binomial coeficients** are symmetric in the middle. However the shape of the distribution depends on the probability of the event occurring or not.

- **binompdf**
  - binomial probability distribution function
- **binomcdf**
  - binomial cumulative probability distribution function

#### binomial probability problem formula

A binomial probability problem has these features:

- a set number of trials $n$
- each trial can be classified as a "success" or "failure"
- the probability of success $p$ is same for each trial
- results from each trial are independent from each other

general strategy is given below for getting $exact\_num$ successes

$P(exact\_num) = \binom{n}{exact\_num} p^{exact\_num} (1-p)^{(n-exact\_num)}$

#### Expected Value and Variance of a binomial variable

- $X$ is number of successes after n trials where $P(success)$ for each trial is $p$.

- The expected value is provided below
  - $E(X) = np$
  - The expected variance of a binomial variable
  - $Var(X) =  np(1-p)$

### Geometric Random Variables

Requirements for geometric rnadom variables

- trial outcome is success or failure
- trial results are independent
- same probability on each trial
- number of successes in finite number of trials (not fixed number of trials)

#### Proof Geometric Random Variables

$X$ is equal to number of independent trials to a get a "sucess" where $P(success)$ for each trial is $p$

- $E(X) = \frac{1}{p}$

### Continuous Random Variables

- what happens to $\mu_{Y}$ and $\sigma_{Y}$ relative to $\mu_{X}$ and $\sigma{Y}$ if $X$ and $Y$ are continuous variables and $K
  - if $Y$ = $X$ + $k$
    - $\mu_Y = \mu_{X} + k$
    - $\sigma_Y = \sigma_{X}$
  - if $Y$ =  $kX$
    - $\mu_Y = k\mu_{X}$
    - $\sigma_Y = k\sigma_{X}$

- if $X$ and $Y$ **independent** random variables:
  - $Var(X \pm Y) = Var(X) + Var(Y)$

#### Sums and Differences of Random Variables

- $X$ and $Y$ are independent random variables
  - $E(X) = \mu_x$
  - $E(Y) = \mu_y$
  - $Var(X) = E((X-\mu_x)^2) = \sigma^2$
  - Addition:
    - $Z = X + Y$
    - $E(Z) = E(X+Y) = E(X) + E(Y)$
    - $Var(Z) = Var(X) + Var(Y)$
    - $\sigma_{Z}^2 = \sigma_{X}^2 + \sigma_{Y}^2$
  - Subtraction:
    - $A = X - Y$
    - $E(A) = E(X-Y) = E(X) - E(Y)$
    - $Var(A) = Var(X) + Var(Y)$
    - $\sigma_{A}^2 = \sigma_{X}^2 + \sigma_{Y}^2$

- useful:
  - $\sigma_{-Y}^2 = \sigma_{Y}^2$
  - $E(aX+b) = aE(X) + b$
  - $\mathit{Var}(aX+b) = a^2\mathit{Var}(X)$
  - $\sigma(aX+b) = a\sigma(X)$

#### Combining Random Variables

- Make sure that variables are independent or that it's reasonable to assume independence, before combining variances

- Even when we subtract two random variables, we still add their variances; subtracting two variables increases the overall variability in the outcomes

- Standard deviation of the combined distributions is the same as taking the sqare root of the combined variances

Assuming $X$ and $Y$ are independent of eachother:

 | Mean | Variance
---------|----------|---------
 Adding $T = X + Y$ | $\mu_T = \mu_X + \mu_Y$ | $\sigma_T^2 = \sigma_X^2 + \sigma_Y^2$
 Subtracting $T = X - Y$ | $\mu_T = \mu_X - \mu_Y$ | $\sigma_T^2 = \sigma_X^2 + \sigma_Y^2$

## Combining Random Variables

- Expected mean of a sum of variables is the sum of the individual means
  - $E(X+Y) = \mu_{X+Y} = \mu_X - \mu_Y$
  - $E(X-Y) = \mu_{X-Y} = \mu_X - \mu_Y$
  
- Expected variance of a sum of variables is the sum of the individual means. Assumes $X, Y$ is independent
  - $Var(X + Y) = Var(X) + Var(Y)$
  - $Var(X + Y) = Var(X) + Var(Y)$

- **Variance** is defined as the average squared difference from the mean
- **standard deviation** is the square root of the variance

## Outcomes, Events, and Probability

- **outcomes** of experiments is how we model random or unpredictable phenomena 
- **outcomes** are elements of a **sample space** $\Omega$
- **events** are subsets of $\Omega$
- **events** are assigned a probability, a number between 0 and 1

## Central Limit Theorem

* [Central Limit Theorem ](https://towardsdatascience.com/understanding-the-central-limit-theorem-642473c63ad8) states that when an infinite number of successive random samples are taken from a population, the sampling distribution of the means of those samples will become approximately normally distributed with mean μ and standard deviation σ/√ N as the sample size (N) becomes larger, irrespective of the shape of the population distribution.

Three components of **central limit theorem**:
    * successive sampling of a population
    * increasing sample size
    * population distribution

* **law of averages** guarantees the convergence of $\mu$ of the average $\bar{X_n}$ of $n$ independent random variables $X_1,...,X_n$, all having the same expectation $\mu$ and variance $\sigma^2$

* **variance of sample means**
  * ${\sigma^2}_{\bar{x}} = \frac{\sigma^2}{n}$

### Useful hints

* On average, the sample means will equal the population mean.

* The shape of the sampling distribution of $\bar{x}$ will match the shape of the parent population when the sample size $n$ is small ($n <30$), but it will be closer to normal than the parent population is. The number 30 is a rule of thumb that has empirically been shown to be good for a wide array of distributions

* If the shape of the population distribution is not known you can not make the normality assumption on the sample population means if the sample size is relatively small (i.e. 30).

* In any normal distribution, we know that approximately $68\%$, of the data falls within one standard deviation of the mean, $95\%$, of data falls within two standard deviations of the mean, and $99.7\%$ of data falls within three standard deviations of the mean.


## Sampling Distributions

### Sampling Distribution and Sample Proportion

Determining if a sample distribution of $\hat{p}$ is approximately normal:


NOTE: the sampling distribution is approximately normal as long as the expected number of successes and failures are both at least 10.

- $np \ge 10 \cap n (1-p)$

### Finding the mean and standard deviation of the sampling distribution

If repeated random samples of a given size n are taken from a population of values for a categorical variable, where the proportion in the category of interest is p, then the mean of all sample proportions (p-hat) is the population proportion (p). The sampling distribution of a sample proportion $\hat{p}$ has:

- $\mu_{\hat{p}} = p$
- $\sigma_{\hat{p}} = \sqrt{\frac{p(1-p)}{n}}$
  - NOTE: for this standard deviation formula to be accurate, our sample size needs to be 10\% or less of the population so we can assume independence.
  - Since the sample size n appears in the denominator of the square root, the standard deviation does decrease as sample size increases. Finally, the shape of the distribution of p-hat will be approximately normal as long as the sample size n is large enough. The convention is to require both np and n(1 – p) to be at least 10.

### Sampling distribution of a sample mean

**Central Limit Theorem** (CLT) is a statistical theory states that given a sufficiently large sample size from a population with a finite level of variance, the mean of all samples from the same population will be approximately equal to the mean of the population.

Parameters are usually unknown, because it is impractical or impossible to know exactly what values a variable takes for every member of the population.

Statistics are computed from the sample, and vary from sample to sample due to sampling variability.

Sampling Distribution of the Sample mean:

- sampling distribution is 

**skew**  is the degree of distortion from the symmetrical bell curve or the normal distribution. It measures the lack of symmetry in data distribution. It differentiates extreme values in one versus the other tail. A symmetrical distribution will have a skewness of 0.

Kurtosis is all about the tails of the distribution — not the peakedness or flatness. It is used to describe the extreme values in one versus the other tail. It is actually the measure of outliers present in the distribution.

- High kurtosis in a data set is an indicator that data has heavy tails or outliers. If there is a high kurtosis, then, we need to investigate why do we have so many outliers. It indicates a lot of things, maybe wrong data entry or other things. Investigate!
- Low kurtosis in a data set is an indicator that data has light tails or lack of outliers. If we get low kurtosis(too good to be true), then also we need to investigate and trim the dataset of unwanted results.

Positive Skewness means when the tail on the right side of the distribution is longer or fatter. The mean and median will be greater than the mode.

Negative Skewness is when the tail of the left side of the distribution is longer or fatter than the tail on the right side. The mean and median will be less than the mode.

variance of the sampling distribution of the sample mean:

- $\sigma^2_{\bar{x}} = \frac{\sigma^2}{n}$

mean of sampling distribution of sample mean

- $\mu_{\bar{x}} = \mu$
- NOTE: for this standard deviation formula to be accurate, our sample size needs to be $10\%$ or less of the population so we can assume independence.

- When the sample size is small ($n\lt 30$), the sampling distribution of the sample mean will have a similar shape to the population, and we were told this population is left-skewed.

## Confidence Interval

Standard error for sampling proportion $\hat{p}$:

- $SE_{\hat{p}} = \sqrt{\frac{\hat{p}(1-\hat{p})}{n}}$

Margin of error: reduced by increasing sample size.

The confidence level refers to the long-term success rate of the method, that is, how often this type of interval will capture the parameter of interest.

A specific confidence interval gives a range of plausible values for the parameter of interest.

A larger margin of error produces a wider confidence interval that is more likely to contain the parameter of interest (increased confidence).

### Assumptions about confidence intervals

Trying to estimate population parameter based on sample. Using the sample proportion we use a confidence interval on the sample proportion.

Conditions assumed:

- Random Sample (take great care)
- Normal condition must hold. Sampling distribution of sample proportions must be roughly normal. The rule of thumb is that per sample with more than 10 successes and failures each. Look at our sample to see if we have greater than 10 successes and failures.
- Independence condition 10% rule: if sampling without replacement. Sample n must be less than 10% of the population.

### Conditions for Inference on a proportion

When we want to carry out inferences on one proportion (build a confidence interval or do a significance test), the accuracy of our methods depend on a few conditions. Before doing the actual computations of the interval or test, it's important to check whether or not these conditions have been met, otherwise the calculations and conclusions that follow aren't actually valid.

The conditions we need for inference on one proportion are:

- Random: The data needs to come from a random sample or randomized experiment.
- Normal: The sampling distribution of $\hat{p}$ needs to be approximately normal 
- needs at least 10 expected successes and 10 expected failures. 
- Independent: Individual observations need to be independent. If sampling without replacement, our sample size shouldn't be more than 10, percent of the population.

**Random Condition** Random samples give us unbiased data from a population. When samples aren't randomly selected, the data usually has some for of bias, so using data that wasn't randomly selected to make inferences about its population can be risky. More specifically, sample proportions are unbiased estimators of their population proportion. This won't happen if samples isn't randomly selected.

**the normal condition** sampling distribution of $\hat{p}$ is approximately normal as long as the expected number of successes and failures are both at least 10. This happens when our sample size n is reasonably large. 

- expected successes: $np \ge 10$
- expected failures: $n(1-p) \ge 10$

When building confidence interval, we can count the number of successes and failures in the sample data to amke sure they are both at least 10.

**independence condition** the individual observations need to be independent. When we are sampling without replacement individual observations aren't technically independent since removing each item changes the population.

If we sample 10\% or less of a population we can treat individual observations as independent. 

If the above conditions holds we can use the formula for the standard deviation of $\hat{p}$

$\sigma_{\hat{p}} = \sqrt{\frac{p(1-p)}{n}}$

WHen building the confidence interval for p we don't know what p is. We substitute $\hat{p}$ as an estimator for p. When we do this, we call it the standard error of $\hat{p}$ to distinguish it from the standard deviation.

So our formula for standard error of $\hat{p}$ is

$\sigma_{\hat{p}} \approx \sqrt{\frac{\hat{p}(1-\hat{p})}{n}}$

**margin of error** is the expression on the other side of the $\pm$

- $\hat{p} \pm z^*\frac{\sqrt{\hat{p}(1-\hat{p}}}{n}$

- **confidence interval** transform data into a range of plausible values for a given parameter
  - quantify confidence in provided estimate

Estimators for distribution features:

- $\mu$  : sample mean
- $\sigma^2$ : sample variance
- $T$ is an estimator for unknown paramber $\theta$
  - **point estimate**: is the estimated for a given sample

- **confidence statements** are made about unknown parameters based on sampling distribution estimators.

### t-statistic

Used to estimate the confidence interval for means from samples.

- samples must be random
- the sampling distribution of $\bar{x}$ is approximately normatl
  - $n \ge 30$ or original distribution is normal
  - individual observations can be considered independent
    - $n \le 10\%$

#### Confidence for inference on mean

The conditions are:

- Random: a random sample or randomized experiment should be used to obtain the data.
- Normal: the sampling distribution of $\bar{x}$ (the sample mean) needs to be approximately normal. This is true if our parent population is normal or if our sample is reasonably large ($n \ge 30$)
- Independent: individual observations need to be independent. If sampling without replacement, our sample size shouldn't be more than $10\%$ of the population.

##### random condition**  

random samples give us unbiased data from a population. When we don't use random selection, the resulting data usually has some form of bias, so using it to infer something about the population can be risky. 

More specifically, sample means are unbiased estimators of their population mean. This will not necessarily happen if we use a non-random sample.

##### **the normal condition**

The sampling distribution of $\bar{x}$ (a sample mean) is approximately normal in a few different cases. The shape of the sampling distribution of $\bar{x}$ mostly depends on the shape of the parent population and the sample size n.

- case 1: **parent population is normally distributed** if the parent population is normally distributed then the sampling distribution of $\bar{x}$ is approximately normal regardless of sample size. So if we know that the parent population is normally distributed, we pass this condition even if the sample size is small. In practice, however, we usually don't know if the parent population is normally distributed.
- case 2: not normal or unknown parent population sample size is large $(n \ge 30)$ The sampling distributeion of $\bar{x}$ is approximately normal as long as the sample size is reasonably large. Because of the central limit theorem, when $n \ge 30$, we can treat the sampling distribution of $\bar{x}$ as approximately normal regardless of the shape of the parent population. There are a few rare cases where the parent population has such an unusual shape that the sampling distribution of the sample mean $\bar{x}$ isn't quire normal for sample sizes near 30. These cases are rate, so in practice, we are usually safe to assume approximately normality in the sampling distribution when $n \ge 30$.
- case 3: not normal or unknown parent population; sample size is small $(n \lt 30)$ as long as the parent population does not have outliers or strong skew, even smaller samples will produce a sampling distribution of $\bar{x}$ that is approximately normal. In practice, we can't usually see the shape of the parent population but we can infer the shape based on the distribution of data in the sample. I fthe data in the sample shows skew or outliers, we should doubt that the parent is approximately normal, and so the smapling distribution of $\bar{x}$ may not be normal either. Bit if the sample data are roughly symmetric and don't show outliers or strong skew, we can assume that the sampling distribution of $\bar{x}$ will be approximately normal. The big idea is that we need to graph our sample data when $n \lt 30$ and then make a decision about the normal condition based on the appearance of the sample data.

#### **The independence condition** 

to use the formula for standard deviation of $\bar{x}$, we need individual observations to be independent. In an experiment, good design usually takes care of independence between subjects (control, different treatments, randomization)

In an observational study that involves sampling wihtout replacement. Individual observations aren't technically independent snce removing each observation changes the population. However the 10\% condition says that if we smaple 10\% or less of the population, we can treat individual observations as independent since removing each observation doesn't change the population all that much as we sample. For instance, if our sample size is $n = 30$, there should be at least $N=300$ members in the population for the sample to meet the independence condidtion.

Assuming independence between observations allows us to use this formula for standard deviation of $\bar{x}$ when we are making confidence intervals or doing significance tests:

- $\sigma_{\bar{x}} = \frac{\sigma}{\sqrt{n}}$

We usually don't know the populaton standard deviation $\sigma$, so we substitute the sample standard deviation $s_x$ as an estimate of $\sigma$. When we do this, we call it the **standard error** or $\bar{x}$ to distinguish it from the standard deviation.

So our formula for standard error of $\bar{x}$ is:

- $\sigma_{\bar{x}} = \frac{s_x}{\sqrt{n}}$

#### **Summary**

- If all three of these conditions are met, then we can we feel good about using ttt distributions to make a confidence interval or do a significance test. Satisfying these conditions makes our calculations accurate and conclusions reliable.
- The random condition is perhaps the most important. If we break the random condition, there is probably bias in the data. The only reliable way to correct for a biased sample is to recollect the data in an unbiased way.
The other two conditions are important, but if we don't meet the normal or independence conditions, we may not need to start over. For example, there is a way to correct for the lack of independence when we sample more than 10, percent of a population, but it's beyond the scope of what we're learning right now.
- The main idea is that it's important to verify certain conditions are met before we make these confidence intervals or do these significance tests.

#### Confidence interval for Mean

$\bar{x} \pm t(\frac{s_x}{\sqrt{n}})$

t-table requires degrees of freedom which is number of samples minus 1.

#### Interpreting a confidence interval for a mean

After we build a confidence interval for a mean, it's important to be able to interpret what the interval tells us about the population and what it doesn't tell us.

A confidence interval for a mean gives us a range of plausible values for the population mean. If a confidence interval does not include a particular value, we can say that it is not likely that the particular value is the true population mean. However, even if a particular value is within the interval, we shouldn't conclude that the population mean equals that specific value.

#### Sample size for a given margin of error for a mean

Approximate sample size required to obtain a desired margin of error:

Traditional:

- $\bar{x} \pm t(\frac{S_x}{\sqrt{n}})$
- for t need to know degrees of freedom, also don't know sample standard deviation

Use estimation for population standard deviation:

- $\bar{x} \pm z(\frac{\sigma}{\sqrt{n}})$

### Chebyshev's inequality

With a probability of $75\%$ the estimator of $T$ is within $2\sigma_T$:

$P(|T - \theta| < 2\sigma_T)  > \frac{3}{4}$

- **random variable** $T$ in a **fixed interval**
$T \in (\theta - \sigma_T, \theta + \sigma_T)$ with probability of $75\%$

- **random interval** covers a fixed but known $theta$

$\theta \in (T - \sigma_T, T + \sigma_T)$ with probability of $75\%$

**confidence interval** only involves an unbiased estimator and knowlege of the standard deviation

#### Making a t-interval for paired data

With paired data, we're typically interested in the difference between each pair—for example, the difference between the pre-test and the post-test data, or the difference between the medicine and the placebo data.

If certain conditions are met, we can construct a ttt interval to estimating the mean of these differences and draw conclusions.

Key idea: when dealing with paired data, we're most interested in the distribution of the difference.

#### Formula for test statistic

$z = \frac{statistic - parameter}{standard\  deviation\ of\ statistic}$

- $\frac{\hat{p} - p_0}{\sqrt{\frac{p_0(1-p_0)}{n}}}$
- $\hat{p}$ is the sample proportion, the parameter $p_0$ is the proportion from the null hypothesis and n is the sample size.

#### General Definition

Example definition:

$(t - c\sigma_T, t + c\sigma_T)$

## Significant Tests

### The idea of significance tests

- Null Hypothesis: things are as we expected.
- Alternative Hypothesis: what we are suspecting or trying to prove.

**significance level** denoted by $\alpha$. Take a sample of people visiting the sight. Then we calculate the probability of getting the statistics for the sample

- Take sample from population. sample mean and standard deviation
- p-value: probability of achieving the mean given that the null hypothesis is true
- if p-value is less than $\alpha$ then we reject the null hypothesis. Probability of getting sample statistics given then null hypothesis is true.

#### Significance Levels

**significance levels** threshold by which compared against the p-value. Important to set significance level ahead of time.

**p-value** assuming that the null hypothesis is true what is the likelihood of getting the samples you got.

We use p-values to make conclusions in significance testing. More specifically, we compare the p-value to a significance level $\alpha$ to make conclusions about our hypotheses.

If the p-value is lower than the significance level whe chose, then we reject the null hypothesis $H_0$ in favor of the alternative hypothesis $H_a$. If the p-value is greater than or equal to the significance level, then we fail to reject the null hypothesis $H_0$ this doesn't mean we accept $H_0$

- p-value $\lt \alpha$ ⇒reject $H_0$ ​⇒ accept $H_a$
- p-value $\ge \alpha$ ⇒ fail to reject $H_0$

- In practice, we should make our hypotheses and set our significance level before we collect or see any data.

#### Type I errors and Type II errors


Action | Reality $H_0$ true | $H_0$ False
---------|----------|--------------------
Reject $H_0$ | Type I Error | Correct Conclusion
Fail to Reject $H_0$ | Correct Conclusion | Type II Error

##### Power in Significance Test

**Power** probability of rejecting the Null hypothesis when the null hypothesis is false

- Power = P(rejecting H_0 | H_0 false)
- 1 - P(not rejecting H_0 | H_0 false)


How to Increase power

- increase $\alpha$
- increase n (increasing n is always a good thing)
- Less variability will increase power but not under your control
- If true parameter farther away will help but not under your control

NOTE: increase $\alpha$ increases the probability of a type I error. Can make a tradeoff.

##### Consequences of errors and significance

Changing $\alpha$ impacts probabilities of Type I and Type II errors. In some tests, one kind of error has more serious consequences than the other.

Type I error is when we reject a true null hypothesis. Lower values of $\alpha$ make it harder to reject a null hypothesis, so choosing lower values for $\alpha$ can reduce the probability of a Type I error. The consequence here is that if null hypothesis is false, it may be more difficult to reject using a lower value for $\alpha$. So using lower values of $\alpha$ can increase the probability of a Type II error.

A type II error is when we fail to reject a false null hypothesis. Higher values of $\alpha$ make it easier to reject the null hypothesis, so choosing higher values for $\alpha$ can reduce the probability of a Type II error. The consequence here is that if the null hypothesis is ture, increasing $\alpha$ makes it more likely than we commit Type I error (rejecting a true null hypothesis)

#### Testing hypothesis about a proportion

The conditions for inference on a proportion:

- Random: the data needs to come from a random sample or randomized experiment.
- Normal: the sampling distribution $\hat{p}$ needs to be approximately normal
  - needs at least 10 expected successes and 10 expected failures
- independent: individual observationsaneeed to be independent. If sampling without replacement, our sample size shouldn't be more than 10\% of the population.

##### The random condition

Random samples give us unbiased data from a population. When samples aren't randomly selected, the data usually has some form of bias, so using data that wasn't randomly selected to make inferences about its population can be risky.

More specifically, sample proportions are unbiased estimators of their population proportion. For example, if we have a bag of candy where 50 percent of the candies are orange and we take random samples from the bag, some will have more than 50percent orange and some will have less. But on average, the proportion of orange candies in each sample will equal \%50 percent. We write this property as $\mu_{\hat p}=p$, which holds true as long as our sample is random.

This won't necessarily happen if our sample isn't randomly selected though. Biased samples lead to inaccurate results, so they shouldn't be used to create confidence intervals or carry out significance tests.

##### The Normal Condition

The sampling distribution of $\hat{p}$ is approximately normal as long as the expected number of successes and failures are both at least 10. This happens when our sample size n is reasonably large. The proof of this is beyond the scope of AP statistics, but our tutorial on sampling distributions can provide some intuition and verification that this condition indeed works.
So we need:

- expected successes $np ge 10$
- expected failures: $n(1−p)\ge 10$
​	
If we are building a confidence interval, we don't have a value of p to plug in, so we instead count the observed number of successes and failures in the sample data to make sure they are both at least 10. If we are doing a significance test, we use our sample size n and the hypothesized value of p to calculate our expected numbers of successes and failures.

##### The independence condition

To use the formula for standard deviation of $\hat{p}$
, we need individual observations to be independent. When we are sampling without replacement, individual observations aren't technically independent since removing each item changes the population.

But the 10\%, percent condition says that if we sample 10\%, percent or less of the population, we can treat individual observations as independent since removing each observation doesn't significantly change the population as we sample. For instance, if our sample size is $n=150$ there should be at least $N=1500$,  1500 members in the population. This allows us to use the formula for standard deviation of $\hat{p}$

- $\sigma_{\hat p}=\sqrt{\frac{p(1-p)}{n}}$

In a significance test, we use the sample size n and the hypothesized value of p.

If we are building a confidence interval for p, we don't actually know what p is, so we substitute $\hat{p}$ as an estimate for ppp. When we do this, we call it the standard error of $\hat{p}$ to distinguish it from the standard deviation. So our formula for standard error of $\hat{p}$ is

- $\sigma_{\hat p}\approx\sqrt{\dfrac{\hat p(1-\hat p)}{n}}$

##### Calculating a z-statistic in a test about proportion

  $z = \frac{\hat{p} - p_0}{ \sqrt{\frac{p_0(1-p_0)}{n}}}$

#### Condition for t test about a mean

- Random: sample has be be randomly chosen from population
  - Random samples give us unbiased data from a population. When we don't use random selection, the resulting data usually has some form of bias, so using it to infer something about the population can be risky.

- Normal:
  - parent population normal
  - $n \ge 30$
  - sample symmetric, no outliers. The big idea is that we need to graph our sample data when $n \lt 30$ and then make a decision about the normal condition based on the appearance of the sample data.

- Independence: 
  - sample with replacement
  - number of samples $n \le 10\%$ 
  - Assuming independence between observations allows us to use the following formula for standard deviation of $\bar{x}$:
    - $\sigma_{bar{x} = \frac{\sigma}{\sqrt{n}}}$
  - we don't kno wthe population standard deviation $\sigma$ so we substitute the sample standard deviation $s_x$ as an estimator for $sigma$. When we do this we call it the standard error of $\bar{x}$ to distinguish it from the the standard deviation.
    - $\sigma_{\bar{x}} \approx \frac{s_x}{\sqrt{n}}$
  
The most important condition is the Random condition. The other two conditions are important but there are ways to correct for the other shortcomings.

#### When to use the z or t statistic in significance tests

Proportion

- $H_0: p = p_1$
- $H_a: p \ne p_1$
- calculate the sample proportion $\hat{p}$
  - find an associated z value for the associated with the sample proportion
  - $z = \frac{\hat{p}-p_0}{\sigma_{\hat{p}}}$
  - $\sigma_{\hat{p}} = \sqrt{\frac{p_0(1-p_0)}{n}}$

Means

- $H_0: \mu = \mu_1$
- $H_a: \mu \ne \mu_1$
- calculate $\bar{x}$
- $z = \frac{\bar{x}-\mu_0}{\sigma_{\bar{x}}}$
- $\frac{\sigma}{\sqrt{n}}$ 
- $\sigma_{\bar{x}} = \frac{\sigma}{\sqrt{n}}$
  - Difficult to know sigma for population therefore use t-statistic
  - $t = \frac{\bar{x}-\mu_0}{\frac{s_x}{\sqrt{n}}}$

### Comparing Two Populations

#### Confidence intervals for difference between two proportions



Ensure the following from the samples of each population:

1. Make sure that the samples can be used for inference
  - Random
  - Normal
    - $n\hat{p} \ge 10$ and $n(1-\hat{p} \ge 10$
2. **confidence level** 
  - $z^*\sqrt{\frac{p(1-p)}{n}}$

3. **confidence interval** 
  - $\sqrt{\frac{\hat{p}(1-\hat{p})}{n}}$

Calculate the confidence interval for $p_1 - p_2$

- $confidence\ interval\ for p_1 - p_2 = (\hat{p}_1 - \hat{p}_2) \pm z^*\sigma_{\hat{p}_1 - \hat{p}_2}$
- $\sigma_{\hat{p}_1 - \hat{p}_2} \approx \sqrt{\frac{\hat{p}_1(1-\hat{p}_1)}{n_1} + \frac{\hat{p}_2(1-\hat{p}_2)}{n_2}}$

### P-value in a two-sample z test for difference of proportions

Calculate the test statistic

The pooled combined proportion of successes in two samples:

$\hat{p}_c = \frac{combined\ count \ of\ success}{combined\ sample\ sizes}$

The test statistic for the test is:

$z = \frac{sample\ difference - hypothesized\ differencl}{standard\ error\ of\ the\ difference}$

This is equal to:

$= \frac{(\hat{p}_1 - \hat{p}_2) - 0}{\sqrt{\frac{\hat{p}_c(1-\hat{p_c})}{n_1} + \frac{\hat{p}_c(1-\hat{p_c})}{n_2}}}$

Then you can look up the appropriate p-value from a z-score table


### Confidence Interval for Difference Between Two Means

How to construct a confidence interfal for the difference in sample means.

Need to use T-statistic because it does a better job of estimating the confidence interval when using an estimate for the standard deviation of the populations.

- $(\bar{x}_1 - \bar{x}_2) \pm t^*\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}$

For calculating degrees of freedom use min($n_1$,$n_2$) - 1

#### Formula for the test statistic

$t = \frac{sample\ difference - hypothesis\ difference}{standard\ error\ of\ the\ difference}$

$=\frac{(\bar{x}_1 - \bar{x}_2) - (\mu_1 - \mu_2)}{\sqrt{\frac{s_1^2}{n_1}} + \frac{s_2^2}{n_2}}$

- The difference between $\mu_1 - \mu_2$ comes from the null hypothesis. In this type of test, we assume no difference in population means, so we can substitute 0 for $\mu_1 - \mu_2$
- $s_1$ and $s_2$ are the two sample standard deviations
- $n_1$ and $n_2$ are the two sample sizes


#### Hypotheses for two-sample t-test

Difference between paired t-test and a two-sample t-test. For a paired t-test doing tests on a single population. For each sample take two measurements. Do this for each member of the sample.

Two-sample t-test. Talking about two different populations. For example, thinking between population of men and population of women. Finding difference of mean of two populations.

NOTE: to do inference must meet the criteria:

- Independence
- Normal
- Random

### Making conclusions about the difference of means

#### Reject vs. fail to reject $H_0$

- P-value $\lt \alpha \rightarrow$ reject $H_0 \rightarrow$ accept $H_0$
- P-value $\ge \alpha \rightarrow$ fail to reject $H_0 \rightarrow$ cannot accept $H_a$

In this type of test, the null hypothesis ($H_0$) is that the two means are equal for there is no difference between the means).

#### Using a confidence interval to test a difference

In a two sided test, the null hypothesis says there is no difference between the two means. In other words, the null hypothesis says that the difference between the two means is 0. We can use a confidence interval instead of a P-value for two sisded tests as long as the confidence level and significance level add up to 100%.

- interval excludes 0 $\rightarrow$ reject $H_0$ $\rightarrow$ accept $H_0$
- interval contains 0 $\rightarrow$ fail to reject $H_0$ $\rightarrow$ cannot accept $H_a$