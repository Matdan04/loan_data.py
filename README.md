# Credit Risk Model Data Preparation
This repository documents the meticulous process of preparing a raw dataset for building a credit risk model that estimates the probability of default for personal accounts. The data, originally denominated in USD, is converted to EUR to align with the geographic focus of the analysis.

## Key Steps in Data Preparation:

  1. Currency Conversion: Implemented a function to convert financial values from USD to EUR, reflecting the relevant economic context.
  2. Categorical Encoding: Developed a robust method to quantify categorical variables, transforming all text columns into numerical representations. This step is crucial to enable the subsequent application of machine learning algorithms that require numerical input.
  3. Risk Management: Adopted an extremely risk-averse approach to data handling. In the absence of complete information, the process errs on the side of caution, assigning the most conservative risk assessments to ensure stringent scrutiny of potential defaults.
  4. Handling Missing Data: Established a protocol where missing information is treated as an indicator of potential risk. The procedure assumes worst-case scenarios in such instances, consistent with the principles of prudent risk management in credit evaluation.
