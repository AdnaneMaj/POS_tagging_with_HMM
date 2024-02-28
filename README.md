# Part-of-speech tagging with Hidden Markov Models

In this repository, I trained a hiddden marov model using the Viterbi Algorithm.
The steps are as follow :
* Guetting and preprocessing the data
* Computing the transitions matrix A and emission matrix B
* Applying the Viterbi Algorithm :
  * initialisation a best_prob matrix (each cell $v_j(t)$ : Viterbi Path probability represents the probability that the HMM is in state j after seeing the first t observations and passing through the most probable state sequence $q1,...,qt−1$,given the HMM defined by A and B)
  * Feed forwardingthe best_prob matrx
