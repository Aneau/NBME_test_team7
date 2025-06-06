# 2025 NLP Final Project team 7

Kaggle Competition:<br>
NBME - Score Clinical Patient Notes<br>
https://www.kaggle.com/competitions/nbme-score-clinical-patient-notes

## Exploring Multi-Model Performance on NBME- Score Clinical Patient Notes
1. DeBERTa-v3-base (Baseline) 
2. Bio_ClinicalBERT 
3. Task-Adaptive Pretraining（TAPT）with DeBERTa-v3-base 
4. DeBERTa-v3-small 
5. DeBERTa-v3-large 
6. Ensemble model-DeBERTa-v3-large+DeBERTa-v1-large+DeBERTa-v1-base

## Team Member Contributions
* Shih-An: Bio-ClinicalBERT、TAPT with DeBERTa-v3-base 
* Xiao-Min: Deberta-v3-base、Deberta-v3-small

## Reference
*	Kaggle notebook
    - https://www.kaggle.com/code/yasufuminakama/nbme-deberta-base-baseline-train  
    - https://www.kaggle.com/code/mcps5601/notebookc5a9c9ffd8
* Papers
    - https://arxiv.org/abs/1904.03323
    - https://aclanthology.org/2024.bea-1.8/
* Hugging Face Model
    - https://huggingface.co/emilyalsentzer/Bio_ClinicalBERT
    - https://huggingface.co/microsoft/deberta-v3-small
    - https://huggingface.co/microsoft/deberta-v3-base
    - https://huggingface.co/microsoft/deberta-v3-large
    - https://huggingface.co/microsoft/deberta-large
    - https://huggingface.co/microsoft/deberta-base
