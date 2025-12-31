# Marketing A/B Testing Project

## Project Overview

Marketing campaigns require significant investment, and not all advertisements lead to meaningful business outcomes. This project evaluates the effectiveness of an advertising campaign using A/B testing to determine whether showing ads leads to higher conversion rates compared to a public service announcement (PSA).

The analysis focuses on measuring incremental lift, statistical significance, and potential revenue impact to support data-driven marketing decisions. 

## Business Objectives

The primary goals of this project are to:

1.Determine whether advertising increases conversion rates compared to no advertising

2.Measure the incremental lift directly attributable to ads

3.Test whether observed differences are statistically significant

4.Identify optimal timing (day and hour) for ad effectiveness

5.Estimate the potential revenue impact if the campaign is scaled



## Project Workflow
1. Data Preprocessing

Loaded and cleaned the dataset

Converted boolean conversion values to integers

Checked and handled missing values

2. Exploratory Data Analysis

Compared conversion rates between Ad and PSA groups

Analyzed conversion trends by day and hour

Visualized patterns to understand ad performance timing

3. A/B Testing

Defined hypotheses:

H₀: Ads do not increase conversion rate

H₁: Ads increase conversion rate

Performed a two-proportion Z-test

Evaluated statistical significance using p-values

4. Incremental Lift Analysis

Calculated conversion rate lift between Ad and PSA groups

Measured additional conversions caused by ads

Estimated incremental revenue assuming a fixed revenue per conversion

5. Timing Impact Analysis (ANOVA)

Conducted ANOVA tests to evaluate the impact of:

Day of highest ad exposure

Hour of highest ad exposure

Identified statistically significant time-based effects


## Final Conclusion

1. A/B testing confirms advertising significantly increases conversions
2. Incremental lift shows conversions attributable to ads
3. ANOVA confirms conversion rates vary by day and hour
4. Campaign should be scaled with time-based budget optimization
5.Marketing team should optimize ad frequency and place ads in peak conversion hours.
