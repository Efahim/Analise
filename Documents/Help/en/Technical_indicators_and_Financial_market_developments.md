
# Technical indicators
## Introduction
Indicators in general are indicators that allow a comparison of different values. In the context of capital markets and market technology, these are key figures that can only be compiled from past prices and revenues.
Many key figures directly generate trading signals (buy, sell) when certain levels are reached. Others help analysts identify which indicators make sense at all in the prevailing market environment.
While indicators can assume all possible values, oscillators fluctuate around a certain average and can be bounded up and down. Furthermore, the indicators can be structured according to their fields of application.
Many indicators can not be clearly assigned to a category because they contain components of various calculations. The classification serves to understand that indicators have specific tasks and sometimes only provide meaningful signals in combination.
## Indicators
### trend following indicators
#### Introduction
Indicators of this group try to find a prevailing trend, ie
To identify course direction. They follow the current trend, i. Trading signals can not be generated until a certain trend has established. They can therefore be used in trend phases - the more sustainable a trend phase, the more successful they are. In phases of sideways movements
Deliver false signals. Only pure trend phases are displayed, but not overdrive phases up or down - oscillators are used for this.
#### MA - Moving Average
The best-known trend-following indicator is the Moving Average. It calculates only an average price and thus shines the price. In practice, there are several moving averages. If the price breaches the MA from below, the trading signal is obtained. If the average is breached from above, the signal will be generated.
#### SMA - Simple Moving Average
Here, the simple arithmetic mean is calculated. Depending on the length of the observation period t, short-, medium- or long-term trends are displayed. Possible periods are 38, 100 and 200 days.
#### WMA - Weighted Moving Average
The weighted moving average weights each price differently. In general, the lower prices are weighted less than the more recent ones.
#### EMA - Exponential Moving Average
The exponential moving average is calculated iteratively from all past prices, i. with different observation periods / existing historical data, different EMAs are calculated despite consideration of the identical title.
EMAt = EMAt-1 + (SF * (Ct-EMAt-1))
EMAt = SF · Ct + (1-SF) · EMAt-1
The advantage of the weighted MAs (WMA, EMA) is that they react faster to trend changes than the simple MAs, since the younger ones are weighted higher than the older ones. In Figure 3, the various MAs are exemplified by the Dax values of 1.5. until 1.11. 2007 - over six months. This period is used for all example charts shown here.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech1.png)

Figure 3: Charts of different moving averages
#### MACD - Moving Average Convergence / Divergence System 
This indicator can serve both as a trend follower and as an oscillator. The MACD is a combination of two lines. The first is made up of the difference between two EMAs, one shorter and one longer, of the course to be considered. The second line results as the EMA of this difference, the so-called trigger.
The MACD line therefore fluctuates around the zero line and the larger this distance, the greater the divergence: the EMAs diverge. That is, the prevailing trend is intensifying. If the MACD line crosses the trigger from below, a buy signal is signaled, otherwise a sell signal. The greater the distance to the zero line, the more successful the signals are, since then the trend intensity is greater than near the zero line. Buy-signal and sell-signal mean price will rise or price will fall.
If a divergence between the MACD line and the price trend is observed, this indicates a trend change. Figure 4 shows a MACD with trigger.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech2.png)


![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech3.png)


Figure 4: MACD chart
#### CCI - Commodity Channel Index
The CCI quantifies the distance to an SMA of the average daily prices. The daily average rate is calculated as the arithmetic mean of the day high, low and close price. If a certain measure is exceeded, an incipient trend is assumed (see Fig. 5, p.7) The usual distance for the generation of trading signals is the distance of 100:

• CCI rises above +100: buy

• CCI drops below +100: hold

• CCI drops below -100: sell

• CCI rises above -100: hold

If the CCI fluctuates in the band of the two signal lines, the use of an oscillator is recommended, as the price does not follow any trend [10]. Figure 5 shows the course.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech4.png)

