Problem Statement
The objective of this experiment is to study and compare the performance of different Recurrent Neural Network (RNN) architectures—Simple RNN, Long Short-Term Memory (LSTM), and Gated Recurrent Unit 
(GRU)—for time series forecasting. Time series data often contains sequential dependencies that traditional neural networks cannot effectively capture. Hence, this experiment explores how different recurrent models 
handle temporal patterns and evaluate their prediction accuracy based on the Mean Squared Error (MSE) metric.

Result

The experiment trained and evaluated three models—SimpleRNN, LSTM, and GRU—on a noisy sine wave dataset consisting of 1000 time steps. Each model was trained for 10 epochs using the Adam optimizer and mean squared error as 
the loss function. The resulting MSE values on the test dataset indicated that LSTM and GRU models performed better than the SimpleRNN model, demonstrating lower error values and smoother convergence during training.
The plotted training loss curves showed that LSTM and GRU maintained better stability and generalization, while SimpleRNN showed relatively higher loss.

Conclusion

From the experiment, it can be concluded that LSTM and GRU architectures outperform the basic SimpleRNN model in modeling sequential dependencies in time series data. This is primarily due to their gating mechanisms,
which effectively handle vanishing gradient issues and capture long-term dependencies. LSTM performs slightly better in accuracy, while GRU achieves comparable performance with reduced computational complexity. 
Hence, for most real-world time series applications, LSTM and GRU are preferred choices over traditional RNNs due to their robustness and efficiency.
