# Consistency Calculator for Prop Firms

This web application helps you verify if your trading performance complies with the consistency rules imposed by most prop firms (proprietary trading companies). It allows you to simulate, track, and analyze your daily results to maximize your chances of being eligible for a payout.

## Main Features

- Input strategy parameters (target profit, consistency rule, min % of best day, min profit/day, min trading days).
- Add and manage daily results (P&L).
- Graphical visualization of performance.
- Automatic analysis of eligibility and points to improve.
- Export results in CSV format.
- Bilingual interface (French/English) and dark mode.

## Usage

### 1. Strategy Setup

At the top of the page, fill in:
- **Target Profit ($)**: total amount to reach.
- **Consistency Rule (%)**: maximum percentage the best day can represent of the total.
- **Min % of Best Day**: minimum percentage of the best day that each day must reach.
- **Min Profit/Day ($)**: minimum profit amount per day.
- **Min Trading Days**: minimum number of days to validate.

### 2. Adding Daily Results

- Enter the P&L (profit or loss) for each day in the provided field.
- Click **Add Day** to save it.
- You can delete a day by clicking the trash icon to the right of each row.

### 3. Visualization and Analysis

- The chart displays the evolution of your daily P&L.
- The cards summarize: total P&L, best day, required minimum/day, optimal P&L/day.
- The eligibility status updates automatically: green if you meet all rules, red otherwise, with a list of points to correct.

### 4. Exporting Data

- Click **Export CSV** to download your results in spreadsheet format.

### 5. Customization

- Use the **FR/EN** button to change the language.
- Activate dark mode with the moon/sun icon.

## Technologies Used

- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Chart.js](https://www.chartjs.org/) for charts
- [Font Awesome](https://fontawesome.com/) for icons
- Native JavaScript (no server-side dependencies)

---

***Version Française****

# Calculateur de Consistance pour Prop Firms

Cette application web vous aide à vérifier si votre performance de trading respecte les règles de consistance imposées par la plupart des prop firms (entreprises de trading de fonds propres). Elle permet de simuler, suivre et analyser vos résultats quotidiens pour maximiser vos chances d’être éligible à un paiement.

## Fonctionnalités principales

- Saisie des paramètres de stratégie (profit cible, règle de consistance, % min du meilleur jour, profit min/jour, jours de trading min).
- Ajout et gestion des résultats quotidiens (P&L).
- Visualisation graphique de la performance.
- Analyse automatique de l’éligibilité et des points à améliorer.
- Export des résultats au format CSV.
- Interface bilingue (Français/Anglais) et mode sombre.

## Utilisation

### 1. Paramétrage de la stratégie

En haut de la page, renseignez :
- **Profit Cible ($)** : montant total à atteindre.
- **Règle de Consistance (%)** : pourcentage maximal que le meilleur jour peut représenter du total.
- **% Min du Meilleur Jour** : pourcentage minimal du meilleur jour que chaque jour doit atteindre.
- **Profit Min/Jour ($)** : montant minimal de profit par jour.
- **Jours de Trading Min** : nombre minimal de jours à valider.

### 2. Ajout des résultats quotidiens

- Saisissez le P&L (profit ou perte) de chaque jour dans le champ prévu.
- Cliquez sur **Ajouter Jour** pour l’enregistrer.
- Vous pouvez supprimer un jour en cliquant sur l’icône poubelle à droite de chaque ligne.

### 3. Visualisation et analyse

- Le graphique affiche l’évolution de vos P&L quotidiens.
- Les cartes récapitulent : P&L total, meilleur jour, minimum requis/jour, P&L optimal/jour.
- Le statut d’éligibilité s’actualise automatiquement : vert si vous respectez toutes les règles, rouge sinon, avec la liste des points à corriger.

### 4. Export des données

- Cliquez sur **Exporter CSV** pour télécharger vos résultats au format tableur.

### 5. Personnalisation

- Utilisez le bouton **FR/EN** pour changer la langue.
- Activez le mode sombre avec l’icône lune/soleil.

## Technologies utilisées

- [Tailwind CSS](https://tailwindcss.com/) pour le style
- [Chart.js](https://www.chartjs.org/) pour les graphiques
- [Font Awesome](https://fontawesome.com/) pour les icônes
- JavaScript natif (aucune dépendance côté serveur)

---
