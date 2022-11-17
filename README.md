# DocumentClassifier

In this project, we categorize research papers based on their abstract into one of the seven domains from Mechanical Engineering (MAE), Computer Science(CS), Electrical Engineering(ECE), Medical, Biochemistry, Civil, and Psychology.
The goal of this project is to implement a generative probabilistic model and a neural network model for this task. We used Latent Dirichlet Allocation (LDA) for the generative probabilistic approach. For the neural network approach, we applied Global Vectors for Word Representation (Glove) to represent words and implement a Bidirectional Long short-term memory (biLSTM) neural network. The two models are tested on prelabeled data from Web of Science (WoS) Dataset and synthetic data generated by the LDA probabilistic model. The performances of both approaches are compared.
