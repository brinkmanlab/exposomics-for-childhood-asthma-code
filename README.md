# Overview of code

Figures-2b-2d-S2-S3-2025-ExWAS-asthma-wheeze-allergy.ipynb:
Jupyter notebook containing Python code used to perform the two rounds of Exposome Wide Association Study (ExWAS) analyses, generates the forest plots used for Figures 2b, 2d and Supplementary figures S2, S3, and S4, and performs Wald tests.

Figure-5-gradient-boosting-5-year-asthma-and-SHAP-analysis.ipynb:
Jupyter notebook that imports the training data, generates a Gradient Boosting Classifier model to predict 5-year asthma, calculates SHAP values and plots the top 25 in a beeswarm plot (Figure 5a), calculates SHAP interaction values and plots interaction for the top 25 features in a heatmap (Figure 5b), and generates 2D partial dependence plots displayed in Figure 5c and Supplementary figurue 16.

Figures-4a-4b-S14-breastmilk-fatty-acid-associations-with-asthma-2025.ipynb:
Performs linear regression analyses that identified association between high adrenic acid levels in human milk and development of 5-year asthma in girls (Figure 4a), 8-year asthma in girls (Figure 4b). Also generates forest plot (Supplementary figure 14) of associations between GLA, DGLA, and AdA concentrations being in the upper quintile and 5 -year asthma after mutually adjusting for levels of all 3 fatty acids and expanded covariates including infant age at time of milk sample collection (n=911 children).

Olink_GSEA_results.Rmd:
Performs Gene Set Enrichment Analysis (GSEA) on cytokine levels measured in children's 1- and 5-year serum. Exposures assessed were DEHP levels in house dust greater than 75th percentile, daily prenatal hand sanitizer use, weekly or more chemical hand cleaner use, and 2 or more courses of systemic antibiotics (birth - 1 year of age). Significant results are output to a CSV file which is sent to a Jupyter notebook named "Plot_significant_olink_pathway_enrichment_results.ipynb".

Olink_GSEA_results_adrenic_acid.Rmd:
Performs Gene Set Enrichment Analysis (GSEA) on cytokines measured in children's 1- and 5-year serum for "adrenic acid levels in human milk > 75th percentile". Significant results are output to a CSV file which is sent to a Jupyter notebook named "Plot_significant_olink_pathway_enrichment_results.ipynb".

Plot_significant_olink_pathway_enrichment_results.ipynb:
Jupyter notebook that reads in CSV files containing significantly enriched pathways identified by the Olink_GSEA_results scripts. Generates the bubble plots used in Figure 4c (adrenic acid levels > 75tg percentile) and Supplementary figures 8c (daily prenatal hand sanitizer), 9a (weekly or more chemical hand cleaner), 10c and 10d (clean home >= 4 times per month between 0-3m), 12c and 12d (dust DEHP levels > 75th percentile), and 15 (two or more systemic antibiotic courses between birth and 12 months of age).
Also identifies leading edge genes found in at least 50% of the significant pathways from each GSEA which are used for characterization of T2-low, T2-low (T1-high), and T2-high cytokine profiles (Table 1). 

Supplementary-figure-13-alpha-diversity-mixed-effects-testing-vitamin_d-2025.ipynb:
For exclusively-breastfed infants, compares alpha diversity of those given a vitamin D supplement (birth-3m) or not (Supplementary figure 13a).Also performs a mixed effects linear model assessing alpha diversity association with vitamin D supplementation in exclusively-breastfed versus partial breastfed infants (Supplementary figure 13b).

Supplementary-figure-6-prenatal-cleaner-associations-with-asthma-with-postnatal-controls-2025.ipynb:
Performs follow-up sensitivity analyses for prenatal cleaner associations with asthma. Generates forest plots for Supplementary figure 6.

Supplementary-figures-S8-S10-cytokine-associations-2026-April-27-.ipynb:
Mann-Whitney tests, unadjusted and adjusted multiple linear regressions for differences in individual cytokine level differences associated with prenataly daily hand sanitizer use and cleaning home 4 or more times per month (birth-3m). Used to generated Supplementary figures 8a, 8b, 10a, 10b. 

Supplementary-figures-S9-S12-eosinophil-ratios.ipynb:
Unadjusted and adjusted associations between weekly or more chemical hand cleaner use (prenatal) and eosinophil/lymphocyte ratios (ELR) and eosinophil/neutrophil ratios (ENR) - Supplementary figure 9.
Unadjusted and adjusted associations between DEHP levels >75th percentile and eosinophil/lymphocyte ratios (ELR) and eosinophil/neutrophil ratios (ENR) - Supplementary figure 12.




