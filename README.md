About:
-------


A convolutional neural net classifier (using Tensor Flow/Keras) that can detect with a high level of accuracy whether a given credit card transaction is legitimate or fraudulent.

The dataset has been collected and analyzed during a research collaboration of Worldline and the Machine Learning Group of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. The datasets contain transactions made using credit cards in September 2013 by European cardholders. The dataset contains transactions that occurred over the period of two days. The dataset is highly unbalanced: 492 frauds out of 284,807 transactions, so the fraudulent transaction class account for 0.172% of all payments.

I addressed the data imbalance by performing randomized sampling of the overrepresented class to reduce it to the size of 2x of the fraudlent class size. I have created a CNN model using Conv1D layers (RELU), Dense layers, and Batch Normalization. My goal was to achieve high accuracy. My current model yields over 98% accuracy rate after 30 epochs.


Install:
--------


Dataset is inside the zip archive (GitHub's 100MB limit). Unzip the dataset file into the notebook folder.