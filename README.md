# Incremental Learning in Image Classification

This is the final project of our course 01TXFSM - Machine learning and Deep learning in Politecnico di Torino.



## What is the problem that you will be investigating? Why is it interesting?

Incremental learning in image classification.

It's a really practical technique, not only in image classification tasks but also in almost all kinds of machine learning tasks where the trained model can be complex. 

What's more, considering the case that we deploy a trained model in an enterprise environment, when new data needs to be trained, the cost of retraining a model may be relatively high. 

Therefore, incremental learning can be a good topic to study on.



## What reading will you examine to provide context and background? What data will you use? 

We will first check the following 4 papers given by our TA Fabio Cermelli:

[1] P. Dhar, R. V. Singh, K. C. Peng, Z. Wu, and R. Chellappa, “Learning without memorizing,” Proc. IEEE Comput. Soc. Conf. Comput. Vis. Pattern Recognit., vol. 2019-June, pp. 5133–5141, 2019.

[2] S. Hou, X. Pan, C. C. Loy, Z. Wang, and D. Lin, “Learning a unified classifier incrementally via rebalancing,” Proc. IEEE Comput. Soc. Conf. Comput. Vis. Pattern Recognit., vol. 2019-June, pp. 831–839, 2019.

[3] S. Rebuffi, A. Kolesnikov, G. Sperl, and C. H. Lampert, “Incremental Classifier and Representation Learning.pdf,” pp. 2001–2010, 2001.

[4] H. Liang et al., “Distilling the knowledge in a neural network (Godfather’s Work),” Stud. Conserv., vol. 59, no. sup1, pp. S96–S99, 2014.

Afterwards we will try to find more papers around the topics of "incremental learning", "distillation", "forgetting" and so on. 

We will use the CIFAR-100 dataset as required in the project description.



## What method or algorithm are you proposing? How do you plan to improve or modify existing implementations?

First we will re-implement the algorithms described in iCaRL: Incremental Classifier and Representation Learning, as required in the project description. 

Then we will try different classification and distillation losses, and different classifiers, as suggested in the project description.



##  How will you evaluate your results? Qualitatively (e.g. plots or figures) and Quantitatively (e.g. what performance metrics or statistical tests)

We will plot figures to show the results of accuracy, with 10 classes per step.

Since CIFAR-100 has 100 classes containing 600 images each, it's a balanced dataset so we can use accuracy as performance metric. 



# Useful references

https://github.com/xialeiliu/Awesome-Incremental-Learning

https://github.com/Barrel-Titor/continual-learning

https://github.com/srebuffi/iCaRL

https://github.com/arunmallya/packnet/blob/master/src/lwf.py

https://github.com/MrtnMndt/OCDVAEContinualLearning

https://github.com/akamaster/pytorch_resnet_cifar10