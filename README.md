# COS470-Fall-Project

Aubin Mugisha, and Caelin Limerick

## Project Proposal

Our project will focus on the 2025 Survey of Household Economics and Decisonmaking (SHED).
We aim to answer two research questions with this data.

1. Among adults who used BNPL in the past year, how are age, income, emergency savings, and credit card ownership related to saying it was the only way they could afford their most recent purchase?

2. Among homeowners with a mortgage, how do monthly payments vary with age, and does adding income and household size improve predictions.

## Data

The Federal Reserve's public SHED file has 12,934 respondents. Initial cleaning identified 2,004 BNPL users with affordability responses and 5,176 homeowners with recorded mortgage payments. We will analyze these two groups separately.

Data and documentation:
[Federal Reserve SHED data](https://www.federalreserve.gov/consumerscommunities/shed_data.htm)
and [2025 codebook](https://www.federalreserve.gov/consumerscommunities/files/SHED_2025codebook.pdf)

## Analysis

We plan to try logistic regression to predict whether someone needed BNPL to afford a purchase. For mortgage payments, we could start with age, then add income and household size to see whether predictions improve.

We may also use survey weights, which give some responses more influence so the sample better represents U.S. adults. We could compare results with and without these weights to see whether the findings change. We may adjust our variables or models as we learn more about the data.

## How our work stands out

[The Federal Reserve report](https://www.federalreserve.gov/publications/2026-economic-well-being-of-us-households-in-2025-credit.htm) already summarizes how BNPL use and reasons for using it differ by income. Our project will look at how age, income, savings, and credit card ownership relate to needing BNPL to afford a purchase. We will also test how well our models predict this response and monthly mortgage payments.

