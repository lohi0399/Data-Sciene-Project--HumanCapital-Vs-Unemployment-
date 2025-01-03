# HumanCapitalVsUnemployment – Focuses on the relationship between human capital investment and unemployment.

#### Lohit Gandham
 -------------------------------------------------

A research inquiry which seeks to examine the potential linkages between government expenditure on health and education and the unemployment rates within different national contexts. This examination is predicated on the assumption that increased investment in human capital development may correlate with labor market outcomes, particularly the rate of unemployment.

NOTE:  We didn't upload any .csv files as the dataset as both our world bank data and the external datasource have been taken directly from the net, so that we always have updated data with us.

### Introduction to the Study:

In framing the research question, the introduction lays out the rationale for examining the interplay between public sector investment in health and education and unemployment rates. Given the current economic debates concerning the role of government in fostering a conducive environment for employment generation, this study becomes particularly relevant.

The central thesis to be explored is whether a robust investment in the health and education sectors by governments correlates with lower unemployment rates, thus implying that such investment could be a strategic lever to enhance employment prospects.

### Clarification of Research Question:

The fundamental research question posed - whether there's a correlation between health and education spending and unemployment rates over time - aims to probe the existence and nature of any such correlations. Additionally, it explores the potential of using these expenditure patterns to forecast future unemployment rates, offering a tool for planning and policy-making.

### Methodology Overview:

The methodology is divided into two key approaches:

1. **Data Extractions and Cleaning:**
   - This is the first step which involves loading our datasets from the web (so that the data always stays updated), and pruning/cleaning it so that we remove any undesired or inconsistent values which may be present.

2. **Data Visualization and Preliminary Examination:**
   - The initial step involves a cursory examination through data visualization techniques to discern patterns or correlations between government spending in health and education and unemployment rates.
   - This phase will also incorporate basic statistical analyses to characterize the data, highlight trends, and note any peculiarities that merit further scrutiny.

3. **Regression and Time Series Examination:**
   - The research will employ regression analysis to ascertain the strength and statistical significance of the relationship between unemployment and government expenditure on health and education, controlling for other factors such as population.
   - Time series analysis will also be applied, allowing for the investigation of how these relationships evolve over time and whether they can be predictive of future unemployment rates.

4. **Inference:**
    - This part mainly involves deriving informed decision from the visualizations and regression results we have so that we can make informed decision, between how the unemployement rate fares against the expenditures in health,population and education.
### Data Source Selection:

Two primary data sources will inform the study:

1. **World Development Indicators (WDI):**
   - The WDI (from World Bank)[1] database offers a rich dataset on various economic indicators, including those central to this study. Its credibility and frequent usage in academic research underpin its selection as a key data source.

2. **Population Data from OECD:**
   - Incorporating population data allows for a nuanced analysis that accounts for the scale of a country's population. The OECD's data repository is recognized for its accuracy and comprehensiveness, making it an appropriate choice for this aspect of the study[2].

### Significance of the Study:

Understanding the dynamics between public spending on health and education and unemployment rates is critical for policymakers. Such insights could guide the formulation of policies aimed at mitigating unemployment through strategic investments. Additionally, the forward-looking aspect of this research, with its predictive intent, could serve as a foundation for proactive policy planning.

Therefore in this research we intend to contribute to the problem on how investment in human capital influences labor market conditions and to furnish policy recommendations based on empirical evidence. In the following sections in this notebook we take you through how we implment our laid out methodology step by step.