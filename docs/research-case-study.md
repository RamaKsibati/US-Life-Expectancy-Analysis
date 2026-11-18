# Research case study — U.S. Life Expectancy

## Objective and scope

This four-person academic project investigated variation in life expectancy among the 50 U.S. states and associations with socioeconomic, environmental and health-related measurements. The team assembled state-level observations and explored many potential explanatory attributes.

The research was **nominated to participate in Senior Design Day**, according to participant Rama Ksibati. It was carried out using Minitab, Tableau, OpenMarkov and spreadsheet tools—not a custom-coded analytics pipeline.

## Preparation and methods

The team's presentation reports excluding rows outside the 50 states (for example, Puerto Rico), evaluating outliers with boxplots, and either retaining, replacing or removing exceptional data points according to the analysis. The original workbook and outlier report preserve this exploratory process.

Methods demonstrated across the presentation include:

- Descriptive statistics, histograms and boxplots
- Probability distribution fitting, including normal, lognormal and Weibull fits
- Correlation and single-/multiple-variable regression
- Hypothesis tests with explicit significance thresholds
- Confidence and prediction intervals
- Conditional probability / Bayesian network analysis
- Decision-tree and neural-network model exploration
- Visual comparisons of different categories of states

## Rama's research section

The presentation's **Appendix: Rama** describes five lines of inquiry.

### 1. Alcohol consumption, life expectancy and homicide rates

Rama checked outliers and fitted a lognormal distribution to alcohol consumption. Her exploratory plots initially suggested an unexpected positive trend with life expectancy, but the fitted-line analysis described the linear correlation as weak. She also investigated the relationship with homicide rates and used a small-sample t-test for selected high-consumption states.

### 2. Flu vaccination, life expectancy and education

She examined the distribution of vaccination rates, fitted relationships with life expectancy and educational attainment, and investigated prediction/hypothesis scenarios. Some reported directions varied across the exploratory views; the presentation itself is the source of these observations.

### 3. COVID-19 mortality, vaccination and life expectancy

She studied COVID-19 death cases alongside flu vaccination rates and life expectancy. Her discussion notes that relationships observed in pairs did not necessarily hold when variables were evaluated jointly.

### 4. Unemployment and life expectancy

She explored unemployment patterns and whether they corresponded to variation in life expectancy.

### 5. Education, homicide, unemployment and alcohol consumption

She investigated the fraction of educated residents and its relationships with homicide rates and unemployment, including how alcohol consumption and unemployment related in conditional analyses.

## Findings and interpretation

The strongest portfolio lesson is **critical interpretation of results**: different techniques sometimes suggested different relationships, and a positive trend in a graph did not necessarily imply a strong, meaningful association.

These are historical, ecological (state-level) analyses. They cannot establish direct individual-level effects or causal relationships. Sampling choices, confounding factors and the handling of outliers also limit the strength of some conclusions. Where the original presentation makes causal assertions, this case study presents them as exploratory associations rather than verified causal findings.

## Team attribution

The original slide deck credits Regina Arriola, Hadi Zalzali, Tanmayee Nukala and Rama Ksibati. The selected personal contributions above come specifically from the section labeled **Appendix: Rama**; broader team methods should not be credited to one member alone.

## Source artifacts

After upload, the repository will contain:

- [Full presentation](../presentation/US-Life-Expectancy-Team-Presentation.pptx)
- [Outlier detection report](../research/Outlier-Detection.docx)
- [Outlier workbook](../research/Identifying-Outliers.xlsx)
- [Original data archive](../data/Research-Data-Sets.zip)

**Status:** Supporting files are being prepared for repository upload. This Markdown case study is not a substitute for the original figures and tests in the presentation.
