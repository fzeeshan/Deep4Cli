# Using Deep Neural Networks to Predict ENSO

***Manuscript Version***
School of Software Engineering, Tongji University, Shanghai 201804, China


Todo

The abstract should summarize the contents of the paper in short terms, i.e. 150-250 words.


time series prediction, deep neural networks, ENSO.


	* *"The dynamical models use physical equations of the ocean and atmosphere to forecast ENSO event, which are computationally very expensive and not available outside the atmospheric scientific community."*



	* "capturing long-term temporal dependencies" -- LSTM
	* CNN+LSTM has been applied on climate problem, like Sea Level Anomalies (SLA), which show great pontential for such kind of problem.[7]



	* only SST prediction, no specified climate problem analysis.[1]
	* only single nino index (NINO3.4) prediction, no spatio information (pattern) considered, and both network model and data input size can be improved.[2]


	* Single SST prediction (Bohai SST)

	* two aspects -- the structure of the model (different layers, memory cells in each layer) && machine learning algorithms (SVR, MLPR)

	* need more training data

2. 《El niño-southern oscillation forecasting using complex networks analysis of LSTM neural networks》 ***（highly related）***

	* Use climate network to construct input and LSTM network as model to predict ENSO, but just priedict single NINO3.4 index, no spatial information discussed, for the experiment, forecast the  NINO3.4 index from 6-month lead, 9-month lead and 12-month lead, use RMSE and MAE, no contrast experiment. the conclusion said that more data and more complex LSTM neural network is needed. 

	* Nino3.4 + Climate Network (Preprocessing)  --> predict Nino34 with different time leads

	* *"We believe this approach has great potential performance skills to augment the ENSO forecasting activity of climate scien- tists and meteorologists. And our vision is to improve the model by increasing the data sample size and the complex- ity of the LSTM architecture."*

	* **pyunicorn** --> which is used for construct Climate Network in this paper.


	
	* [How Good Have ENSO Forecasts Been Lately?](https://www.climate.gov/news-features/blogs/enso/how-good-have-enso-forecasts-been-lately) (a good reference when inroduce the prediction situation of ENSO )

		* *"how well the forecasts have matched reality"*
		* lead time --> *" The month from which forecasts are made is often called the start month, and the season that the forecast is for is often called the target season."*
		* measurements (MAE && RMSE && Correlation Coefficient)
		* *"we have a long way to go in improving their performance and utility beyond that.  It is especially hard to predict the timing of ENSO transitions and the correct strength. "*







	* *"CNNs are particularly suitable for gridded data exploiting the spatial correlations"*
	* LSTM / CNN+ConvLSTM / Sequence LSTM
	* *"reoccuring spatial patterns" (ENSO)*
	* Both in single grid cell (get one grid on the whole region) and grid spatial pattern capture (predict a single img-like grid pattern)
	* *"All the used network designs outperform the regression."*













14. 《Sequence to Sequence Weather Forecasting with Long Short-Term Memory Recurrent Neural Networks》






***Outline:***




***Outline:***

***Outline:***




	* the single nino index predition with LSTM 



	*  Four other index --> ONI
	*  LSTM model, random forest, linear regression

***Outline:***



