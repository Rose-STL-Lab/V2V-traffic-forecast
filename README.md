# Traffic Forecasting using Vehicle-to-Vehicle Communication

### Paper:
Steven Wong, Lejun Jiang, Robin Walters, Tamás G. Molnár, Gábor Orosz, Rose Yu [Traffic Forecasting using Vehicle-to-Vehicle Communication](https://arxiv.org/abs/2104.05528) L4DC 2021

### Dataset:
1000 seconds of V2V communication data - Lead and Ego Velocity and Position vs time

### Abstract:
We take the first step in using vehicle-to-vehicle (V2V) communication to provide real-time on-board traffic predictions.
In order to best utilize real-world V2V communication data, we integrate first principle  models with deep learning. Specifically, we train  recurrent neural networks  to improve the predictions given by first principle models.
Our approach is able to predict the velocity of individual vehicles up to a minute into the future with improved accuracy over first principle-based baselines.
We conduct a comprehensive study  to evaluate different methods of integrating first principle models with deep learning techniques.  The source code for our models is available here.

This is the code repository for the paper "Traffic Forecasting using Vehicle-to-Vehicle Communication" in L4DC2021.

The source code of our four models are presented here:

1. Vel-FC
2. Ego-only LSTM-FC
3. VelLSTM-FC
4. ResLSTM-FC

For details of each model, check out the respective jupyter notebooks and our paper.
