# Simulation d'un écosystème proies-prédateurs 🐾

## **Description du projet**
Ce projet est une **simulation d'un écosystème** où des **proies** et des **prédateurs** interagissent dans un environnement dynamique.  
L'écosystème inclut également la gestion de la **génération d'herbe**, ressource essentielle pour les proies.  

L'objectif principal est de modéliser ces interactions et de visualiser leur évolution à travers une représentation graphique.

---

## **Caractéristiques principales**
- **Langage utilisé** : C
- **Structure modulaire** : Organisation en fichiers `.c`, `.h`, et compilation en `.o`.
- **Entités de l'écosystème** :
  - **Proies** : Se nourrissent de l'herbe et se reproduisent.
  - **Prédateurs** : Chassent les proies pour survivre.
  - **Herbe** : Ressource essentielle pour la survie des proies.
- **Représentation graphique** : Affichage de la grille de l'écosystème, mettant en évidence les entités et l'évolution de leurs interactions.

---

## **Fonctionnalités principales**
- Génération d'un **monde** sous forme de grille où chaque case peut contenir :
  - **Herbe** (qui repousse avec le temps).
  - **Proies** (qui se déplacent, mangent et se reproduisent).
  - **Prédateurs** (qui chassent les proies pour se nourrir, et se reproduisent).
- Simulation des cycles de vie des entités :
  - **Reproduction** des proies et prédateurs selon des conditions spécifiques.
  - **Mort des prédateurs** en cas de manque d'énergie.
- **Statistiques** : Évolution des populations (affichée à chaque itération).

---

## **Prérequis**
Pour exécuter ce projet, vous devez disposer de :
- Un compilateur C tel que **GCC**.
- (Facultatif) Une bibliothèque graphique comme **SDL2** pour un affichage graphique enrichi.

---

## **Compilation et exécution**
### **Compilation**
Le projet inclut un `Makefile` pour simplifier la compilation :  
```bash
make
