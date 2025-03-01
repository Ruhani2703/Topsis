# Topsis-Ruhani-102203833

This package provides an implementation of the **TOPSIS** (Technique for Order of Preference by Similarity to Ideal Solution) algorithm. TOPSIS is a decision-making method that helps in ranking and selecting the best alternative based on a set of criteria. It evaluates the alternatives based on their relative distance to the ideal and worst-case solutions.

## What is TOPSIS?

**TOPSIS** is a popular method in Multi-Criteria Decision Analysis (MCDA) used for solving decision-making problems. The basic idea is to choose the alternative that is closest to the ideal solution and farthest from the worst solution. This method is widely used in various fields, such as operations research, business, and engineering.

### Steps Involved in TOPSIS:

1. **Construct the Decision Matrix**: Represent the alternatives and criteria in a matrix format.
2. **Normalize the Decision Matrix**: Normalize the data to make the units consistent.
3. **Apply Weights to the Criteria**: Each criterion is assigned a weight based on its importance.
4. **Determine the Ideal and Worst Alternatives**: Identify the best and worst values for each criterion.
5. **Calculate the Distance**: Calculate the Euclidean distance of each alternative from the ideal and worst alternatives.
6. **Calculate the TOPSIS Score**: Compute the score based on the ratio of the distance from the worst and the sum of the distances from both ideal and worst alternatives.
7. **Rank the Alternatives**: Rank the alternatives based on their TOPSIS score.

## Installation

To install the `Topsis-FirstName-RollNumber` package, follow these steps:

### Step 1: Install using pip

You can install the package directly from PyPI using `pip`:

```bash
pip install Topsis-Ruhani-102203833
```

### Step 2: Verify Installation
topsis --version
### Step 2: Usage Example
topsis <InputDataFile> <Weights> <Impacts> <ResultFileName>


This will calculate the TOPSIS score and ranks and save the result in `result.csv`.

## License

MIT License
# Topsis
