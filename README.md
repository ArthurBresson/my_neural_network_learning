# 🧠 my_neural_network_learning

Un projet d'apprentissage pratique et d'implémentation *from scratch* des réseaux de neurones, basé sur la série de cours référence **"Neural Networks: Zero to Hero" d'Andrej Karpaty** (ex-Head of AI chez Tesla, cofondateur d'OpenAI).

---

## 🎯 Objectif du Projet

L'objectif de ce dépôt est de comprendre en profondeur le fonctionnement interne des réseaux de neurones et des modèles de langage (LLMs) en reconstruisant leurs briques fondamentales à partir de zéro, sans dépendre uniquement de frameworks haut niveau au départ.

En suivant la pédagogie de Karpaty, ce projet retrace l'évolution complète de l'IA moderne : des fondements mathématiques de la rétropropagation jusqu'à l'architecture Transformer.

---

## 📚 Programme & Sujets Couverts

Ce projet reprend et implémente les concepts clés enseignés par Andrej Karpaty :

- **Micrograd :** Implémentation d'un moteur d'autodifférenciation (autograd) et d'un réseau de neurones basique à partir de zéro en Python.
- **Makemore (N-grams & MLP) :** Création de modèles de langage autorégressifs pour la génération de texte (du modèle statistique N-gram au Multi-Layer Perceptron inspiré de Bengio et al.).
- **BatchNorm & ResNet :** Compréhension et implémentation des couches de normalisation (Batch Normalization) et des connexions résiduelles pour stabiliser l'entraînement.
- **WaveNet & CNNs :** Structuration des réseaux profonds et traitement séquentiel / hiérarchique des données.
- **Building GPT & Transformers :** Implémentation complète d'un modèle type GPT (Generative Pre-trained Transformer) avec mécanismes d'Attention (Self-Attention, Multi-Head Attention), masquage et embeddings.

---

## 🛠️ Stack Technique

- **Langage :** Python 3.x
- **Bibliothèques :** PyTorch, NumPy, Matplotlib, Jupyter Notebooks

---

## 💡 Philosophie d'Apprentissage

> *"What I cannot create, I do not understand."* — Richard Feynman

En reconstruisant les algorithmes de gradient descent, de rétropropagation et les têtes d'attention ligne par ligne, ce projet permet d'acquérir une compréhension intuitive et rigoureuse du **Machine Learning**, du **Deep Learning** et de **l'IA Générative**.

---

## 🚀 Structure du Dépôt

```text
my_neural_network_learning/
├── notebooks/          # Explorations et implémentations pas à pas (Micrograd, Makemore, GPT...)
├── src/                # Scripts Python nettoyés et réutilisables
├── data/               # Datasets de démonstration (ex: noms, textes pour l'entraînement)
├── requirements.txt    # Dépendances du projet
└── README.md
