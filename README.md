# Traffic Forecasting using Vehicle-to-Vehicle Communication

### Paper:
Steven Wong, Lejun Jiang, Robin Walters, Tamás G. Molnár, Gábor Orosz, Rose Yu [Traffic Forecasting using Vehicle-to-Vehicle Communication](https://arxiv.org/pdf/2104.05528.pdf) L4DC 2021

### Dataset:
------
1000 seconds of V2V communication data - Lead and Ego Velocity and Position vs time

### Abstract:
We take the first step in using vehicle-to-vehicle (V2V) communication to provide real-time on-board traffic predictions.
In order to best utilize real-world V2V communication data, we integrate first principle  models with deep learning. Specifically, we train  recurrent neural networks  to improve the predictions given by first principle models.
Our approach is able to predict the velocity of individual vehicles up to a minute into the future with improved accuracy over first principle-based baselines.
We conduct a comprehensive study  to evaluate different methods of integrating first principle models with deep learning techniques.  The source code for our models is available here.

### Description:
The source code of our four models are presented here:

1. Vel-FC
2. Ego-only LSTM-FC
3. VelLSTM-FC
4. ResLSTM-FC
For details of each model, check out the respective jupyter notebooks and our paper.

### Requirements:
* Python 3.6
* Torch 1.5.1
* Scipy
* NumPy 
* MatPlotLib 

### Cite:
    @misc{wong2021traffic,
      title={Traffic Forecasting using Vehicle-to-Vehicle Communication}, 
      author={Steven Wong and Lejun Jiang and Robin Walters and Tamás G. Molnár and Gábor Orosz and Rose Yu},
      year={2021},
      eprint={2104.05528},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
    }
