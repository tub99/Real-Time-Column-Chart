# Real-Time-Column-Chart
This column chart is a data visualization app which  refreshes itself after a period of time and does real time visualization on data provided by  user

# User-Configurable properties
    1.title of the chart
		2.number Of divLines in axis
		3.refresh Time of the chart
		4.number Of ColumnSets To Display
		5.number of datasets
		6.color of datasets
		
#Sample Data
``` javascript
{
		"chart": {
			"title": " Real Time Analysis",
			"numOfdivLines":5,
			"refreshTime":"1000",
			"numOfColumnSetsToDisplay":"6"
		},

		"dataset": [
			{
				"color": "B3C1D0",
				"seriesname": "Internal",
				"data":[{"value": 100},{"value": 80},{"value": 75},{"value": 315}]
			},
			{
				"color": "6582A0",
				"seriesname": "External",
				"data":[{"value":42},{"value": 120},{"value": 88},{"value":123}]
			},
				{
				"color": "cccccc",
				"seriesname": "dfcdv",
				"data":[{"value":24},{"value": 115},{"value": 46},{"value":300}]
			}
		]
		
}
```
# The Real Time Column Chart
<p><img src="screenshot/pic2.PNG"></img></p>