Figure 5: CCI chart
In the first step, the so-called significant price is determined for each period (day, week, month, etc.). This is calculated as the arithmetic mean of the highest, lowest and closing prices. This results in a simple MA (ie a SMA of the significant price, usually over twenty periods). Finally, in the third step, the CCI is calculated as the difference between the significant price and its SMA divided by 0.015 times the standard deviation from the typical price to the SMA. The factor 0, 015 is an arbitrary constant proposed by the developer Lambert, so that the indicator is mainly in the band between -100 and +100.
### Sales Indicators
#### Introduction
The conversions have a very high relevance for the technical analysis. The indicators in this group point to volume trends and can, in conjunction with other indicators, also provide trading signals on their own.
#### OBV - On Balance Volume
This indicator is intended to show whether liquidity flows into or out of a paper. The OBV corresponds to a sales chart, which is compared to the daily change in prices. With rising prices the volume is added to the OBV of the previous day, with falling it is deducted. So if the prices rise without the indicator taking part in this movement, ie if there is divergence, the prices are at a top and falling prices could follow. In conjunction with his MA trading signals can thus be generated.
The calculation depends on today's closing price:
this is higher than yesterday: OBV = OBVgestern + volume today
this is lower than yesterday: OBV = OBVgestern - volume today
are both the same: OBV = OBVgestern
The assumption that all sales are made on a positive day is a simplification and quite questionable. Therefore, the OBV is considered obsolete today.
It is also criticized that the OBV does not pay any attention to the strength of a price movement and there are now indicators that describe the price / volume ratio in more detail (see ADL).
#### Accumulation / Distribution Line
This line represents a further development of the OBV concept by calculating a continuous index as a volume indicator and weighting today's price performance with the revenues. Depending on the ratio of the closing price to the average price of a day, a certain percentage of the daily turnover is added to or subtracted from the ADL value of the previous day. If, for example, the closing price above the mean, one part is added.
Compared to the OBV only one reasonable part of the turnover is considered. Both indicators are shown in Figure 6 for the SAP share.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech5.png)

Figure 6: ADL and OBV chart of the SAP share
### Volatility Indicators
#### Introduction
Volatility is the measure of the magnitude of price fluctuations. The higher the flexibility of the prices, the less certain are the predictions for trend determination. The indicators in this group therefore do not provide any information on trends in the paper, but give indications of trends in the volatility, ie whether the fluctuation range increases or decreases.
#### standard deviation
This value is rarely used as a stand-alone indicator, but is usually part of other indicators. The standard deviation, however, is a vivid example of a volatility indicator and also provides independent indications of price behavior (see Fig. 7, p. 11) For example, very high or low values may indicate a possible trend change. But it is very difficult to find usable parameters, in this case the period for the calculation. Too short an area turns out to be too often, while a too long one responds to traits, so you miss a lot of trading opportunities. Statistically, scattering is only meaningful for symmetrical distributions with a central maximum. Asymmetries and local minima reduce the validity of the derived predictive values. 
#### Chaikin's Volatility
Volatility is defined as an expanding range between daily high and low. An MA is calculated on this difference and the indicator is finally the rate of change of this MA (see Fig. 7, p. 11)
Chaikins's Volatility = ROCx (MAy (H - L))
Chaikin interprets the progression so that a short-term steep rise indicates an impending ground, ie a trend reversal. A long-term decline, however, is to indicate an imminent high point (trend change down).
## Oscillators
### Momentum oscillators
#### Introduction
The basic consideration in this type of oscillator is the observation that price movements are accelerated at the beginning and end of a trend, i. a trend tends to be S-shaped. This type of indicator can therefore indicate an imminent trend change.
#### MOM - Momentum
Momentum is one of the most commonly used indicators. From today's closing price, the closing price of n days is subtracted. The result is a graph oscillating around the midpoint line (see Fig. 8, p. 12)

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech6.png)


Figure 7: Chaikin's Volatility and Standard Deviation
MOMt = Ct - Ct-n + 1
This indicator is already integrated in the first form in the software POSET.
#### Trix
The name of this oscillator is derived from its calculation - the ROC of a triplet EMA (tripple exponential) is mapped. The triple glazing should filter out insignificant price fluctuations and place the emphasis of the weighting in the middle of the period (see Fig. 8, page 12, complete formula see section A.1, page.38
#### RSI - Relative Strength Index
The RSI is an evolution of the MOM and measures the intrinsic strength of a title by correlating the upward movement with the downward movement over a given period of time. The indicator therefore fluctuates between 0 and 100. Leaving the extreme zones (20, 80 or 30, 70) is often used as a trading signal (see Fig. 8, page.12)

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech7.png)


