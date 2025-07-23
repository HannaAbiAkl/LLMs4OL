# LLMs4OL

Source code and experimentation for the LLMs4OL at ISWC challenge.

[Challenge link](https://sites.google.com/view/llms4ol2025/home)

## Data
The data used is the scholarly data where a model should construct an ontology by predicting terms and linking them to types from scholarly documents.

## Experiments
Experiments were done for SubtaskA on the scholarly data:
- Zero-shot: predicting terms and types via zero-shot prompt with Flan-T5
- Few-shot: predicting terms and types via few-shot prompted examples with Flan-T5

## Results
Results on train data show that the model is capable of predicting all terms and is sometimes verbose in type classification (i.e., classifies some terms as types).
