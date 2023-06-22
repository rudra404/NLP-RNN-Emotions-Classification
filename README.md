# Emotions Classification using RNNs
This project aims to use RNNs for classifying reddit comments into 14 different emotions. Several Experiments are carried out to get the best possible results using RNNs. Data pre-processing and exploration are also done.

There is a notebook for data exploration and visualisation, one for some initial experiments conducted on the dataset, and one bug notebook which has all 4 of the main experiments listed below. Experiments were originally conducted in separate notebooks which can be found in the folder.

## Description
The task at hand is a multi-class text classification problem. Using the ‘GoEmotions’ dataset, we must use a total of 14 emotion labels out of the original 27 categories and achieve the best performance possible on correctly classifying the reddit comments in this dataset. At the later stages of this project, the group must combine results obtained from this experimentation and deliver and deploy a complete pipeline.<br /><br />
For the individual experimentation, each team member selected a different machine learning approach and experimented with different hyperparameters, pre-trained vectors, and settings selected by the individual. The data pre-processing, dataset split, and merging and deletion of labels is all kept the same, making the comparison of experiment outcomes from the whole group easier and more feasible.<br /><br />
For my experiments, I chose to work with RNNs because several new comparative studies show that RNNs are capable of performing well on multi-class text classification problems such as ours. They can process variable-length sequences and capture contextual information from previous inputs which should give them a performance edge over other methods like SVM, naïve bayes, and decision trees. However, correctly implementing it is crucial as there are several parameters and settings that can be varied that affect performance of the model drastically. 

## List of experiments
With RNNs, I have conducted comparisons of:<br />
1. Pre-trained word embeddings (with 2 different implementation methods)<br />
2. RNN architecture variations<br />
3. Optimizers and related parameters<br />
4. Fine-tuning using pre-trained models<br /><br />

## Acknowledgements

Project supervisor: [Dr. Diptesh Kanojia](https://www.linkedin.com/in/dipteshkanojia/)
