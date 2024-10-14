This project implements a Part-of-Speech (POS) tagger in Java using a Hidden Markov Model (HMM) and the Viterbi algorithm. It assigns POS tags to words in a sentence based on learned probabilities derived from training data. The model is trained on paired sentence and tag datasets, where it computes the likelihood of transitions between tags and the likelihood of words being associated with specific tags (emission probabilities).

The Viterbi algorithm is then applied to find the most probable sequence of POS tags for an input sentence by considering both transition probabilities between tags and emission probabilities for words. This method ensures that the tagger efficiently handles unseen words and transitions during decoding. Additionally, the tagger can be evaluated on test data and used interactively through a console-based interface.
