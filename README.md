# Global-Terrorism-Analysis
The United Nations Global Terrorism Analysis (UNGTA) dataset is a comprehensive repository of terrorist incidents recorded from 1970 to 1973, containing 1,982 incidents across 135 features. This project performs an end-to-end Exploratory Data Analysis (EDA) to uncover meaningful patterns in global terrorism — covering geographic hotspots, attack methods, target types, perpetrator groups, and casualty trends.

The dataset includes detailed attributes such as date, country, region, city, attack type, weapon used, target type, group name, number killed, number wounded, and binary flags for success and suicide attacks. Together, these features paint a rich picture of early-era global terrorism during the Cold War period.

The analysis follows the UBM framework — Univariate, Bivariate, and Multivariate analysis — supported by 15+ visualizations built using Matplotlib and Seaborn, with NumPy used for efficient statistical computations.

Key findings from the data reveal that 1970 was the most incident-heavy year with 651 attacks, while 1972 was the deadliest with 566 people killed — demonstrating that frequency and lethality do not always move together. The United States and United Kingdom dominate incident counts, reflecting Cold War-era domestic political violence by groups such as the Weather Underground and the IRA.

The most common attack method was Bombing/Explosion, while Firearms-based attacks proved to be the most lethal on average. Private Citizens & Property and Diplomatic targets were the most frequently attacked target types. The overall attack success rate was 85.1%, highlighting the critical importance of pre-emptive intelligence over reactive security responses.

Casualty data showed extreme right-skew — 62.6% of all attacks resulted in zero casualties, while a small number of events caused mass casualties up to 81 killed in a single incident. This distribution pattern required log-transformation for proper visualization and analysis.

Missing values were handled systematically: numeric casualty fields were filled with 0 (missing = no documented casualties), categorical fields were labeled 'Unknown', and binary flag columns were set to 0. Outliers were retained rather than removed, as extreme events are the most policy-critical data points in terrorism analysis.

The insights from this EDA are directly applicable to policy makers, security agencies, and humanitarian organizations. By identifying which regions, groups, attack types, and target categories carry the highest risk, stakeholders can allocate counter-terrorism resources more efficiently and develop data-driven prevention strategies.
