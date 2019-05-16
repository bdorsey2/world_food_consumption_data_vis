# world_food_consumption_data_vis
## Author: Brian Dorsey
### Worldwide Food/Feed Consumption

### Introduction: 
My core dataset is the global food balance data from the United Nation’s Food and Agriculture Organization (FAO). It represents the human food and livestock feed consumption by country from 1961-2013. I augmented the dataset with world population data from the same time period in order to show relative measures of consumption in the context of country population. For one plot I pulled a small set of data around the top U.S trade partners to see the connections between the top agricultural exporter (U.S.) and top consumption countries. I found the FAO data in the Kaggle dataset repository, the population data from the world bank data website, and trade data from a fortune.com blog.
I chose the main dataset out of my deep interest in food. I would consider myself a foodie and a serious home cook. Over time I’ve become interested in how food is grown, and where our food comes from. I’m fascinated by the things that can be inferred about people and society just by learning about what they eat. The FAO dataset provides a comprehensive global picture of what and how much countries eat around the world. I wanted to explore the differences in diets among different countries and the overall trends of consumption. Within the context of country population, consumption trends highlight other important issues such as, the distribution of resources and environmental sustainability. 


### Summary of Data: 

![hist1961](https://user-images.githubusercontent.com/40878527/57831442-fbb93080-7769-11e9-869e-0231416f5285.png)

![hist2012](https://user-images.githubusercontent.com/40878527/57831420-f0fe9b80-7769-11e9-9e94-3839ae96a93e.png)

These histograms show a summary of a time lapse plot which shows the number of countries grouped by a ratio of people to consumption. Consumption is in 1000 Tonne units. The mass of the distribution has moved down from 1961-2013 showing that there is more food consumption per person. 

![barplot](https://user-images.githubusercontent.com/40878527/57831115-150dad00-7769-11e9-8b2c-2a85c6d50370.png)
 
The barplot shows world consumption of both food and feed by year. There is a clear increasing trend with a much more food than feed consumption. In 1992 there is a large jump due to additional country tracking.

![boxplot](https://user-images.githubusercontent.com/40878527/57831381-d0cedc80-7769-11e9-9ae5-4aa01370d537.png)
 
This boxplot shows the top 10 consumed food groups by year as a percentage of world food consumption that year. Interestingly, starch used to compose the largest percentage of world consumption early in the timeline. By the end of the timeline, starch is the lowest consumed food group of the top 10, and vegetables compose the largest percentage of world consumption.

![scatterplot](https://user-images.githubusercontent.com/40878527/57831158-2c4c9a80-7769-11e9-9acb-93f10492763f.png)
 
This scatterplot shows country food and feed consumption plotted against population. I fitted a linear regression line to demonstrate that countries above the line have higher consumption per population relative to the average, and countries below the line have lower consumption per population relative to the average.

![chloropleth](https://user-images.githubusercontent.com/40878527/57831340-b563d180-7769-11e9-9711-fb9a941123c5.png)

This chloropleth map is a 2013 screenshot of a time lapse showing the population data by country. Country population is important in providing context to country consumption as show in the other plots.

![connectionmap](https://user-images.githubusercontent.com/40878527/57831486-1b505900-776a-11e9-87b4-5915f82dd0c6.png)

The connection map shows the U.S’s top trade partners and total trade dollars in billions. This is pertinent to the world consumption data, as the U.S is the largest agricultural exporter in the world, and is closely tied with the top food consuming countries.

![heatmap](https://user-images.githubusercontent.com/40878527/57831456-083d8900-776a-11e9-808a-a955cf9b8cae.png)

This heatmap focuses on the top consuming country in the world – China. It shows the most consumed food groups in China from 1961-2013. The standout observations are that rice, starchy roots, sweet potatoes andnd cereals have become a smaller percentage of China’s total consumption. Conversely, vegetables now make up the largest percentage of total consumption of any food groups. 

![stackedarea](https://user-images.githubusercontent.com/40878527/57831178-3a022000-7769-11e9-806c-93add43b3402.png)
 
The stacked area plot shows the consumption of the top 10 food groups by year. Once again it shows wheat products, fruits, and vegetables were consumed less than starchy roots earlier in the timeline, but have seen growth in consumption beyond starchy roots by 2013.

![treemap](https://user-images.githubusercontent.com/40878527/57831204-4c7c5980-7769-11e9-99fb-0b888be7edd7.png)

The treemap shows the top 10 countries by consumption of the top 10 food groups. As the most populous country. China leads consumption in most groups, with milk products being the largest exception; where India and U.S exceed China’s consumption.


 ![bubblemap](https://user-images.githubusercontent.com/40878527/57831365-c6acde00-7769-11e9-859c-dffd180ac5f0.png)
 
### Storyline: 
The interactive plot snapshots above show the food and feed consumption by country as a percentage of world consumption from 1961-2013. Over the time period there has been a major shift in top consumers away from Europe. By 2013 the top 10 ranks consist of countries from almost every region such as, Brazil, Mexico, Indonesia, Russia, and Nigeria. The most significant explanatory variable is population as the top consuming countries correlate largely with the most populous countries illustrated in the chloropleth plot. There also appears to be a larger concentration of the world consumption in the top country, China, which consumes over a quarter of total food.

### Results/Summary/Conclusion:
In summary, the dataset confirmed the relationship between population and food consumption but told an interesting story from a diet or food group perspective. Overall, there was a clear trend in countries moving towards a more balanced and varied source of foods. The large increase in vegetable consumption shows a generally more healthful global food system. The data also showed that food is more readily available to countries as consumption increased in absolute terms and relative terms to population. There were still outliers in countries that over consumed or under consumed on a per population basis. The U.S serving as an example of the former. In the latter case, depending on the country their under consumption most likely reflected their economic status or perhaps cultural differences in eating habits. Although, I briefly looked at trade, if given more time I would also like to look at food imports and exports. In addition, as food is related to health and nutrition, I would also like to explore relationships between this dataset and general health statistics about each country.

### Citations:
* https://www.kaggle.com/dorbicycle/world-foodfeed-production
* https://data.worldbank.org/indicator/sp.pop.totl
* http://fortune.com/2018/03/07/biggest-us-trade-partners/
