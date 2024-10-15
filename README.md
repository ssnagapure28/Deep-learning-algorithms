This project implements a Neural Machine Translation (NMT) model using Long Short-Term Memory (LSTM) networks and attention mechanisms. The model translates sentences from English to Spanish. The project is built using TensorFlow and Keras and includes data preprocessing, model training, and evaluation.
1. Clone the repository:
git clone https://github.com/username/nmt-project.git
cd nmt-project

2. Set up a virtual environment (optional but recommended):
python3 -m venv venv
source venv/bin/activate

3. Install the required dependencies:
pip install -r requirements.txt


Model Architecture
Encoder:
2 LSTM layers are used to encode the input English sentence into a fixed-size context vector.
Attention Mechanism:
The attention mechanism helps the decoder focus on relevant parts of the input sequence.
Decoder:
The Spanish sentence is decoded from the context vector using 2 LSTM layers and the attention output.
