# Classification du Cancer du Sein avec le Deep Learning 🎗️

Ce projet est dédié à la classification des images médicales mammaires afin d'aider au diagnostic précoce du cancer du sein à l'aide de modèles de Deep Learning.

---

## 📸 Contexte Médical et Imagerie

Le dépistage s'effectue généralement à l'aide d'un **mammographe**, un appareil de radiographie spécialement conçu pour l'étude de la glande mammaire. Cet appareil permet de capturer des structures internes à haute résolution afin de détecter d'éventuelles anomalies (masses, microcalcifications).

### L'Appareil Mammaire (Mammographe)
<p align="center">
  <img src=""C:\Users\HP\Downloads\MRI Bleu.png"" alt="Mammographe 3D" width="400"/>
  <br><em>Figure 1 : MRI - mammographie de clichés mammaires.</em>
</p>

---

## 🔬 Interprétation des Différents Résultats

Les images obtenues via mammographie ou échographie mammaire sont analysées par le modèle pour être classées. Les structures d'une poitrine dense ou la présence d'une masse peuvent indiquer différents stades :

1. **Normal / Tissu Dense :** Absence d'anomalie visible, bien que la densité mammaire puisse masquer de petites lésions.
2. **Bénin (Benign) :** Présence d'une masse non cancéreuse (ex: kyste, adénofibrome), souvent caractérisée par des contours réguliers et nets.
3. **Malin (Malignant) :** Présence d'une tumeur cancéreuse, présentant généralement des contours irréguliers, spiculés ou infiltrants.

## 🚀 Objectifs du Projet

- **Prétraitement des données :** Redimensionnement, normalisation et augmentation des images médicales.
- **Classification automatisée :** Entraînement d'un réseau de neurones convolutifs (CNN) pour différencier les cas sains, bénins et malins.
- **Évaluation :** Analyse des performances du modèle via des matrices de confusion et des courbes ROC pour garantir une sensibilité élevée (minimiser les faux négatifs).

## 🛠️ Technologies Utilisées

- **Langage :** Python
- **Environnement de développement :** Google Colab / Jupyter Notebook
- **Librairies principales :** TensorFlow / Keras (ou PyTorch), OpenCV, NumPy, Matplotlib, Scikit-learn

## 📈 Résultats et Métriques du Modèle
---
💡 *Projet réalisé dans le cadre de l'application de l'Intelligence Artificielle à la santé.*
<p align="center">
  <img src="C:\Users\HP\Downloads\données.png" />
  <br><em>Figure 2 : Données ayant à l'étude - source : Kaggle.</em>
</p>

<p align="center">
  <img src="C:\Users\HP\Downloads\données.png" />
  <br><em>Figure 3 : Données ayant à l'étude - source : Kaggle.</em>
</p>

<p align="center">
  <img src="C:\Users\HP\Downloads\model séquentiel.png"/>
  <br><em>Figure 5 : Modèle séquentiel.</em>
</p>

<p align="center">
  <img src="C:\Users\HP\Downloads\visual seabrn.png" />
  <br><em>Figure 4 : Visualisation des données avec seaborn.</em>
</p>

<p align="center">
  <img src="C:\Users\HP\Downloads\techvidan.png" />
  <br><em>Figure 5 : Techvidan.</em>
</p>

<p align="center">
  <img src="C:\Users\HP\Downloads\heatmap.png"/>
  <br><em>Figure 5 : Heatmap.</em>
</p>
---