Figure 8: RSI, MOM and Trix
#### Chaikin's Oscillator
This oscillator is a further development of the ADL line in which two EMAs are formed on them and whose difference is represented as an oscillator. So it indicates a trend change of the ADL line, i. a turn of the
Liquidity that flows into and out of the market (see Fig. 9, p.13)
Chaikin's Oscillator = EMAx (ADL) - EMAy (ADL)
### Trend Determination and Trend Indicators
#### Introduction
As described in section 2.2.1.1 (page 3), trend-following indicators only work in trend phases. There are estimates that only about 30 percent of the time, prices follow a trend and move sideways the rest of the time. So one needs an aid to determine if the market is in a trend phase [11]. Various indicators have been developed, the most popular of which are presented in this section.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech8.png)

Figure 9: Chaikin's Oscillator of the SAP Share
#### DMI - Directional Movement Index
This system generates two lines (+ DI, -DI) that measure the positive and negative movements of the course. It is assumed that today's high will be above yesterday's level if the trend is positive - in a downtrend analogous to today's low below yesterday's level. To calculate the + DI and DI, first calculate the so-called true range, which is defined as the maximum (TRt = max (TRa; TRb; TRc)) of the following differences:

TRa = Ht - Lt; Daily high today minus daily low today

TRb = Ht - Ct-1; Day high today minus the closing price yesterday

TRc = Lt - Ct-1; Daily low today minus closing price yesterday

The difference between today's high and yesterday's high equals the + DM and the difference of the analog lows the -DM. The + DI is now calculated by dividing this + DM by the TRt (analogous to -DI). The parameter of this indicator is the time. The default value is t = 14 days, i. the + DI14 is the quotient of the sum of the + DM of the last 14 days and the sum of the TR of this range. 
The DMI is now calculated from the difference of + DM and -DI divided by the sum of both numbers multiplied by 100%. The result is a percentage that is used to quantify the expression / intensity of the prevailing trend.
Due to its high volatility, the DMI is rarely represented. In Figure 10 (p.14) it can be seen including + DI and -DI together with the ADX.

#### ADX - Average Directional Index
While the two sub-indices + DI and -DI mainly determine the trend direction, the ADX is used exclusively for the determination of the trend strength. The ADX is the sealed variant of the DMI, as shown in Figure 10 (page 14). With increasing ADX, ie increasing trend strength, the crossing points of the DI lines are used as signals. Cuts the
+ DI the -DI from below, it is a buy signal, the other way around a sell-signal.
If the ADX is falling, these signals are ignored. Since in the time window in Figure 10 all crossing points are generated when the ADX is falling, this system does not provide any signals during the period.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech9.png)

Figure 10: DMI chart (with + DI and -DI) and the ADX
#### AROON-up / down indicator
The AROON indicator consists of two lines - the AROON-UP and the AROON-DOWN line. Here, too, the basic idea is: with a rising trend, rising highs always follow each other - with decreasing trend analogously lower and lower lows.
Both lines are calculated from the number of periods (days, weeks, etc.) that have elapsed since the last high (or low).
The parameter is the period length, which in practice is between 8 and 30 periods. A stable trend is when one of the two lines is stable over about 70%. The intersection of both lines indicates a possible future trend reversal.
The weak point of this indicator is the generally increasing volatility in the markets. Information is being distributed and processed faster and faster, so that trend phases are interrupted more and more often by consolidation phases.
#### AROON Oscillator
This indicator is nothing else than the difference between AROON-UP and - DOWN and therefore does not generate any new insights and is mentioned here only for the sake of completeness.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech10.png)

Figure 11: AROON chart (UP, DOWN and Oscillator)
 # Classification with Support Vector Machines
## Theory
A Support Vector Machine (SVM) is a certain type of machine learning and a so-called classifier, i. With this method, a set of objects can be divided into two classes based on their characteristics. Each feature (e.g., size, weight, age) of an object represents one dimension of its vector - examples of classification are e.g. male / female or fruit / vegetables.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech11.png)

