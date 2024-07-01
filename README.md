# Global-Warming
Analysing the change in land and ocean temperatures over the years, focusing on different metrics, resulting in global warming
## Introduction
Global warming refers to the long-term rise in the average temperature of the Earth's climate system. This phenomenon is primarily driven by human activities, notably the burning of fossil fuels such as coal, oil, and natural gas, which release greenhouse gases (GHGs) like carbon dioxide (CO₂), methane (CH₄), and nitrous oxide (N₂O) into the atmosphere. I have collected my dataset from the Berkeley Earth Temperature Study and tried to do an analysis of the land, ocean temperatures, rise of temperature globally and then focused on the rise of temperature specifically in India.

I have used Python for this analysis and utilised various modules of it for the forecasting and plotting of visuals to better understand the trend and anomalies associated with the temperature rise in the world.
There are three datasets:
1. **Global Land and Ocean-and-Land Temperatures** : contains the temperature variations year wise for land and ocean rise specifically
2. **Global Average Land Temperature by Country** : country-wise segregated temperature variations over the years
3. **Global Land Temperatures By City** : city-wise temperature variations in countries

## Land And Ocean Analysis
![image](https://github.com/Koninikax/Global-Warming/assets/96631757/3ddabac0-f281-463b-aea8-09954b7b8892)

Both land and ocean temperatures exhibit an upward trend over time.
Land temperatures show a steeper increase compared to ocean temperatures.
The rising trend lines provide evidence of global warming and highlight the impact on our planet’s environment.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/46306890-b6d4-4f75-9e47-e534d5eeecdb)

Both land and ocean temperatures show an upward trend over time.
The increase is more pronounced after approximately 1950.
Rising temperatures indicate climate change.
Land and ocean warming contribute to overall global warming.
Ocean temperatures matter significantly due to their heat absorption capacity.
Human activities (e.g., burning fossil fuels) release greenhouse gases, intensifying the greenhouse effect.
The graph reflects this impact on Earth’s temperature.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/596e8f09-0b9e-4c1d-8c76-e6a4bcd251f8)

All lines show fluctuations but exhibit an overall upward trend.
Notably, the increase is more pronounced after approximately 1950.
The rising trend lines indicate long-term global warming.
Land temperatures directly impact ecosystems, agriculture, and human habitats.
Ocean temperatures matter due to their role in climate regulation and sea level rise.
Since the pre-industrial period (1850-1900), Earth’s average global temperature has increased by approximately 1.1°C (1.9°F).
Most of this warming has occurred since 1975, with a rate of roughly 0.15 to 0.20°C per decade12.
Accelerated Warming:
The rate of warming since 1982 is more than three times faster: approximately 0.36°F (0.20°C) per decade.
Recent decades have seen significantly accelerated temperature increases, especially in the Arctic region.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/8ea18e9e-f239-469d-85a4-4c7c115fdcae)


Land Max Temperature and Land Average Temperature have a strong positive correlation (close to 1). As land temperatures rise, the average temperature also increases.
Land and Ocean Average Temperature are highly positively correlated. This suggests that when land and ocean temperatures increase, they do so in tandem.
Implications:
The positive correlations indicate that various temperature metrics move together. When one rises, others tend to follow suit.
Global warming affects both land and ocean temperatures, impacting ecosystems, sea levels, and weather patterns.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/a64e8707-89b6-45de-b019-e9a47217f297)

The graph shows temperature anomalies (deviations from a baseline) over time.
Anomalies are positive when temperatures are higher than the baseline and negative when lower.
Consistent Warming Trend:
All four lines (Land Average, Land Max, Land Min, and Land/Ocean Average) exhibit an upward trend.
This consistent warming suggests long-term global climate change.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/9cebfe0d-0e78-4e76-8b7e-647f14758aa2)


Trend Component:
The top panel shows a clear upward trend in temperature over time (from around 1860 to 2000).
This suggests a long-term increase in temperatures, which aligns with global warming observations.

Seasonal Variation:
The middle panel represents the seasonal component. It captures regular fluctuations within each year.
Seasonal variations are expected due to natural cycles (e.g., summer and winter).

Residuals (Noise):
The bottom panel displays residuals—irregularities not explained by trend or seasonality.
These random fluctuations may result from short-term weather patterns or measurement noise.

## Country-wise Analysis

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/e4717877-f7d6-42a5-a5c3-cf130b7e47d0)

