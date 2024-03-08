# Algorithme de résolution pour l'inférence logique

Ce référentiel contient une implémentation de l'algorithme de résolution pour l'inférence logique. L'algorithme de résolution est une méthode fondamentale de raisonnement et de logique automatisés, utilisée pour vérifier la validité des énoncés logiques en logique propositionnelle.

## Table des matières

- [Aperçu](#aperçu)
- [Comment ça marche](#comment-ça-fonctionne)
- [Utilisation](#utilisation)
- [Exemples](#exemples)

## Aperçu

L'algorithme de résolution est une procédure de décision permettant de vérifier la validité d'une formule logique du premier ordre par réfutation. Il fonctionne en essayant de trouver une contradiction à partir de l'ensemble des clauses obtenues en convertissant la formule d'entrée en forme normale conjonctive (CNF).

Ce référentiel fournit une implémentation Python de l'algorithme de résolution, permettant aux utilisateurs de saisir des expressions logiques et de déterminer leur validité.

## Comment ça fonctionne

Les principales étapes de la mise en œuvre de l’algorithme de résolution sont les suivantes :

1. **Conversion en CNF** : L'expression logique d'entrée est convertie en forme normale conjonctive (CNF) à l'aide de la fonction `to_cnf` de la bibliothèque `sympy`.

2. **Négation et simplification** : La forme CNF de l'expression d'entrée niée est générée, puis simplifiée en utilisant à nouveau `to_cnf`.

3. **Résolution** : L'algorithme effectue une résolution sur l'ensemble des clauses obtenues à partir du CNF nié et simplifié.

4. **Contrôle de validité** : Si une clause vide (contradiction) est dérivée, la formule originale est considérée comme valide.

## Utilisation

Pour utiliser l'algorithme de résolution :

1. Clonez ce référentiel sur votre machine locale :

    ```bash
    clone git https://github.com/your-username/resolution-algorithm.git
2. Installez les dépendances requises. La bibliothèque sympy est utilisée pour les mathématiques symboliques :
    `pip installe sympy`
3. exécutez l'algorithme de résolution `python Resolution Algorithm.py`

## Exemples
![Algorithme de résolution](https://github.com/YOUNESELKACIMI/Resolution-algorithm/assets/119015253/405a7b9d-8e0f-4484-bd6a-62ad23b08679)
