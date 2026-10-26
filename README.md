# Frais judiciaires et dépens – id est avocats

*English version below.*

Outil en ligne d’estimation des frais judiciaires, de l’avance de frais et des dépens, développé par id est avocats Sàrl. Interface en français et en anglais.

> **Aide au calcul uniquement.** Les tarifs laissent une marge d’appréciation au tribunal ; le résultat est une estimation que l’utilisateur doit vérifier. Voir [AVERTISSEMENT.md](AVERTISSEMENT.md).

Version 1.8 (beta), octobre 2026. Historique : [CHANGELOG.md](CHANGELOG.md).

## Ce que fait l’outil

L’outil estime les frais judiciaires, l’avance exigible, les dépens à verser à la partie adverse en cas d’échec et ceux qui seraient obtenus en cas de succès. Il présente le résultat en deux cadres successifs, l’exposition en cas d’échec puis la situation en cas de succès, avec une valeur centrale, une fourchette et la base légale de chaque montant, ainsi qu’un résumé prêt à copier. En option, il tient compte des honoraires estimés de l’avocat de la partie et de sa position de demandeur ou de défendeur, y compris en cas de demande reconventionnelle : le bilan comprend alors le montant des demandes, en supposant une issue identique sur chacune d’elles.

- **Procédure civile, Vaud et Genève** : conciliation ; en première instance, procédures ordinaire, simplifiée et sommaire, mesures provisionnelles et superprovisionnelles, mémoire préventif, procédure sommaire de poursuite, exécution et incidents (récusation, intervention, sûretés, suspension, décisions incidentes, ordonnances, restitution, irrecevabilité faute d’avance).
- **Autorité compétente (Vaud)** : en procédure sommaire, pour les mesures provisionnelles et superprovisionnelles, le mémoire préventif et les incidents, l’émolument dépend de l’autorité (juge de paix, président ou tribunal d’arrondissement, Tribunal des baux, Chambre patrimoniale cantonale, Cour civile du Tribunal cantonal).
- **Voies de droit cantonales** : appel et recours contre une décision finale, sommaire, provisionnelle ou incidente, ou contre une ordonnance ; recours pour retard injustifié ; mesures provisionnelles en deuxième instance ; révision, interprétation et rectification.
- **Arbitrage** : nomination et récusation d’arbitres, concours du juge d’appui, recours devant le tribunal cantonal, dépôt d’une sentence.
- **Tribunal fédéral** : recours en matière civile, avec trois scénarios (jugement au fond, irrecevabilité après examen, irrecevabilité manifeste selon l’art. 108 LTF).
- **Marchés publics** : recours devant la Cour de droit administratif et public (Vaud), la Chambre administrative (Genève), le Tribunal administratif fédéral et le Tribunal fédéral.

Une option permet d’ajouter à l’étape choisie les autres étapes de la procédure (conciliation, incidents, première instance, deuxième instance, Tribunal fédéral) pour obtenir le coût d’une procédure menée jusqu’au bout, étape par étape et au total.

L’outil tient compte de la nature de l’affaire (pécuniaire ou non), de la matière (travail, bail, consommation, assurances complémentaires, autres litiges exemptés), de l’issue de la procédure (transaction, retrait, irrecevabilité, renonciation aux débats, décision non motivée), de la demande reconventionnelle, des parties supplémentaires, de l’élection de for, des frais de preuves, de la représentation de la partie adverse et de la TVA sur les dépens.

L’estimation centrale correspond à ce que les tribunaux décident le plus souvent pour une cause d’ampleur ordinaire ; la méthode est expliquée dans l’outil et vérifiée sur la jurisprudence dans [VERIFICATION.md](VERIFICATION.md). La correspondance entre les articles des tarifs et l’outil figure dans [CORRESPONDANCE.md](CORRESPONDANCE.md).

## Ce que l’outil ne couvre pas

Le droit de la famille, la protection de l’adulte et de l’enfant, les procédures spéciales et non contentieuses (successions, expropriation, mise à ban, etc.), la modération des notes d’honoraires et les émoluments de chancellerie ne sont pas couverts. Les autres cantons ne le sont pas non plus.

## Utilisation

