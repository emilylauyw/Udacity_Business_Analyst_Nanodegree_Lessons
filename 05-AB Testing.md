# 05 - A/B Testing

## A/B Testing Fundamentals
- Learn how to set up AB testing and analyze tests
- AB testing is a type of experiment with 2 variants, A and B. Which are the controlled and variation in a controlled experiment
- When you don't have enough data to use modelling techniques.

### 2 Types of Experiments:
- Matched pair design
- Randomized Design

### Experiment Design
- In an experiment, each individual in a test is called a unit.
- A unit can be a person, store, a run on a production line, a view to a website

### Split groups to 2 comparable groups:
#### 1. Treatment Group: the collection of units that will be getting the treatment.
- Treatment = change you are making

#### 2. Control Group
- Baseline comparison for the treatment group.
- No treatment / change is applied

### Variables
- Experimental Variable (aka treatment or independent): Variable you can change to see how it affects the target variable.
- Control Variable (aka predictor): Variables most influential on the outcome of the target variable.
- Target variable: The variable that we are trying to predict the outcome for

#### Control Variable vs Predictor Variables
Predictor: to build equation, to make prediction of a future value.
control: use to make sure that the treatment units and control units are as similar to each other as possible.

### 5 Steps to determine which control variables should be used to set up the experiment
1. List of potential variables
2. Is variable data available?
3. Logical connection between control and target variable
4. Test correlation between control and target Variables
5. Test correlation between control variables

### Lurking Variable (aka confounding variable)
- Highly correlated with both target variable and another control variable
- Cause to overweight a control variable or include the control variable that really isn't important

### Decide how long to run the test
- At least 1 cycle (e.g. full week)
- Having a full cycle of data reduces the chance of having bias in the responses
- Full cycle is not always possible for the length of an experiment

## Randomized Design Tests
- Technique where the treatment and control units are selected completely randomly
- Used in situation where very little opportunity to control variables, and there the volume and velocity of data is high enough that you're not worries about bias
- Examples: Website-based experiments & Phone system-based Experiments

###Treatment & Control Variables
- Ensure that both the treatment and control groups are representative of the population.

### To design a randomized experiment
1. What is the unit of diversion?
	- How you will assign units to the control or treatment groups.
	- Most experiments do is try to split units at the user level.
2. What is the population of people we're targeting?
  - E.g. All visitors to the site that don't already have the app
3. What is the duration of the test?
4. What is the size of our treatment and control groups?
  - Duration & Size: Ensures control and treatment groups are representative of your population.

### Prepare data for analysis
1. Clean data (remove unwanted data points)
	- Related only to control variables
	- Unethical to remove data for reasons other than for control purposes
2. Calculate lift/difference from treatment to control group
3. Communicate our results

### Observation
- Treatment average is higher than the control average
	- How can we be sure this result wasn't random?
	- how can we be sure that the difference we see in the test actually exists in the entire population?

#### Test of mean analysis
- Statistical calculation of whether the mean values of the treatment and control groups are the same.
- Give us an idea about the magnitude of the impact by the treatment
- Similar to linear regression, a test of means analysis included a T-test, which gives you a P-value

#### P-value
- P-value: likelihood the actual difference between the means is 0
- P < 0.05 (statistically significant, indicating a confidence interval of 95%)
- Tell us how likely it is that the two means are in fact the same or no difference between the treatment and control groups.
- The closer the p-value is to 0, the more likely that the two means are different.

## Matched Pair Design Tests
- Matched pairing sets up treatment and control groups for an experiment by matching on a unit by unit basis using a set of control variables.
- Goal is to create 2 groups of units that are as similar as possible to each other so that we can confidently say that any changes during the test are due to the introduction of the experimental variable.
- Must be set up ahead of time
- All units must be known before the start of the experiment
- Usually used when the volume of observations or individuals are fairly low
- Concern for bias is great and the cost for observation is high by comparison

### How to select Treatment Units
1. Identify outliers
- In general, less than ten treatment units is very low
- the smaller the number of treatment units, the less confidence we will have that the experiment results are valid.
2. Decide number of treatment units

### How to select Control Units
