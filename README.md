# HalluSafe-at-SemEval-Task-6-SHROOM

# This project is about:
Detecting Hallucination and overgeneration mistakes in Large Language Models, regarding the SemEval2024-Task-6-SHROOM.
We have trained DeBERTa-v3 model on Stanford Natural Language Inference dataset, and fine-tuned on SHROOM dataset to detect hallucinations for Machine Translation, Definition Modeling, and Paraphrase Generation tasks.

## About the notebooks in this repository:
- **DeBERTa_v3_large_NLI.ipynb**: The notebook for training DeBERTa_v3_large on Stanford Natural Language Inference dataset.
- **DeBERTa_v3_large_NLI_finetuning_DM.ipynb**: The notebook for fine-tuning DeBERTa_v3_large (trained on NLI) on SHROOM data for DM task.
- **DeBERTa_v3_large_NLI_finetuning_MT.ipynb**: The notebook for fine-tuning DeBERTa_v3_large (trained on NLI) on SHROOM data for MT task.
- **DeBERTa_v3_large_NLI_finetuning_PG.ipynb**: The notebook for fine-tuning DeBERTa_v3_large (trained on NLI) on SHROOM data for PG task.
- **shroom_Falcon_7B.ipynb**: The notebook for fine-tuning Falcon-7B on SHROOM data.


## Saved Models Links:
### NLI_model: *https://drive.google.com/drive/folders/1EV83Jtot4pPh9h5vwPXbANROoHaqykKa?usp=sharing*

### DM_model: *https://drive.google.com/drive/folders/1-QAS6bJqLFu1VEz5QGxai29O8N-zOaCT?usp=sharing*

### MT_model: *https://drive.google.com/drive/folders/1pYzRYe1mKg1LhFz2ATJDSU1FlnBDz8kV?usp=sharing*

### PG_model: *https://drive.google.com/drive/folders/1YmhZzfgp61WvUTy99Xuu2Ia_9uj6uniN?usp=sharing*

### Falcon_7B_model: *https://drive.google.com/drive/folders/1-o4ihAXaWTnJNK9eTeQiwRjI8yvvpCNb?usp=sharing*

## Data Information:
- **SHROOM_Dataset folder**: contains the original SHROOM task dataset.
- **Our_labeled_data folder**: contains the data samples we have labeled.


---------------------------------------
## Dataset Examples:

| task | column_name | column_value |
|----------|----------|-------------------------------------------------------------------|
| PG    | SRC| The budget cannot be adopted against the will of the European Parliament.|
|          | HYP|  The European Parliament does not approve the budget. |
|          | Label| Not Hallucination|
| DM    | SRC| Communistic birds. What is the meaning of communistic? |
|          | TGT| Living or having their nests in common. |
|          | HYP|Of or pertaining to communism. |
|          | Label| Hallucination|


------------------

## Contributors
- Zahra Rahimi: [Linkedin](https://www.linkedin.com/in/zahra-rahimi-7a089115b/), [Github](https://github.com/z-rahimi-r)
- Hamidreza Amirzadeh: [Linkedin](https://linkedin.com/in/hamidreza-amirzadeh-26635a181/), [Github](https://github.com/Hamiiidreza)
- Alireza Sohrabi: [Linkedin](https://www.linkedin.com/in/sohraabi/), [Github](https://github.com/SohrabiAlir)



