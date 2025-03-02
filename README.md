# MAGIC-Gamma-Telescope-Particle-Identification

To analyze particle identification performance, multiple machine learning models were tested to compare variations in results and accuracy. Among them, a neural network (NN) model achieved an overall accuracy of 86%.

Interestingly, the model was significantly better at predicting Gamma particles (Class 1) than Hadron particles (Class 0). Gamma particles were identified with high precision (94%), whereas Hadron particle predictions were less reliable, with a lower precision of 74%.

| Class  | Precision | Recall | F1-Score | Support |
|--------|-----------|--------|----------|---------|
| **0 (Hadron)** | 0.74 | 0.87 | 0.80 | 1,185 |
| **1 (Gamma)**  | 0.94 | 0.86 | 0.90 | 2,619 |
| **Overall Accuracy** | - | - | **0.86** | **3,804** |
| **Macro Avg** | 0.84 | 0.86 | 0.85 | 3,804 |
| **Weighted Avg** | 0.87 | 0.86 | 0.86 | 3,804 |

The results suggest that while the model is highly effective at recognizing Gamma particles, improvements could be made in distinguishing Hadron particles more accurately.
