Built a simple A/B testing project as part of the Probability & Statistics for Machine Learning & Data Science course by DeepLearning.AI (Coursera).
Using session data from 4,186 users over 20 days, I compared a control group and a variation group to see whether a background color change affected average session duration.

Instead of relying only on built-in statistical libraries, I implemented several core statistical calculations manually, including sample statistics, degrees of freedom, t-value, p-value, and the final hypothesis testing decision process. This helped me better understand how statistical significance is determined in practice.

The analysis showed that the variation group had a slightly higher average session duration than the control group, and the hypothesis test result indicated a statistically significant difference at a 5% significance level.

Tech Stack: Python, NumPy, Pandas, SciPy
