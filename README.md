# Marketing-Data-Analysis-A-B-Testing
This notebook performs a comprehensive analysis of derived from a marketing campaign dataset.

## Dataset

The dataset has 12 columns.

- **user id:** Unique identifier for each user.
- **date served:** The date the ad was served to the user.
- **marketing channel:** The channel through which the ad was delivered.
- **variant:** A/B test variant shown to the user.
- **converted:** Boolean indicating whether the user subscribed after seeing the ad.
- **language displayed:** The language used to display the ad.
- **language preferred:** The user's preferred language.
- **age group:** The user's age group.
- **date subscribed:** The date the user subscribed, if they converted.
- **date canceled:** The date the user canceled their subscription, if applicable.
- **subscribing channel:** The channel through which the user subscribed.
- **is retained:** Boolean indicating whether the user retained their subscription after one month.

## Conversion Rate Analysis Notebook

This notebook calculates the overall conversion rate and further examines conversion rates across various customer segments. The analysis also delves into the daily conversion rates for different customer categories. Finally, it presents key findings through effective data visualizations.

**Key Findings of Conversion Rate Analysis:**

*  Out of 7309 people marketed to, 1015 subscribed, resulting in an overall conversion rate of 13.89%
* **Marketing Channel**: Email has the highest conversion rate (35%), significantly outperforming other channels like Facebook, Instagram, and Push, which hover around 10% or less.

* **Variant**: The personalization variant shows a much higher conversion rate (16%) compared to the control group (7%).

* **Language Displayed**: German leads with a very high conversion rate (70%), followed by Arabic (50%), while Spanish and English have much lower rates (10%).

* **Preferred Language**: German also dominates as the preferred language (40%), while others like Arabic, English, and Spanish have lower rates (10–15%).

* **Age Group**: Younger audiences (19-24 years and 24-30 years) show the highest conversion rates (20%), while older groups (35+ years) convert less (5–10%).

* **Subscribing Channel**: Most channels, including Facebook, House Ads, Instagram, and Push, have near-perfect conversion rates (100%), except for Email (80%).
*  All marketing channels show a noticeable spike in conversion rates. However, From 12 January to 17 January, House Ads exhibited the lowest conversion rate compared to other channels.

## A/B Test Notebook

The goal of this analysis is to evaluate the effectiveness of personalized email messaging in driving user conversions, comparing it to generic upsell emails. By conducting A/B testing and performing statistical analysis, the study aims to identify whether personalized messaging leads to higher conversion rates across different language segments, providing insights for optimizing email marketing strategies.

**Main Hypothesis:** I hypothesize that personalized messaging in emails will lead to a significant improvement in user conversions compared to generic upsell emails.

**Null Hypothesis (H₀):** Personalized messaging has no impact on conversions compared to generic upsell emails.

**Alternative Hypothesis (H₁):** Personalized messaging has a significant impact on conversions compared to generic upsell emails.

**Key Findings of A/B:**

Statistical analysis, including a t-test and lift calculation, revealed a significant positive impact of personalized messaging on overall conversions.  Further segmentation by language showed varying effects, with Spanish and English speakers demonstrating significant improvements, while Arabic and German speakers showed no significant change. These findings provide actionable insights for optimizing email marketing strategies.

##  Required Libraries
The following Python libraries are used for data manipulation, analysis, and visualization:

*   `pandas`: For handling and manipulating data in DataFrame structures.
*   `numpy`: For numerical operations and computations.
*   `matplotlib`: For creating static visualizations and plots.
*   `seaborn`: For enhanced data visualization with a clean aesthetic.
*   `scipy`: for T-test








