# Digital Transformation and Entrepreneurial Development in Nepal

## Research Project: Does Digital Transformation Boost Business Establishments?

This repository contains research materials for analyzing the relationship between digital transformation and entrepreneurial development in Nepal. The study examines whether improvements in digital connectivity are associated with the formation of new businesses using annual macroeconomic and Information and Communication Technology (ICT) indicators.

**Research title:** *Does the Digital Transformation Boost Business Establishments? Impacts of Digital Transformation for Entrepreneurial Development in Nepal*

**Authors:** Asmita Subedi and Jeebanath Adhikari

**Study country:** Nepal

**Data source:** World Bank — World Development Indicators (WDI)

**Study period:** 2006–2024, subject to data availability and model-specific estimation samples.

---

## 1. Introduction

Digital transformation has become an important factor in economic development, innovation, and entrepreneurship. Digital technologies enable businesses to access information, communicate with customers, participate in online markets, and improve operational efficiency.

In Nepal, expanding internet access, mobile connectivity, broadband infrastructure, and secure digital services may create opportunities for entrepreneurs to establish and operate businesses. However, digital infrastructure alone may not be sufficient to promote entrepreneurial development. Digital literacy, financial access, institutional quality, and a supportive business environment may also influence the creation of new businesses.

This research investigates the relationship between digital transformation and entrepreneurial development in Nepal using a composite Digital Transformation Index (DTI) and new business density as the principal outcome variable.

## 2. Research Objectives

The main objective is to examine the relationship between digital transformation and new business formation in Nepal.

Specific objectives are to:

- Construct a composite Digital Transformation Index using selected ICT indicators.
- Examine the short-run relationship between digital transformation and new business density.
- Investigate the possibility of a long-run relationship using appropriate time-series methods.
- Examine temporal predictive relationships between digital transformation and entrepreneurial development.
- Discuss the implications for digital infrastructure, entrepreneurship policy, digital literacy, and access to finance.

## 3. Research Questions

1. How can digital transformation in Nepal be measured using ICT indicators?
2. Is digital transformation associated with changes in new business density?
3. Is there evidence of a short-run or long-run relationship between digital transformation and entrepreneurial development?
4. Do past values of digital transformation help predict new business density, or vice versa?
5. What policy measures could help Nepal translate digital development into entrepreneurial opportunities?

## 4. Data and Variables

The study uses annual indicators from the World Bank's World Development Indicators database.

| Variable | Description | Role |
|---|---|---|
| New Business Density (NBD) | New formal business registrations relative to the working-age population, according to the source definition | Dependent variable |
| Digital Transformation Index (DTI) | Composite index constructed using selected ICT indicators | Main explanatory variable |
| Internet Users | Individuals using the Internet (% of population) | DTI component |
| Fixed Broadband Subscriptions | Fixed broadband subscriptions per 100 people | DTI component |
| Mobile Cellular Subscriptions | Mobile cellular subscriptions per 100 people | DTI component |
| Secure Internet Servers | Secure Internet servers per 1 million people | DTI component |

