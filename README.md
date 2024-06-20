# CSE3000 Research Project - TU Delft university
## Leveraging LLMs for Classifying Subjective Topics Behind Public Discourse

## Setup
1. Clone Repository
2. Setup Python Version: 3.12.0
3. Run "pip install requirements.txt"

## Instructions
1. Upload the dataset
2. Run *Topic_modeling.ipynb* notebook first to get the labels for the dataset (main topics of the dataset) and to get the weak labels for fine-tuning using BERTopic 
2. Run *Prompting_methods.ipynb* notebook to run the prompting method for: **Identifying Gold Labels** and **Exploring Subjective Human Labels**.
3. Run *Fine_Tuning_LLaMa-2.ipynb* notebook to fine-tune the LLaMa model using QLoRa for **Identifying Gold Labels**
4. Run *evaluation/Micro_F1_Score.ipynb* notebook to Micro-F1 score to evaluate the prompting methods  
5. Run *evaluation/Fleiss_Kappa.ipynb* notebook to compute Fleiss Kappa metrics to get the inter-annotator disagreement
6. Run *preprocess_results/Preprocess_Results_MV.ipynb* notebook to preprocess results for **Identifying Gold Labels** (prompting methods) 
6. Run *preprocess_results/Preprocess_Results_Finetuning.ipynb* notebook to preprocess results for **Identifying Gold Labels** (fine-tuning results)
6. Run *preprocess_results/Preprocess_Results_All_Annotators.ipynb* notebook to preprocess results for **Exploring Subjective Human Labels**