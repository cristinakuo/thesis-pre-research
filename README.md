# Supervised Sequence Labelling of Speech Data: a Comparison of Network Architectures
Here I implement experiments that appear in Chapter 5 of the book *Supervised Sequence Labelling with Recurrent Neural Networks* by Alex Graves.

The data for the experiments come from the TIMIT corpus of prompted speech. The audio data is divided into sentences, each of which has a corresponding phonetic transcript.

The task is to classify every input timeframe according to the phoneme it belongs to.

Input data is characterised as a sequence of vectors of Mel-frequency cepstral coefficients (MFCC).

### Network Architectures to be compared:
- Multi Layer Perceptron with 10 context windows (in both directions)
- Bidirectional Recurrent Neural Network
