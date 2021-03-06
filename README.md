# Surfs Up Weather Analysis for Oahu  

## Purpose of this analysis:  

In order to obtain funding for a surf shop in Oahu, Hawaii, an exhaustive analysis of the weather was performed.  
Also, with the long term in mind, great documentation within the code will be kept. Create an app   

Tools
- Python  
- SQLite  
- SQLAlchemy  
- Flask  
- Jupyter Notebook  
- VS Code  


## Findings  
- 12 months precipitation beginning August 23, 2017.  
	- Average precipitation per day is less than 1 inch  
	- Plot shows the September, February and June have the most frequent precipitation  
		- highest levels occurring in September, late January-early February, and April
![Plotted_Precipitation](https://user-images.githubusercontent.com/83401820/131230840-f8b98ec8-0408-42ae-a5a9-2feafba39aeb.png)  
![Yearlong_Precipitation_Stats](https://user-images.githubusercontent.com/83401820/131230841-02d7da00-3e5d-4eeb-a59e-a55064509232.png)  

- Using the most active weather station (USC0519281):  
	- Minimum Temp is 54.0  
	- Maximum Temp is 85.0  
	- Average Temp is 71.66  
	- Based on the histogram - Most of the temperatures were over 67 degrees  
![Histogram](https://user-images.githubusercontent.com/83401820/131230844-c6597da9-9ec0-4c21-8d8e-535513fad1df.png)  

- All June Temps vs All December Temps  
	- The June and December Temps yielded almost identical statistics with just a few differences  
		- There were nearly 200 fewer temps taken in December vs. June  
		- Average temp in June is 75 degrees vs. December is 71 degrees  
		- Minimum temp in June is 64 degrees vs. December is 56 degrees  
![June_Temps](https://user-images.githubusercontent.com/83401820/131230846-dd97418f-39ed-441f-9922-c41e4b0009cc.png)  
![Dec_Temps](https://user-images.githubusercontent.com/83401820/131230843-0de96de3-4f5d-4b8c-9bc4-a676f6e04e53.png)  

- All June Precipitation vs All December Precipitation  
	-  The June and December Precipitations yielded varying statistical results revealing the following:  
		- Average precipitation in June was nearly 1/2 that of December  
		- The precipitation data for December was spread out nearly 1/3 more than June's precipitation data  
		- Maximum precipitation in December was 6.42 while June's max was 4.43  
![June_Prec](https://user-images.githubusercontent.com/83401820/131230845-84146137-be64-4295-9f5a-1dd72a14c433.png)  
![Dec_Prec](https://user-images.githubusercontent.com/83401820/131230842-f3cbd84b-bc8f-4765-8d81-42e4af99cd2a.png)  

## Summary  
In summary, it can be concluded that Oahu may or may not be a great place to invest in for a surf shop.  
While it appears to rain almost daily, the amount of precipitation amounts are not great, which would indicate possibly passing  
showers or drizzling.  
Something to consider would be the heavy rain months such as June and December. Could the surf shop provide other amenities  
or even alternative offerings during this time?  
Finally, if the investment into Oahu is not feasible, the code is written as such to possibly analyze other locations in Hawaii  
which may prove less risky.  

	
	


