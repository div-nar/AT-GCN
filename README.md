# AT-GCN

The objective of our project is to improve the accuracy and reliability of forecasting fatal incidents within conflict zones through deep learning models, in particular, we intend to propose a novel Transformer-based architecture leveraging multi-head-based self-attention to capture temporal dependencies. The rationale behind selecting this topic stems from the pressing need to enhance early warning systems for humanitarian and security purposes. By accurately predicting such events, we can potentially save lives by providing timely and effective responses from international organizations. 

We intend to utilize data from the 2023/24 ViEWS prediction challenge, to forecast the monthly number of fatalities from organized political violence across different geographical units, primarily focusing on sub-national datasets for Africa and the Middle East (pgm). The variable under study that we wish to predict is ged_sb -  the best (most likely) estimate of the total number of battle-related deaths (BRDs) from state-based conflict as per the UCDP (Uppsala Conflict Data Program) definition. We aim to predict this over a five-year window, ranging from 2016-2021. 

Our proposed architecture chooses to incorporate the recommendations provided by existing literature while utilizing more modern deep learning innovations to provide a robust architecture that will be able to process data, capturing both local and global dependencies for both the spatial and temporal dimensions. We choose to build on Patrick Brandt's work utilizing a spatiotemporal graph convolution network, utilizing a GCN as proposed in the paper leveraging its granularity and minimal feature engineering qualities to capture spatial dependencies. 

In addition to this, we propose modifications to the temporal model using the sequential nature of time-series data as a justification to incorporate transformers allowing us to capture short and long-term dependencies a first in this field. 


