# Projet BERT - Analyse de Sentiments  

## 📝 Contenu  
- **Notebook** : [Projet_BERT.ipynb](Projet_BERT.ipynb)  
- **Vidéo** : [video.mp4](video.mp4) *(7 minutes)*  
- **Modèle** : Dossier `my_bert_sentiment_model/`  

## 🚀 Utilisation  
```python
from transformers import pipeline  
modele = pipeline("text-classification", model="./my_bert_sentiment_model")  
print(modele("J'ai adoré ce film !"))  # → 👍 Positif  
