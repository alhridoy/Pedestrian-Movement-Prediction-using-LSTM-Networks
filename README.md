# Pedestrian-Movement-Prediction-using-LSTM-Networks
-  Processed a dataset of pedestrian positions, where each entry includes details such as TrackID, bounding box coordinates, frame number, lost status, occlusion status, and generation status.

- Implemented a Sequential LSTM model in Keras to predict future positions based on historical movement data, using an input sequence length of 8 and output sequence length of 12. Trained the model with 'adam' optimizer and mean squared error (MSE) as the loss function.

- Evaluated the model's performance by calculating the Average Displacement Error (ADE) and Final Displacement Error (FDE). Achieved an ADE of approximately 15.77, indicating the model's accuracy in predicting future pedestrian positions.
