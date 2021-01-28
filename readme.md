Dataset -> Quora Question Pairs on Kaggle.

Architecture
------------

Q1 -> glove_emb_layer -> LSTM  \ 
                                \
                                concatenated output -> dense network with dropout -> single node output.
                                /
Q2 -> glove_emb_layer -> LSTM  /


Futurework - Use PyTorch Lightning and torchtext 0.8