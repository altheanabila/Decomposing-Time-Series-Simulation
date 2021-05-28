# Decomposing-Time-Series-Simulation
This time, I would like to doing a simulation of time series decomposition. We will break down into 2 kind of decomposition which are multiplicative and additive. 
Using a dummy dataset [us-airlines-monthly-aircraft-miles-flown.csv](https://github.com/altheanabila/Decomposing-Time-Series-Simulation/blob/main/us-airlines-monthly-aircraft-miles-flown.csv), we capture the decomposition in both ways.


1. import related libraries

![text image](https://github.com/altheanabila/Decomposing-Time-Series-Simulation/blob/main/pic%201.png)

2. load the dataset, and indexing the date

![textimage](https://github.com/altheanabila/Decomposing-Time-Series-Simulation/blob/main/pic%202.png)


3. running the seasonal decomposition for additive model
`result = seasonal_decompose(decomp_df['MilesMM'], model='additive')`

![textimage](https://github.com/altheanabila/Decomposing-Time-Series-Simulation/blob/main/pic%203.png)


4. running the seasonal decomposition for multiplicative model

`result2 = seasonal_decompose(decomp_df['MilesMM'], model='multiplicative')`

![textimage](https://github.com/altheanabila/Decomposing-Time-Series-Simulation/blob/main/pic%204.png)