Figure 12: SVM classification for linear separable data
The characteristics must be present numerically and, if necessary, transformed (for example, the gender: male: = 1, female: = 2). A hyperplane in space is calculated which separates both classes and has a maximum distance to them (see Fig. 12, p.16)
Because most datasets are not directly linear, SVMs allow you to use special functions to transform the data into higher-dimensional spaces and linearly separate them. The learning algorithm for linear separation only calculates with the scalar product of two input vectors (objects) xiyi. These are now transferred by means of a function Φ into a higher-dimensional space, e.g. through the following transformation.
Thus, it suffices here to calculate only the square of ˙x and ˙y in the R2 in order to be able to linearly separate the data in a three-dimensional space and thus to be able to perform a nonlinear separation in two-dimensional space.
It is often not the case that the training objects are all linearly separable, not even in higher dimensions. The cause, in addition to a nonlinear relationship, may be measurement errors or just outliers. In order for a classification to be possible, false classifications are allowed, but their errors are each penalized with a value (distance to the separation level), the sum of which is multiplied by a value C, which is freely selectable, and added to the optimization problem wird13. The larger the value chosen for C, the more outliers are considered and their errors minimized. The maximization of the distance during optimization is less important (see Fig. 13). Thus, with increasing C, the generalizability of the model decreases.
In this paper, using financial time series, the financial market forecast as a classification will increase. Price will fall, ie. After training an SVM with the help of historical values (price development, indicators), it should use predicted values to predict a rising or falling price through classification.
## Integration in poset
In the software Poset there is the class Operator, from which two types of operators are derived:
#### TransformOperator: If an operator of this type is applied to a column (dimension) of an SVM matrix, it alters these values. Currently integrated are Operators for binarization, scaling, and standardization.
#### AppendOperator: Operators of this class add new columns (ie new dimensions to the vectors) to an SVM matrix - the following two derived classes exist:
#### LagOperator: This operator extends the matrix by historical values of the time series (see [6], page 62) - parameter is the number of backward periods.
#### TrendOperator: The matrix is added to three columns (rising, falling, neutral). Parameters are here on the one hand the time horizon and the threshold. If the value of the time series exceeds the threshold within this horizon, the values +1, 0, 0 are added (analogously if the threshold falls below the threshold, or if the value remains within the band).
Since the indicators in the SVM matrix add columns, they were derived from the AppendOperator class. The operators receive their values from the so-called DifferenceBuilder, which transfers a maximum of two values each (minuend and subtrahend). In this type of implementation, therefore, only indicators with two different values can be used.
For the implementation the following indicators were selected:
MACD as a trend following indicator.
RSI as a momentum oscillator. The normal momentum can be mapped by the already integrated lag operator.
AROON as trend indicator.
The parameters for the indicators can be set like the other operators via the POSET interface for the predictors (see Fig. 15, p. 19)
# Experiment description
The software POSET makes it possible to train, evaluate and test different SVMs. On the one hand, different kernel functions and their parameters can be varied in POSET. On the other hand, the

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech12.png)

Figure 14: Class diagram operators
![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech13.png)

Figure 15: Indicators in POSET
Datasets (training, validation and test datasets and their predictors) are moved (rolled).
In this work, only the RBF kernel is used because it is both universal and has fewer parameters than the sigmoide and the polynomial kernel. Another reason is that the RBF kernel causes less numerical difficulties than e.g. the polynomial.
In the first step, the reference models are created. The data are based on the stocks of the DAX index. The target variable is the binarized (dichotomized) difference between the close and the open price of one day (+ 1 = price has gone up, -1 price has fallen). It should be predicted whether the price will rise or fall the next day.
It is assumed that the performance of the past five trading days contains sufficiently hidden information for the forecast of the future price development. In [6] on page 86, Dumse has achieved the (local) optimum (weighted hit rate) for eight days in his model. At just about one to three days in terms of the hit rate, the SVM predicted permanently rising values. In the test period, prices increased in 68.9% of the cases and the optimum was 68.9%.
The six dimensions of the vector that should lead to the forecast are, on the one hand, the five close-open differences of the previous day. Secondly, the difference between the open price of the current day and the close price of the previous day. These values are called in POSET predicators and can be additionally binarized, standardized or scaled to the value range [0; 1].
The setup of the experiment is as follows: First the training partition is defined between 1.12.2005 and 30.11.2006, the validation partition is the following month (ie December 2006) and finally the test partition is the next month (January 2007). The validation partition is used to determine the optimal parameters and then apply them to the test partition. The weighted hit rate serves as a guideline.
This configuration is then postponed and evaluated eleven times, one month at a time (see Fig. 16, p.21). As a training partition, twelve months are chosen as it is assumed that this periodicity also contains information that can be used by the SVM.
These values now serve as benchmarks for the following experiments, each of which adds an extra dimension to the vectors. Their values are provided by the selected technical indicators with their default parameters and the forecasting result is compared with those of the reference models. In the second step, these individual indicators may also be varied in their own parameters, if that suggests an improvement. In the third step, the reference model is extended by all indicators at the same time and the resulting forecasting result is evaluated. In doing so, several dimensions are added to the vectors.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech14.png)

