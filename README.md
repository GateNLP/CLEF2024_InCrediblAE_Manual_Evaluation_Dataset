# CLEF2024_InCrediblAE_Manual_Evaluation_Dataset
Manual evaluation dataset of CheckThat! Lab at CLEF 2024 Task 6: Robustness of Credibility Assessment with Adversarial Examples (InCrediblAE) to assess semantic similarities between adversarial samples and the original samples. Each sample pair is judged by at least two annotators, and a third annotator is invited if there is a conflict between the two annotators.

## Structure:

* README.md: This file
* InCrediblAE_Manual_Evaluation_Dataset.csv: Anonymised Manual Evaluation Dataset
* LICENSE: License file CC0 1.0 Universal

## Dataset Headings:

* adversarial_samples: adversarial samples submitted by task paticipants
* original_samples: original example from Fack-checking task (the data from the FEVER shared task https://arxiv.org/abs/1811.10971v1)
* annotator1_stance: semantic similarities stance from annotator 1 (0: Preserve the Meaning, 1: Change the Meaning, 2: No sense)
* annotator1_confidence: confidence from annotator 1 (5:very confidnt, 1:not condident)
* annotator2_stance: semantic similarities stance from annotator 2 (0: Preserve the Meaning, 1: Change the Meaning, 2: No sense)
* annotator2_confidence: confidence from annotator 2 (5:very confidnt, 1:not condident)
* annotator3_stance: semantic similarities stance from annotator 3 (0: Preserve the Meaning, 1: Change the Meaning, 2: No sense)
* annotator3_confidence: confidence from annotator 3 (5:very confidnt, 1:not condident)
* agreed_labels: Label based on the majority votes

## Data Statistics(Based on agreed label):
* Preserve the Meaning (0): 318
* Change the Meaning (1): 246
* No sense (2): 116
* Cohen's Kappa = 0.5240984623870923

## Reference:
 Przybyła, Piotr, Ben Wu, Alexander Shvets, Yida Mu, Kim Cheng Sheang, Xingyi Song, and Horacio Saggion. "Overview of the CLEF-2024 CheckThat! lab task 6 on robustness of credibility assessment with adversarial examples (incrediblae)." Working Notes of CLEF (2024).
