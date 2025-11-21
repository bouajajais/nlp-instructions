# Sujet 03 : NLP Multimodal

## Rappel du sujet

Le **NLP multimodal** traite conjointement du texte et d'autres modalités (images, audio, vidéo). Les modèles multimodaux peuvent comprendre des images avec du texte, extraire du texte d'images, ou générer du contenu combinant plusieurs modalités.

## Tronc commun (obligatoire)

1. **Choisir une tâche multimodale** : VQA (Visual Question Answering), OCR + analyse, description d'image, etc.
2. **Utiliser un modèle multimodal** : GPT-4 Vision, CLIP, ou OCR + LLM
3. **Préparer des données** : Images + texte
4. **Implémenter la pipeline** : Traitement image + texte → résultat
5. **Baseline mono-modale** : Texte seul ou image seule

## Extensions possibles

1. **OCR structuré** : Extraire et analyser des documents
2. **Fusion multimodale** : Combiner embeddings texte + image
3. **Génération multimodale** : Créer images à partir de texte

## Pipeline typique

1. Choix de la tâche et données
2. Prétraitement des images
3. Extraction/embedding des modalités
4. Fusion et raisonnement
5. Évaluation

## Datasets suggérés

- Images + captions
- Documents scannés
- Infographies
- Screenshots + descriptions
