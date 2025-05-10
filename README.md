Accurately predicting protein structural flexibility is
crucial for understanding protein function, interactions, and drug
design. Existing computational approaches, including molecular
dynamics simulations and deep learning models, face challenges
such as high computational costs, scalability issues, and limited
generalization to novel sequences. In this study, we propose
a deep learning framework that integrates transformer-based
embeddings with a bidirectional long short-term memory (BiLSTM) network to predict per-residue B-factors from protein
sequences. We utilize the ESM-2 transformer model to generate
rich sequence embeddings, which are then processed through
a BiLSTM network to capture long-range dependencies and
local sequential information. The proposed model is trained on a
dataset of 1,192 protein sequences obtained from the Protein Data
Bank. Experimental results demonstrate a Pearson correlation
coefficient of 0.6481 between predicted and actual B-factors,
indicating that our model effectively captures protein flexibility
trends while leaving room for further optimization. Future work
includes incorporating graph neural networks, refining feature
representations, and expanding datasets to enhance prediction
accuracy. Our findings contribute to advancing AI-driven protein
flexibility prediction, with potential applications in structural
biology and drug discovery.
