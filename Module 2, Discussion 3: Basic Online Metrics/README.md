# Module 2, Discussion 3: Basic Online Metrics

**Course:** MKT-6306 — Digital Marketing Analytics  
**Topic:** GoFundMe fundraising campaign metrics and correlation analysis

## Assignment instructions

1. Visit [GoFundMe](https://www.gofundme.com/).
2. Review at least 10 charitable fundraising campaigns. Record the amount raised and the remaining **distance to goal** (goal minus amount raised). Exclude campaigns that have exceeded their fundraising goals.
3. Examine whether higher distance to goal is associated with more or less money raised. Use correlation analysis to quantify the relationship.
4. Interpret positive and negative correlations.
5. Evaluate other available campaign metrics, such as number of donors or donations and time since campaign creation, for relationships with the amount raised.
6. Prepare a report with the calculated correlations and what they mean.
7. Recommend ways to improve fundraising success, with supporting reasoning.
8. Submit the initial discussion response by the course deadline.

The assigned Excel correlation tutorial is [Using Excel to calculate a correlation coefficient and interpret the relationship between variables](https://youtu.be/sGlsdHD-lcA).

## Files

- `GoFundMe_Correlation_Analysis.xlsx` — campaign observations, formula-based metrics, Pearson correlations, and methodology notes.

## Method

The worksheet contains 25 manually selected observations from research notes compiled in October 2026. It includes a starting group of 10 campaigns and an additional 15 across multiple categories. Excel's `CORREL` function is used to calculate Pearson correlation coefficients.

- **Amount raised:** dollars received by a fundraiser.
- **Distance to goal:** fundraising target minus amount raised.
- **Goal achieved:** amount raised divided by goal.
- **Average donation:** amount raised divided by donation count.

## Main results

| Relationship | Pearson r (25 campaigns) |
| --- | ---: |
| Amount raised vs. distance to goal | +0.020 |
| Amount raised vs. number of donations | +0.399 |
| Amount raised vs. fundraising goal | +0.598 |
| Amount raised vs. percentage of goal achieved | +0.419 |

The correlation between funds raised and distance to goal is close to zero in this sample. The data also show how unusually large contributions can affect correlations in a small sample. These relationships should not be interpreted as evidence of causation.

## Data limitations

The sample is non-random, campaigns have different targets and ages, and the underlying GoFundMe totals may change. Original campaign URLs were not retained with every observation. Before citing individual fundraisers as verified research, independently check their public pages and record the retrieval dates and URLs. This dataset is intended for coursework and exploratory analysis, not population-level conclusions.
