
Experiment: Designing a custom CNN network using VGG blocks and train using different optimizer and batch size.

Investigating the impact of different optimizers and batch sizes on the performance of a custom CNN built with VGG blocks.
This is interesting because:

It explores how optimization algorithms and data feeding strategies affect a specific network architecture (VGG blocks).
It can reveal insights into how these factors influence training efficiency and accuracy. 
The findings could be valuable for researchers and practitioners who design and train CNNs for various tasks. 

1. Finding the optimal architecture:  VGG blocks offer flexibility, but choosing the right combination and number of blocks for this specific task can be challenging.

2. Data dependency: The effectiveness of optimizers and batch sizes can be highly dependent on the size and characteristics of the dataset. 

3. Training time: Experimenting with different configurations requires running multiple training sessions, which can be time-consuming.

4. Overfitting vs underfitting: It's difficult to find the balance between optimizers and batch sizes that avoid overfitting the training data while achieving good generalization performance.

![image](https://github.com/sultanrafeed/CNN-prediction/assets/62619778/478de9b2-a881-4037-ae7f-dec3d57ae69b)

**Optimizer Used and Batch Size**
Possible optimizer:
1. RMSProp
2. Adam
3. AdamW
4. SparseAdam
5. Adamx
6. NAdam
7. RAdam
8. SGD

Batch sizes:
8, 16, and 32
For each optimizer, we will record the loss corresponding to each epoch (or epoch intervals). We will repeat the experiment for different batch size.

Performance of optimizers will be determined by the final loss after the last epoch as well as the rate of loss convergence. 



