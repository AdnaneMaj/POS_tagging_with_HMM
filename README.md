# Part-of-Speech Tagging with Hidden Markov Models

In this repository, I've trained a Hidden Markov Model to perform tagging tasks using the Viterbi Algorithm. The steps are as follows:

* Getting and preprocessing the data (Penn Treebank Corpus)
* Computing the transition matrix A and emission matrix B
* Applying the Viterbi Algorithm:
  * Initialization of the best_prob matrix (each cell $v_j(t)$: **Viterbi Path probability** represents the probability that the HMM is in state j after seeing the first t observations and passing through the most probable state sequence $q_1,...,q_{t−1}$, given the HMM defined by A and B)
  * Feed forwarding the **best_prob** matrix and the **best_path** matrix
  * Feed backward and getting the best sequence of tags for the input text.

Exemple :
![image](https://github.com/AdnaneMaj/POS_tagging_with_HMM/assets/52354033/63627566-b04e-42b7-8939-f39d1df6cb30)

We got an accuracy of 77%

