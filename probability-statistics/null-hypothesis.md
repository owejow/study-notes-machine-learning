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
  - [Statistics Intro: Mean, median and Mode](#statistics-intro-mean-median-and-mode)
    - [Sample Variance](#sample-variance)
    - [Why divide by n-1 for unbiased sample variance](#why-divide-by-n-1-for-unbiased-sample-variance)
    - [Box and Whisker Plots](#box-and-whisker-plots)
    - [Outliers](#outliers)
  - [Modeling Data Distributions](#modeling-data-distributions)
    - [How parameters change as data is shifted and scaled](#how-parameters-change-as-data-is-shifted-and-scaled)
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
  - [Confidence Interval for Mean](#confidence-interval-for-mean)
    - [Chebyshev's inequality](#chebyshevs-inequality)
      - [General Definition](#general-definition)

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

$P(A \mid B) = P(A)\ and\ P(B)$

and

$P(B \mid A) = P(B)$

NOTE: $\mid$ means "given. $P(A \mid B)$ can be read as "the probability that Event $A$ occurs Given Event $B$ has occured."

Use independence with probabilities. Look at experimental results to see if independence holds. We test our assumption and assume that the events are independent if probabilities are significantly different. The measure of significantly different should be quantified statistically. Even though two events are dependent it does NOT mean that there is a causal relationship between the two.

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

## Modeling Data Distributions

**percentile rank** two ways of calculating

1. percentage of the data that is below amount in question
1. percentage of the data that is at or below the amount in question

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

* $X$ is number of successes after n trials where $P(success)$ for each trial is $p$. 
  * The expected value is provided below
    * $E(X) = np$
  * The expected variance of a binomial variable
    * $Var(X) =  np(1-p)$

### Geometric Random Variables

Requirements for geometric rnadom variables

* trial outcome is success or failure
* trial results are independent
* same probability on each trial
* number of successes in finite number of trials (not fixed number of trials)

#### Proof Geometric Random Variables

$X$ is equal to number of independent trials to a get a "sucess" where $P(success)$ for each trial is $p$

* $E(X) = \frac{1}{p}$

### Continuous Random Variables

* what happens to $\mu_{Y}$ and $\sigma_{Y}$ relative to $\mu_{X}$ and $\sigma{Y}$ if $X$ and $Y$ are continuous variables and $K
  * if $Y$ = $X$ + $k$
    * $\mu_Y = \mu_{X} + k$
    * $\sigma_Y = \sigma_{X}$
  * if $Y$ =  $kX$
    * $\mu_Y = k\mu_{X}$
    * $\sigma_Y = k\sigma_{X}$

* if $X$ and $Y$ **independent** random variables:
  * $Var(X \pm Y) = Var(X) + Var(Y)$

#### Sums and Differences of Random Variables

* $X$ and $Y$ are independent random variables
  * $E(X) = \mu_x$
  * $E(Y) = \mu_y$
  * $Var(X) = E((X-\mu_x)^2) = \sigma^2$
  * Addition:
    * $Z = X + Y$
    * $E(Z) = E(X+Y) = E(X) + E(Y)$
    * $Var(Z) = Var(X) + Var(Y)$
    * $\sigma_{Z}^2 = \sigma_{X}^2 + \sigma_{Y}^2$
  * Subtraction:
    * $A = X - Y$
    * $E(A) = E(X-Y) = E(X) - E(Y)$
    * $Var(A) = Var(X) + Var(Y)$
    * $\sigma_{A}^2 = \sigma_{X}^2 + \sigma_{Y}^2$
  
* useful:
  * $\sigma_{-Y}^2$ = \sigma_{Y}^2

#### Combining Random Variables

* Make sure that variables are independent or that it's reasonable to assume independence, before combining variances

* Even when we subtract two random variables, we still add their variances; subtracting two variables increases the overall variability in the outcomes

* Standard deviation of the combined distributions is the same as taking the sqare root of the combined variances

Assuming $X$ and $Y$ are independent of eachother:

 | Mean | Variance
---------|----------|---------
 Adding $T = X + Y$ | $\mu_T = \mu_X + \mu_Y$ | $\sigma_T^2 = \sigma_X^2 + \sigma_Y^2$
 Subtracting $T = X - Y$ | $\mu_T = \mu_X - \mu_Y$ | $\sigma_T^2 = \sigma_X^2 + \sigma_Y^2$

## Combining Random Variables

* Expected mean of a sum of variables is the sum of the individual means
  * $E(X+Y) = \mu_{X+Y} = \mu_X - \mu_Y$
  * $E(X-Y) = \mu_{X-Y} = \mu_X - \mu_Y$
  
* Expected variance of a sum of variables is the sum of the individual means. Assumes $X, Y$ is independent
  * $Var(X + Y) = Var(X) + Var(Y)$
  * $Var(X - Y) = Var(X) - Var(Y)$

* **Variance** is defined as the average squared difference from the mean
* **standard deviation** is the square root of the variance

## Outcomes, Events, and Probability

* **outcomes** of experiments is how we model random or unpredictable phenomena 
* **outcomes** are elements of a **sample space** $\Omega$
* **events** are subsets of $\Omega$
* **events** are assigned a probability, a number between 0 and 1

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

## Confidence Interval for Mean

* **confidence interval** transform data into a range of plausible values for a given parameter
  * quantify confidence in provided estimate

Estimators for distribution features:

* $\mu$  : sample mean
* $\sigma^2$ : sample variance
* $T$ is an estimator for unknown paramber $\theta$
  * **point estimate**: is the estimated for a given sample

* **confidence statements** are made about unknown parameters based on sampling distribution estimators.

### Chebyshev's inequality

With a probability of $75\%$ the estimator of $T$ is within $2\sigma_T$:

$P(|T - \theta| < 2\sigma_T)  > \frac{3}{4}$

* **random variable** $T$ in a **fixed interval**
$T \in (\theta - \sigma_T, \theta + \sigma_T)$ with probability of $75\%$

* **random interval** covers a fixed but known $theta$

$\theta \in (T - \sigma_T, T + \sigma_T)$ with probability of $75\%$

**confidence interval** only involves an unbiased estimator and knowlege of the standard deviation


#### General Definition

Example definition:

$(t - c\sigma_T, t + c\sigma_T)$