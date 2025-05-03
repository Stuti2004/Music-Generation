# Music-Generation
This project focuses on automatic music generation using a deep learning approach. Specifically, it uses:

**Long Short-Term Memory (LSTM) networks** — a type of recurrent neural network (RNN) well-suited for sequence prediction tasks like music, where temporal patterns matter.
**Grey Wolf Optimization (GWO)** — a metaheuristic algorithm inspired by the leadership and hunting behavior of grey wolves, used here to optimize hyperparameters (like the number of LSTM units, learning rate, and batch size) for better model performance.
**Dataset:** MAESTRO MIDI dataset (or similar), preprocessed into sequences of pitch, step, and duration.
**Model Architecture:** LSTM-based neural network predicting the next note’s pitch, step, and duration.
**Optimization:** First, the model is trained using manually set hyperparameters.
Then, GWO is applied to automatically find the best hyperparameter combination, improving performance (measured by loss) across generations.
**Music Generation:** After training, the model is used to generate sequences of notes.
These sequences are converted to MIDI format and saved as audio files
