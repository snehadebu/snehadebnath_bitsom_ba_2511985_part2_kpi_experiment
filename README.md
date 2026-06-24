# KPI Framework, Experiment Analysis and Recommendation

## Business Context

A subscription-based digital product company tested a new onboarding campaign to improve user activation and paid conversion.

Users were randomly assigned to:

- Control Group (existing onboarding)
- Treatment Group (new onboarding campaign)

The objective was to determine whether the new onboarding experience should be launched to all users.

## Dataset Description

The dataset contains user-level experiment data including:

- User information
- Experiment group assignment
- Traffic source
- Device type
- Trial activity
- Onboarding completion
- Paid conversion
- Revenue
- Refund requests
- Support tickets
- Engagement score

## North Star Metric

Paid Conversion Rate

This metric was selected because it directly measures the business outcome of converting users into paying customers.

## KPI Tree Summary

Primary Drivers:

- Landing Page Performance
- Onboarding Effectiveness
- Trial Quality

Guardrail Metrics:

- Refund Rate
- Support Ticket Rate
- Average Revenue Per User

## Data Quality Checks

The following checks were performed:

- Missing values
- Group count validation
- Duplicate user ID review
- Invalid binary value review
- Segment distribution review
- Revenue outlier review

## Experiment Analysis Approach

Control and treatment groups were compared across:

- Landing page visit rate
- Trial start rate
- Onboarding completion rate
- Paid conversion rate
- Revenue metrics
- Refund rate
- Support ticket rate
- Engagement score
- Days to convert

Additional analysis was completed by:

- Region
- Device Type
- Traffic Source

## Hypothesis Test Summary

Null Hypothesis:

The treatment does not improve paid conversion rate.

Alternative Hypothesis:

The treatment improves paid conversion rate.

Results:

- Control Conversion Rate = 3.17%
- Treatment Conversion Rate = 6.99%
- Relative Lift = 120%

The treatment demonstrated significantly stronger performance.

## Final Recommendation

Launch the new onboarding campaign.

## Assumptions and Limitations

- Limited experiment duration
- Future user behavior may differ
- Social traffic performance requires monitoring

## Screenshots Included

- summary_metrics.png
- hypothesis_test_output.png
- kpi_tree_preview.png
