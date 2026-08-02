# Specularé

**Simulateur de business plan, financement et valorisation pour PME.**

Application web autonome (HTML / CSS / JavaScript, sans framework) qui construit un
business plan sur 3 à 10 ans et met à l'épreuve des décisions stratégiques, avec un
modèle financier intégré à trois états articulés (compte de résultat, bilan, trésorerie).

## Fonctionnalités

- **Moteur année par année** : compte de résultat, bilan et flux de trésorerie articulés,
  bilan Actif − Passif équilibré par construction.
- **Décisions instanciables** : recrutement, élargissement de gamme (nouvelle référence
  datée), ouverture de site, ouverture de capital, rachat de parts, cession d'activité —
  chacune renommable et duplicable (plusieurs occurrences dans la même prévision).
- **Financement** : portefeuille d'emprunts en annuités constantes (solveur PMT/durée),
  tableau d'amortissement, report déficitaire.
- **Analyse par référence produit** : chiffre d'affaires, mix, marge et taux de marge par
  référence, avec paramètres par année.
- **Valorisation DCF** : flux de trésorerie disponibles actualisés au WACC, valeur terminale
  (Gordon et multiple de sortie), pont valeur d'entreprise → capitaux propres, sensibilité.
- **Conseiller CFO** : moteur de règles qui transforme les indicateurs en constats chiffrés
  et en leviers d'action (trésorerie, endettement, rentabilité vs coût du capital…).
- **Scénarios** nommés et comparables, **export CSV et PDF**, persistance locale.

## Utilisation

Ouvrir `index.html` dans un navigateur — aucune installation, aucun serveur requis.

## Pile technique

JavaScript « vanilla » (aucun framework), [Chart.js](https://www.chartjs.org/) pour les
graphiques. Séparation structure (`index.html`) / style (`styles.css`) / logique (`app.js`).

---

Projet d'apprentissage à la croisée de la finance d'entreprise et du développement web.
