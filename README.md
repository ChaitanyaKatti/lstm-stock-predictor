# lstm-stock-predictor

This is PyTorch implementation of the LSTM(Long-short-term memory) model to predict prices of day-to-day stock data.

# How to run
- Use Python 3.10.9
- Git clone using `git clone https://github.com/ChaitanyaKatti/lstm-stock-predictor.git`
- Install requirements using `pip install -r requirements.txt`
- Download stock data and place the .csv files in `/data/stocks` folder
- Edit data, model, training, and simulation parameters in `config.py`.
- Run main.py using `python main.py`
- Look at the terminal for training progress and the `/plots` folder for results.

# Model Architecture
<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/ChaitanyaKatti/lstm-stock-predictor/assets/96473570/8de3e718-3986-4605-a851-0643837626f0" alt="LSTM Basic" width=50%>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Figure 1:</b> Forward pass in LSTM</td>
  </tr>
  
  <tr>
    <td align="center">
      <img src="https://github.com/ChaitanyaKatti/lstm-stock-predictor/assets/96473570/7e6f9814-2b17-439b-865f-3c5891db411e" alt="LSTM Recurrent Diagram" width=50%>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Figure 2:</b> Recurrency of LSTM</td>
  </tr>
  
</table>
