This program analyzes experimental healthcare data to compare the effectiveness of medicines. A one-sample t-test is used to compare a sample mean with a reference value, while one-way ANOVA is used to determine whether significant differences exist among multiple medicine groups.

**1. Problem scenario**

A pharmaceutical company has developed three medicines:

* Medicine A
* Medicine B
* Medicine C

The company wants to analyze their effectiveness using patient experimental data.

We will use:

Pain reduction score from 0–10, where a higher score means greater reduction in pain.

We will perform two different statistical tests:

**Test 1 — One-sample t-test**

We will ask: Is the average pain reduction produced by Medicine A significantly different from the company's benchmark of 6 points?

**Test 2 — One-way ANOVA**

We will ask: Is there a statistically significant difference in average pain reduction among Medicine A, Medicine B, and Medicine C?

This is a good example because students can see why we need different statistical tests for different questions.

**2. First understand the statistical concepts**

**What is a t-test?** 
A t-test is used to determine whether a difference between means is statistically significant.

There are different types:
* One-sample t-test
* Independent two-sample t-test
* Paired t-test

Here we use a one-sample t-test.

**What is a one-sample t-test?**

A one-sample t-test compares: One sample mean vs a known/reference value.

Our question is: Is Medicine A's average pain reduction different from 6?

Suppose the pharmaceutical company's benchmark is: **μ0​=6**

Medicine A gives us 15 observations. The sample mean is approximately: xˉ=6.13

So we're testing whether: 6.13 is significantly different from 6

**Hypotheses for the t-test**

We need two hypotheses.

**Null hypothesis: H0​:μ=6**

Meaning: Medicine A's true average pain reduction is 6.

**Alternative hypothesis: H1​:μ != 6**

Meaning: Medicine A's true average pain reduction is different from 6.

Because we're testing different from, this is a two-tailed test.
