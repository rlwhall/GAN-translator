# Building an English to German Translation Tool

## Goal 
<br/>

We wanted to build our own English to German translator using a generative adversarial network (GAN).
<br/>
<br>

### Approach

The problem was approached using the following steps: 
1. Finding a corpus – The English-German NLTK 'comtrans' corpus was used
2. Data Preparation – Sentences were cleaned (punctuation removed, lowercase etc.), had keyword tags added, tokenized, and padded
3. Training Model Creation – a GAN neural network using LSTMs was designed to train an internal state
4. Prediction Model Creation – The internal state from the training model was then used in combination with a decoding model for prediction
<br />
<br>

### Directories
* **final-files:** The final project files.
* **working-files:** Project files in progress.
<br />
<br />


