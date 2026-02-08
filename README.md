# geo411-precipitation
R analysis of precipitation data for Buffalo and San Diego
Use of descriptive statistics, histograms, and hypothesis tests such as one sided and two sided t-tests
The precipitation of Buffalo over 1940 to 2025 follows a relatively normal curve while San Diego has a much drier climate skewing to significantly lower values. This is also shown by the p-value of the t-tests on the Buffalo data all being well under 0.01 while San Diego had a p-value of 0.95, showing that there is no true difference in means equal to zero
Tools: Descriptive measures functions such as "mean(precip$SanDiego)", histogram functions such as "hist(precip$Buffalo)" and t-testing procedures such as
#Unequal Variance Assumed, one-sided test
t.test(bfloLate, bfloEarly, alternative = "greater")

These tools and methods are an effective way to determine if data follows a normal distribution and if there is a true difference between means not equal to zero. This could be helpful to predict measures such as precipitation for the following year for the sake of agriculture.