1. Choisir le domaine (procédure civile ou marchés publics), le canton, la nature de l’affaire, le stade de la procédure, le type de procédure et la matière ; à Vaud, l’autorité compétente lorsque l’outil la demande.
2. Indiquer la valeur litigieuse (sauf pour une affaire non pécuniaire) et, le cas échéant, la demande reconventionnelle.
3. Compléter les options utiles : issue de la procédure, ampleur de la cause, position de la partie et honoraires de son avocat, représentation de la partie adverse, parties supplémentaires, élection de for, frais de preuves, heures d’avocat (Vaud), domicile à l’étranger de la partie adverse ou de la partie représentée.
4. Lire l’exposition en cas d’échec, les dépens en cas de succès, le détail par poste et les notes, puis copier le résumé.

La langue se choisit en haut de la page (FR / EN) ; l’adresse `?lang=en` ouvre directement la version anglaise. L’affichage peut être réglé en mode clair, sombre ou automatique.

## Protection des données

id est avocats ne collecte aucune donnée dans le cadre de l’utilisation de l’outil : les calculs sont effectués dans le navigateur et les montants saisis ne sont pas conservés. Seuls le mode d’affichage et la langue sont mémorisés dans le stockage local du navigateur (clés `idest-frais:theme` et `idest-frais:lang`). L’outil est hébergé sur GitHub, qui peut collecter certaines informations, notamment au moyen de cookies, conformément à sa propre déclaration relative à la protection des données.

## Sources et tests

- Bases légales, jurisprudence et choix de calcul : [SOURCES.md](SOURCES.md).
- Correspondance article par article : [CORRESPONDANCE.md](CORRESPONDANCE.md).
- Cas de référence : [CAS-DE-TEST.md](CAS-DE-TEST.md).
- Vérification des estimations sur des arrêts vaudois et genevois : [VERIFICATION.md](VERIFICATION.md).

## Licence

© 2026 id est avocats Sàrl.

Le code est distribué sous licence GNU Affero General Public License, version 3 ou toute version ultérieure (AGPL-3.0-or-later). Voir [LICENSE](LICENSE).

Les tableaux et textes juridiques (barèmes, notes, principes, documentation) sont en outre mis à disposition sous licence [Creative Commons Attribution – Pas d’utilisation commerciale 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.fr). Attribution : « id est avocats Sàrl, Frais judiciaires et dépens ».

---

# Court costs and party costs – id est avocats (English)

Online tool estimating court fees, the advance on costs and party costs (dépens) under Swiss law, developed by id est avocats Sàrl. Interface in French and English.

> **Calculation aid only.** The tariffs leave the court a margin of discretion; the result is an estimate that users must check. See the [disclaimer](AVERTISSEMENT.md#disclaimer-english).

## What the tool does

The tool estimates court fees, the advance on costs, the opposing party’s costs payable if the case is lost and the party costs that would be obtained if it is won. The result is shown in two boxes (exposure if lost, position if won); optionally, it takes into account the estimated fees of the party’s own lawyer and whether the party is claimant or defendant. It shows a central value, a range and the legal basis of each amount, together with a summary ready to copy.

- **Civil proceedings in Vaud and Geneva**: conciliation; at first instance, ordinary, simplified and summary procedures, interim and ex parte measures, protective briefs, summary debt enforcement proceedings, enforcement and incidental matters.
- **Competent authority (Vaud)**: in summary proceedings, interim and ex parte measures, protective briefs and incidental matters, the fee depends on the authority.
- **Cantonal remedies**: appeal and objection against final, summary, interim or incidental decisions and procedural orders; unjustified delay; interim measures at second instance; review, interpretation and rectification.
- **Arbitration**: appointment and challenge of arbitrators, assistance by the supporting judge, challenge before the cantonal court, deposit of an award.
- **Federal Supreme Court**: appeal in civil matters, with three scenarios.
- **Public procurement**: appeals in Vaud, Geneva, before the Federal Administrative Court and the Federal Supreme Court.
- **Whole proceedings**: an option adds the other stages (conciliation, incidental matters, first instance, second instance, Federal Supreme Court) to show the cost of proceedings pursued to the end.

Family law, child and adult protection, special and non-contentious proceedings and other cantons are not covered. Court submissions must be filed in the official language of the court; the English texts are for reference only.

## Data protection

id est avocats does not collect any data through the use of the tool: calculations are performed in the browser and the amounts entered are not stored. Only the display mode and language are stored in the browser’s local storage. The tool is hosted on GitHub, which may collect certain information, including by means of cookies, in accordance with its own privacy statement.

## Licence

© 2026 id est avocats Sàrl. Code licensed under the GNU AGPL 3.0 or any later version (see [LICENSE](LICENSE)); legal tables and texts also available under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Attribution: “id est avocats Sàrl, Court costs and party costs”.
