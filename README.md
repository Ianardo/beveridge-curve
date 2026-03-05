# Beveridge Curve Analysis
## Background
The Beveridge Curve is a graphical representation of the relationship between unemployment and job vacancies. The curve typically slopes downward, indicating the intuitive fact that as unemployment increases, the number of job vacancies tends to decrease, and vice versa. 

The position on the curve can tell us where we are in the business cycle. For example, during a recession, we would expect to see higher unemployment and fewer job vacancies, placing us on the lower right part of the curve. Conversely, during an economic expansion, we would expect to see lower unemployment and more job vacancies, placing us on the upper left part of the curve.

Shifts in the curve itself (as opposed to movements *along* the curve) can indicate changes in the efficiency of the labor market. That is, if there is a shift outward (to the right), it might tell us that for a given level of unemployment, there are more job vacancies than before. Ergo, the labor market has become less efficient at matching workers to jobs. We have seen this in the aftermath of the 2008 financial crisis, and more recently, in the aftermath of the COVID-19 pandemic. We will explore these regime shifts in the Beveridge Curve in this notebook.

## Specifications
### Data
The data for this analysis comes from the St. Louis Federal Reserve's [FRED](https://fred.stlouisfed.org/) database. We will be using the following series:
- Unemployment Rate [(UNRATE)](https://fred.stlouisfed.org/series/UNRATE)
- Job Openings: Total Nonfarm [(JTSJOL)](https://fred.stlouisfed.org/series/JTSJOL)

### Repo Structure
- `main.ipynb`: The main Jupyter notebook containing the analysis and visualizations.
- `requirements.txt`: A list of Python packages required to run the notebook.
- `img/`: A directory containing the generated chart from the analysis.
- `raw_data/`: A directory containing the raw data files downloaded from FRED.

## Findings
The analysis reveals that, indeed, there have been significant shifts in the Beveridge Curve during the periods following the 2008 financial crisis and the COVID-19 pandemic. The curve has shifted outward, indicating a decrease in the efficiency of the labor market in matching unemployed workers to available job vacancies. This suggests that structural changes in the economy, such as changes in the types of jobs available or changes in worker preferences, may be contributing to this phenomenon.
