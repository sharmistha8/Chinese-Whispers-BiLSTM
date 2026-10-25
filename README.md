# Chinese Whispers Game Using BiLSTM

## Project Overview
This project simulates the Chinese Whispers game using a Bidirectional Long Short-Term Memory (BiLSTM) model. It demonstrates how a spoken message can change as it passes through eight virtual players.

## Objectives
- Convert speech into text using speech recognition.
- Use a trained BiLSTM model to process text sequences.
- Simulate message changes across multiple players.
- Observe differences between the original and final messages.

## Technologies Used
- Python
- Google Colab
- TensorFlow and Keras
- BiLSTM (Bidirectional Long Short-Term Memory)
- Speech Recognition

## How It Works
1. The user speaks a sentence through a microphone.
2. Speech recognition converts the speech into text.
3. The BiLSTM model processes the text.
4. A simulated word-change function modifies the message across eight virtual players.
5. The final message is displayed for comparison.

## Example

**Original message:**  
`the boy is playing in the garden`

**Final message:**  
`this cat is sleeping on the things`

## Conclusion
This project demonstrates how messages can change during repeated transmission and introduces basic concepts of speech recognition, natural language processing, and sequence modelling.

## Run the Project
Open the `.ipynb` notebook in Google Colab and run the cells in order. Allow microphone access when prompted.
