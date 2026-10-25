# NLI avec BERT et des LLM locaux

Projet réalisé en cours de traitement du langage naturel à CentraleSupélec.

On teste de l'inférence en langage naturel (NLI) : à partir de deux phrases,
le modèle doit dire si la seconde découle de la première, la contredit
ou n'a aucun rapport avec elle.

## Les approches effectuées

- Fine-tuning de BERT sur une tâche de NLI
- Un deuxième essai de BERT avec 20 epochs
- Même chose avec DistilBERT, plus léger
- Comparaison avec des LLM qu'on fait tourner en local

## Les modèles

Les fichiers `model.safetensors` sont trop gros pour GitHub (plus de 100 Mo),
ils ne sont donc pas dans ce dépôt. Il faut relancer l'entraînement
pour les regénérer.

## Lancer le projet

pip install -r requirements.txt

Puis ouvrir les notebooks dans l'ordre.

## Auteurs

James Lemaitre
