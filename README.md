# TripleAAA

## Description
Projet de monitoring système en Python avec génération de dashboard HTML.

## Fonctionnalités
- Surveillance CPU (cœurs, fréquence, utilisation)
- Surveillance RAM (utilisée, totale, pourcentage)
- Top 3 des processus les plus gourmands (CPU et RAM)
- Analyse de fichiers par extension dans /home
- Génération automatique d'un dashboard HTML

## Prérequis
```bash
pip install psutil distro
```

## Utilisation
```bash
python monitor.py
```

Le dashboard sera généré dans `/var/www/html/index.html`

## Structure du projet
- `monitor.py` : Script principal de monitoring
- `template.html` : Template HTML pour le dashboard
- `template.css` : Feuille de style CSS
- `.gitignore` : Exclusion des fichiers HTML/CSS du versioning

## Branches
- **main** : Branche principale
- **Tristan** : Développement Tristan Algorithmique
- **Fabio** : Développement Fabio Affichage
- **Caleb** : Développement Caleb Administration
