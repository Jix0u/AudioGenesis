# Audiogenesis: Background Music Generation with RNN (LSTMs)
Audiogenesis is a background music generation model that harnesses the power of Recurrent Neural Networks (RNNs) specifically Long Short-Term Memory (LSTM) units. This model generates soothing background music tailored to text prompts and advertisements by learning from a vast database of MIDI files.

## How it Works
1. **MIDI Encoding**:
Audiogenesis starts by encoding MIDI files into a format understandable by RNNs with features step, pitch, and duration. MIDI files contain musical notes, timing, and other parameters crucial for music generation.
2. **LSTM Architecture**:
The core of Audiogenesis lies in its LSTM units. LSTMs are a type of RNN designed to capture dependencies over long sequences, making them ideal for generating music with coherent structures.
3. **Text Prompt Embedding**:
Text prompts and advertisements are embedded into a format compatible with the LSTM network. This embedding serves as the input to the LSTM units, guiding the generation process towards music that complements the given text.
4. **Training on MIDI Database**:
Audiogenesis is trained on a diverse database of MIDI files encompassing various musical styles, genres, and compositions. This extensive training enables the model to learn the nuances of musical composition and style.

## Sample Generated Music from Text Prompts
https://github.com/Jix0u/AudioGenesis/assets/55889031/490030bb-aba8-4ee6-9a1d-496fdea8b94e

https://github.com/Jix0u/AudioGenesis/assets/55889031/2983c477-ffb3-4cbf-96be-d774bf29efc4

https://github.com/Jix0u/AudioGenesis/assets/55889031/ee0be572-524d-4445-a29c-8b620c07b3fd

## References
The architecture of Audiogenesis draws inspiration from the advancements in LSTM-based music generation models.

## Usage
To utilize Audiogenesis and generate background music from text prompts, follow these steps:

### Notebook Contents
Inside the repository, you will find:

- Model Definition: Details regarding the architecture of Audiogenesis, including LSTM units and text prompt embedding techniques.
- Training Scripts: Scripts and code for training the Audiogenesis model using your own MIDI dataset or pre-existing data.
- Inference Code: Code for generating background music using the trained model. You can input your text prompts to receive musical compositions.
- Evaluation Techniques: Techniques for evaluating the quality of generated music, ensuring coherence and relevance to the given text prompts.

The repository includes MIDI files alongside corresponding text prompts for training and evaluation purposes.
