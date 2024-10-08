# BH-PCMLAI-PA1-M5 - Will a Customer Accept the Coupon?

Notebook Link: https://github.com/n-tanay/BH-PCMLAI-PA1-M5-SUB/blob/main/BH-PCMLAI-PA1-M5-Coupon-Acceptance-by-Customer.ipynb

## Overview

This analysis aims to understand the key factors that influence customers to accept or reject coupons, focusing on identifying the characteristics and conditions most likely to lead to coupon acceptance. The findings are based on data from multiple features, including occupation, social context, destination type, income, and age.

## Technical Details

*   Data was analyzed using chi-square tests to determine relationships between features and coupon acceptance.
*   The analysis focused on key features including occupation, social context, income, age, and destination type.
*   Visualizations such as histograms and KDE plots were used to understand the distribution of coupon acceptance across these features.

## Key Findings

The findings section will focus on the characteristics of individuals with a Coffee House coupon done as part of the Independent Investigation. While this is geared towards the Coffee House coupon segment, the concepts and steps taken to arrive at these distinctions can be applied to all the other coupon types.

### Profile of a Person Who Accepted a Coupon

*   **Occupation**: Healthcare-related occupations, such as healthcare practitioners and technical roles, have the highest acceptance rates due to predictable schedules and regular breaks.
*   **Frequency of Coffee House Visits**: Moderate visitors (4-8 times per month) are more likely to accept coupons, indicating familiarity with and appreciation for such offers.
*   **Social Context**: Traveling with friends significantly increases coupon acceptance, suggesting social influence plays a role.
*   **Age**: Younger individuals, particularly those below 21, show higher acceptance rates, likely due to a greater interest in deals and social activities.
*   **Income**: Moderate-income individuals ($75,000 - $87,499) are more receptive to coupons, likely seeking value.
*   **Destination**: Non-urgent destinations correlate with higher acceptance, implying customers are more relaxed and open to trying new offers.
*   **Other Factors**: Acceptance is higher during moderate weather and for coupons with shorter expiration times (e.g., 2 hours).

### Profile of a Person Who Did Not Accept a Coupon

*   **Occupation**: Sales-related roles, which have less flexibility, tend to have lower acceptance rates.
*   **Frequency of Coffee House Visits**: People who rarely visit or visit too frequently (more than 8 times) show lower interest in accepting coupons.
*   **Social Context**: Those traveling alone or with passengers other than friends tend to reject coupons, suggesting less social influence.
*   **Age**: Older individuals tend to have lower acceptance rates, possibly due to different spending habits.
*   **Income**: Very high or low-income individuals are less interested in coupons, likely due to differing perceived value.
*   **Destination**: People headed to work or urgent destinations are less likely to accept coupons, indicating that time constraints reduce engagement.
*   **Other Factors**: Extreme weather and longer expiration times negatively impact coupon acceptance.

## Statistical Test Results

While this is geared towards the Coffee House coupon segment, the concepts and steps taken to arrive at these distinctions can be applied to all the other coupon types.

A chi-square test was conducted to compare customer profiles and their likelihood of accepting coupons:

*   **Occupation, coffee house visitation frequency, passenger context, and destination type** are strong predictors of coupon acceptance, with all having statistically significant relationships (p-values < 0.05).
*   The features tested show that occupation, social context, and destination type have the strongest influence on acceptance.

## Next Steps and Recommendations

While this is geared towards the Coffee House coupon segment, the concepts and steps taken to arrive at these distinctions can be applied to all the other coupon types.

1. **Targeted Marketing Campaigns**: Focus on healthcare professionals, younger individuals, and those traveling with friends to maximize coupon uptake.
2. **Optimize Coupon Timing and Expiration**: Offer coupons during non-urgent times and moderate weather, with shorter expiration times to drive a sense of immediacy.
3. **Leverage Social Context**: Promote group offers to encourage social use of coupons.
4. **Focus on Flexible Occupations**: Target people with predictable schedules and more break opportunities, like healthcare practitioners.
5. **Tailored Offers Based on Income**: Different income groups respond better to different types of offers; adjust campaigns accordingly.
6. **Adjust Messaging for Urgent Destinations**: Avoid targeting people heading to urgent destinations or provide relevant, quick incentives.
7. **Test and Iterate**: Conduct A/B testing for combinations of targeting strategies to refine and improve campaigns.

These insights provide a data-driven foundation for more effective coupon marketing campaigns, enabling targeted, context-aware promotional strategies that align with customer behavior.