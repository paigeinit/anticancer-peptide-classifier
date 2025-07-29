# Anticancer Peptide Classifier
#### Binary classifier for anticancer peptide sequences using a bidirectional GRU

This project was my final assessment for an introductory machine learning course I took at university. The objective was to build a binary classifier to predict whether a given peptide sequence had anticancer properties. The data consisted of amino acid sequences in FASTA format.

The requirements were as follows:

- Develop a fully functional model and report both the ROC AUC and the PR AUC.
- Structure your code as a complete, end-to-end, and reproducible program and use a parameter seed for all stochastic components.
- Run the training and evaluation process over 5 trials using seeds from 1 to 5. Report the mean and standard deviation of both ROC AUC and PR AUC scores.
- Achieve a mean ROC AUC of at least 0.83.
- Achieve a standard deviation of ROC AUC no greater than 0.015.
- Achieve a mean PR AUC of at least 0.43.
- Include a discussion at the end of your notebook.

I implemented one-hot encoding and a bidirectional GRU (Gated Recurrent Unit) neural network to identify relevant sequence patterns. The notebook includes all preprocessing, model training, and evaluation steps, including the final discussion.

### 🔧 Tools/frameworks used:
- TensorFlow (Keras)
- pandas, numpy, sklearn

### 📂 Dataset
The original peptide sequence dataset was provided in an academic setting and is **not included** here for licensing reasons.

## Results Summary

Across 5 seeded runs, the model achieved:

- **Average ROC AUC**: ~0.84 

- **Average PR AUC**: ~0.45

- **ROC AUC Std Dev**: ~0.0097
