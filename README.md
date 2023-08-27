This project is about Health, here I explored four datasets from World Health Organization:
- Prevalence of obesity among adults, BMI >= 30 (%);
- Life expectancy (years);
- Countries that have passed legislation on Universal Health Coverage (UHC);
- Alcohol consumption in litres of pure alcohol.

There are 176 observations.


There are 3 hypothesis tests:
1. Countries with a Universal Health Coverage have a higher Life Expectancy?
	H0: Countries with UHC have a life expectancy <= mean(life expectancy)
	H1: Countries with UHC have a life expectancy > mean(life expectancy)

2. Countries that have a higher obesity among adults have a lower life expectancy?
	H0: Countries with higher obesity have a life expectancy >= mean(life expectancy)
	H1: Countries with higher obesity have a life expectancy < mean(life expectancy)

3. Countries that have higher alcohol consumption have a lower life expectancy?
	H0: Countries with higher alcohol consumption have a life expectancy >= mean(life expectancy)
	H1: Countries with higher alcohol consumption have a life expectancy < mean(life expectancy)

Hypothesis test: ttest_ind
Significance level = 0.02

