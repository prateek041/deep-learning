# Sequence Modelling

Sequence Modelling is a concept that involves making predictions based on a sequence of data points.
The method of choice, for making those predictions has evolved over time, going from statistics (N-Grams),
all the way to Neural Networks (RNN, LSTM, Transformers).

# Language Modelling

Language modelling is a subset of Sequence modelling. It is the task of predicting the next word (or words)
in a sequence based on previous words. The goal is to assign probabilities to sequences of words so that 
more likely sentences have higher probabilities that less likely ones.

Example:
"I love machine learning"
is more probable than
"I machine love learning".

We want the systems to be smart enough so that they get so good at predicting the next word in a sequence,
that they can directly communicate with a human, in their own language.