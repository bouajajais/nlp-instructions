# Sujet 05 : Tool Calling / MCP

## Rappel du sujet

Le **tool calling** permet aux LLMs d'appeler des fonctions ou outils externes (calculatrice, API, base de données). Le **Model Context Protocol (MCP)** standardise cette intégration.

## Tronc commun (obligatoire)

1. **Définir des outils** : Fonctions que le LLM peut appeler
2. **Implémenter l'interface** : Parsing des appels, exécution
3. **Gestion d'erreurs** : Validation, retry
4. **Démonstration** : Exemples concrets
5. **Baseline** : Sans outils vs avec outils

## Extensions possibles

1. **MCP standard** : Architecture MCP-compliant
2. **Outils multiples** : Coordination de plusieurs outils
3. **Validation** : Vérification des paramètres
4. **Outils asynchrones** : Gestion d'appels longs

## Pipeline typique

1. Choix des outils nécessaires
2. Définition des interfaces
3. Implémentation de l'orchestration
4. Tests et validation
5. Évaluation

## Exemples d'outils

- Calculatrice
- Recherche web
- Accès base de données
- API externes
