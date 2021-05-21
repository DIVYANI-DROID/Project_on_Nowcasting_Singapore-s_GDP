# Project_on_Nowcasting_Singapore_GDP
This is a project based on an example of econometric models.

Excel sheets provided in this repository are forecasted IIP and PP values.

First I tried using Simple linear regressions to see if that's sufficient, before moving on to a complex model. 
For this I checked out some repositories to see how this works.
Econometric models are statistical models used in econometrics. An econometric model specifies the statistical relationship that is believed to hold between the various economic quantities pertaining to a particular economic phenomenon. [Source:https://en.wikipedia.org/wiki/Econometric_model#:~:text=Econometric%20models%20are%20statistical%20models,to%20a%20particular%20economic%20phenomenon.]
Nowcasting:Nowcasting in economics is the prediction of the present, the very near future, and the very recent past state of an economic indicator. The term is a contraction of "now" and "forecasting" and originates in meteorology. [https://en.wikipedia.org/wiki/Nowcasting_(meteorology)#:~:text=Nowcasting%20is%20weather%20forecasting%20on,other%20authors%20in%20the%20field.]  

With nowcasting models, economists at the MTI [Ministry of Trade & Industry Singapore] are able to bridge this gap and provide advance estimates of GDP about two weeks after the end of a quarter.

Singapore’s Economic Structure [Source: https://www.mti.gov.sg/-/media/MTI/Resources/Economic-Survey-of-Singapore/2020/Economic-Survey-of-Singapore-2020/Ch6_AES2020.pdf]
Looking at the MTI’s annual Economic Survey of Singapore 2020, we could see that around 70% of Singapore’s GDP is contributed by Services Producing Industries (SPI), while Goods Producing Industries (GPI) make up the remaining 20–30%.
Notably, the Manufacturing and Construction sectors contribute significantly to GPI, while the sectoral contributions to GDP in SPI appear to be more diverse.
A simple linear model with just 2 regressors — GPI and SPI

Bridge models:
In particular, the bridge models provide short-run projections of quarterly time series by using the information available on indicators at monthly frequency (the model thus creates a “bridge”). In general, these models are used for one- or, at most, two-quarter ahead forecasts. [Source: http://www.dt.mef.gov.it/en/attivita_istituzionali/analisi_programmazione_economico_finanziaria/modellistica/bridge_models.html#:~:text=In%20particular%2C%20the%20bridge%20models,%2C%20two%2Dquarter%20ahead%20forecasts.]

