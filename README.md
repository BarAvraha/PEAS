Black box attacks, where adversaries have limited knowledge of the target model, pose a significant threat to machine learning systems. Adversarial examples generated with a substitute model often suffer from limited transferability to the target model. While recent work explores ranking perturbations for improved success rates, these methods see only modest gains. 

We propose a novel strategy called PEAS that can boost the transferability of existing black box attacks. PEAS leverages the insight that samples which are perceptually equivalent exhibit significant variability in their adversarial transferability. Our approach first generates a set of images from an initial sample via subtle augmentations. We then evaluate the transferability of adversarial perturbations on these images using a set of substitute models. Finally, the most transferable adversarial example is selected and used for the attack. 

Our experiments show that PEAS can double the performance of existing attacks, achieving a 2.5x improvement in attack success rates on average over current ranking methods. We thoroughly evaluate PEAS on ImageNet and CIFAR-10, analyze hyperparameter impacts, and provide an ablation study to isolate each component's importance.

This work is based on the paper: PEAS: A Strategy for Crafting Transferable Adversarial Examples
to boost the transferability of existing black box attacks.
review at the ACM Transactions on Intelligent Systems and Tech-
nology (TIST) journal (Rank Q1).”
