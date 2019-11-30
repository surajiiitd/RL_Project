# Deep Reinforcement Learning for Imbalanced Classification
# (Reinforcement Learning Project)
Deep_RL contains the deep Q learning technique.
To run it, follow the below guidelines:
1. use tools tools/conv_*.py to prepare datasets; read the headers of those files; data is expected to be in ../data
2. pretrained HPC models are in trained_hpc, or you can use tools/hpc_svm.py to recreate them; they are needed in ../data
3. run python3.6 main.py --dataset [dataset] --flambda [lambda] --use_hpc [0|1] --pretrain [0|1], choose dataset from config_datasets/
4. you can also evaluate the agent on the test set with eval.py --dataset [dataset] --flambda [lambda]



Baseline Methods: 
1. DNN : Deep Neural Network (Using CNN with FC layers)
2. Oversampling Method : Using SMOTE method
3. Undersampling Method : Sample the data randomly

Imbalance ratio = Np(number of positive samples)/ Nn(number of negative samples)
i.e, the number of positive samples and negative samples are equal then, imabalance ratio = 1.

Supplementary contains the report of the results. It contains all baseline model results.


Reference for Code : https://github.com/jaromiru/cwcf
