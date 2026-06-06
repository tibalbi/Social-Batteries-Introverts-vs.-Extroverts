# Social Batteries: Introverts vs. Extroverts

This project explores how self-reported behavioral indicators differ between people labelled as **Introverts** and **Extroverts**. The analysis focuses on solitude, social event attendance, going outside, friendship circle size, and social media posting frequency.

## Research Question

**How do introverts and extroverts differ in their social behavior, solitude patterns, and digital engagement?**

### Sub-questions

* Which behavioral variables show the clearest difference between introverts and extroverts?
* Do introverts spend more time alone than extroverts?
* Are extroverts more active in offline social activities, such as social events and going outside?
* Is digital engagement, measured through post frequency, also higher among extroverts?
* What limitations should be considered before interpreting these patterns?

## Dataset

The dataset used in this project is the Kaggle dataset **Extrovert vs. Introvert Behavior Data**, published by Rakesh Kapilavai.

Source: Kaggle, Extrovert vs. Introvert Behavior Data
Repository file: `data/personality_dataset.csv`

The dataset contains behavioral indicators and a personality label. The main variables used are:

* `Time_spent_Alone`
* `Social_event_attendance`
* `Going_outside`
* `Friends_circle_size`
* `Post_frequency`
* `Personality`

## Methodology

The analysis was conducted using Python in Jupyter Notebook.

Main steps:

1. Loaded the dataset from CSV.
2. Inspected the dataset structure, missing values, and variable types.
3. Cleaned column names and checked consistency of categorical labels.
4. Calculated descriptive statistics by personality group.
5. Compared introverts and extroverts using group averages and distributions.
6. Created visualizations using two tools:

   * Python / Matplotlib for exploratory charts.
   * Datawrapper or Flourish for presentation-ready visualizations.
7. Interpreted the results as descriptive patterns, not as causal evidence.

## Main Insights

* Introverts report spending substantially more time alone than extroverts.
* Extroverts show higher values for social event attendance, going outside, friendship circle size, and post frequency.
* The strongest contrast appears in solitude and offline social interaction variables.
* Digital behavior follows the same direction, with extroverts posting more frequently on average.
* The dataset is useful for comparison, but not enough to generalize to a broader population without stronger metadata.

## Data Limitations

The dataset has important limitations:

* It appears to be based on self-reported behaviors.
* The documentation provides limited information about participant recruitment.
* The demographic composition of the sample is not clearly described.
* The method used to assign personality labels is not fully documented.
* It is unclear whether the dataset comes from a real survey or was synthetically generated.

For this reason, the findings should be interpreted as descriptive patterns within the available dataset.

## Repository Contents

* `data/`: original or cleaned dataset.
* `notebooks/`: reproducible Jupyter Notebook with the analysis.
* `visuals/`: exported charts used in the presentation.
* `docs/`: methodology, limitations, and final presentation.

## License

This project is shared for educational purposes as part of a Data Visualization individual assignment.

Suggested license for this repository: **CC BY-NC-SA 4.0**, unless a different license is required by the dataset source.
