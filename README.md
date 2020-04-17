# MinorStrokeMetaanalysis

This will be the Repository for the R script to perform a meta-analysis of the 90 day recurrence rate of minor stroke.

The plan is to use the 
- Packages dmetar, meta, and metafor
- Random effects model
- Double arcine transformation (Freeman & Tukey, 1950)
- Clopper Pearson method for 95% confidence intervals of a proportion

... to calculate the pooled stroke recurrence rate.

I will measure heterogeneity by calculating Q, I^2, and tau-squared.
A metaregression will be performed if there is high heterogeneity.

The underlying code and overall supervision is provided by gntem2.

References:
Freeman, M. F., & Tukey, J. W. (1950). Transformations related to the angular and the square root. Annals of Mathematical Statistics, 21, 607--611.
