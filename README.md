# 🐍 Séance pédagogique S-PYTH-1005  
# Manipulation des chaînes de caractères dans l'interpréteur Python

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Module](https://img.shields.io/badge/Module-M--PYTH-green)
![Niveau](https://img.shields.io/badge/Niveau-Débutant-orange)

---

# 📌 Informations générales

| Élément | Description |
|---|---|
| **Référence séance** | S-PYTH-1005 |
| **Module** | M-PYTH – Programmation Python |
| **Thématique** | Manipulation des chaînes de caractères |
| **Langage utilisé** | Python |
| **Environnement** | Interpréteur Python / IDLE |
| **Prérequis** | Variables, types de données et opérateurs |

---

# 🎯 Présentation de la séance

Cette séance permet de découvrir et manipuler le type de données :

```python
str
```
## en Python.

Une chaîne de caractères représente une suite de caractères Unicode permettant de stocker et manipuler du texte.

Les chaînes sont omniprésentes dans les applications informatiques :

 - affichage d'informations ;
 - saisie utilisateur ;
 - traitement de fichiers ;
 - communication réseau ;
 - gestion de données textuelles.

Les activités proposées sont réalisées principalement dans :

 - l'interpréteur Python ;
 - l'environnement IDLE.

🎓 Objectifs pédagogiques

À la fin de cette séance, vous serez capable de :

✅ créer une chaîne de caractères ;

✅ déclarer une variable de type str ;

✅ afficher le contenu d'une chaîne ;

✅ accéder à un caractère avec un indice ;

✅ comprendre le principe d'indexation ;

✅ utiliser la concaténation ;

✅ répéter une chaîne ;

✅ utiliser les méthodes principales de manipulation :

```python
upper()
lower()
capitalize()
swapcase()
```

✅ extraire une sous-chaîne avec le découpage (slicing) ;

✅ utiliser l'indexation négative ;

✅ comprendre le principe d'immuabilité des chaînes ;

✅ modifier indirectement une chaîne.


# 🧩 Travail préparatoire

Avant de commencer la séance, effectuer une recherche sur les notions suivantes :

## ASCII

Système historique de codage permettant de représenter des caractères à l'aide de valeurs numériques.

## Unicode

Standard informatique permettant de représenter les caractères de nombreuses langues dans un même système.

## Séquence de données

Suite ordonnée d'éléments pouvant être parcourus individuellement.

## Encodage

Méthode utilisée pour transformer des caractères en données numériques stockables ou transmissibles.


# 📚 Contenu de la séance
## 1 - Création d'une chaîne de caractères

Une chaîne Python est de type :
```python
str

Exemples :

"Bonjour"

"Python"

"2026"

"Bonjour PQDI"

```
Une chaîne représente une suite ordonnée de caractères Unicode.



# 2 - Délimitation d'une chaîne

## Python accepte :

Avec des guillemets doubles
```python
message = "Bonjour"
```

Avec des apostrophes
```python
message = 'Bonjour'
```

## ⚠️ Erreur fréquente

Exemple incorrect :
```python
'Bonjour
```
Python génère une erreur car la chaîne n'est pas terminée.

Erreur possible :
```python
EOL while scanning string literal
```
Signification :
```python
End Of Line
```
# 3 - Caractères spéciaux

### Exemple :

Lorsqu'il fait froid

Solution avec guillemets doubles :
```python
"Lorsqu'il fait froid"
```
ou avec un caractère d'échappement :

```python
'Lorsqu\'il fait froid'
```
### Le symbole :
```python
\'
```
permet d'insérer une apostrophe dans une chaîne.

# 4 - Affectation à une variable

### Exemple :
```python
chaine = "Bonjour PQDI"
```
Affichage :
```python
chaine
```
ou :
```python
print(chaine)
```

# 5 - Indexation des caractères

Les chaînes sont indexées à partir de zéro.

### Exemple :
```python
chaine = "Bonjour PQDI"
```

|Caractère|B|o|n|j|o|u|r| |P|Q|D|I|
|---------|-|-|-|-|-|-|-|-|-|-|-|-|
|Indice   |0|1|2|3|4|5|6|7|8|9|10|11|

Accès au caractère :
```python
chaine[3]

# Résultat :

j
```
# 6 - Immuabilité des chaînes

Les chaînes Python ne peuvent pas être modifiées directement.

### Exemple interdit :
```python
chaine[1] = "i"
```
Erreur :
```python
TypeError
```

Une nouvelle chaîne doit être créée.

# 7 - Longueur d'une chaîne

## La fonction :
```python
len()
```
permet d'obtenir le nombre de caractères.

### Exemple :

```python
chaine = "Bonjour"

len(chaine)

# Résultat :

7
```

# 8 - Concaténation

La concaténation permet d'assembler plusieurs chaînes.

Opérateur utilisé :

## +

### Exemple :
```python
chaine1 = "Bonjour"
chaine2 = " PQDI"

chaine1 + chaine2
```
Résultat :
```python
Bonjour PQDI
```
# 9 - Répétition d'une chaîne

L'opérateur :

## *

permet de répéter une chaîne.

### Exemple :
```python
"Bonjour " * 3
```
Résultat :
```python
Bonjour Bonjour Bonjour
```

# 10 - Méthodes principales
Passage en majuscules
```python
message.upper()
```
Résultat :
```python
BONJOUR
```
Passage en minuscules
```python
message.lower()
```
Première lettre en majuscule
```python
message.capitalize()
```
Inversion majuscule/minuscule
```python
message.swapcase()
```
# 11 - Extraction de sous-chaînes

Python utilise le découpage :
```python
chaine[début:fin]
```
### Exemple :
```python
A = "Bonjour"

A[1:3]
```
Résultat :
```python
on
```
Autres exemples :
```python
A[3:]
```
Résultat :
```python
jour
```
```python
A[:3]
```
Résultat :
```python
Bon
```
# 12 - Indexation négative

Python permet d'accéder aux caractères depuis la fin.

### Exemple :
```python
chaine = "Bonjour PQDI"
```
Dernier caractère :
```python
chaine[-1]
```
Résultat :
```python
I
```
Avant dernier caractère :
```python
chaine[-2]
```
Résultat :
```python
D
```
# 📝 Exercices pratiques
## Exercice 1

Créer une variable contenant :

Python est formidable

Afficher son contenu.

## Exercice 2

Afficher :

le premier caractère ;
le dernier caractère ;
le quatrième caractère.

## Exercice 3

Afficher la longueur de la chaîne.

## Exercice 4

Transformer :

bonjour pqdi

en :

BONJOUR PQDI

## Exercice 5

Transformer :

BONJOUR PQDI

en minuscules.

## Exercice 6

Extraire :

jour

depuis :

"Bonjour"

## Exercice 7

Extraire :

Bon

## Exercice 8

Créer une chaîne composée de :

********************

## Exercice 9

Remplacer le caractère :

P

dans :

Python

par :

J

# 💻 Exercice IDLE

Créer un programme demandant le prénom de l'utilisateur.
Pour entrer une information utiliser la fonction input("Entrer votre prénom), cette fonction vous retourne la valeur saisie
cette fonction fera l'objet d'un séance 
utilisation :
```python
prenom = input("Entrer votre prénom)
```
## Exemple :

Entrez votre prénom : Alice

Résultat attendu :

Bonjour Alice


# ✅ Validation des acquis

À la fin de cette séance, vous devez savoir :

☑ créer une chaîne Python ;

☑ utiliser les indices ;

☑ comprendre l'indexation ;

☑ utiliser len() ;

☑ concaténer des chaînes ;

☑ répéter une chaîne ;

☑ utiliser les méthodes principales ;

☑ extraire une sous-chaîne ;

☑ utiliser les indices négatifs ;

☑ expliquer pourquoi une chaîne est immuable.

# 📂 Organisation du dépôt
```text
S-PYTH-1005/
│
├── README.md
│
├── exercices/
│   ├── exercice_01.py
│   ├── exercice_02.py
│   └── ...
│
└── idle/
    └── bonjour_prenom.py
```
