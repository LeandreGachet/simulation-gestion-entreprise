# Pilotage d'une entreprise simulée sur cinq périodes

Un jeu d'entreprise : une équipe dirige une société informatique fictive, « Comm'Puters », et décide à chaque période de ses prix, de ses volumes et de ses investissements. Les décisions se prennent avant de connaître le résultat, et chaque période part de l'état laissé par la précédente.

Projet de BUT 1, en équipe.

## Démarche

**Compte de résultat prévisionnel** construit avant chaque prise de décision. Décider sans chiffrer, c'est parier ; le prévisionnel transforme un choix en hypothèse testable.

**Simulateur de marge** développé sous Excel et affiné période après période — cinq versions successives, chacune corrigée de ce que la précédente n'avait pas anticipé. Le modèle apprend des écarts entre prévu et réalisé.

**Suivi sous Power BI** de la trajectoire de l'entreprise sur l'ensemble des périodes.

## Ce que ça produit

Un outil d'aide à la décision et l'expérience de son usage sous contrainte : construire un modèle de marge, s'en servir pour arbitrer, constater l'écart, corriger le modèle. C'est le cycle que suit tout travail de prévision en entreprise — la valeur n'est pas dans la justesse du premier chiffre mais dans la vitesse à laquelle le modèle se corrige.

## Contenu

| | |
|---|---|
| `periodes/*CR previsionnel.xlsx` | les comptes de résultat prévisionnels |
| `periodes/*simulateur marge.xlsx` | le simulateur de marge, versions P2 à P5 |
| `tableau_de_bord.pbix` | le suivi de la trajectoire |

## Co-auteurs

Projet d'équipe. Publié avec l'accord de tous.

---

**Léandre Gachet** — BUT Science des données, IUT de Vannes, Université de Bretagne-Sud
