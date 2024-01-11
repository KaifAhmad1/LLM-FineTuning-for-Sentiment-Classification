## Fine-Tuning Microsoft Phi-2 for Sentiment Analysis in Finance News Headlines

### Overview
The code aims to develop an efficient sentiment analysis model for financial headlines. It involves data preparation, quantization of a pre-trained language model, training, and evaluation with a focus on accuracy and other metrics. Additionally, the model undergoes fine-tuning using Layer-wise Relevance Aggregation (LORA), and the training progress is monitored using TensorBoard. The ultimate goal is to achieve accurate sentiment predictions for financial data.

### Dataset
- **Source:** FinancialPhraseBank Downloaded from Kaggle
- **Size:** 4845 datapoints, 4837 unique
- **Sentiments (%):**
  - Positive: 28%
  - Neutral: 59%
  - Negative: 12%

### Model Fine-Tuning
Explore the fine-tuning of the Small Open Source Model **Micrsoft-Phi-2** for sentiment classification on financial news Headlines.

