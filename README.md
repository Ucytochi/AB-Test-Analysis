## [Project Description](#project_des)
---
Given two different datasets of a company's customers' activities (orders and visits) and a compiled list of hypotheses that may help boost revenue, we aimed at prioritizing these hypotheses and analyzing the results of the A/B test on the given data.

Basically, we looked at:

* Prioritizing hypotheses
* The cumulative revenue and cumulative average order size by groups.
* Convertion Rate by Groups
* The relative difference in cumulative average order size and conversion of one group over the other.
* The statistical significance of the difference in conversion and average order size between the groups using the unfiltered data compared with the filtered data.
---
## Datasets Features

<b>Hypotheses Dataset</b>

- `Hypotheses` — brief descriptions of the hypotheses
- `Reach` — user reach, on a scale of one to ten
- `Impact` — impact on users, on a scale of one to ten
- `Confidence` — confidence in the hypothesis, on a scale of one to ten
- `Effort` — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

<b>Orders Dataset</b>

- `transactionId` — order identifier
- `visitorId` — identifier of the user who placed the order
- `date` — of the order
- `revenue` — from the order
- `group` — the A/B test group that the user belongs to

<b>Visits Dataset</b>

- `date` — date
- `group` — A/B test group
- `visits` — the number of visits on the date specified in the A/B test group specified
---
The datasets used in this analysis were provided by Practicum100 by Yandex. I have not rights to share them.

The library used for the analysis - pandas, numpy, datetime, matplotlib, and scipy.


