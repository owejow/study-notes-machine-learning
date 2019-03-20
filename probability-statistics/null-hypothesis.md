# Statistics and Probability

- [Statistics and Probability](#statistics-and-probability)
  - [Probability](#probability)
    - [Statistical Significance of Experiment](#statistical-significance-of-experiment)
    - [Addition Rule for Probability](#addition-rule-for-probability)
    - [Multiplication Rule for Probability](#multiplication-rule-for-probability)
    - [Probability of at least one success](#probability-of-at-least-one-success)
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

- $P(B \mid A) = P(B)

### Probability of at least one success

The following formulas can be used:

- P(at least 1 successes) $=$ 1 - P(all failures)
- P(at least 1 failure) $=$ 1 - P(all successes)

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