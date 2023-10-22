# Adversarial Attacks using Cleverhans

- Launches an Adversarial Attack on ImageNet dataset using GANs from Cleverhans 4.0
- Adversarial samples are generated for a subset of the ImageNet dataset using 2 methods:
1. Fast Gradient Sign Method
2. Momentum Iterative Method
- Adversarial samples are saved and used for inference on a pre-trained ResNet model, allowing us to compare the results of both methods