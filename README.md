# AI-Music-Generator
This project is an AI-based music generator that learns musical patterns from MIDI files and creates entirely new compositions using a Recurrent Neural Network (LSTM). The system uses the music21 library for MIDI processing and TensorFlow/Keras to train and generate music sequences.

1. Features
- Extracts notes and chords from MIDI files
- Converts sequences of notes into a machine-learning-friendly format
- Builds and trains an LSTM-based neural network
- Generates a brand-new 500-note musical composition
- Outputs the result as a downloadable .mid (MIDI) file

2. Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- music21 (for MIDI file parsing and generation)
- Jupyter Notebook or Google Colab (optional for running)

3. Usage
- Place your .mid files inside the midi_songs/ directory.
- Run the preprocessing and training scripts.
- Use the generation script to create a new music piece.
- Check the generated_music.mid output!

4. License
This project is open-source and available under the MIT License.

