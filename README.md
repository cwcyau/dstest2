# Data Science Exercise

During the interview you will be asked questions about a problem which is described below. You should be prepared to answer questions about the problem paying particular attention to the guidance.

## Problem Description

You are interested in predicting the time taken for a graduate student to complete their PhD ($Y$) and you are given the following model:

$$Y = \beta_0 + \beta_1 A + \beta_2 A^2 + \beta_3 G + \epsilon$$

where
- $A$ denotes age at start of PhD (in years),
- $G$ denotes the undergraduate GPA (between 0.0 and 4.0).


However, another modeller claims that the following model specification:

$$Y = \beta_0 + \beta_1 A + \beta_3 G + \epsilon$$

is superior to the other model.

## Example Data

You have been given some example data `phd.csv` to explore these models. You may choose any approach that you see fit but should pay attention to the guidance below. 

At the interview you will be asked about your data exploration. 

You may prepare **one** slide to aid in describing your work. 

You are not expected to spend more than 3-4 hours on this task.

## Guidance

The following guidance will give you an indication of the type of questions you might be asked at interview. Good responses are expected to be concise but also precise in the terminology and language used:

- Can you qualitatively describe the models and what they mean?
- Can you describe how you would fit such models using likelihood-based inference given some data $(Y, A, G)$?
- What process would you use to determine if one model is better than the other?
