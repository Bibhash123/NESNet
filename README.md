# NESNet: A Deep Network for EstimatingNear-surface Pollutant Concentrations
With the threat of atmospheric pollution on the rise in recent years, round-the-clock monitoring of the concentration of atmospheric gases has become utterly necessary. As opposed to traditional _in situ_ measurement strategies, satellite monitoring offers a convenient alternative for truly global coverage. However, satellite measurements do not provide information about the vertical profile of concentration, and estimation methods must be used to deduce near-surface concentration. Existing works that address this problem often adopt approaches that use auxiliary variables such as meteorological parameters and population density information along with vertical column density measurements. In remote areas where such information is not available, these methods are likely to fail. In our work, we propose **NESNet**, a convolutional neural network that has been designed to perform the estimation of near-surface concentrations of atmospheric trace gases using only vertical column density (VCD) values. We demonstrate the working of our method for nitrogen dioxide, sulfur dioxide, and ozone. The proposed method shows RMSE scores of 6.272, 7.20, and 16.03 µg/m³, NO<sub>2</sub>, and O<sub>3</sub> respectively. 
![Network_final](https://user-images.githubusercontent.com/64698873/138562660-48d590df-5050-4e49-90a1-9227ba1fc61f.png)

As compared to other commonly used models, NESNet performs relatively well in predicting the pattern of concentrations. The figure shown below compares the predictions by NESNet to predictions made with other models.

![image](https://user-images.githubusercontent.com/64698873/138562788-f038ad0c-07db-4ea0-8bfc-2d2c99c2089b.png)
 
 The datasets used for this work are available in the following links
 - NO<sub>2</sub>: https://www.kaggle.com/bibhash123/no2estimation
 - SO<sub>2</sub>: https://www.kaggle.com/bibhash123/so2estimation
 - O<sub>3</sub>: https://www.kaggle.com/bibhash123/o3estimation
