# About this project
I built a stock market trend prediction model using Association rule mining approach.

# Approach
Association rule mining is a technique of finding correlation between different variables in a dataset. It is commonly used in market basket analysis for finding the relation in customer's buying activities (transactions), then based on that information, proposed an approriate strategy to increase the sale.

In stock market analysis, association is less common compared to time-series analysis approach, including state-of-the-art deep learning approach of LSTM model. However, there are some existing research on the field, which analyse the correlation between different companies' stock price changes.

I want to try a different approach using Association rule mining technique. Focused on the trend of stock price, I try to find the relation between the previous changes in the price and the present changes (which expresses the "trend" of the stock price). For example: If in three nearest days, the price went up, down and down, it is most likely that the price of today will go down. Association rule mining is the perfect tool for this kind of approach. I use it to find all of the possible and reliable "trend" in the dataset. From that, I can make the prediction about the stock price trend in the future.

# Dataset
I used three indices for the data, namely VNIndex, Nikkei255 Index and HangSengIndex which is publicly available online. The data is pre-processed and convert to appropriate format for my implementation.

# Implementation
The implementation is included in the notebook attached. 

Have fun\
Nam Ha
