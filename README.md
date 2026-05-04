<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=2500&pause=800&color=2E86C1&background=FFFFFF00&center=true&vCenter=true&multiline=false&width=750&lines=🛒+Automatisation+des+Ventes+|+Python;📊+Analyse+E-commerce+Intelligente;💰+CA+Brut+·+CA+Net+·+TVA+·+TTC;🏆+Projet+de+Fin+d'Année+—+LMI2" alt="Titre animé"/>

<br/>

![Python](https://img.shields.io/badge/Python-3.14-blue?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Graphiques-orange?style=for-the-badge)
![CSV](https://img.shields.io/badge/Données-CSV-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Statut-✅%20Terminé-brightgreen?style=for-the-badge)

</div>

---

<div style="background-color:#e8f5e9; padding:30px; color:black;">
  <strong style="font-size:35px;">📋 Description</strong>
  <p>
    Ce projet automatise l'analyse des ventes d'une entreprise <strong>e-commerce</strong>.
    Le script Python génère un fichier CSV, effectue des calculs financiers et produit des graphiques.
  </p>
</div>

---

<div style="background-color:#fce4ec; padding:30px; color:black;">
  <strong style="font-size:30px;">🎯 Objectifs du projet</strong>
  <br/><br/>
  <p>Ce projet a été conçu avec plusieurs objectifs pédagogiques et techniques :</p>
  <ul>
    <li>🐍 <strong>Maîtriser Python</strong> — appliquer les bases du langage (boucles, fonctions, manipulation de fichiers) dans un contexte réel.</li>
    <li>📂 <strong>Manipuler des fichiers CSV</strong> — générer, lire et écrire des données structurées à l'aide des modules <code>csv</code> et <code>pandas</code>.</li>
    <li>🧮 <strong>Automatiser des calculs financiers</strong> — calculer automatiquement le CA Brut, le CA Net, la TVA et le CA TTC sans intervention manuelle.</li>
    <li>📊 <strong>Visualiser les données</strong> — produire des graphiques clairs et lisibles avec <code>matplotlib</code> pour faciliter la prise de décision.</li>
    <li>🏆 <strong>Identifier les tendances</strong> — détecter le produit le plus rentable et analyser les performances de vente.</li>
    <li>📁 <strong>Exporter les résultats</strong> — sauvegarder les données traitées dans des fichiers <code>.csv</code> et <code>.xlsx</code> réutilisables.</li>
    <li>🤝 <strong>Travailler en équipe</strong> — organiser et répartir le travail dans le cadre d'un projet collaboratif de fin d'année.</li>
  </ul>
</div>

---

<div style="background-color:#e3f2fd; padding:30px; color:black;">
  <strong style="font-size:30px;">📦 Bibliothèques utilisées</strong>
  <br/><br/>

  | Bibliothèque | Version | Rôle |
  |---|---|---|
  | **Python** | 3.14 | Langage principal du projet |
  | **Matplotlib** | ≥ 3.x | Génération des 3 graphiques (barres, camembert, courbes) |
  | **Pandas** | ≥ 2.x | Manipulation et analyse des données CSV |
  | **CSV** | intégré | Lecture et écriture des fichiers `.csv` |
  | **OS** | intégré | Gestion des chemins et fichiers du système |

  <br/>
  <p>Installez toutes les dépendances en une seule commande :</p>

```bash
pip install -r requirements_raed_tasnim_rima.txt
```

</div>

---

<div style="background-color:#fff9c4; padding:30px; color:black;">
  <strong style="font-size:30px;">✨ Ce que fait le programme</strong>
  <ul>
    <li>📄 Génère automatiquement le fichier <code>ventes.csv</code></li>
    <li>💰 Calcule le CA Brut : Prix × Quantité</li>
    <li>💸 Calcule le CA Net après remise</li>
    <li>🏦 Calcule la TVA à 20%</li>
    <li>📊 Affiche le CA Total dans le terminal</li>
    <li>🏆 Trouve le produit le plus rentable</li>
    <li>📁 Exporte les résultats dans <code>resultats_final.csv</code></li>
    <li>📈 Génère 3 graphiques avec Matplotlib</li>
  </ul>
</div>

---

<div style="background-color:#e8eaf6; padding:30px; color:black;">
  <strong style="font-size:30px;">🧮 Formules utilisées</strong>
  <ul>
    <li>CA Brut = Prix × Quantité</li>
    <li>CA Net = CA Brut × (1 − Remise / 100)</li>
    <li>TVA = CA Net × 0.20</li>
    <li>CA TTC = CA Net + TVA</li>
  </ul>
</div>

---

<div style="background-color:#e3f2fd; padding:30px; color:black;">
  <strong style="font-size:30px;">🚀 Comment lancer le projet</strong>
  <ol>
    <li>Cloner le dépôt : <code>git clone &lt;lien-github&gt;</code></li>
    <li>Installer les dépendances : <code>pip install -r requirements_raed_tasnim_rima.txt</code></li>
    <li>Lancer le script : <code>py analyse_ventes_raed_tasnim_rima.py</code></li>
  </ol>
</div>

---

## 📂 Fichiers du projet

```
automatisation-ventes/
│
├── analyse_ventes_raed_tasnim_rima.py     ← Script principal (à lancer)
├── requirements_raed_tasnim_rima.txt      ← Dépendances Python
├── README.md                              ← Ce fichier
├── .gitignore                             ← Fichiers exclus de Git
└── venv/                                  ← Environnement virtuel Python
    ├── Scripts/                           ← Exécutables (Windows)
    ├── Lib/                               ← Bibliothèques installées
    └── pyvenv.cfg                         ← Configuration de l'environnement
```

> ⚠️ `ventes.csv`, `resultats_final.xlsx`, `resultats_final.csv` et `graphiques_ventes.png` sont **générés automatiquement** par le code.

---

<div style="background-color:#c8e6c9; padding:20px; color:black;">
  <strong style="font-size:30px;">👥 Équipe</strong>
  <ul>
    <li><strong>Raed Hammouda</strong></li>
    <li><strong>Tasnim Ben Romdhane</strong></li>
    <li><strong>Rima Ben Arfi</strong></li>
  </ul>
</div>

---

<div style="background-color:#eeeeee; padding:15px; color:blue;">
  <strong style="font-size:25px;">📄 Licence LMI2</strong>
  <p>Projet académique réalisé dans le cadre du cours <strong>Logiciels</strong> — 2025/2026.</p>
</div>

---

<div align="center">
<img src="https://img.shields.io/badge/Made%20with-❤️%20&%20Python-red?style=for-the-badge"/>
</div>
