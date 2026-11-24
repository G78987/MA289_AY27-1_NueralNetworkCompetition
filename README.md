# MA289_AY27-1_NueralNetworkCompetition
The problem and prediction goal: Measure the similarity of two tokens using an embedding matrix trained with a neural network. The prediction goal is to accuracy guess the two works similarity by minimizing the mean squared error between the submission and the ideal answer.

The model(s) used: I created a 2 layers neural network and a [900x100] embedding matrix from which I measured token similarities.

Your validation approach: I used cross-entropy loss to verify my trained model.

Your final Kaggle score: 0.07818 (3rd place).

Instructions for reproducing your results: Download all files. Run code file entitled "MA289 Neural Network". Upload files as prompted in the code. Once the code is finished running it will create an output CSV that will download to the computer. The code first creates a [900x100] embedding matrix and fills it with random values. It then uses a two-layer neural network, which takes the embeddings as its inputs and predicts the most likely output word, to refine the matrix using back propagation. Finally, it takes the embedded values and calculates their similarity and exports that information in a CSV file.

Acknowledgement: Gen AI was used both for coding and in helping me understand how the neural network can be applied to this problem.
