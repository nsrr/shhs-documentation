# Data Analysis Tip Sheet

A number of key sleep-related variables in the Sleep Heart Health Study are not normally distributed.  Modeling these variables as the dependent variables violates assumptions of linear regression.  Achieving normality, or identifying alternative methods to use these data is important not only for consistency across publications, but also for accurate reporting of results.

This document highlights key analytical issues and provides “food for thought” as well as some suggestions for use of selected sleep-related variables in SHHS.

**Respiratory Disturbance Index (RDI):** A number of RDI variables exist in the data set. These variables are highly skewed, with many people having small values and relatively few with very large values.  When RDI is the dependent variable log-transformation is recommended.  Since RDI=0 cannot be log-transformed, one should add some constant.  Key questions are: what value should the constant take? Should the constant be added to every RDI value or just to RDI=0? It turns out that slightly different answers to these seemingly minor questions could have non-trivial effects on the result.  It seems that the following transformation performed best, at least in some subsets:

`NEWVA = log(OLDVAR + 0.1).`


**Obstructive Apnea Index (OAI):**  There is one OAI index in the data set. It reflects obstructive events associated with a 4% desaturation or arousal.  Nearly 30% of the cohort has a zero value for this variable.  Since there are many zero values, some SHHS investigators have chosen to dichotomize the variable. For instant, >=3 obstructive events or >=4 central events per hour would constitute a positive outcome. One could also use this construction as a predictor variable.

**Central Apnea Index (CAI):**  Several variables describe central breathing events, with different thresholds for desaturation and requirement/non-requirement of arousals.  Central events are uncommon, with ˜58% of the cohort having zero values. Thus, when central events are of interest, some shhs investigators have chosen to dichotomize these variables. For instance >=3 central events or >=4 central events would constitute a positive outcome.  This construction would also be used as a predictor variable. This approach does not require use of a continuous distribution, and also allows the analyst to conduct sensitivity analyses.

**Sleep Stages:** These data are reported in the data set as integers. Stage 1 and stage 3 – 4 are not normally distributed, but stage 2 and REM sleep are. Thus, to use these data as continuous dependent variables, stages 1 and 3 – 4 must be transformed. Some shhs investigators have transformed the latter two variables with the following formula `–log(-log(P+0.001))`. (NOTE: since the data are integers, values must be divided by 100 prior to transformation to yield proportions).

**Sleep time below 90% O2:** The percent of total sleep time with oxygen levels below 75%, 80%, 85% and 90% were recorded. Since a considerable proportion (25%) of the cohort had zero values, some shhs investigators have dichotomized this variable according to whether they spent >5% and >10% of sleep time with oxygen levels below a specific O2 level. This construction can be used as a predictor or outcome variable.

**A General Note:**  back-transformation of the difference between two means of a log-transformed variable generates the geometric mean ratio (which is, more or less, the ratio of two medians). Not so for log-log transformation.

**Independent Continuous Predictors:**

The RDI and other sleep variables are often key predictors, rather than dependent variables. In such cases, log transformation is not needed but the challenge is even greater:  How to model those variables appropriately?  Three general approaches are commonly used (not necessarily mutually exclusive).  For each approach, we mention below key issues that out to be considered.

_Paradigm 1_:  Statistical hypothesis testing. Fit the variable as is (continuous), test the null on its coefficient. If significant, fit a quadratic term as well.  If NOT significant, conclude a linear relation (or log-linear if using a log-linear model).

Drawbacks:

- There is a clear trend to minimize the use of P-values in statistical inference.
- A straight line and parabola are not the only possible shapes of the dose-response function in the data

_Paradigm 2_:  Categorical analysis.  Categorize the variable.  Issues:  how many categories?  Where to place the cutoff values?  A key consideration is having “enough data” within each category.  Some people prefer “clinical cutpoint” but sometimes the argument is circular since clinical cutpoints are (or should be) based on research findings.

Drawbacks:

- Results could be strongly dependent on the location of cutoff points.
- Tail effects are sometimes hidden (collapsed into an average effect of the last category)
- Categorical analysis is often followed by a “test for trend” which is erroneously interpreted as a test for monotonic dose-response. It is not.
- The risk function is forced to behave as a step-function
(References available).

_Paradigm 3_:  Non-parametric or semi-parametric dose-response functions. Not as sensitive to location of cutoff points. Fewer model-imposed restriction. Visual display of the dose-response function.

Drawbacks:

- A bit more complicated to fit (though not much)
- No “concise” list of point estimates (though can be read off the graph)
- Other (beyond the scope of this document)
(Reference and a PowerPoint presentation available)

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

<div class="center">
<div class="btn-group">
  <a href=":pages_path:/3-dataset-introduction.md" class="btn btn-success">
    Dataset Introduction
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>

