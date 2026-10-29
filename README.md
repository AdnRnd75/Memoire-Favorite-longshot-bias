# Efficience informationnelle et biais comportementaux sur les marchés de prédiction

**Une analyse empirique du favorite-longshot bias sur les marchés de paris sportifs**

Mémoire de Master 2 Banque-Finance, École d'Économie de la Sorbonne (Université Paris 1 Panthéon-Sorbonne), 2025-2026.
Auteur : Adrien Renaud. Directeurs : Jérôme Glachant et Richard Houbron.

## Question

Le favorite-longshot bias (les paris sur les outsiders rapportent en moyenne moins que ceux sur les favoris) se vérifie-t-il sur les marchés de paris du football anglais, et son intensité dépend-elle du niveau de la division (Premier League, Championship, League One), que nous prenons comme indicateur de liquidité et d'attention du marché ?

## Données et méthode

- Cotes avant match de Bet365 et résultats, issus de [Football-Data.co.uk](https://www.football-data.co.uk/) (accès libre), saisons 2019/20 à 2023/24 : 7 265 matchs, 21 795 paris.
- Probabilités implicites normalisées, régression du profit d'un pari d'un euro sur la probabilité implicite (erreurs-types groupées par match), calibration, simulations de Monte Carlo, probabilités de Shin, stratégies fictives.

## Principaux résultats

- Les résultats sont compatibles avec un favorite-longshot bias en League One (pente de 0,443 ; intervalle de confiance à 95 % de 0,15 à 0,74 ; p = 0,003), stable selon le bookmaker, le moment où les cotes sont relevées et la méthode de calcul des probabilités.
- Ce biais n'est pas observé en Premier League ni en Championship, mais les tests ne détecteraient pas un biais nettement plus faible.
- La différence entre divisions est de preuve modérée : le test joint des trois pentes est tout juste au seuil (p = 0,052) et les comparaisons deux à deux ne résistent pas à une correction de Holm.

## Contenu du dépôt

- `Efficience_informationnelle_et_biais_comportementaux.pdf` : le mémoire.

Les données ne sont pas incluses : elles sont téléchargeables sur Football-Data.co.uk.

## Citer ce travail

Renaud, A. (2026). *Efficience informationnelle et biais comportementaux sur les marchés de prédiction*. Mémoire de Master 2 Banque-Finance, Université Paris 1 Panthéon-Sorbonne.

© Adrien Renaud, 2026. Merci de citer ce travail en cas de réutilisation.
