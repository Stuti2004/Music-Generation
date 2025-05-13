# Music-Generation
This project focuses on automatic music generation using a deep learning approach. Specifically, it uses:
**Long Short-Term Memory (LSTM) networks** — a type of recurrent neural network (RNN) well-suited for sequence prediction tasks like music, where temporal patterns matter.
**Dataset:** MAESTRO MIDI dataset, preprocessed into sequences of pitch, step, and duration.
**Model Architecture:** LSTM-based neural network predicting the next note’s pitch, step, and duration.
**Music Generation:** After training, the model is used to generate sequences of notes.
These sequences are converted to MIDI format and saved as audio files
