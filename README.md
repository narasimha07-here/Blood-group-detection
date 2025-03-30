🔬 Blood Group Detection from Fingerprints
This project uses deep learning to predict blood groups from fingerprint images. The model is built using ResNet and trained with the Fastai library for efficient transfer learning.

Overview:
Traditional blood group testing requires physical blood samples, but this project explores a non-invasive approach by analyzing fingerprint patterns. The model is trained on a Kaggle dataset and fine-tuned using data augmentation techniques to improve generalization.

Technologies Used:

Python

Fastai

PyTorch

ResNet (Transfer Learning)

Methodology:

Dataset: Used a publicly available fingerprint dataset from Kaggle.

Preprocessing: Applied augmentations like rotation, flipping, and brightness adjustments to enhance generalization.

Model Training: Fine-tuned ResNet using Fastai's fine_tune method.

Evaluation: Achieved 91% accuracy on test data.

Real-World Testing: Observed performance drop on real-time fingerprints due to quality differences, highlighting the need for fingerprint scanner sensors.

Future Improvements:

Use fingerprint scanners for better real-world accuracy.

Train on more diverse datasets to improve generalization.

Explore contrast enhancement and other preprocessing techniques.
