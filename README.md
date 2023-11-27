# Li-ion battery RUL and SOH prediction

Our proposed model determines the remaining useful life of lithium-ion batteries at any point in the battery’s life cycle. The architecture of our model is composed of two LSTM neural network models: the first one predicts the SOH of the battery while the second model predicts the RUL and uses SOH as its input. The application’s input consists of numeric datasets and our output displays the battery's remaining life in percentage. With our results, we can conclude that our models and their architecture successfully predict the RUL at any stage of the battery’s life. Our goal was to simplify the current methods of calculating the SOH and RUL with fewer cycles and without needing to measure the capacity. Our results imply that we were successful, however lost some accuracy due to the limited data imputed. 

# Dataset used:
B. Saha and K. Goebel (2007). “Battery Data Set”, NASA Prognostics Data Repository, NASA Ames Research Center, Moffett Field, CA. https://phm-datasets.s3.amazonaws.com/NASA/5.+Battery+Data+Set.zip
