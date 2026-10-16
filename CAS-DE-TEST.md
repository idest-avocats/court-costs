# Cas de test

Cas vérifiés avec l’outil (version 1.3). À refaire après chaque modification. Sauf mention contraire : procédure civile, partie adverse représentée par un avocat et domiciliée en Suisse (TVA incluse), aucune option. Montants en francs ; « centre » désigne la valeur centrale affichée.

Les scripts de test du moteur (129 contrôles) reprennent ces cas et les complètent.

## Vaud

| # | Données | Résultat attendu | Point contrôlé |
|---|---|---|---|
| 1 | Procédure ordinaire, 80’000 | émolument 7’000 ; avance 3’500 ; dépens 3’405 à 17’026 (centre 8’172) | art. 18 TFJC, art. 4 et 19 TDC, TVA |
| 2 | Cas 1, partie adverse domiciliée à l’étranger | dépens 3’150 à 15’750 (centre 7’560) | pas de TVA |
| 3 | Appel, 35’300 | émolument 1’353 | HC/2023/60 (art. 62 TFJC) |
| 4 | Appel, 30’001 | émolument 1’300 | HC/2024/1 |
| 5 | Procédure ordinaire, travail, 44’866 | émolument 3’500 | réduction de moitié (art. 22 al. 9 TFJC) |
| 6 | Procédure ordinaire, 200’000, irrecevabilité avant la première audience | émolument 3’166 | HC/2024/291 (art. 22 al. 3 TFJC) |
| 7 | Procédure ordinaire, travail, 20’000 | émolument 0 ; dépens dus | art. 114 CPC |
| 8 | Appel, travail, 20’000 | émolument 0 | TF 4A_332/2015 |
| 9 | Procédure simplifiée, bail d’habitation, 20’000 | émolument 0 ; dépens 0 à 1’500 (centre 0) | art. 12 LJB, art. 16 TDC |
| 10 | Mesures provisionnelles et superprovisionnelles, 50’000 | émolument 500 à 1’800 ; avance 250 à 900 | art. 28 et 30 TFJC, art. 98 CPC |
| 11 | Appel, 80’000, 10,126 heures | dépens centre 3’908 | CACI du 25 novembre 2025 (3’900) |
| 12 | Non pécuniaire, procédure ordinaire, ampleur moyenne | émolument 3’750 à 300’000 (centre 13’962) ; dépens 681 à 56’753 | art. 21 TFJC, art. 9 TDC |
| 13 | Sûretés, valeur au fond 80’000 | émolument 300 à 1’600 ; dépens centre 1’703 | art. 51 et 28 TFJC |
| 14 | Appel contre une décision incidente, valeur au fond 80’000 | émolument 1’800 | art. 66 et 62 TFJC |
| 15 | Procédure ordinaire, 80’000, avocat stagiaire | dépens 2’554 à 12’769 | art. 21 TDC |
| 16 | Procédure simplifiée, 20’000, agent d’affaires breveté | dépens 1’277 à 4’256 | art. 10 TDC |
| 17 | Assurance complémentaire LAMal, procédure ordinaire | émolument 0 | art. 114 CPC |

## Genève

| # | Données | Résultat attendu | Point contrôlé |
|---|---|---|---|
| 18 | Procédure ordinaire, 80’000 | émolument 2’000 à 8’000 (centre 5’000) ; dépens 9’699 à 11’854 (centre 10’777) | art. 17 et 85 RTFMC, art. 25 et 26 LaCC |
| 19 | Cas 18, partie adverse domiciliée à l’étranger | dépens centre 9’991 | débours de 3 % sans TVA |
| 20 | Procédure ordinaire, 600’000 | émolument centre 30’000 | tarif interne du TPI |
| 21 | Prud’hommes, 60’000 | émolument 0 ; dépens 0 | art. 19 al. 3 et 22 al. 2 LaCC |
| 22 | Contrat de consommation, 60’000 | émolument 0 ; dépens dus | art. 22 al. 5 LaCC |
| 23 | Procédure ordinaire, 80’000, transaction à la première audience | émolument 1’000 à 2’000 ; dépens 3’233 à 11’854 | art. 7 RTFMC, art. 23 al. 2 LaCC |
| 24 | Non pécuniaire, procédure ordinaire, ampleur moyenne | émolument 200 à 50’000 (centre 1’048) ; dépens 667 à 19’998 | art. 18 et 86 RTFMC |
| 25 | Sûretés, valeur au fond 80’000 | émolument 300 à 2’000 ; dépens 2’155 à 7’184 (centre 2’155) | art. 21 et 87 RTFMC |
| 26 | Révision, valeur au fond 80’000 | émolument 500 à 10’000 | art. 43 RTFMC |
| 27 | Dépôt d’une sentence, aucune partie domiciliée en Suisse | émolument 400 à 1’000 | art. 50 RTFMC |
| 28 | Assurance complémentaire LAA, client assuré | émolument 0 ; dépens 0 | art. 22 al. 3 LaCC |

## Tribunal fédéral

| # | Données | Résultat attendu | Point contrôlé |
|---|---|---|---|
| 29 | Recours en matière civile, 80’000 | émolument 1’500 à 5’000 ; dépens 3’000 à 10’000 | tarif et règlement du TF |
| 30 | Cas 29, art. 108 LTF | émolument 200 à 500 ; dépens 0 ; avance inchangée | TF 4A_259/2025 |

## Marchés publics

| # | Données | Résultat attendu | Point contrôlé |
|---|---|---|---|
| 31 | Vaud, marché de 800’000 | émolument 5’000 à 10’000 ; dépens 525 à 10’500 | art. 3 et 11 TFJDA |
| 32 | Genève, marché de 800’000 | émolument au plus 15’000 (centre 1’500) ; indemnité centre 1’500 | art. 2 et 6 RFPA, pratique de la Chambre administrative |
| 33 | TAF, marché de 800’000, 20 heures | émolument 5’000 à 20’000 ; dépens 4’000 à 8’000 | art. 4 et 10 FITAF |
| 34 | Tribunal fédéral, marché de 45,9 millions | dépens centre 22’000 | TF 2C_50/2022 |

## Interface

| # | Contrôle | Résultat attendu |
|---|---|---|
| 35 | Langue EN (`?lang=en`) | mêmes montants ; libellés et notes en anglais |
| 36 | Affaire non pécuniaire | champ de valeur masqué ; résumé « affaire non pécuniaire » |
| 37 | Stade « Sûretés » | libellé « Valeur litigieuse au fond » ; champ « Ampleur de la cause » affiché |
| 38 | Genève, assurance complémentaire | case « Votre client est l’assuré » affichée |

© 2026 id est avocats Sàrl, sous licence [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr).
