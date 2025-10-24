# How has life expectancy at birth for women evolved relative to that for men in the Dominican Republic between 1960 and 2020?

## Abstract

Using World Bank World Development Indicators (WDI) data, this study examines the evolution of life expectancy at birth in the Dominican Republic between 1960 and 2020. The analysis compares female life expectancy at birth with male life expectancy at birth, capturing long-term trends in population health, gender disparities, and socio-economic shocks. Over the period, female life expectancy remained consistently slightly higher than male life expectancy, while both increased significantly overall. However, male life expectancy experienced a notable decline in 1965 during the civil war, reflecting the impact of socio-political instability on mortality. Over subsequent decades, female life expectancy grew slightly faster than male, leading to a modest increase in divergence by 2020. These patterns reveal persistent gender differences in longevity, as well as the influence of historical events on population health outcomes.

## 1. Question

How has life expectancy at birth for women evolved relative to that for men in the Dominican Republic between 1960 and 2020?

- **Female life expectancy proxy**: Life expectancy at birth, female (years)
- **Male life expectancy proxy**: Life expectancy at birth, male (years)

## 2. Data

- **Source**: World Bank World Development Indicators (WDI)
- **Indicators**:
  - Life expectancy at birth, female (years)
  - Life expectancy at birth, male (years)
- **Coverage**: Dominican Republic, 1960–2020
- **Notes**: National-level data only

## 3. Method

1. Filtered dataset for the Dominican Republic and selected female and male life expectancy indicators.
2. **Extracted relevant columns**: Year, Indicator Name, and Value.
3. Pivoted the dataset to create a side-by-side chronological comparison of female versus male life expectancy.
4. Produced a dual-line time series plot to visualize long-term trends, divergences, and the impact of historical events on mortality.

(Analysis is descriptive; no causal inference applied.)

## 4. Results

- **Female life expectancy (years)**: Increased steadily from 1960 to 2020, remaining consistently higher than male life expectancy.
- **Male life expectancy (years)**: Increased overall, but experienced a sharp decline in 1965 corresponding to the civil war.
- **Comparison**: Over the long term, female life expectancy grew slightly faster than male, producing a modest widening of the gender gap by 2020.

(Figure 1. Dominican Republic: Female vs. Male Life Expectancy at Birth, 1960–2020)

(Table 1. Pivoted dataset summary)

## 5. Interpretation

- The persistent higher life expectancy for women reflects biological, behavioral, and socio-cultural factors influencing longevity.
- The male life expectancy drop in 1965 highlights the vulnerability of population health to conflict and socio-political disruptions.
- The slight faster growth in female life expectancy over time suggests ongoing improvements in women’s health and survival relative to men.
- Understanding these trends is essential for planning healthcare, social services, and gender-sensitive interventions to address population health needs.

## 6. Limitations

- National aggregates may obscure regional or socio-economic differences in mortality and life expectancy.
- WDI estimates for earlier years rely on modeled data, introducing some uncertainty.
- The analysis is descriptive and does not isolate causal factors such as health interventions, environmental changes, or economic shocks.

## 7. Next Steps / Extensions

- Explore correlations between life expectancy and public health investments, GDP per capita, and education.
- Disaggregate by sex and age cohorts to understand how specific groups are affected differently over time.
- Compare the Dominican Republic’s life expectancy trends with other Caribbean countries to contextualize regional patterns.
- Investigate the long-term impact of conflict, epidemics, and policy interventions on male and female mortality differentials.
