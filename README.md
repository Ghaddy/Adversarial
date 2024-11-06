Enhancing Security of Online Interfaces: Adversarial Handwritten Arabic CAPTCHA Generation

Description:
CAPTCHAs are widely used to protect online services, but they have increasingly become vulnerable to machine learning attacks. In this study, we propose a novel approach to generating adversarial Arabic handwritten CAPTCHAs using five adversarial perturbation techniques:

Expectation Over Transformation (EOT)
Scaled Gaussian Translation with Channel Shifts Attack (SGTCS)
Jacobian-based Saliency Map Attack (JSMA)
Immutable Adversarial Noise (IAN)
Connectionist Temporal Classification (CTC)
We also conduct comprehensive usability and security evaluations of the generated CAPTCHAs to assess their effectiveness. By leveraging recent advancements in machine learning, our approach offers a robust strategy for creating Arabic handwritten CAPTCHAs that enhance security against potential attacks.

Evaluation Results:
Our evaluation results demonstrate that the JSMA technique provided the highest security level, with 30% of meaningless word CAPTCHAs completely unrecognized, and 6.66% for meaningful words. From a usability standpoint, the JSMA technique achieved the best accuracy, with 75.6% for meaningless words and 90.6% for meaningful words.

The project repository contains :Evaluation Results: This file contains the usability and security evaluations dataset of the generated Arabic handwritten CAPTCHAs.


Code Structure:
The project repository contains the following main files:

adversarial-eot.ipynb: This script generates the adversarial images using EOT.
adversarial-ian.ipynb: This script generates the adversarial images using IAN.
adversarial-jsma.ipynb: This script generates the adversarial images using JSMA.
adversarial-ctc.ipynb: This script generates the adversarial images using CTC.
adversarial-sgtcs.ipynb: This script generates the adversarial images using SGTCS.
