## Training Project (online marketplace)

### Goal: 
Assisted Yandex team in the analysis of the data from a real estate agency. It is an archive of sales ads for realty in St. Petersburg, Russia, and the surrounding areas collected over the past few years. The goal is to learn how to determine the market value of real estate properties and define the parameters. This project is useful for building an automated system that is capable of detecting anomalies and fraudulent activity.

### The following tasks were completed:
1. Studied the following parameters: price, vehicle's age when the ad was placed, mileage, number of cylinders, and condition. Plotted histograms for each of these parameters. Studied how outliers affect the form and readability of the histograms.
2. Determined the upper limits of outliers, removed the outliers and store them in a separate DataFrame, and continued to work with the filtered data.
3. Used the filtered data to plot new histograms. Compared them with the earlier histograms (the ones that included outliers). Drew conclusions for each histogram.
4. Studied how many days advertisements were displayed (days_listed). Plotted a histogram. Calculates the mean and median. Described the typical lifetime of an ad. Determined when ads were removed quickly, and when they were listed for an abnormally long time.
5. Analyzed the number of ads and the average price for each type of vehicle. Plotted a graph showing the dependence of the number of ads on the vehicle type. Selected the two types with the greatest number of ads.
6. Identified factors impact the price most. Took each of the popular types detected at the previous stage and studied whether the price depends on age, mileage, condition, transmission type, and color. For categorical variables (transmission type and color), plotted box-and-whisker charts, and created scatterplots for the rest.

### Examples of graphs:
![image](https://github.com/gzhuldas/Training_EDA_Statistics_Yandex/assets/72769986/0a9a391f-2ef3-4f6f-854b-e1af783cdd40)


![image](https://github.com/gzhuldas/Training_EDA_Statistics_Yandex/assets/72769986/faebd5fd-6edb-4e7c-bb8d-d152d5a39a3f)


![image](https://github.com/gzhuldas/Training_EDA_Statistics_Yandex/assets/72769986/43804442-5e42-4232-a585-35fee9b01c36)


