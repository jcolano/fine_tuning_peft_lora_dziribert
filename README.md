# Fine Tuning of DiziriBERT with PEFT + LoRA For Binary Classification

## This model's objective is to classify Algerian dialect text as either Hateful or Non-Hateful

1. Import Libraries
Import necessary libraries such as Transformers, PyTorch, and Pandas.

2. Setup and Configuration
Define the model, tokenizer, and other hyperparameters like learning rate and batch size.

3. Prepare Datasets
Load stratified training and validation datasets from CSV files and tokenize them.

4. Define Metrics and Training Arguments
Set up the metrics for evaluation and configure the training settings using TrainingArguments.

5. Peft and LoRA Configuration
Apply Peft and LoRA configurations to the base model to enhance its capabilities.

6. Model Training
Initialize and train the model using the Trainer class.

7. Save Model
Save the fine-tuned model and tokenizer for future use.

8. Inference Preparation
Reload the fine-tuned model and prepare the test dataset.

9. Perform Inference
Run inference on the test dataset, saving both predicted labels and associated probabilities.

10. Evaluate Performance
Compare predicted and true labels to calculate metrics such as accuracy, precision, and F1 score. Also, calculate the ROC-AUC.

11. Identify False Positives
Extract and save instances where the model made false-positive predictions.
