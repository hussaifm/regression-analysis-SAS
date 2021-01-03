# Regression Analysis (Overview)
1.Simple linear regression model

2.Two-way ANOVA with interaction

3.Two-way ANOVA no interaction 

# Simple linear regression model
*Research question: Are cholesterol levels and resting blood pressure related?*

Statistical Model: Yi = α + βXi + ɛi

Dependent Variable: chol (serum cholesterol in mg/dl). 

Independent variable: trestbps (resting blood pressure in mm Hg on admission to the hospital)

Statistical hypothesis (HT): β = 0

Analyzing the data:

# Results
1) The slope of trestbps is 0.36402 and the corresponding p-value is 0.0321.

2) The correlation p-value is also 0.0321 which is similar to the p-value to the slope and the correlation coefficient is 0.12317.

# Conclusion 
1)	The pvalue is < 0.05, we reject the HT and there is relationship between the cholesterol levels and resting blood pressure. Also, because the slope is positive then the relationship is positive between cholesterol levels and resting blood pressure.

2)	We can conclude again that there is relationship between cholesterol levels and resting blood pressure. Moreover, the goodness of fit is not very good, the R squared is 0.0152

# Two-way ANOVA with interaction
*Research Questions:*

1) Are the interaction between target variable and sex variable significant?
HT:(β0)jk = 0

2) In males(M) = 1, are the population mean of cholesterol levels the same between those who have heart disease =1, and those who haven’t heart disease = 0.
HT: µMD1=µMD2 , where µ1D1  and µ1D2  denote population means of cholesterol levels in those with heart disease =1 and without heart disease = 0 in  (M)males=1

3) In patients with heart disease (1), are the population means of cholesterol levels the same among males and females?
HT: µMD1=µFD1, where µMD1 and µFD1 denote the population means of cholesterol levels in those with heart disease (1) among males and females.

Dependent variable: chol (serum cholesterol in mg/dl).

Fixed effect variable: Sex effect (Male = 1, Female = 0), heart disease effect ‘target’ (No heart disease = 0, w.heart disease = 1) 

Statistical model: Yijk=µ+βj+θ+(βθ)jk+εijk

# Results
1)From the first table below, the p-value of the interaction between the target and sex is 0.8208. 

2)From the second table below, the p-value for the males who have heart disease and without heart disease is 0.2006. 

3)The p value for the patients who have heart disease for both genders is 0.0077.

# Conclusion
1) The interaction between sex and target is not significant. 

2) Statistically, the cholesterol level is the same for those who have heart disease and those who don’t have heart disease among males only.

3) The cholesterol levels in those who have heart disease and those who don’t have heart disease are NOT the same in both males and females because the p-value is significant. 

# Two-way ANOVA no interaction 
*Research Question: Two research questions:*

Are the population means of the cholesterol levels same between males and females after adjusting disease affect?
HT:µM=µF where µM and µFdenote population means of the cholesterol levels in males and females.

Are the population means of the cholesterol levels same among those with heart disease and those without heart disease after adjusting sex effect? 
HT:µD1=µD0 where µD1 and µD0denote population means of the cholesterol levels in those who suffer from hear disease = 1, and no heart disease = 0

Dependent variable: chol (serum cholesterol in mg/dl).

Fixed effect variable: Sex effect (Male = 1, Female = 0), heart disease effect ‘target’ (No heart disease = 0, w.heart disease = 1) 

Statistical model: Yijk=µ+βj+θk+εijk, βj where is disease ‘target’ effect j = 1,0    0k is sex effect k = 0, 1

# Results  
 The corresponding p-value of the F test for target is 0.0092 and The corresponding p-value of the F test for sex is <.0001
# Conclusion 
The target effect is statistically significant after adjusting disease effect.

The sex effect is statistically significant after adjusting target effect. 

If we compare the means from post hoc table, it shows females have higher cholesterol levels than males because the p-value is significant. Also statistically, those who don’t have heart disease have higher cholesterol levels than those who have heart disease!

to be continued.....
