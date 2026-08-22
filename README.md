# Atelier Scikit-learn — Prédiction de l'état de capteurs IoT

## Contexte

Une entreprise possède plusieurs bâtiments équipés de capteurs IoT. Chaque capteur collecte régulièrement des informations sur la température, l'humidité, la pression, la consommation énergétique, le bâtiment, la date et l'heure de la mesure. Chaque mesure possède également un état (`OK`, `ALERTE`, `ERREUR`).

**Objectif général** : construire un modèle de Machine Learning capable de prédire automatiquement l'état d'un capteur à partir de ses mesures.

**Workflow suivi** :
Dataset → Chargement → Exploration → Nettoyage → X / y → Train / Test → Prétraitement → Modèle → fit() → predict() → Évaluation → Sauvegarde → Chargement → Réutilisation

Le détail de chaque partie (objectif, code, explication, résultats et interprétation) se trouve dans le notebook : `notebooks/atelier_scikit-learn_iot.ipynb`.

---

## Structure du projet

```
atelier_scikit-learn_iot/
│
├── data/
│   └── mesures_capteurs.csv
│
├── notebooks/
│   └── atelier_scikit-learn_iot.ipynb
│
├── models/
│   ├── modele_capteur.joblib
│   └── modele_capteur.pkl
│
└── README.md
```

---

## Avancement de l'atelier

| Partie | Description | Statut |
|---|---|---|
| 0 | Mise en place de l'environnement | ✅ |
| 1 | Gestion des doublons | ✅ |
| 2 | Sélection de X (caractéristiques) et y (cible) | ✅ |
| 3 | Découpage Train / Test | ✅ |
| 4 | Gestion des valeurs manquantes | ✅ |
| 5 | Mise à l'échelle | ✅ |
| 6 | Entraînement et prédiction (KNN) | ✅ |
| 7 | Évaluation du modèle | ✅ |
| 8 | Sauvegarde du modèle | ✅ |
| 9 | Chargement et réutilisation du modèle | ✅ |
| 10 | Bonus | ⏳ |