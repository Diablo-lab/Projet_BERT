# Projet BERT - Analyse de Sentiments  

## 📝 Contenu  
- **Notebook** : [Voir le notebook ici](https://github.com/Diablo-lab/Projet_BERT/blob/main/Projet_BERT.ipynb)
- **Vidéo** : [video.mp4](video.mp4) *(7 minutes)*  
- **Modèle** : Dossier `my_bert_sentiment_model/`  

## 🚀 Utilisation  
```python
from transformers import pipeline  
modele = pipeline("text-classification", model="./my_bert_sentiment_model")  
print(modele("J'ai adoré ce film !"))  # → 👍 Positif  
