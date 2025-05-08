# Projet BERT - Analyse de Sentiments  

## 📝 Contenu  
- **Notebook** : [Projet_BERT_Analyse_Sentiments.ipynb](Projet_BERT_Analyse_Sentiments.ipynb)
- **Vidéo** : [Regarder la démo](https://youtu.be/...) *(7 minutes)*  

## 🚀 Utilisation  
```python
from transformers import pipeline
modele = pipeline("text-classification", model="bert-base-uncased")
print(modele("Ce film est génial !"))  # → POSITIVE
