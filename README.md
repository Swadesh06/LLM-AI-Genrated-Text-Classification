# LLM Text Classification 

The following is an open project done under club VLG of IITR, which centred around classification of text by recognising wether or not it has been generated by a Large Language model.

![download](https://github.com/Swadesh06/LLM-AI-Genrated-Text-Classification/assets/129365476/d2ed9f91-bce7-4e30-bae8-90d566ffad5a)

## Dataset links:
Given Dataset- https://www.kaggle.com/competitions/llm-detect-ai-generated-text/data
Augmented Dataset by MIT - https://www.kaggle.com/datasets/jdragonxherrera/augmented-data-for-llm-detect-ai-generated-text


## About the data
### Given Datset-
-train.csv - Columns for ID , text columns , and generated column for displaying classified labels

### Augmented Dataset 
- contains text columns for classifation and Label column for prediction results


## Setup:

- setup for each model used is given separately below:

  ### DistilBERT(public score 0.803) :
  
<img width="294" alt="Screenshot 2024-01-15 at 10 00 56 PM" src="https://github.com/Swadesh06/LLM-AI-Genrated-Text-Classification/assets/129365476/17bc2e7f-6a64-48fd-9220-3383c62e517b">

In this setup I also downloaded the output files after the first Internet "on" run and uploaded them into the input directory so as to save the effort of having to have a first run with intenet on whenever I opened the notebpok again.


 ### RoBERTa (public score 0.672 ):
 
<img width="392" alt="Screenshot 2024-01-15 at 10 10 20 PM" src="https://github.com/Swadesh06/LLM-AI-Genrated-Text-Classification/assets/129365476/be025669-4a2c-48a2-bf24-ed7c42a69f80">

RoBERTa performed poorer despite being a more adavnced model due to overfitting and lack of optimization to make the suitable tokenizing changes. I implemented them later but some changes were left to be accomodated and time didn't allow for them.

### BERT (public score N/A) :

<img width="408" alt="Screenshot 2024-01-15 at 10 04 34 PM" src="https://github.com/Swadesh06/LLM-AI-Genrated-Text-Classification/assets/129365476/5576d19f-0469-4718-bbe4-329841930082">

BERT 


