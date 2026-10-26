# Cas de test

Cas vérifiés avec l’outil (version 1.8). À refaire après chaque modification. Sauf mention contraire : procédure civile, partie adverse représentée par un avocat et domiciliée en Suisse (TVA incluse), aucune option. Montants en francs ; « centre » désigne la valeur centrale affichée.

Les scripts de test du moteur (129 contrôles) reprennent ces cas et les complètent.

## Vaud

| # | Données | Résultat attendu | Point contrôlé |
|---|---|---|---|
| 1 | Procédure ordinaire, 80’000 | émolument 7’000 ; avance 3’500 ; dépens 3’405 à 17’026 (centre 10’215) | art. 18 TFJC, art. 4 et 19 TDC, TVA |
| 2 | Cas 1, partie adverse domiciliée à l’étranger | dépens 3’150 à 15’750 (centre 9’450) | pas de TVA |
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

## Autorité compétente (Vaud) et dépens en cas de succès

| # | Données | Résultat attendu | Point contrôlé |
|---|---|---|---|
| 39 | Mesures provisionnelles, 50’000, autorité selon la valeur | émolument 300 à 1’600 | art. 28 TFJC, président ou tribunal d’arrondissement |
| 40 | Cas 39, Cour civile | émolument 900 à 3’000 | art. 28 TFJC |
| 41 | Cas 40, avec mesures superprovisionnelles | émolument 1’250 à 3’350 | art. 28 et 30 TFJC |
| 42 | Procédure sommaire, 5’000, Chambre patrimoniale cantonale choisie | émolument maximal 3’000 (juge de paix par défaut : 800) | art. 28 TFJC |
| 43 | Mémoire préventif, Cour civile | 350 | art. 30 TFJC |
| 44 | Sûretés, Cour civile | émolument 900 à 3’000 | art. 51 et 28 TFJC |
| 45 | Procédure ordinaire, 80’000, partie représentée domiciliée à l’étranger | dépens en cas de succès 3’150 à 15’750 (sans TVA) ; dépens en cas d’échec inchangés | TVA |
| 46 | Procédure ordinaire, 80’000, partie adverse sans avocat | dépens en cas d’échec 0 ; dépens en cas de succès 3’405 à 17’026 | art. 24 TDC |
| 47 | Genève, prud’hommes, 90’000 | dépens en cas d’échec et de succès 0 | art. 22 al. 2 LaCC |
| 48 | Marchés publics, Genève, autorité seule partie | dépens en cas d’échec 0 ; dépens en cas de succès environ 1’500 | art. 6 RFPA, pratique |

## Ensemble de la procédure

| # | Données | Résultat attendu |
|---|---|---|
| 51 | Vaud, conciliation, 80’000, avec deux incidents de sûretés, première instance ordinaire, appel et Tribunal fédéral (jugement au fond) | frais judiciaires 14’690 ; avances successives 11’190 ; dépens 21’267 ; exposition totale environ 35’957 (23’264 à 66’816) |
| 52 | Vaud, première instance ordinaire, 80’000, avec appel et Tribunal fédéral | exposition totale environ 30’661 ; dépens en cas de succès 17’861 |
| 53 | Cas 52 à Genève | exposition totale environ 35’743 (appel : 4’500 de frais judiciaires et 6’466 de dépens) |
| 54 | Option désactivée | retour à l’étape choisie seule |

## Situation en cas d’échec et de succès

| # | Données | Échec | Succès |
|---|---|---|---|
| 55 | Vaud, procédure ordinaire, 80’000, position non précisée | 17’215 (frais 7’000, dépens 10’215) | 10’215 (dépens à recevoir) |
| 56 | Cas 55, demandeur, honoraires de 12’000 | 29’215 | 78’215 (80’000 + 10’215 − 12’000) ; part non couverte 1’785 |
| 57 | Cas 55, défendeur, honoraires de 12’000 | 109’215 (80’000 + 29’215) | −1’785 (10’215 − 12’000) |
| 58 | Vaud, conciliation avec première instance, appel et Tribunal fédéral, demandeur, honoraires de 40’000 | 71’561 (frais 13’700, dépens 17’861, honoraires 40’000) | 57’861 (80’000 + 17’861 − 40’000) |
| 59 | Vaud, procédure ordinaire, 80’000, demande reconventionnelle de 30’000, honoraires de 12’000, position non précisée | 35’858 (frais 9’500, dépens 14’358, honoraires 12’000) | 2’358 ; note invitant à indiquer la position |
| 60 | Cas 59, demandeur principal (défendeur reconventionnel) | 65’858*, dont 30’000* de demande reconventionnelle | 82’358 (80’000 + 14’358 − 12’000) ; demande reconventionnelle rejetée |
| 61 | Cas 59, défendeur principal (demandeur reconventionnel) | 115’858 (80’000 + 35’858) ; demande reconventionnelle rejetée | 32’358* (30’000* + 14’358 − 12’000) |
| 62 | Conciliation avec première instance ordinaire ajoutée | champ « Demande reconventionnelle » affiché | — |

## Comparaison avec la jurisprudence (recalibrations des versions 1.7 et 1.8)

| # | Données | Résultat attendu | Arrêt |
|---|---|---|---|
| 63 | Vaud, procédure ordinaire, 121’697 | dépens centre 14’358 | CREC du 21 juillet 2026 : 12’000 (dépens légèrement réduits) |
| 64 | Genève, appel, 178’429 | émolument centre 9’000 ; dépens centre 10’096 | ACJC du 5 juin 2024 (C/5443/2021) : 9’000 et 6’000 |
| 65 | Genève, appel, 270’314 | dépens centre 12’239 | ACJC du 20 avril 2021 (C/16647/2016) : 12’200 |
| 66 | Genève, appel, 28’866 | émolument centre 1’800 | ACJC du 6 juin 2023 (C/25602/2019) : 1’800 |
| 67 | Tribunal fédéral, 30’000 | émolument 2’000 ; dépens 2’500 | TF 4A_171/2025 : 2’000 et 2’500 |
| 68 | Tribunal fédéral, 276’144 | émolument 8’000 ; dépens 9’000 | TF 4A_1/2024 : 8’000 et 9’000 |
| 69 | Vaud, appel, 322’900 | dépens centre 7’057 | CACI du 12 février 2026 (PT18.026077) : 11’500 |
| 70 | Vaud, mesures provisionnelles, président du tribunal d’arrondissement | émolument centre 495 | CACI du 14 mai 2024 : 400 |

Le détail de la vérification figure dans [VERIFICATION.md](VERIFICATION.md).

## Interface

| # | Contrôle | Résultat attendu |
|---|---|---|
| 35 | Langue EN (`?lang=en`) | mêmes montants ; libellés et notes en anglais |
| 36 | Affaire non pécuniaire | champ de valeur masqué ; résumé « affaire non pécuniaire » |
| 37 | Stade « Sûretés » | libellé « Valeur litigieuse au fond » ; champ « Ampleur de la cause » affiché |
| 38 | Genève, assurance complémentaire | case « Votre client est l’assuré » affichée |
| 49 | Vaud, procédure ordinaire | champ « Autorité compétente » masqué |
| 50 | Vaud, mesures provisionnelles | champ « Autorité compétente » affiché |

© 2026 id est avocats Sàrl, sous licence [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr).
