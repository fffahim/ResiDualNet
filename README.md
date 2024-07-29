# ResiDualNet : A novel electric vehicle charging data imputation
Electric vehicles (EVs) are an eco-friendly mode of transportation, significantly reducing
greenhouse gas emissions. The development of EV charging stations is crucial not only for
supporting the increasing number of EVs but also for integrating them into a smart grid
infrastructure. Efficient utilization of these charging stations requires optimization of energy
management and budget allocation, achievable through accurate forecasting of EV charging
behaviors. Reliable forecasting depends on the availability of high-quality data, which is often
compromised by connectivity issues and equipment failures leading to missing values. To
address these challenges, this study introduces ResiDualNet (Residual Dual LSTM-CNN Path
Network), a residual sequence-to-sequence technique for imputing missing EV charging data.
This model effectively captures underlying temporal and long-term dependencies, performing
well even with limited data. We compare our proposed model with two commonly used
imputation methods—KNN and Mean imputation—across four different EV charging datasets.
Experimental results demonstrate that our model significantly outperforms the others, showing
an average improvement of 74% across all datasets. Furthermore, to validate the effectiveness of
our imputation model, we apply three widely used forecasting algorithms to predict EV charging
load. The results indicate that SCINet surpasses other forecasting techniques. Moreover, for
SCINet, the dataset imputed by our proposed model performs second best after the real dataset,
confirming the effectiveness of our imputation approach.
