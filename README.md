# A/B Testing for CTR of "Learn More" Button Colors

## Project Overview
This case study project performs an A/B test to analyze whether the Click-Through Rate (CTR) of the "Learn More" button in blue color is equal to the CTR of the "Learn More" button in green color in LunarTech AI's website. The test is designed to validate the hypothesis that there is no significant difference between the CTR for both button colors.

## Objective
The hypothesis to be tested is:
- **Null Hypothesis (H0)**: The CTR of the "Learn More" button in blue color is equal to the CTR of the "Learn More" button in green color.
- **Alternative Hypothesis (H1)**: The CTR of the "Learn More" button in blue color is not equal to the CTR of the "Learn More" button in green color.

## Data
The dataset `data.csv` contains the following columns:
- `user_id`: Unique identifier for each user.
- `group`: The experimental group to which the user belongs:
  - `con`: Control group (users who saw the blue "Learn More" button).
  - `exp`: Experimental group (users who saw the green "Learn More" button).
- `click`: Indicator of whether the user clicked the button:
  - `1`: Clicked.
  - `0`: Did not click.

