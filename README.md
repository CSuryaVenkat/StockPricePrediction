<h1>Project Overview</h1>
<p>This project implements a bidirectional Long Short-Term Memory (LSTM) neural network using Keras to perform time series forecasting. The model is designed to predict future values based on sequences of past data.</p>

<h2>Overview</h2>
<p>Time series forecasting involves predicting future values of a sequence based on previously observed values. LSTM networks, a type of recurrent neural network (RNN), are particularly suited for this task due to their ability to capture long-term dependencies and patterns in sequential data. Bidirectional LSTMs further enhance this capability by processing the input sequence in both forward and backward directions.</p>

<h2>Components</h2>
<ul>
  <li><strong>Hyperparameters:</strong>
    <ul>
      <li><strong>DROPOUT:</strong> Dropout rate to prevent overfitting by randomly setting a fraction of input units to 0 during training.</li>
      <li><strong>WINDOW_SIZE:</strong> The size of the input sequence, derived from SEQ_LEN.</li>
    </ul>
  </li>
  <li><strong>Model Architecture:</strong>
    <ul>
      <li><strong>Bidirectional LSTM Layers:</strong> Three layers of bidirectional LSTMs to capture dependencies in the sequence data from both directions.</li>
      <li><strong>Dropout Layers:</strong> Applied after the first two LSTM layers to prevent overfitting.</li>
      <li><strong>Dense Layer:</strong> A single dense (fully connected) layer to produce the final output.</li>
      <li><strong>Activation Layer:</strong> Linear activation function to provide the output directly.</li>
    </ul>
  </li>
</ul>

<p>This implementation provides a robust starting point for time series forecasting using bidirectional LSTMs, allowing you to capture intricate patterns in your data. Adjust the model architecture and hyperparameters based on your specific dataset and forecasting requirements.</p>
<h2>Results</h2>
<p>Below are the screenshots of the model loss plot and Bitcoin price prediction plot:</p>

<!-- Insert screenshots using img tags -->
<img src="path/to/model_loss_plot.png" alt="Model Loss Plot">
<img src="path/to/bitcoin_price_prediction_plot.png" alt="Bitcoin Price Prediction Plot">
