## Fine-Tuning Microsoft Phi-2 for Sentiment Analysis in Finance News Headlines

### Overview
The code aims to develop an efficient sentiment analysis model for financial headlines. It involves data preparation, quantization of a pre-trained language model, training, and evaluation with a focus on accuracy and other metrics. Additionally, the model undergoes fine-tuning using Layer-wise Relevance Aggregation (LORA), and the training progress is monitored using TensorBoard. The ultimate goal is to achieve accurate sentiment predictions for financial data.

### Dataset
- **Source:** "/content/drive/MyDrive/all_financial_sentiment_data.csv"
- **Size:** 4846 entries, 2 columns ("sentiment," "text")
  
**Data Info:** 
- No missing values.
- **Columns:** "sentiment" and "text" (object type).
- **Label Distribution:** "Neutral" (2879), "Positive" (1363), "Negative" (604).

**Data Preparation:**
- Balanced split into training and testing sets for each sentiment. Additional evaluation set created.


