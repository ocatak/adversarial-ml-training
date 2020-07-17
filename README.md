# Adversarial Machine Learning Mitigation: *Adversarial Learning*

There are several attacks against deep learning models in the literature, including **fast-gradient sign method** (FGSM), **basic iterative method** (BIM) or **momentum iterative method** (MIM) attacks. These attack are the purest form of the gradient-based evading technique that is used by attackers to evade the classification model. 

## Cite The Code
If you find those results useful please cite this paper :
```
    @PROCEEDINGS{catak-adv-ml-2020,
    title = {Deep Neural Network based Malicious Network Activity Detection Under Adversarial Machine Learning Attacks},
    booktitle = {Proc.\ 3rd International Conference on Intelligent Technologies and Applications (INTAP 2020)},
    volume = 5805,
    series = {LNCS},
    publisher = {Springer},
    year = {2020}
    }
```
## Introduction
In this work, I will present a new approach to protect a malicious activity detection model from the several adversarial machine learning attacks. Hence, we explore the power of applying adversarial training to build a robust model against FGSM attacks. Accordingly, (1) dataset enhanced with the adversarial examples; (2) deep neural network-based detection model is trained using the KDDCUP99 dataset to learn the FGSM based attack patterns. We applied this training model to the benchmark cyber security dataset.

The adversarial machine learning has been used to describe the attacks to machine learning models, which tries to mislead models by malicious input instances. Figure shows the typical adversarial machine learning attack.

![Adversarial machine learning attack](adversarial_attack.png)

A typical machine learning model basically consists of two stages as training time and decision time. Thus, the adversarial machine learning attacks occur in either training time or decision time. The techniques used by hackers for adversarial machine learning can be divided into two, according to the time of the attack:

* **Data Poisoning**: The attacker changes some labels of training input instances to mislead the output model.
* **Model Poisoning**: The hacker drives model to produce false labeling using some perturbated instance after the model is created.

Our model is able to respond to the model attacks by hackers who use the adversarial machine learning methods. Figure illustrates the system architecture used to protect the model and to classify correctly.
![Adversarial machine learning attack mitigation](adversarial-machine-learning-mitigation.png)