Figure 16: Evaluation area
# Evaluation
## readings
### Reference Models
For each of the twelve evaluation areas, the best combination of parameters is chosen based on the validation partition and applied to the test partition. Since all parameters are also applied to the test partition, here you can specify the difference between the chosen and the optimal result.
A short test on four evaluation partitions of the reference configuration provides information on the parameter range to be examined (see Fig. 17, p. 22) As you can see in the graph, the range for γ above 2-8 seems to be uninteresting, but as a precaution 2-4 is chosen as the upper limit. The range for C may also be relevant above 215, but is not considered here for two reasons. On the one hand, the computational burden for large C increases disproportionately high in the context of this work, and on the other hand, lower parameter values are better for the generalizability of the models
suitable (see Fig. 13 on page 17).
Since the RBF kernel is chosen here for the SVM, there are only two parameters (γ and C) that can be varied. The parameter range for the grid to be examined is set to be 2-1 ≤ C ≤ 215 and 2-20 ≤ γ ≤ 2-4 (the step size of the exponent is 2). To decide whether the predictors should be binarized, scaled, standardized, or not transformed, they are tentatively applied to a validation partition. Figure 18 (p. 23) shows that the best results are achieved without the use of an operator.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech15.png)

Figure 17: Weighted hit rates of four evaluation partitions of the reference configuration
Figure 19 (p. 27) also graphically shows how the measured values are collected. Based on the optimum of the validation partition, the weighted hit rate is measured on the test partition. Since POSET automatically applies the entire parameter range of the training and evaluation partition to the test partition, it is also possible to measure the optimum and specify the difference to the result obtained. In this example on the first validation and test partition, the optimal combination of parameters is determined as C = 215 and γ = 2-14 and applied to the test partition. This results in a weighted hit rate of 62.4%, with a theoretical optimum of 70.1% (Δ = 7, 7 percentage points, or 12.3%). The test partition thus represents the application of this forecasting method.
The measured values for the model described above are reproduced in Table 1 (page 24) and represent the reference values.
### MACD
In the next step, a MACD indicator will be added to the standard model as an additional dimension. Initially, the default parameters (12, 26 and 9 periods) are used. The measured values are shown in Table 2 (page 24).

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech16.png)

Figure 18: A validation partition of the reference model with transformed predictors by operators
Changing the MACD parameter values to 2, 4 and 3 days changes the result as shown in Table 3 (page 24). Parameter values of 6, 13 and 5 days give the values in Table 4 (page 25).
### AROON
Now an AROON indicator will be added to the standard model as a further dimension. At first, the default parameter (8-30 periods, here 19 days) is used. The measured values are shown in Table 5 (p. An Aroon with the parameter of two days gives the results in Table 6 (p. 25). If you extend the standard model by an aroon with the parameter of one day, the calculations result in the values in Table 7 (p. 26).

### RSI
The extension of the standard model by an RSI over 14 periods leads to the results in Table 8 (p. 26). The RSI over two days leads to the results in Table 9 (p. 26).
### Combination of RSI, Aroon and MACD
In this part of the experiment, the three different indicators are combined. The MACD and RSI are used with their default parameters.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech17.png)

