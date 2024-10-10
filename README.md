# Analysis of Dailly Nurse Staffing for Health Care Providers in Q1 of 2024

## Overview

This analysis focuses on the PBJ Daily Nursing Staff data from the first quarter of 2024 and the Provider dataset collected in September 2024. The goal was to understand staffing patterns across healthcare providers and how these patterns correlate with key performance indicators such as Quality Measure (QM) Ratings. The primary roles analyzed were Registered Nurses (RNs), Licensed Practical Nurses (LPNs), and Certified Nursing Assistants (CNAs), with an emphasis on contractor-to-employee ratios and their impact on care quality.

## Dataset 
- The dataset initially contained 14,626 providers, but the analysis was narrowed to 2,534 providers based on the contractor-to-employee ratio (threshold of 0.4 for each role).
- Providers that didn't use contractors or only used them for a small number of roles (such as administrative or supervisory) were excluded, as these roles showed little variation in contractor usage.

## Analysis
<p>The first step involves loading datasets such as the PBJ Daily Nursing Staff data for Q1 2024 and the Provider dataset from September 2024. Essential preprocessing steps, including handling missing data, ensuring the correct data types, and filtering for relevant features (e.g., contractor-to-employee ratios, RN staffing hours), were applied. Additional variables related to the distribution of staffing hours across RNs, LPNs, and CNAs were computed. This involved filtering providers based on contractor usage and excluding roles that did not demonstrate significant variation in staffing practices.</p>

<p>The analysis begins by exploring the data with basic summary statistics to identify general trends, such as the average staffing hours and turnover rates. Box plots, histograms, and correlation heatmaps were employed to visualize contractor-to-employee ratios for different roles (RNs, LPNs, CNAs) and to understand the relationships between staffing variables and QM ratings.
</p>
<p>A correlation matrix was calculated and displayed as a heatmap, highlighting key relationships between staffing levels (particularly RN staffing) and QM Ratings. This revealed some weak positive correlations, especially for total RN staffing hours and a strong negative correlation for staff turnover.</p>

## Insights and Key Findings

- RNs, LPNs, and CNAs are critical roles where contractors are frequently used.
- The highest demand for contractors was in states like Illinois, New York, Maryland, and Pennsylvania.
- A weak positive correlation between RN staffing and QM ratings was observed, indicating that higher RN hours are associated with better care quality.
- Turnover rates had a negative correlation with QM ratings, showing that high turnover reduces care quality.
- Providers with the lowest staffing hours and highest penalties were identified, and strategies were recommended for increasing staffing to improve QM ratings and avoid regulatory penalties.

## Recommendations
These were the actionable recommendations based on the analysis of the data made for a nurse staffing agency that specialize in long-term care facilities.
- Prioritize RN Staffing: Clipboard Health should focus its recruitment and placement efforts on RNs, as they are crucial to improving care quality and regulatory compliance. Facilities with low RN staffing hours, especially those categorized as "understaffed," are prime candidates for additional RN support.
- Target Understaffed Facilities: Facilities like Kent County Nursing Home (TX) and Lawrence County Manor (MO), which are severely understaffed, should be prioritized. Increasing RN and CNA hours in these facilities can improve their compliance with care standards, helping them avoid penalties and enhance their QM Ratings.
- Offer Temporary and Flexible Staffing Solutions: Clipboard Health should provide on-demand and temporary staffing services to facilities that struggle with maintaining consistent staffing levels, particularly during peak times or periods of high turnover. This service would be highly beneficial for large facilities, such as For-Profit - Partnership and Government - County, that face fluctuations in staffing needs.
- Consulting on Staffing Mix: Many facilities rely heavily on LPNs and CNAs, which may not be sufficient to meet care quality standards. Clipboard Health should offer consultation services to help facilities optimize their staffing mix, ensuring that the right balance of RNs, LPNs, and CNAs is maintained
- Expand Regional Presence: Clipboard Health can capitalize on the high demand for contractors in states such as Illinois, New York, Maryland, and Pennsylvania. By focusing marketing efforts on these regions, Clipboard Health can gain a competitive edge, provided it can offer competitive rates and high-quality staff.




