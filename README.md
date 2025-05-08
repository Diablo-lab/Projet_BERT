# Projet BERT - Analyse de Sentiments  

## 📝 Contenu  
- **Notebook** : [Projet_BERT.ipynb](Projet_BERT.ipynb) *(Clique pour voir le code)*  
- **Vidéo** : [Regarder la démo](https://youtu.be/...) *(7 minutes)*  

## 🚀 Utilisation  
```python
from transformers import pipeline
modele = pipeline("text-classification", model="bert-base-uncased")
print(modele("Ce film est génial !"))  # → POSITIVE