Upward Trend: The majority of countries exhibit an upward trend in average temperatures. This consistent rise suggests a global phenomenon.
Evidence for Global Warming: The overall upward trajectory aligns with scientific consensus on global warming due to greenhouse gas emissions.

![newplot](https://github.com/Koninikax/Global-Warming/assets/96631757/6dfc2e78-10b9-47ca-8c35-16116ba1a0ee)
![newplot](https://github.com/Koninikax/Global-Warming/assets/96631757/a5e15af5-eff0-4f84-b851-042dd5d42f3f)

These two maps show the difference in temperature rise over the years globally.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/0de43597-7740-467b-8885-30ac5384806f)

Temperature and Uncertainty: As average temperature increases, there is a wider spread in temperature uncertainty.
Yearly Variation: The color-coded data points represent different years, showing how temperature predictions have become more uncertain over time.
Higher Temperatures: The most pronounced uncertainty occurs at higher average temperatures.
 This suggests that predicting temperatures becomes more challenging as they rise.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/705a65cd-7570-4626-b09d-7131e7b133a3)

Increasing Trend: The red line slopes upward, indicating a general increase in average temperature.
Global Warming: The rise in temperature suggests global warming.
Recent Acceleration: The steeper slope near 2000 suggests a more rapid increase in recent years.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/b50496e1-9b25-4043-b351-d6123f0f82e2)

The forecast graph represents the temperature forecast for India using the ARIMA (AutoRegressive Integrated Moving Average) model.
Temperature Trend: The forecasted temperature remains relatively stable over the years.
Confidence Interval: The shaded area around the forecast line likely represents the confidence interval or uncertainty range.
Limited Variation: The flat trend suggests minimal temperature fluctuations.


## Analysis of Temperature Variations in India

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/9799bcbb-2aba-4456-8024-4892a770deee)

Upward Trend: The trend line indicates a consistent rise in average temperature.
Time Span: The data spans from around 1800 to just beyond 2000.
Climate Change Impact: The graph highlights the impact of climate change on India’s regional climate.
The sudden spikes or drops could be outliers caused by extreme weather events, data errors or any other major factors.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/480ccec9-2463-4ab5-ae45-f95d0165af3f)

Slope (Rate of Change): The slope of approximately 0.00465 indicates that, on average, the temperature increases by about 0.00465 degrees Celsius per year.
Intercept (Baseline): The intercept of around 16.549 degrees Celsius represents the initial temperature value (around the year 1800).
Overall Trend: The positive slope suggests a gradual rise in average temperatures over the observed period.
Long-Term Climate Change: This model provides evidence of long-term climate change, which is essential for understanding global warming and its impact.
 However, this linear regression captures a simplified trend. 

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/4753fd60-a410-4d92-b6d0-414b16b1321b)


Average Temperature: The top plot shows the actual average temperature data over time. It fluctuates between approximately 24.5 and 25.5 degrees Celsius.
Trend: The middle plot represents the trend component. It remains relatively stable around 22.5 degrees Celsius, capturing the long-term behavior of temperature changes.
Seasonal Variation: The third plot displays pronounced fluctuations around zero. This component represents the repeating seasonal pattern in temperature variations.
Residuals (Irregular Component): The bottom plot shows random scatter around zero. These residuals represent the noise or irregularities left after removing trend and seasonality effects.

![image](https://github.com/Koninikax/Global-Warming/assets/96631757/480edf80-b1da-4a5a-87b7-b3d499f9370c)

Since Abohar was recorded to have the maximum temperature over the range of years being analysed, I did a forecast for just specifically the Abohar region.
Stable Trend: The red line remains relatively flat, indicating minimal temperature change over the forecast period (2015 to 2035).
Confidence Interval: The shaded pink area represents uncertainty. Temperatures may range between approximately 26°C and 27°C.
Consistent Climate: According to this model, Abohar City’s temperature is expected to remain stable in the coming years.

## Conclusion
First, the historical data reveals a consistent upward trend in average temperatures over centuries, emphasizing the impact of climate change. The linear regression model reinforces this, projecting a gradual increase in temperatures. Additionally, the seasonal decomposition highlights recurring patterns, aiding our understanding of long-term climate variations. Finally, the ARIMA forecast suggests stable temperatures, but with some uncertainty. Collectively, these graphs underscore the urgent need for climate action, as rising temperatures pose significant challenges to ecosystems, weather patterns, and human well-being.

