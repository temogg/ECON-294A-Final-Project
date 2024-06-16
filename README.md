# ECON-294A-Final-Project
Hi Pedro,

Hi Pedro,

I quickly realized how daunting my original proposal was, so I decided to break it down into smaller chunks and compare unemployment rates to crime rates. I refocused my study on the relationship between unemployment rates and crime in five major U.S. states (California, Texas, New York, Florida, Illinois) and the national average. This analysis examines the relationship between unemployment rates and both violent and property crime rates from 2000 to 2020. Unemployment rates are the key independent variable, with median household income and poverty rates included as control variables.

Data for unemployment, crime rates, median household incomes, and poverty rates were compiled and merged on the 'DATE' column. Crime data were sourced from the FBI, while economic data came from the Federal Reserve of St. Louis (FRED). Multiple regression analyses were conducted using "StatsModels" in Python, with separate models for violent and property crime rates in each state and the national average.

To address multicollinearity, Variance Inflation Factor (VIF) was calculated for each predictor. Visualizations comparing actual and predicted crime rates were created to assess model accuracy.

My hypothesis suggests a positive correlation between unemployment rates and crime rates, driven by the notion that higher unemployment leads to increased financial strain and social instability. However, the strength of this relationship is uncertain due to various influencing factors. By including control variables, the analysis aims to isolate the effect of unemployment on crime rates.
