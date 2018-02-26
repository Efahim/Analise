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

