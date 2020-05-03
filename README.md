# Mediocre Social Network Apps Incorporated Continues Downward Spiral

_Nameless Hotshot Reporter_

_New Cal Times_

_May 2, 2020_

  More bad news appears on the horizon for the stock prices of Mediocre Social Network Apps Incorporated.  The company has struggled for the past few years as consumer interests have waned in its Headbook and Line apps in favor of the competitor’s  Instachat and TokTik. 
  
  The company hoped that as millions of Americans have more time on their hands (due to the recent pandemic), interests in their social network offerings would increase. The  company shareholders prefer to be cautious in these uncertain times, so they hired several statistical analysts from the renowned University of California, Berkeley to study their stock prices. 
The company’s stock prices have followed a dismal but variable downward trend since 2015, as evidenced by Figure 1:

![Original Data](https://github.com/fmcquarrie3/STAT153-Final-Project/blob/master/orig_price.png)

The volatility in stock price (as seen in the jagged shapes and temporary upticks)  prevents easy analysis or prediction. The volatility in price also changes over time, being more evident in the early years of the stocks after the company went public and gained its footing. 

  After several weeks of intense work, the UC Berkeley analysts have cracked the code of the behavior of the stock prices. The first accounted for the volatility in the prices through  a simple mathematical transformation of the data. After testing various curves that could have created the shape of the prices, they settled on a simple downward linear trend:
 
![Linear Trend](https://github.com/fmcquarrie3/STAT153-Final-Project/blob/master/linear.png)

 
I expect readers would be alarmed by how much the linear curve seems to oversimplify the data. Even with my background in economics and general statistics, I was dubious when I first viewed the analysts’ work. But they explained to me that the downward linear trend was only half of  the model behind the stock prices. They also discovered a particular type of noise that compounds the linear trend. 

  Noise is something that has to be accounted for in models of any kind on any subject. Rarely would we ever see a relationship in the real world that follows a perfect straight line, or a perfect parabola, etc. The data that we see and collect is some true relationship (linear, quadratic, logarithmic, etc), plus some noise. This noise arises from measures that we can’t control - e.g. a scale estimating weight is off by a tenth of a gram, or market measurements not aligned to capturing the market leanings perfectly. Noise can come in many forms.
  
  
  The Berkeley analysts discovered the noise that accompanied the linear trend was made up of two factors:  irreducible noise (i.e. market leanings are not rational and will never follow a perfect linear relationship) and noise that depends on the noise of the previous day. This means that information about the previous day of stock prices affects the value of today’s stock price. For example, when California’s shelter-in-place order was enacted on March 17, stocks across industries took a hit as economists worried about the effects of the virus. This downward shock compounded itself for the next few days, decreasing the company’s  stock price further. This trend continued until the marketing team came up with a campaign to entice people stuck at home to use the company’s apps, which created a temporary uptick in stock prices.  This time dependence pattern results in the local dips and rises that we see in the stock prices above.

  Once the analysts’ finalized their model of the stock prices, they forecasted (a fancy word for predicted) the stock price for Mediocre Social Network Apps Incorporated for the next 10 days and presented the following  graph to the shareholders:

![Forecast](https://github.com/fmcquarrie3/STAT153-Final-Project/blob/master/forecast_mar18.png)

  Unfortunately, the forecasts weren’t positive. It appears that Mediocre Social Network Apps Incorporated will continue to face dismal results unless they can use this national crisis to reflect and pivot their company’s offerings. 


#### Project Information:
_Note 1_: We’re aware that the stock data only goes up to the third quarter of September 2019 and not to the present, but by creative license we have extended the dataset to tell a more compelling story (as per the instructions of the assignment!)

_Note 2_: Github markdown doesn't support html tags, so attempting to center the images prevented them from being displayed in the final file. 

Authors: Francie McQuarrie, Purva Kapshikar

May 2, 2020

STAT153 Final Project
