# Projet BERT - Analyse de Sentiments  

## 📝 Contenu  
- **Notebook** : [Projet_BERT_Analyse_Sentiments(1).ipynb](Projet_BERT_Analyse_Sentiments(1).ipynb)
- **Vidéo** : [Regarder la démo](https://youtu.be/...) *(7 minutes)*  

## 🚀 Utilisation  
```python
from transformers import pipeline
modele = pipeline("text-classification", model="bert-base-uncased")
print(modele("Ce film est génial !"))  # → POSITIVE
