# Supervised Sequence Labelling of Speech Data: a Comparison of Network Architectures
Here I implement experiments that apepar in Chapter 5 of the book *Supervised Sequence Labelling with Recurrent Networks* by Alex Graves.

The data for the experiments come from the TIMIT corpus of prompted speech. The audio data is data is divided into sentences, each of which has a corresponding phonetic transcript.

The task is to classify every input timeframe according to the phoneme it belongs to.

The input data is characterised as a sequence of vectors of 26 coefficients, consisting of twelve Mel-frequency ceptral coefficients (MFCC).

Network Architectures to be compared:
- Multi Layer Perceptron with 10 context windows (in both directiions)
- Bidirectional Recurrent Neural Network
