This project aims to classify customer reviews into sentiment categories using a fine-tuned BERT (Bidirectional Encoder Representations from Transformers) model. The goal is to automatically understand and categorize user feedback to improve business insights, customer experience, and product quality.

Good (Positive feedback)

Bad (Negative feedback)

Neutral (Mixed or ambiguous feedback)

Worst (Extremely negative or harmful feedback)

Technologies & Tools Used:
Python

PyTorch – For model definition and training

Transformers (HuggingFace) – For BERT tokenizer and architecture

Google Colab – Training and running the model

Google Drive – Saving and loading custom model weights

Matplotlib / Plotly – For visualizing prediction distribution

Features:
Real-time Text Classification: Input any customer review, get instant sentiment prediction.

Fine-tuned BERT Model: Achieves contextual understanding beyond keyword spotting.

Class Distribution Control: Bias the training dataset or sampling so that final output respects 70-20-10 pattern.

Local Deployment with Google Drive: Save and reuse models without retraining every time.

Scalable: Can be expanded to include multilingual models or aspect-based sentiment analysis.