Figure 19: Example measured value on partition 1 of the reference model
### Naive forecast
In order to have a comparison to another forecasting method, the naive prognosis is considered here.
At the same time, the market trend is being continued: if the price rose yesterday, a rising price is also forecasted for today.
## evaluations
### Introduction
Looking at the results qualitatively, the standard model can be compared first with the naive prognosis to give an orientation in the evaluation of the prognosis values.
When looking at the results, tendencies appear to be apparent: in all experiments, the average hit rate deviates from that of the reference model. However, in order to rank the models and test whether the deviations are also significant, statistical methods must be used. In [5] it is described why for the measured values in this work the usual methods (for example t-test) are unsuitable. For example, questionable whether the measured values are normally distributed. If they are not, the tests will be corrupted because more extremes will occur than with a normal distribution. Table 13 (page 30) shows the weighted hit rates of all models. The average values and the resulting estimates are not meaningful for two reasons. On the one hand, the partitions are of different lengths and, on the other hand, it is debatable whether mean values can be compared over different areas [5].
In [5] the Wilcoxon sign-rank test is compared to compare two classifiers, and the Friedman test is used to compare several classifiers. If significant differences are identified in the latter, a post-hoc test may (and only if so) be performed - a Nemenyi test is recommended. This usually follows a positive H test (Kruskal-Wallis test) - so it is intended for independent samples. A Friedmann test for dependent samples is generally followed by a Wilcoxon Wilcox test or a Dunn ranking test.

### Wilcoxon Sign Rank Test

This test verifies the locations of two non-normally distributed measurements in small samples. It is based on replacing the measurements with their rankings. This has the advantage that the distributions of the ranked measures under the null hypothesis do not depend on the particular form of distributions of the underlying observations.
The initial question is whether there are significant differences between the distributions of the measurements of the respective sample halves (H1 hypothesis) or not (H0 hypothesis). Two series of measurements are always compared, in this case always the reference model with a measurement extended by one indicator. This is a two-sided test. The one-sided test tested whether one sample was significantly larger or smaller than another.
The models with the indicator AROON 19 and the naïve prognosis at a confidence level of 90% are significantly different from the reference model. The AROON 19 model is even at a level of 95%, the naive even at 97.5% significantly differentiate. All other models do not differ statistically from this. Only at a confidence level of 50-60% are the models with an AROON 2 or a MACD 2,4,3 better than the reference model. Statistically, this has no significance.
The comparisons with the RSI tests result in too few rank differences (n = 4) and therefore too many identical statements (m = 8, also called bonds), in order to make a statement about a possible distinctness. These models are statistically indistinguishable from the reference model.
In order to statistically investigate whether the two deviant models are significantly better or worse, one-sided tests are carried out in which αzeiteitig = 2αeinseitig. With an alpha risk of 0.1, it can be said that both models are significantly worse than the reference model.
### Friedman test
The common approach to investigating whether several samples differ significantly is parametric analysis of variance. The problem here, as in the t-test, is the essential requirement of the normal distribution of the samples. For this reason, Demsar proposes the Friedman test in [5] for the comparison of classifiers. It is suitable for the comparison of paired, ie dependent, samples and the nonparametric counterpart to the parametric ANOVA.
For each partition, ranks are formed between the models and the average rank is determined for each. If the differences between the models are only random (H0 hypothesis), each rank would have to be approximately equal in the models, i. the rank sums or the average ranks are about the same. The counter-assumption (H1 hypothesis) states that there is a non-random, systematic difference between two samples - one model is better than the other.
Figure 22 compares the distribution of measurements and their rankings.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech18.png)

Figure 22: Comparison of the distribution of the measured values and their ranking values
# Conclusion
The experiments carried out here do not achieve any significant improvements in the predictive value of SVMs by adding the indicators used here to the parameters used. The Wilcoxon test revealed that the reference model, augmented by an AROON-19 or the naïve prognosis, is significantly (α = 0, 1) worse than the reference model alone. Significant improvements through the inclusion of indicators can not be ruled out in general.
This study can be extended by the following studies:
• Modifications to the standard model
- Variation of the predictors
- Variation of the parameters
- Variation of kernels
• Modification of the parameters of the indicators used here
• Different combinations of the indicators used here
• Addition of further indicators
• Addition of additional titles (eg DOW JONES index)
• Addition of other values, such as Currency or exchange rates or base rate
Finally, the correlations between the results of the validation and test partitions could be studied to assess the stability of the model selection. A correlation analysis between the training and validation or test partitions would allow statements about the generalizability of the procedure.
The ranges of the parameters in this study are on the one hand not very dense and on the other hand very small. This applies both to the SVMs and to the indicators. It is to be considered whether such a large number of parameters to be varied instead of a grid evaluation (as used here for the SVM parameters) may not even be used for determining the parameters themselves evolutionary algorithms Nnten. One method that is particularly suitable for problems with high numbers of parameters (such as in industrial manufacturing processes) is that of swarm intelligence. As a result, the number of parameter values to be examined could be reduced to testable numbers.
