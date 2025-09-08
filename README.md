# 🌫️💀 Impact de la pollution sur le taux de mortalité – PACA (2019–2020)

Projet d’exploration/analyse en **notebook Jupyter** : pollution atmosphérique (NO₂, PM₂.₅), météo (OpenWeather), démographie et **mortalité** en région PACA (2019–2020).  
Objectifs : nettoyer et explorer les données, étudier les corrélations (polluants ↔ mortalité), réaliser ACP / clustering, et synthétiser les résultats.

---

## 🗂️ Contenu du dépôt

├── Projet Exploration de donnees.ipynb # notebook unique (pipeline complet en etl)
├── data/ # jeux de données 
├── figures/ # graphiques exportés par le notebook
├── requirements.txt
└── .gitignore


- **Notebook** : chargement/nettoyage, features, visualisations, corrélations, ACP, clustering, export de figures.


---

## 📚 Données & variables

- **Pollution** : NO₂, PM₂.₅ (mesures agrégées par zone/période).
- **Météo (optionnel)** : température, vent, humidité via **OpenWeather**.
- **Démographie / Mortalité** : agrégations par âge/sexe/période/zone.



## ⚙️ Installation

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
# source .venv/bin/activate

pip install -r requirements.txt

(Optionnel) Clé OpenWeather

##🧑‍💻 Auteurs

 Touati Malik Abdel Hamid — 2025