**Data source:** [World Bank — World Development Indicators](https://databank.worldbank.org/source/world-development-indicators)

The effective sample may be shorter than 2006–2024 because of missing observations and the requirements of individual econometric models. The final sample period and number of observations should be reported from the actual estimation output.

## 5. Methodology

### 5.1 Data Preparation and Exploratory Analysis

The analysis begins by collecting annual indicators, checking data availability, identifying missing observations, and examining the variables' distributions and trends.

Descriptive statistics and graphical analysis help identify patterns and potential data-quality issues before econometric estimation.

### 5.2 Digital Transformation Index Using PCA

Principal Component Analysis (PCA) is used to combine selected ICT indicators into a composite index.

PCA transforms correlated variables into principal components that summarize variation in the original data. The first principal component may be used as the Digital Transformation Index if supported by its loadings and explained variance.

The analysis should document the standardization procedure, PCA loadings, explained variance, and interpretation of the resulting index.

### 5.3 First-Difference Ordinary Least Squares

First-difference OLS is used to investigate the short-run association between changes in digital transformation and changes in new business density.

A simplified model is:

\[
\Delta NBD_t = \alpha + \beta \Delta DTI_t + \varepsilon_t
\]

Where:

- \(\Delta NBD_t\) represents the change in new business density.
- \(\Delta DTI_t\) represents the change in the Digital Transformation Index.
- \(\alpha\) is the intercept.
- \(\beta\) measures the estimated relationship between the two changes.
- \(\varepsilon_t\) is the error term.

The interpretation depends on the estimated coefficient, statistical uncertainty, diagnostic tests, and the model's assumptions.

### 5.4 Autoregressive Distributed Lag Model

The ARDL framework can be used to investigate dynamic relationships between variables and, when its assumptions are satisfied, distinguish short-run effects from a possible long-run relationship.

An error-correction representation can describe how deviations from a long-run relationship are adjusted over time.

Before interpreting ARDL estimates, the analysis must check integration properties, lag selection, sample size, and the validity of the model. Standard ARDL bounds testing is not appropriate for variables integrated of order two, I(2).

### 5.5 Granger-Causality Testing

Granger-causality testing examines whether the past values of one variable provide additional predictive information about another variable.

The results should be interpreted as evidence about temporal predictive relationships under the selected model, not as definitive proof of economic causation.

Small annual samples can make these tests sensitive to lag selection and reduce statistical power.

## 6. Analytical Workflow

The research follows these general steps:

1. Collect annual data from the World Development Indicators database.
2. Inspect indicator definitions, units, and data availability.
3. Prepare a consistent dataset for analysis.
4. Conduct descriptive statistics and trend analysis.
5. Construct the Digital Transformation Index using PCA.
6. Examine the time-series properties of the variables.
7. Estimate the first-difference OLS model.
8. Estimate ARDL and error-correction models if the data support them.
9. Conduct Granger-causality tests using an appropriate specification.
10. Evaluate model diagnostics and robustness.
11. Interpret the results and discuss policy implications.

## 7. Expected Research Contribution

This research contributes to the discussion of digital transformation and entrepreneurship in Nepal by bringing together multiple indicators of digital connectivity into a composite index.

The study also distinguishes between short-run changes and potential long-run relationships, subject to the limitations of the available annual data.

The findings may help inform discussion about how digital infrastructure, entrepreneurial capabilities, access to finance, and institutional support interact in the development of Nepal's entrepreneurial ecosystem.

## 8. Policy Implications

Potential policy areas arising from this research include:

- Expanding affordable and reliable internet and broadband infrastructure.
- Improving digital literacy and entrepreneurial skills.
- Increasing access to finance for start-ups and small businesses.
- Supporting secure digital payments and online business services.
- Improving the business registration environment.
- Strengthening institutional support for entrepreneurship and innovation.

These are potential policy implications to assess against the empirical evidence, rather than predetermined conclusions.

## 9. Limitations

Several limitations should be considered when interpreting the analysis:

- Missing observations may reduce the effective sample size.
- Small samples can make time-series estimates and statistical tests less reliable.
- The PCA-based index depends on the selected indicators and construction method.
- ICT infrastructure indicators do not directly measure firm-level digital adoption.
- New business density captures formal business formation rather than every form of entrepreneurial activity.
- Observational time-series models may identify associations without establishing causality.
- Other factors, including economic conditions, financing constraints, institutional quality, and policy changes, may influence new business formation.

## 10. Reproducibility

For transparent and reproducible research, the repository should document:

- The data source and indicator codes.
- Data-cleaning procedures and treatment of missing values.
- The PCA method and component diagnostics.
- The econometric equations and lag-selection criteria.
- The estimation period and observation count for each model.
- The statistical software and package versions.
- The regression results, diagnostic tests, and robustness checks.

The actual files and dependencies should be listed according to the repository's current contents.

## 11. Conclusion

This research investigates whether digital transformation is associated with entrepreneurial development in Nepal using ICT indicators, a composite Digital Transformation Index, and time-series econometric methods.

By examining short-run relationships, potential long-run dynamics, and temporal predictive relationships, the study seeks to provide evidence relevant to Nepal's digital development and entrepreneurship policies.

The conclusions should be based on the verified estimation results and interpreted in light of data limitations, model assumptions, and the distinction between association and causation.

## References and Data

- World Bank. *World Development Indicators*. https://databank.worldbank.org/source/world-development-indicators

Consult the World Bank's indicator metadata for the exact definitions and units of the variables used in the analysis.

## Authors

**Asmita Subedi**  
Research interests: Digital transformation, entrepreneurial development, and applied data analysis.

**Jeebanath Adhikari**

---

*This README documents the research design and analytical framework. Update it with verified results, figures, tables, and the actual repository structure before treating it as the final research documentation.*
