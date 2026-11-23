# L'inflation en France, 2000-2025 : qui a fait monter les prix ?

Rapport d'analyse en Power BI, construit à partir des données de l'Insee.

![Qui a fait monter les prix](analyse-inflation-france-insee/inflation.png)


**Question posée :** entre 2021 et 2025, quels secteurs ont tiré l'inflation, année après année, et lesquels sont des chocs passagers ou des hausses régulières ?

## Ce que montre l'analyse

- **Le moteur de l'inflation change chaque année.**
  - 2021 : l'**énergie** apporte environ 1,4 point sur 2,8 % d'inflation (la moitié), alors qu'elle pèse 7,5 % du budget des ménages.
  - 2022 : l'**alimentation** est le premier contributeur (environ 2,0 points sur 5,8 %).
  - 2023 à 2025 : les **services** sont en tête (environ 1,6, 1,2 puis 1,1 point).
- **L'énergie est volatile, les services sont réguliers.** Sur 12 mois, la variation des prix de l'énergie va de −8 % à +33 % (41 points d'écart). Celle des services reste entre +0,6 % et +4,0 % (3,3 points).
- **L'inflation moyenne est retombée à 0,9 % en 2025**, contre 5,2 % au pic de 2022. Mais en août 2026 elle est à 2,4 % sur un an, avec une énergie à +16,7 %.

## Contenu du rapport (6 pages)

1. Accueil
2. Vue d'ensemble : l'inflation de 2000 à 2025 en trois phases
3. Qui a fait monter les prix : contribution de chaque secteur, année par année
4. Choc ou tendance : énergie et services comparés sur 12 mois
5. Au rayon : grande distribution, santé, communication, logement
6. Conclusions : ce qu'on retient, décisions possibles, indicateurs à suivre

Chaque page explique comment lire le graphique et ce qu'il faut en retenir.

## Données et sources

- Insee, « L'essentiel sur… l'inflation » (fichier de données) : indices des prix mensuels par famille de produits depuis 2000, inflation annuelle depuis 1987, grande distribution, santé, communication, logement.
- Insee, indices des prix à la consommation (IPC) de décembre 2021 à décembre 2025 : **poids de chaque famille de produits dans le budget des ménages**, année par année.
- Insee, IPC d'août 2026 : inflation sur un an (2,4 %) et variation de l'énergie (+16,7 %).

## Méthode

**Variation d'un prix** = (valeur finale − valeur de départ) ÷ valeur de départ.

**Contribution d'un secteur à l'inflation** = variation du secteur, de décembre à décembre × poids du secteur cette année-là.

Exemple, services en 2022 : l'indice passe de 90,39 à 92,98, soit +2,9 %. Poids des services en 2022 : 48,06 %. Contribution : 2,9 % × 48,06 % ≈ 1,4 point.

En additionnant les cinq secteurs, on retrouve l'inflation publiée par l'Insee, à 0,1 point près (2,8 / 5,8 / 3,7 / 1,3 / 0,8 % pour 2021 à 2025, contre 2,8 / 5,9 / 3,7 / 1,3 / 0,8 % publiés).


Power BI Desktop (modèle de données, mesures DAX, visuels), Power Query, données Insee. 


