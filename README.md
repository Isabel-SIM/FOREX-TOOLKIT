<h1> FOREX TOOLKIT </h1>
The Forex Toolkit (FTX) APP aims to provide various functionalities related to currency conversion, currency analysis, and currency forecasting. 
The APP utilises the following steps to determine the “best investment outlook” for its user:
<br><br>
<b>- Currency Data Retrieval:</b> <br>
FTX retrieves currency data using the ExchangeRate-API to obtain the latest currency conversion rates.
<br><br>
<b>- Currency Conversion:</b> <br>
FTX allows users to convert an amount from one currency to another using the retrieved currency conversion rates.
<br><br>
<b>- Currency Map Visualisation:</b> <br>
FTX visualises the currencies on a map using the Folium library. The map displays markers for each currency, representing its location based on country coordinates.
<br><br>
<b>- Currency Analysis and Forecasting:</b> <br>
FTX performs currency analysis and forecasting using the machine learning models XGBoost and Random Forest. It trains the models on historical currency data and generates predicted prices for future dates. FTX also calculates the root mean squared error (RMSE) as an evaluation metric for the models.
<br><br>
<b>- Buy/Sell Signals:</b> <br>
FTX provides buy/sell signals based on the predicted prices compared to historical prices. It generates signals for each currency and plots the forecast results.
<br><br>
<b>- Best Investment Outlook:</b> <br>
FTX determines the currency with the most buy signals, the currency with the highest cumulative percentage change to USD, and the currency with the best investment outlook based on a combined score considering buy signals and cumulative change. 
<br><br>
<b>- Unique Algorithm:</b> <br>
The process to generating the currency with the best investment outlook, is an algorithm unique to FTX. 
<br><br>
<b>- Chatbot Interface:</b> <br>
Finally, FTX includes a chatbot interface powered by OpenAI's text-based language model. Users can interact with the chatbot to ask questions or seek any further assistance regarding currency-related topics.

## Before you run the application
 - You will download the ipynb file:
    - CODE.ipynb
      
 - Make sure you have completed the below imports:
    - pip install folium
    - pip install xgboost
    - pip install openai
    - pip install Console
      

## Below is the graphical forecast output (AUD, CHF, EUR)
![forecast_results_AUD](https://github.com/Isabel-SIM/FOREX-TOOLKIT/assets/127584188/4d5906c8-23fb-4ffe-a137-01ea02cd4939)
![forecast_results_CHF](https://github.com/Isabel-SIM/FOREX-TOOLKIT/assets/127584188/110a467b-4030-4d00-aa3f-c50923686100)
![training_results_EUR](https://github.com/Isabel-SIM/FOREX-TOOLKIT/assets/127584188/9680d539-e8d6-45ef-91b7-b36642b13192)


## Below is the graphical training output (AUD, CHF, EUR) 
![training_results_AUD](https://github.com/Isabel-SIM/FOREX-TOOLKIT/assets/127584188/9446eeb8-15aa-45a6-a3de-a756cb41700b)
![training_results_CHF](https://github.com/Isabel-SIM/FOREX-TOOLKIT/assets/127584188/573061f9-f977-46ce-8d3a-9638ed168129)
![training_results_EUR](https://github.com/Isabel-SIM/FOREX-TOOLKIT/assets/127584188/967879d3-996c-40a2-8ec2-92d71249babe)


## Below is the plotted forecast for AUD only
![AUD_forecast_plot](https://github.com/Isabel-SIM/FOREX-TOOLKIT/assets/127584188/bd7a4d25-7bb8-4ef8-98bf-d4e6ddfee28e)


  
## Below is the plotted forecast for CHF only
![CHF_forecast_plot](https://github.com/Isabel-SIM/FOREX-TOOLKIT/assets/127584188/3a740b20-f63c-493c-a66d-ed5ec240b5fe)


  
## Below is the plotted forecast for EUR only
![EUR_forecast_plot](https://github.com/Isabel-SIM/FOREX-TOOLKIT/assets/127584188/976c20e4-59ff-442b-9f7d-cfa1a503a15a)




## Conclusion
The Forex Toolkit (FTX) APP provides users with a robust and versatile toolkit. By seamlessly integrating features such as data retrieval, conversion, visualisation, analysis, forecasting, investment insights, and chatbot interaction, the application enhances the user experience, facilitating informed decision-making in the realm of global currencies. FTX empowers users to navigate the complexities of the financial landscape, enabling them to make intelligent and well-informed choices regarding currency transactions and investments.

