# CS-539-Project-Stock-Prediction
Includes: 
- MLP
- LSTM
   - code: initial_LSTM.ipynb
   - Accuracy: Low (~50%)
   - though low accuracy, we still decided to give LSTM a try by changing it to a hybrid model
   - leading up to CLAM...
- CLAM (best path ForestCLAM_CLAM attached on github)
   - code: CNN_LSTM_Attention_Model.ipynb
   - Accuracy: ~70%
- Random Forest (best path too large for github)
   - code: RandomForest.ipynb
   - Accuracy: ~80%
- Forest-CLAM
   - code: RandomForest_CNN_LSTM_Attention_Model.ipynb
   - The best CLAM check point is saved
   - Decison tree yeilds consistent results and is too large to save, so it needs to be trained
   - Total Gain: ~200%+ compared to initial capital
- Data used for CLAM and Forest models
