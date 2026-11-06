# Fribourg: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Fribourg, Switzerland, which global-law reads at `switzerland/fribourg/acts/`.

The law of the canton of Fribourg (Etat de Fribourg, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-fr/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in French, the canton's first official language in the collection, exactly as the canton publishes it.

## What this repository holds

792 instruments with 1723 versions: the original 591 acts with 1522 consolidated versions, plus 201 instruments with one current consolidated corpus version each. The additional scope includes decrees, decisions, intercantonal agreements and tariffs. RSF 122.91.3 is excluded because four glyphs in the official PDF cannot be decoded reliably. The two image-incomplete acts are identified below.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `10-1-cst/` | Constitution du canton de Fribourg (RSF 10.1) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2025 |
| `10-2/` | Loi relative à la Journée du bilinguisme (RSF 10.2) | 1 | one version (the oldest available), 1 July 2015 |
| `10-3-lsen/` | Loi sur les seniors (RSF 10.3) | 1 | one version (the oldest available), 1 July 2016 |
| `10-4-lpsh/` | Loi sur la personne en situation de handicap (RSF 10.4) | 1 | one version (the oldest available), 1 January 2018 |
| `16-1-lresp/` | Loi sur la responsabilité civile des collectivités publiques et de leurs agents et agentes (RSF 16.1) | 3 | oldest version available, then each consolidated version: 1 July 2015 to 1 June 2026 |
| `17-1-lprd/` | Loi sur la protection des données (RSF 17.1) | 4 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `17-3-lvid/` | Loi sur la vidéosurveillance (RSF 17.3) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 July 2026 |
| `17-5-linf/` | Loi sur l'information et l'accès aux documents (RSF 17.5) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `17-6-larch/` | Loi sur l'archivage et les Archives de l'Etat (RSF 17.6) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2021 |
| `28-1-lalp/` | Loi d'application de la législation fédérale sur la poursuite pour dettes et la faillite (RSF 28.1) | 2 | oldest version available, then each consolidated version: 1 July 2015 to 1 January 2024 |
| `31-1-lacp/` | Loi d'application du code pénal (RSF 31.1) | 5 | oldest version available, then each consolidated version: 1 January 2018 to 1 July 2026 |
| `33-1-lcao/` | Loi sur les amendes d'ordre de droit cantonal et de droit fédéral (RSF 33.1) | 2 | oldest version available, then each consolidated version: 1 January 2022 to 1 July 2026 |
| `44-1-lbpe/` | Loi sur les bourses et les prêts d'études (RSF 44.1) | 2 | oldest version available, then each consolidated version: 1 August 2016 to 19 August 2025 |
| `45-1-lfad/` | Loi sur la formation des adultes (RSF 45.1) | 1 | one version (the oldest available), 1 January 2003 |
| `52-1-lpci/` | Loi sur la protection civile (RSF 52.1) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 July 2025 |
| `52-2-lprotpop/` | Loi sur la protection de la population (RSF 52.2) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 July 2025 |
| `76-1-lex/` | Loi sur l'expropriation (RSF 76.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2023 |
| `87-2/` | Loi encourageant la construction de logements à caractère social (RSF 87.2) | 1 | one version (the oldest available), 1 January 2011 |
| `97-1/` | Loi sur la coopération au développement et l'aide humanitaire internationales (RSF 97.1) | 1 | one version (the oldest available), 1 April 2012 |
| `110-1-lstat/` | Loi sur la statistique cantonale (RSF 110.1) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2025 |
| `112-5/` | Loi déterminant les districts administratifs (RSF 112.5) | 1 | one version (the oldest available), 1 January 2016 |
| `112-7-lfcla/` | Loi sur l'accueil de la commune municipale bernoise de Clavaleyres par le canton de Fribourg et sa fusion avec la commune de Morat (RSF 112.7) | 1 | one version (the oldest available), 1 June 2018 |
| `114-1-1-ldcf/` | Loi sur le droit de cité fribourgeois (RSF 114.1.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2024 |
| `114-21-1-lch/` | Loi sur le contrôle des habitants (RSF 114.21.1) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2022 |
| `114-22-1-lalei/` | Loi d'application de la loi fédérale sur les étrangers (RSF 114.22.1) | 3 | oldest version available, then each consolidated version: 1 July 2015 to 1 January 2022 |
| `114-22-2-lint/` | Loi sur l'intégration des migrants et des migrantes et la prévention du racisme (RSF 114.22.2) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 July 2019 |
| `115-1-ledp/` | Loi sur l'exercice des droits politiques (RSF 115.1) | 8 | oldest version available, then each consolidated version: 1 July 2016 to 1 July 2026 |
| `115-5-lfipol/` | Loi sur le financement de la politique (RSF 115.5) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 June 2023 |
| `115-6-lpfc/` | Loi sur la participation de l'Etat aux frais de campagne électorale (RSF 115.6) | 2 | oldest version available, then each consolidated version: 1 July 2015 to 1 June 2023 |
| `116-1/` | Loi sur le droit de pétition (RSF 116.1) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2023 |
| `121-1-lgc/` | Loi sur le Grand Conseil (RSF 121.1) | 4 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2023 |
| `122-0-1-locea/` | Loi sur l'organisation du Conseil d'Etat et de l'administration (RSF 122.0.1) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `122-0-4/` | Loi portant adaptation de la législation cantonale à la LOCEA (RSF 122.0.4) | 1 | one version (the oldest available), 1 January 2003 |
| `122-1-3-ltce/` | Loi relative au traitement et à la prévoyance professionnelle des conseillers d'Etat, des préfets et des juges cantonaux (RSF 122.1.3) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2022 |
| `122-3-1/` | Loi sur les préfets (RSF 122.3.1) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2022 |
| `122-8-2/` | Loi réglant la durée des fonctions publiques accessoires (RSF 122.8.2) | 1 | one version (the oldest available), 1 January 2016 |
| `122-23-7-locn/` | Loi sur l'Office de la circulation et de la navigation (RSF 122.23.7) | 1 | one version (the oldest available), 1 July 2017 |
| `122-26-3/` | Loi instituant un Bureau et une Commission de l'égalité hommes-femmes et de la famille (RSF 122.26.3) | 1 | one version (the oldest available), 1 February 2004 |
| `122-70-1-lpers/` | Loi sur le personnel de l'Etat (RSF 122.70.1) | 5 | oldest version available, then each consolidated version: 1 January 2018 to 1 February 2023 |
| `122-73-1-lcp/` | Loi sur la Caisse de prévoyance du personnel de l'Etat (RSF 122.73.1) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `122-91-1-lcmp/` | Loi sur les marchés publics (RSF 122.91.1) | 2 | oldest version available, then each consolidated version: 1 July 2016 to 1 January 2023 |
| `124-1-lpal/` | Loi sur la publication des actes législatifs et de la Feuille officielle (RSF 124.1) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2024 |
| `126-2/` | Loi concernant le tarif des émoluments de chancellerie (RSF 126.2) | 1 | one version (the oldest available), 12 March 1924 |
| `126-3/` | Loi instituant une délégation de pouvoirs au Conseil d'Etat pour la fixation des taxes et émoluments (RSF 126.3) | 1 | one version (the oldest available), 28 April 1953 |
| `129-1-2/` | Loi modifiant la formule du serment en application de l'article 49 al. 2 de la Constitution fédérale du 29 mai 1874 (RSF 129.1.2) | 1 | one version (the oldest available), 15 December 1875 |
| `130-1-lj/` | Loi sur la justice (RSF 130.1) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2024 |
| `130-5-lalavi/` | Loi d'application de la législation fédérale sur l'aide aux victimes d'infractions (RSF 130.5) | 1 | one version (the oldest available), 1 January 2011 |
| `137-1-lav/` | Loi sur la profession d'avocat (RSF 137.1) | 1 | one version (the oldest available), 1 July 2015 |
| `140-1-lco/` | Loi sur les communes (RSF 140.1) | 7 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2024 |
| `140-2-lagg/` | Loi sur les agglomérations (RSF 140.2) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2023 |
| `140-6-lfco/` | Loi sur les finances communales (RSF 140.6) | 1 | one version (the oldest available), 1 January 2021 |
| `141-1-1-lefc/` | Loi relative à l'encouragement aux fusions de communes (RSF 141.1.1) | 2 | oldest version available, then each consolidated version: 1 July 2016 to 1 July 2020 |
| `142-1-lpfi/` | Loi sur la péréquation financière intercommunale (RSF 142.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2019 |
| `181-1-lmed/` | Loi sur la médiation administrative (RSF 181.1) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `184-1-lcyb/` | Loi sur la cyberadministration (RSF 184.1) | 6 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2027 |
| `190-1-lrcce/` | Loi concernant les rapports entre les communautés confessionnelles et l'Etat (RSF 190.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2024 |
| `193-1/` | Loi portant reconnaissance de la Communauté israélite du canton de Fribourg (RSF 193.1) | 1 | one version (the oldest available), 1 January 2008 |
| `210-1-lacc/` | Loi d'application du code civil suisse (RSF 210.1) | 5 | oldest version available, then each consolidated version: 1 July 2015 to 1 March 2024 |
| `211-2-1-lec/` | Loi sur l'état civil (RSF 211.2.1) | 1 | one version (the oldest available), 1 January 2018 |
| `212-4-1-larace/` | Loi sur l'aide au recouvrement et l'avance de contributions d'entretien (RSF 212.4.1) | 1 | one version (the oldest available), 1 January 2022 |
| `212-5-1-lpea/` | Loi concernant la protection de l'enfant et de l'adulte (RSF 212.5.1) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 July 2020 |
| `214-2-1-laldfr/` | Loi d'application de la loi fédérale sur le droit foncier rural (RSF 214.2.1) | 3 | oldest version available, then each consolidated version: 1 March 2007 to 1 September 2023 |
| `214-5-1-lrf/` | Loi sur le registre foncier (RSF 214.5.1) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 December 2025 |
| `214-7-1-lcgeo/` | Loi sur la géoinformation (RSF 214.7.1) | 2 | oldest version available, then each consolidated version: 1 April 2013 to 1 March 2024 |
| `214-12-1-lalfaie/` | Loi d'application de la loi fédérale sur l'acquisition d'immeubles par des personnes à l'étranger (RSF 214.12.1) | 1 | one version (the oldest available), 1 January 2011 |
| `220-3-lsrc/` | Loi sur le Service du registre du commerce (RSF 220.3) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 June 2024 |
| `222-3-1-lablf/` | Loi d'application relative au bail à loyer et au bail à ferme non agricole (RSF 222.3.1) | 1 | one version (the oldest available), 1 July 2015 |
| `222-4-3-lalbfa/` | Loi d'application de la loi fédérale sur le bail à ferme agricole (RSF 222.4.3) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2022 |
| `261-1-ln/` | Loi sur le notariat (RSF 261.1) | 2 | oldest version available, then each consolidated version: 1 July 2016 to 1 September 2021 |
| `262-1/` | Loi sur la légalisation des signatures (RSF 262.1) | 2 | oldest version available, then each consolidated version: 1 January 2006 to 1 March 2024 |
| `340-1-lepm/` | Loi sur l'exécution des peines et des mesures (RSF 340.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2022 |
| `411-0-1-loi-scolaire-ls/` | Loi sur la scolarité obligatoire (RSF 411.0.1) | 11 | oldest version available, then each consolidated version: 1 August 2016 to 1 January 2027 |
| `411-4-1/` | Loi sur les écoles libres publiques (RSF 411.4.1) | 1 | one version (the oldest available), 1 July 2006 |
| `411-5-1-lps/` | Loi sur la pédagogie spécialisée (RSF 411.5.1) | 4 | oldest version available, then each consolidated version: 1 January 2003 to 1 September 2022 |
| `412-0-1-less/` | Loi sur l'enseignement secondaire supérieur (RSF 412.0.1) | 6 | oldest version available, then each consolidated version: 1 August 2016 to 15 August 2025 |
| `413-1-1/` | Loi sur l'orientation professionnelle, universitaire et de carrière (RSF 413.1.1) | 1 | one version (the oldest available), 1 January 2008 |
| `413-4-1-locms/` | Loi sur l'Office cantonal du matériel scolaire (RSF 413.4.1) | 1 | one version (the oldest available), 1 July 2017 |
| `413-5-1-lmds/` | Loi sur la médecine dentaire scolaire (RSF 413.5.1) | 1 | one version (the oldest available), 1 August 2016 |
| `414-4/` | Loi relative aux subventions pour les constructions d'écoles enfantines, primaires et du cycle d'orientation (RSF 414.4) | 2 | oldest version available, then each consolidated version: 1 September 2011 to 1 January 2023 |
| `420-1-lfp/` | Loi sur la formation professionnelle (RSF 420.1) | 2 | oldest version available, then each consolidated version: 1 August 2016 to 1 January 2020 |
| `431-0-1-luni/` | Loi sur l'Université (RSF 431.0.1) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 August 2025 |
| `432-12-1-lhes-so-fr/` | Loi sur la Haute Ecole spécialisée de Suisse occidentale//Fribourg (RSF 432.12.1) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2022 |
| `460-1-lsport/` | Loi sur le sport (RSF 460.1) | 1 | one version (the oldest available), 1 July 2015 |
| `480-1-leac/` | Loi sur l'encouragement des activités culturelles (RSF 480.1) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 October 2026 |
| `481-0-1-lice/` | Loi sur les institutions culturelles de l'Etat (RSF 481.0.1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 October 2026 |
| `482-1-lpbc/` | Loi sur la protection des biens culturels (RSF 482.1) | 1 | one version (the oldest available), 1 July 2015 |
| `514-2/` | Loi sur la subvention des exercices de tir (RSF 514.2) | 1 | one version (the oldest available), 16 January 1914 |
| `551-1-lpol/` | Loi sur la Police cantonale (RSF 551.1) | 3 | oldest version available, then each consolidated version: 1 April 2014 to 1 January 2023 |
| `610-1-lfe/` | Loi sur les finances de l'Etat (RSF 610.1) | 3 | oldest version available, then each consolidated version: 1 August 2017 to 1 January 2024 |
| `613-1/` | Loi adaptant certaines dispositions de la législation cantonale à la réforme de la péréquation financière et de la répartition des tâches entre la Confédération et les cantons (RSF 613.1) | 1 | one version (the oldest available), 1 January 2008 |
| `616-1-lsub/` | Loi sur les subventions (RSF 616.1) | 1 | one version (the oldest available), 1 January 2014 |
| `631-1-licd/` | Loi sur les impôts cantonaux directs (RSF 631.1) | 8 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `631-2/` | Loi sur la mise en œuvre de la réforme fiscale (RSF 631.2) | 1 | one version (the oldest available), 1 January 2020 |
| `631-12/` | Loi fixant le coefficient annuel des impôts cantonaux directs de la période fiscale 2026 (RSF 631.12) | 8 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `632-1-lico/` | Loi sur les impôts communaux (RSF 632.1) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2023 |
| `635-1-1-ldmg/` | Loi sur les droits de mutation et les droits sur les gages immobiliers (RSF 635.1.1) | 6 | oldest version available, then each consolidated version: 1 January 2016 to 1 March 2024 |
| `635-2-1-lisd/` | Loi sur l'impôt sur les successions et les donations (RSF 635.2.1) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2022 |
| `635-4-1-livar/` | Loi sur l'imposition des véhicules automobiles et des remorques (RSF 635.4.1) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `635-4-2-libat/` | Loi sur l'imposition des bateaux (RSF 635.4.2) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 April 2024 |
| `635-6-1-liaa/` | Loi sur l'impôt destiné à compenser la diminution de l'aire agricole (RSF 635.6.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 October 2023 |
| `710-1-latec/` | Loi sur l'aménagement du territoire et les constructions (RSF 710.1) | 7 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2027 |
| `721-0-1-lpnat/` | Loi sur la protection de la nature et du paysage (RSF 721.0.1) | 3 | oldest version available, then each consolidated version: 1 July 2015 to 1 October 2023 |
| `725-1-lcpa/` | Loi sur la protection des animaux (RSF 725.1) | 1 | one version (the oldest available), 1 July 2012 |
| `725-3-ldch/` | Loi sur la détention des chiens (RSF 725.3) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `731-3-1-ldis/` | Loi sur la défense incendie et les secours (RSF 731.3.1) | 1 | one version (the oldest available), 1 July 2021 |
| `732-1-1-lecab/` | Loi sur l'assurance immobilière, la prévention et les secours en matière de feu et d'éléments naturels (RSF 732.1.1) | 4 | oldest version available, then each consolidated version: 1 July 2018 to 1 July 2025 |
| `732-2-1/` | Loi sur l'assurance obligatoire du mobilier contre l'incendie (RSF 732.2.1) | 1 | one version (the oldest available), 1 January 2011 |
| `750-1-ldp/` | Loi sur le domaine public (RSF 750.1) | 2 | oldest version available, then each consolidated version: 1 July 2012 to 1 January 2023 |
| `770-1-len/` | Loi sur l'énergie (RSF 770.1) | 4 | oldest version available, then each consolidated version: 1 August 2013 to 1 April 2026 |
| `770-4/` | Loi instituant un Fonds cantonal de l'énergie (RSF 770.4) | 1 | one version (the oldest available), 1 July 2011 |
| `772-0-2-laee/` | Loi sur l'approvisionnement en énergie électrique (RSF 772.0.2) | 1 | one version (the oldest available), 1 November 2003 |
| `772-1-1/` | Loi sur le statut des Entreprises électriques fribourgeoises et de leur Caisse de pensions (RSF 772.1.1) | 1 | one version (the oldest available), 1 January 2002 |
| `780-1-lmob/` | Loi sur la mobilité (RSF 780.1) | 4 | oldest version available, then each consolidated version: 1 January 2016 to 1 March 2026 |
| `781-1-lalcr/` | Loi d'application de la législation fédérale sur la circulation routière (RSF 781.1) | 5 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `785-1-lalni/` | Loi d'application de la législation fédérale sur la navigation intérieure (RSF 785.1) | 3 | oldest version available, then each consolidated version: 1 May 2016 to 1 January 2023 |
| `810-2-lgd/` | Loi sur la gestion des déchets (RSF 810.2) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2022 |
| `810-3-lsites/` | Loi sur les sites pollués (RSF 810.3) | 1 | one version (the oldest available), 1 January 2013 |
| `812-1-lceaux/` | Loi sur les eaux (RSF 812.1) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2026 |
| `815-1-lclim/` | Loi sur le climat (RSF 815.1) | 1 | one version (the oldest available), 1 October 2023 |
| `820-2-lpms/` | Loi sur les prestations médico-sociales (RSF 820.2) | 1 | one version (the oldest available), 1 January 2018 |
| `820-6/` | Loi d'application de la loi fédérale sur le nouveau régime de financement des soins (RSF 820.6) | 1 | one version (the oldest available), 1 January 2018 |
| `821-0-1-lsan/` | Loi sur la santé (RSF 821.0.1) | 6 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `821-11-1-lefs/` | Loi sur l'encouragement de la formation dans le domaine des soins (RSF 821.11.1) | 1 | one version (the oldest available), 1 January 2026 |
| `821-30-1-lsal/` | Loi sur la sécurité alimentaire (RSF 821.30.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2022 |
| `821-32-1-lep/` | Loi sur l'eau potable (RSF 821.32.1) | 2 | oldest version available, then each consolidated version: 1 May 2014 to 1 March 2020 |
| `821-40-11/` | Loi approuvant les mesures urgentes du Conseil d'Etat visant à surmonter l'épidémie de COVID-19 (RSF 821.40.11) | 2 | oldest version available, then each consolidated version: 6 November 2020 to 1 April 2021 |
| `821-44-1/` | Loi sur la lutte contre l'alcoolisme (RSF 821.44.1) | 1 | one version (the oldest available), 1 July 2015 |
| `821-44-4/` | Loi instituant un fonds pour la lutte contre les toxicomanies (RSF 821.44.4) | 1 | one version (the oldest available), 1 July 2015 |
| `822-0-1-lhfr/` | Loi sur l'hôpital fribourgeois (RSF 822.0.1) | 3 | oldest version available, then each consolidated version: 1 July 2015 to 1 January 2025 |
| `822-0-3-lfih/` | Loi concernant le financement des hôpitaux et des maisons de naissance (RSF 822.0.3) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2023 |
| `822-2-1-lsm/` | Loi sur l'organisation des soins en santé mentale (RSF 822.2.1) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2019 |
| `830-1-lif/` | Loi sur l'indemnité forfaitaire (RSF 830.1) | 1 | one version (the oldest available), 1 January 2018 |
| `831-0-1-lasoc/` | Loi sur l'aide sociale (RSF 831.0.1) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `834-1-2-lifap/` | Loi sur les institutions spécialisées et les familles d'accueil professionnelles (RSF 834.1.2) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2019 |
| `834-1-4/` | Loi abrogeant la loi concernant la constitution de la fondation de droit public cantonal «Bellevue» pour l'accueil de personnes handicapées psychiques et mentales et constituant un droit de superficie en faveur de la fondation «HorizonSud» (RSF 834.1.4) | 1 | one version (the oldest available), 1 January 2007 |
| `835-1-lste/` | Loi sur les structures d'accueil extrafamilial de jour (RSF 835.1) | 3 | oldest version available, then each consolidated version: 1 July 2018 to 1 July 2022 |
| `835-5-lej/` | Loi sur l'enfance et la jeunesse (RSF 835.5) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2020 |
| `836-1-lafc/` | Loi sur les allocations familiales (RSF 836.1) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `836-3-lamat/` | Loi sur les allocations de maternité (RSF 836.3) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `836-4-lpcfam/` | Loi sur les prestations complémentaires pour les familles (RSF 836.4) | 1 | one version (the oldest available), 1 January 2026 |
| `841-1-1-la-avs-ai/` | Loi d'application de la loi fédérale sur l'assurance-vieillesse et survivants et de la loi fédérale sur l'assurance-invalidité (RSF 841.1.1) | 1 | one version (the oldest available), 1 January 2016 |
| `841-3-1/` | Loi sur les prestations complémentaires à l'assurance-vieillesse, survivants et invalidité (RSF 841.3.1) | 4 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2022 |
| `842-1-1-lalamal/` | Loi d'application de la loi fédérale sur l'assurance-maladie (RSF 842.1.1) | 1 | one version (the oldest available), 1 January 2017 |
| `842-1-4/` | Loi relative à la dissolution de la Mutualité scolaire du canton de Fribourg (RSF 842.1.4) | 1 | one version (the oldest available), 1 January 1994 |
| `842-2-1-laa/` | Loi d'application de la loi fédérale du 20 mars 1981 sur l'assurance-accidents (RSF 842.2.1) | 1 | one version (the oldest available), 1 January 2008 |
| `842-2-4/` | Loi abrogeant la loi créant une assurance scolaire contre les accidents (RSF 842.2.4) | 2 | oldest version available, then each consolidated version: 1 September 2006 to 1 September 2019 |
| `862-2-locct/` | Loi instituant un Office de conciliation en matière de conflits collectifs de travail (RSF 862.2) | 1 | one version (the oldest available), 1 February 1989 |
| `866-1-1-lemt/` | Loi sur l'emploi et le marché du travail (RSF 866.1.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2020 |
| `866-3-3/` | Loi sur la constitution de réserves de crise bénéficiant d'allégements fiscaux (RSF 866.3.3) | 1 | one version (the oldest available), 1 January 2003 |
| `900-1-lpec/` | Loi sur la promotion économique (RSF 900.1) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2020 |
| `900-2-lpfa/` | Loi sur la politique foncière active (RSF 900.2) | 2 | oldest version available, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `910-1-lagri/` | Loi sur l'agriculture (RSF 910.1) | 2 | oldest version available, then each consolidated version: 1 April 2018 to 1 January 2022 |
| `911-10-1-lgn/` | Loi sur Grangeneuve (RSF 911.10.1) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2022 |
| `914-10-6/` | Loi d'application de la législation fédérale sur l'élimination des déchets animaux (RSF 914.10.6) | 1 | one version (the oldest available), 1 January 2013 |
| `914-20-1-laar/` | Loi sur l'assurance des animaux de rente (RSF 914.20.1) | 1 | one version (the oldest available), 1 January 2014 |
| `917-1-laf/` | Loi sur les améliorations foncières (RSF 917.1) | 6 | oldest version available, then each consolidated version: 1 January 2018 to 1 December 2025 |
| `921-1-lfcn/` | Loi sur les forêts et la protection contre les catastrophes naturelles (RSF 921.1) | 4 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2023 |
| `922-1-lcha/` | Loi sur la chasse et la protection des mammifères, des oiseaux sauvages et de leurs biotopes (RSF 922.1) | 3 | oldest version available, then each consolidated version: 1 July 2015 to 1 January 2022 |
| `923-1-lpeche/` | Loi sur la pêche (RSF 923.1) | 4 | oldest version available, then each consolidated version: 1 August 2017 to 1 January 2022 |
| `931-1/` | Loi sur l'exploitation des mines (RSF 931.1) | 2 | oldest version available, then each consolidated version: 1 January 1992 to 1 January 2023 |
| `931-2/` | Loi sur la recherche et l'exploitation des hydrocarbures (RSF 931.2) | 1 | one version (the oldest available), 1 January 2008 |
| `940-1-lcom/` | Loi sur l'exercice du commerce (RSF 940.1) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2021 |
| `940-2/` | Loi sur l'exercice de la prostitution (RSF 940.2) | 1 | one version (the oldest available), 1 July 2015 |
| `941-2-lrec/` | Loi sur les réclames (RSF 941.2) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `951-1-lt/` | Loi sur le tourisme (RSF 951.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2022 |
| `952-1-lepu/` | Loi sur les établissements publics (RSF 952.1) | 2 | oldest version available, then each consolidated version: 1 July 2017 to 1 July 2020 |
| `954-1/` | Loi sur l'accès des jeunes aux médias (RSF 954.1) | 1 | one version (the oldest available), 1 January 2024 |
| `958-1-lajar/` | Loi sur les jeux d'argent (RSF 958.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2021 |
| `961-1-lbcf/` | Loi sur la Banque cantonale de Fribourg (RSF 961.1) | 1 | one version (the oldest available), 3 August 2016 |
| `10-22/` | Ordonnance sur le soutien aux initiatives en faveur du bilinguisme (RSF 10.22) | 3 | oldest version available, then each consolidated version: 1 July 2018 to 1 December 2024 |
| `10-42/` | Ordonnance relative au Fonds en faveur de l'inclusion des personnes en situation de handicap dans le monde du travail (RSF 10.42) | 1 | one version (the oldest available), 17 August 2021 |
| `17-15-rsd/` | Règlement sur la sécurité des données personnelles (RSF 17.15) | 3 | oldest version available, then each consolidated version: 3 November 2015 to 1 January 2022 |
| `17-16-osi/` | Ordonnance sur la sécurité de l'information (RSF 17.16) | 2 | oldest version available, then each consolidated version: 1 August 2023 to 21 April 2026 |
| `17-31-ovid/` | Ordonnance sur la vidéosurveillance (RSF 17.31) | 1 | one version (the oldest available), 1 January 2012 |
| `17-53-rtcinf/` | Règlement du Tribunal cantonal sur l'information du public en matière judiciaire (RSF 17.53) | 3 | oldest version available, then each consolidated version: 1 March 2018 to 1 January 2026 |
| `17-54-oad/` | Ordonnance sur l'accès aux documents (RSF 17.54) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 July 2019 |
| `17-61-rarch/` | Règlement sur l'archivage (RSF 17.61) | 2 | oldest version available, then each consolidated version: 1 July 2019 to 1 January 2026 |
| `33-11-ocao/` | Ordonnance sur les amendes d'ordre de droit cantonal et de droit fédéral (RSF 33.11) | 7 | oldest version available, then each consolidated version: 1 January 2022 to 1 July 2027 |
| `44-11-rbpe/` | Règlement sur les bourses et les prêts d'études (RSF 44.11) | 4 | oldest version available, then each consolidated version: 1 September 2016 to 17 August 2026 |
| `44-13/` | Ordonnance relative aux mesures d'encouragement de la formation par un soutien financier durant la formation dans le domaine des soins infirmiers (RSF 44.13) | 2 | oldest version available, then each consolidated version: 1 July 2024 to 1 January 2026 |
| `45-11-rfad/` | Règlement sur la formation des adultes (RSF 45.11) | 3 | oldest version available, then each consolidated version: 1 January 2003 to 1 February 2022 |
| `45-12/` | Ordonnance relative aux exigences de qualité imposées aux institutions actives dans la formation des adultes et la formation continue à des fins professionnelles (RSF 45.12) | 1 | one version (the oldest available), 1 October 2003 |
| `52-11-rpci/` | Règlement sur la protection civile (RSF 52.11) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 October 2026 |
| `52-21-rprotpop/` | Règlement sur la protection de la population (RSF 52.21) | 1 | one version (the oldest available), 1 October 2026 |
| `87-23/` | Ordonnance fixant les limites de revenu et de fortune des locataires donnant droit à un abaissement supplémentaire selon la loi encourageant la construction de logements à caractère social (RSF 87.23) | 1 | one version (the oldest available), 1 April 2005 |
| `97-11/` | Ordonnance sur la coopération au développement et l'aide humanitaire internationales (RSF 97.11) | 2 | oldest version available, then each consolidated version: 1 April 2012 to 1 February 2022 |
| `110-11-orstat/` | Ordonnance concernant l'exécution des relevés statistiques cantonaux (RSF 110.11) | 3 | oldest version available, then each consolidated version: 3 March 2020 to 1 February 2026 |
| `111-11/` | Ordonnance relative à la population dite légale (RSF 111.11) | 3 | oldest version available, then each consolidated version: 1 October 2017 to 1 February 2025 |
| `111-13/` | Ordonnance indiquant les effectifs au 31 décembre 2025 de la population dite légale des communes du canton de Fribourg (RSF 111.13) | 8 | oldest version available, then each consolidated version: 9 September 2019 to 25 August 2026 |
| `112-51-oncd/` | Ordonnance indiquant les noms des communes et leur rattachement aux districts administratifs (RSF 112.51) | 6 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `114-1-11-rdcf/` | Règlement sur le droit de cité fribourgeois (RSF 114.1.11) | 5 | oldest version available, then each consolidated version: 1 January 2018 to 1 December 2024 |
| `114-3-11/` | Ordonnance sur les documents d'identité (RSF 114.3.11) | 1 | one version (the oldest available), 1 March 2012 |
| `114-21-12/` | Ordonnance relative à la plate-forme informatique contenant les données des registres des habitants (RSF 114.21.12) | 3 | oldest version available, then each consolidated version: 1 July 2016 to 1 February 2022 |
| `114-22-13/` | Règlement concernant la détention en matière de droit des étrangers (RSF 114.22.13) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 February 2022 |
| `114-22-14/` | Ordonnance relative à la lutte contre la traite des êtres humains (RSF 114.22.14) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 February 2022 |
| `114-22-16/` | Ordonnance fixant les émoluments en matière de police des étrangers (RSF 114.22.16) | 3 | oldest version available, then each consolidated version: 1 December 2013 to 1 November 2019 |
| `114-22-21-oint/` | Ordonnance sur l'intégration des migrants et des migrantes et la prévention du racisme (RSF 114.22.21) | 3 | oldest version available, then each consolidated version: 1 July 2017 to 1 July 2022 |
| `114-23-11-oas/` | Ordonnance sur l'asile (RSF 114.23.11) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 February 2022 |
| `114-23-12/` | Ordonnance sur la répartition dans le canton des requérants d'asile, des personnes admises à titre provisoire et des personnes à protéger sans autorisation de séjour (RSF 114.23.12) | 1 | one version (the oldest available), 1 January 2003 |
| `114-23-13/` | Ordonnance sur la désignation de l'organe chargé de représenter les requérants d'asile mineurs non accompagnés (personne de confiance) (RSF 114.23.13) | 1 | one version (the oldest available), 1 January 2013 |
| `115-11-redp/` | Règlement sur l'exercice des droits politiques (RSF 115.11) | 5 | oldest version available, then each consolidated version: 1 October 2016 to 1 July 2026 |
| `115-51-ofipol/` | Ordonnance sur le financement de la politique (RSF 115.51) | 1 | one version (the oldest available), 1 March 2025 |
| `115-61/` | Ordonnance fixant la participation de l'Etat aux frais de campagne des élections cantonales de 2026 et nationales de 2027 (RSF 115.61) | 1 | one version (the oldest available), 26 April 2024 |
| `115-611/` | Ordonnance CHA relative à la mise sous pli et à l'envoi de la publicité des partis politiques en vue des élections (RSF 115.611) | 1 | one version (the oldest available), 1 July 2015 |
| `121-6/` | Ordonnance parlementaire fixant le nombre de membres de la Commission des finances et de gestion et de la Commission des affaires extérieures (RSF 121.6) | 1 | one version (the oldest available), 1 March 2023 |
| `122-0-12-oadir/` | Ordonnance fixant les attributions des Directions du Conseil d'Etat et de la Chancellerie d'Etat (RSF 122.0.12) | 9 | oldest version available, then each consolidated version: 1 June 2017 to 1 June 2026 |
| `122-0-13/` | Ordonnance désignant les unités administratives des Directions du Conseil d'Etat et de la Chancellerie d'Etat (RSF 122.0.13) | 11 | oldest version available, then each consolidated version: 1 January 2018 to 1 June 2026 |
| `122-0-14-oiv/` | Ordonnance relative à l'identité visuelle de l'Etat de Fribourg (RSF 122.0.14) | 6 | oldest version available, then each consolidated version: 1 July 2015 to 1 November 2026 |
| `122-0-15/` | Règlement protocolaire (RSF 122.0.15) | 4 | oldest version available, then each consolidated version: 1 February 2019 to 17 October 2025 |
| `122-0-17-ogsce/` | Ordonnance sur la gestion des séances du Conseil d'Etat (RSF 122.0.17) | 5 | oldest version available, then each consolidated version: 8 April 2014 to 1 April 2024 |
| `122-0-21-real/` | Règlement sur l'élaboration des actes législatifs (RSF 122.0.21) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 November 2026 |
| `122-0-31/` | Règlement de la Conférence des secrétaires généraux (RSF 122.0.31) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 August 2023 |
| `122-0-51-oinf/` | Ordonnance relative à l'information sur les activités du Conseil d'Etat et de l'administration (RSF 122.0.51) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 November 2026 |
| `122-0-61-rofc/` | Règlement sur l'organisation et le fonctionnement des commissions de l'Etat (RSF 122.0.61) | 1 | one version (the oldest available), 1 January 2011 |
| `122-0-81/` | Ordonnance relative à la sécurité et à la protection de la santé au travail dans l'administration cantonale (RSF 122.0.81) | 3 | oldest version available, then each consolidated version: 1 June 2015 to 1 January 2023 |
| `122-3-21/` | Ordonnance concernant les indemnités de représentation et de déplacement des préfets (RSF 122.3.21) | 1 | one version (the oldest available), 1 July 2017 |
| `122-3-111/` | Règlement de la Conférence des préfets relatif à son organisation (RSF 122.3.111) | 1 | one version (the oldest available), 1 November 2019 |
| `122-8-41/` | Ordonnance concernant la rémunération des membres des commissions de l'Etat (RSF 122.8.41) | 1 | one version (the oldest available), 1 January 2018 |
| `122-24-411/` | Ordonnance DIAF sur l'organisation et le fonctionnement du Conseil des jeunes (RSF 122.24.411) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 December 2024 |
| `122-28-16/` | Ordonnance fixant les émoluments du Service de la mobilité (RSF 122.28.16) | 2 | oldest version available, then each consolidated version: 5 June 2012 to 1 January 2026 |
| `122-28-32-opic/` | Ordonnance sur les projets immobiliers importants de l'Etat et sur la Commission d'examen des projets immobiliers de l'Etat (RSF 122.28.32) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 February 2022 |
| `122-28-56/` | Ordonnance fixant les émoluments du Service des ponts et chaussées (RSF 122.28.56) | 3 | oldest version available, then each consolidated version: 1 May 2016 to 1 January 2026 |
| `122-70-11-rpers/` | Règlement du personnel de l'Etat (RSF 122.70.11) | 6 | oldest version available, then each consolidated version: 1 July 2018 to 1 January 2026 |
| `122-70-12/` | Règlement sur le temps de travail du personnel de l'Etat (RSF 122.70.12) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2022 |
| `122-70-13-odf/` | Ordonnance sur la formation du personnel de l'Etat (RSF 122.70.13) | 2 | oldest version available, then each consolidated version: 1 June 2015 to 1 July 2023 |
| `122-70-14-oharc/` | Ordonnance relative au harcèlement et aux difficultés relationnelles sur le lieu de travail (RSF 122.70.14) | 2 | oldest version available, then each consolidated version: 1 July 2016 to 1 July 2022 |
| `122-70-15/` | Ordonnance sur la Consultation Espace santé-social (RSF 122.70.15) | 2 | oldest version available, then each consolidated version: 1 January 2019 to 1 October 2024 |
| `122-70-17/` | Ordonnance relative à la surveillance de l'utilisation d'Internet par le personnel de l'Etat (RSF 122.70.17) | 1 | one version (the oldest available), 1 February 2015 |
| `122-70-18/` | Ordonnance relative à la contribution de soutien en faveur des associations de personnel (RSF 122.70.18) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2022 |
| `122-70-19-ooca/` | Ordonnance sur l'organe de conciliation et d'arbitrage en matière de conflits collectifs de travail impliquant le personnel de l'Etat (RSF 122.70.19) | 1 | one version (the oldest available), 1 July 2019 |
| `122-70-21-oode/` | Ordonnance relative à la conduite, par objectifs, du développement et de l'évaluation du personnel de l'Etat (RSF 122.70.21) | 1 | one version (the oldest available), 1 January 2022 |
| `122-70-23-oode-ens/` | Ordonnance relative à la conduite, par objectifs, du développement et de l'évaluation du personnel enseignant de la DFAC (RSF 122.70.23) | 1 | one version (the oldest available), 1 November 2022 |
| `122-70-31/` | Ordonnance sur le travail mobile du personnel de l'Etat (RSF 122.70.31) | 2 | oldest version available, then each consolidated version: 1 July 2017 to 1 November 2020 |
| `122-70-43-orps/` | Ordonnance relative à la réintégration de personnes atteintes dans leur santé (RSF 122.70.43) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 October 2024 |
| `122-70-72/` | Ordonnance relative à l'adoption de mesures favorisant la création de places de stages dans l'administration cantonale et l'intégration des jeunes demandeurs d'emploi dans le monde du travail (RSF 122.70.72) | 1 | one version (the oldest available), 1 September 2009 |
| `122-70-83/` | Ordonnance concernant les conditions de retraite des agents et agentes de la force publique (RSF 122.70.83) | 4 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2024 |
| `122-72-18/` | Ordonnance sur la garantie de la rémunération en cas de maladie et d'accident du personnel de l'Etat (RSF 122.72.18) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `122-72-21/` | Ordonnance relative à la classification des fonctions du personnel de l'Etat (RSF 122.72.21) | 13 | oldest version available, then each consolidated version: 1 January 2018 to 1 August 2025 |
| `122-72-22-recf/` | Règlement relatif à la procédure d'évaluation et de classification des fonctions du personnel de l'Etat (RSF 122.72.22) | 4 | oldest version available, then each consolidated version: 1 June 2015 to 1 January 2026 |
| `122-72-25/` | Ordonnance relative à la classification des fonctions dans l'échelle spéciale des fonctions (RSF 122.72.25) | 2 | oldest version available, then each consolidated version: 1 January 2004 to 1 July 2020 |
| `122-72-26/` | Ordonnance relative au maintien de la situation salariale acquise en cas d'abaissement de la classification d'une fonction (RSF 122.72.26) | 1 | one version (the oldest available), 1 May 2007 |
| `122-72-28/` | Ordonnance relative à la classification de la fonction de praticien formateur ou praticienne formatrice HES dans le domaine des soins (RSF 122.72.28) | 1 | one version (the oldest available), 1 January 2010 |
| `122-72-31/` | Ordonnance concernant la fixation des échelles de traitements du personnel de l'Etat pour l'année 2026 (RSF 122.72.31) | 7 | oldest version available, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `122-72-41/` | Ordonnance sur les primes de reconnaissance pour le personnel de l'Etat (RSF 122.72.41) | 2 | oldest version available, then each consolidated version: 1 January 2023 to 1 January 2026 |
| `122-72-82/` | Ordonnance concernant la classification de fonctions subventionnées (RSF 122.72.82) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 February 2022 |
| `122-73-61/` | Règlement relatif au Fonds d'entraide sociale (RSF 122.73.61) | 2 | oldest version available, then each consolidated version: 19 August 2014 to 1 July 2022 |
| `122-90-11/` | Ordonnance relative à la gestion par prestations (RSF 122.90.11) | 1 | one version (the oldest available), 1 June 2008 |
| `122-90-12/` | Ordonnance relative à la désignation des unités administratives autorisées à se gérer par prestations (RSF 122.90.12) | 3 | oldest version available, then each consolidated version: 29 June 2010 to 1 January 2022 |
| `122-90-21/` | Ordonnance relative à la gestion de la mise à jour et de la publication des catalogues de prestations (RSF 122.90.21) | 2 | oldest version available, then each consolidated version: 1 July 2009 to 1 August 2025 |
| `122-91-11-rcmp/` | Règlement sur les marchés publics (RSF 122.91.11) | 4 | oldest version available, then each consolidated version: 1 October 2011 to 1 June 2026 |
| `122-93-12/` | Règlement concernant la Commission d'acquisition des immeubles (RSF 122.93.12) | 7 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2024 |
| `122-94-11/` | Ordonnance sur la gouvernance de la durabilité (RSF 122.94.11) | 1 | one version (the oldest available), 1 April 2023 |
| `122-96-11-ogdsi/` | Ordonnance sur la gouvernance de la digitalisation et des systèmes d'information de l'Etat (RSF 122.96.11) | 11 | oldest version available, then each consolidated version: 1 October 2017 to 21 April 2026 |
| `122-97-11/` | Ordonnance concernant l'exploitation et la gestion des restaurants et mensas de l'Etat (RSF 122.97.11) | 1 | one version (the oldest available), 1 July 2004 |
| `124-11-rpal/` | Règlement sur la publication des actes législatifs (RSF 124.11) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2019 |
| `124-21/` | Ordonnance concernant la Feuille officielle (RSF 124.21) | 6 | oldest version available, then each consolidated version: 1 January 2016 to 1 April 2025 |
| `130-11-rj/` | Règlement sur la justice (RSF 130.11) | 4 | oldest version available, then each consolidated version: 1 January 2018 to 1 December 2025 |
| `130-21-rcm/` | Règlement du Conseil de la magistrature (RSF 130.21) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2019 |
| `130-41/` | Ordonnance du Conseil de la magistrature concernant la publication des règlements internes des autorités judiciaires (RSF 130.41) | 1 | one version (the oldest available), 1 October 2012 |
| `131-11-rtc/` | Règlement du Tribunal cantonal précisant son organisation et son fonctionnement (RSF 131.11) | 2 | oldest version available, then each consolidated version: 1 November 2016 to 1 January 2026 |
| `132-11/` | Règlement du Ministère public relatif à son organisation et à son fonctionnement (RSF 132.11) | 1 | one version (the oldest available), 1 January 2015 |
| `134-11-omed/` | Ordonnance sur la médiation en matière civile, pénale et pénale pour les mineurs (RSF 134.11) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2023 |
| `137-11-oav/` | Ordonnance sur la profession d'avocat (RSF 137.11) | 4 | oldest version available, then each consolidated version: 1 July 2015 to 1 January 2023 |
| `137-12/` | Règlement sur le stage et les examens de notaire (RSF 137.12) | 3 | oldest version available, then each consolidated version: 1 July 2017 to 1 January 2023 |
| `140-11-relco/` | Règlement d'exécution de la loi sur les communes (RSF 140.11) | 4 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2021 |
| `140-21/` | Ordonnance coordonnant le passage de l'ancienne à la nouvelle loi sur les agglomérations (RSF 140.21) | 1 | one version (the oldest available), 1 January 2021 |
| `140-22-ragg/` | Règlement sur les agglomérations (RSF 140.22) | 3 | oldest version available, then each consolidated version: 1 September 2021 to 1 January 2023 |
| `140-61-ofco/` | Ordonnance sur les finances communales (RSF 140.61) | 1 | one version (the oldest available), 1 January 2021 |
| `140-71-orb/` | Ordonnance répertoriant les bourgeoisies du canton de Fribourg (RSF 140.71) | 1 | one version (the oldest available), 1 January 2023 |
| `142-11-opfi-2026/` | Ordonnance sur la péréquation financière intercommunale pour l'année 2026 (RSF 142.11) | 10 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2027 |
| `150-13-oecpja/` | Ordonnance relative aux procédures administratives par voie électronique (RSF 150.13) | 1 | one version (the oldest available), 1 June 2017 |
| `150-14/` | Règlement du Tribunal cantonal sur la communication électronique dans le cadre des procédures de droit administratif (RSF 150.14) | 1 | one version (the oldest available), 1 January 2018 |
| `184-13-ogv/` | Ordonnance sur le guichet virtuel (RSF 184.13) | 6 | oldest version available, then each consolidated version: 1 June 2017 to 21 April 2026 |
| `184-16/` | Ordonnance concernant la mise en œuvre du Référentiel cantonal de données de personnes, organisations et nomenclatures (projet pilote) (RSF 184.16) | 6 | oldest version available, then each consolidated version: 1 August 2019 to 1 February 2025 |
| `190-12/` | Ordonnance relative à la Commission cantonale pour les questions d'aumônerie (RSF 190.12) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 February 2022 |
| `210-11-oacc/` | Ordonnance d'application du code civil suisse (RSF 210.11) | 4 | oldest version available, then each consolidated version: 30 November 2015 to 1 February 2022 |
| `211-2-11-rec/` | Règlement sur l'état civil (RSF 211.2.11) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 December 2024 |
| `211-5-11-osf/` | Ordonnance concernant la surveillance des fondations (RSF 211.5.11) | 1 | one version (the oldest available), 1 January 2014 |
| `212-3-85/` | Ordonnance concernant la surveillance des enfants placés chez des parents nourriciers (RSF 212.3.85) | 1 | one version (the oldest available), 1 January 2014 |
| `212-4-11-oarace/` | Ordonnance sur l'aide au recouvrement et l'avance de contributions d'entretien (RSF 212.4.11) | 3 | oldest version available, then each consolidated version: 1 January 2022 to 1 January 2025 |
| `212-5-11-opea/` | Ordonnance concernant la protection de l'enfant et de l'adulte (RSF 212.5.11) | 3 | oldest version available, then each consolidated version: 1 July 2015 to 1 February 2022 |
| `214-2-13/` | Ordonnance fixant les émoluments de l'Autorité foncière cantonale (RSF 214.2.13) | 1 | one version (the oldest available), 1 January 2024 |
| `214-5-11-relrf/` | Règlement d'exécution de la loi sur le registre foncier (RSF 214.5.11) | 5 | oldest version available, then each consolidated version: 1 April 2017 to 1 February 2025 |
| `214-7-11-ocgeo/` | Ordonnance sur la géoinformation (RSF 214.7.11) | 1 | one version (the oldest available), 1 March 2024 |
| `214-7-12-ocmo/` | Ordonnance sur la mensuration officielle (RSF 214.7.12) | 1 | one version (the oldest available), 1 March 2024 |
| `222-3-11-oblfna/` | Ordonnance relative au bail à loyer et au bail à ferme non agricole (RSF 222.3.11) | 2 | oldest version available, then each consolidated version: 1 July 2017 to 1 February 2022 |
| `222-3-12/` | Ordonnance concernant l'usage de la formule officielle pour la conclusion d'un nouveau bail à loyer (RSF 222.3.12) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 January 2024 |
| `222-5-91/` | Ordonnance établissant un contrat-type de travail pour les travailleurs et travailleuses du service de maison (RSF 222.5.91) | 2 | oldest version available, then each consolidated version: 14 February 2017 to 1 May 2025 |
| `261-11-rn/` | Règlement d'exécution de la loi du 20 septembre 1967 sur le notariat (RSF 261.11) | 5 | oldest version available, then each consolidated version: 1 July 2016 to 1 October 2025 |
| `262-11/` | Ordonnance sur la légalisation des signatures (RSF 262.11) | 1 | one version (the oldest available), 1 January 2006 |
| `340-11-oepm/` | Ordonnance relative à l'exécution des peines et des mesures (RSF 340.11) | 4 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `341-1-13/` | Ordonnance concernant la durée du travail et les horaires de certaines catégories de collaborateurs et collaboratrices rattachés à l'Etablissement de détention fribourgeois (RSF 341.1.13) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2022 |
| `411-0-11-rls/` | Règlement de la loi sur la scolarité obligatoire (RSF 411.0.11) | 7 | oldest version available, then each consolidated version: 1 August 2018 to 1 January 2023 |
| `411-0-16/` | Ordonnance fixant des montants maximaux facturables dans le cadre de la scolarité obligatoire (RSF 411.0.16) | 2 | oldest version available, then each consolidated version: 1 August 2016 to 1 August 2020 |
| `411-0-17/` | Ordonnance fixant les arrondissements pour l'inspection des écoles primaires et des écoles du cycle d'orientation (RSF 411.0.17) | 1 | one version (the oldest available), 1 August 2015 |
| `411-5-11-rps/` | Règlement sur la pédagogie spécialisée (RSF 411.5.11) | 3 | oldest version available, then each consolidated version: 1 May 2010 to 1 February 2022 |
| `412-0-11-ress/` | Règlement sur l'enseignement secondaire supérieur (RSF 412.0.11) | 7 | oldest version available, then each consolidated version: 1 January 2014 to 15 August 2025 |
| `412-0-14/` | Règlement concernant la passerelle de la maturité professionnelle ou spécialisée aux hautes écoles universitaires (RSF 412.0.14) | 3 | oldest version available, then each consolidated version: 1 August 2017 to 1 August 2025 |
| `412-0-16/` | Ordonnance fixant les écolages et les taxes d'inscription des écoles du secondaire du deuxième degré (RSF 412.0.16) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `412-1-11-reg/` | Règlement sur les études gymnasiales (RSF 412.1.11) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 February 2022 |
| `412-1-31-remg/` | Règlement concernant les examens de maturité gymnasiale (RSF 412.1.31) | 4 | oldest version available, then each consolidated version: 1 August 2017 to 1 August 2025 |
| `412-3-11-recpt/` | Règlement sur l'école de commerce à plein temps (RSF 412.3.11) | 4 | oldest version available, then each consolidated version: 1 August 2016 to 1 August 2025 |
| `412-4-21-recg/` | Règlement sur la formation en école de culture générale (RSF 412.4.21) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2025 |
| `413-1-11/` | Règlement sur l'orientation professionnelle, universitaire et de carrière (RSF 413.1.11) | 2 | oldest version available, then each consolidated version: 1 September 2010 to 1 February 2022 |
| `413-1-12/` | Ordonnance relative aux prestations payantes du Service de l'orientation professionnelle et de la formation des adultes (RSF 413.1.12) | 1 | one version (the oldest available), 1 January 2013 |
| `413-5-11-rmds/` | Règlement sur la médecine dentaire scolaire (RSF 413.5.11) | 2 | oldest version available, then each consolidated version: 1 August 2016 to 1 February 2022 |
| `413-5-17-opoint/` | Ordonnance fixant la valeur du point du tarif des prestations du Service dentaire scolaire (RSF 413.5.17) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `413-5-26/` | Ordonnance relative aux indemnités spéciales versées au personnel du Service dentaire scolaire (RSF 413.5.26) | 1 | one version (the oldest available), 1 January 2018 |
| `413-5-112/` | Ordonnance DSAS concernant la médecine dentaire scolaire (facturation aux communes des coûts de la mobilité des contrôles dentaires) (RSF 413.5.112) | 1 | one version (the oldest available), 1 September 2016 |
| `414-41/` | Règlement sur les subventions pour les constructions d'écoles enfantines, primaires et du cycle d'orientation (RSF 414.41) | 1 | one version (the oldest available), 1 January 2014 |
| `415-0-11-rpens/` | Règlement relatif au personnel enseignant de la Direction de la formation et des affaires culturelles (RSF 415.0.11) | 5 | oldest version available, then each consolidated version: 1 May 2018 to 1 August 2025 |
| `415-4-42/` | Ordonnance fixant les honoraires pour l'encadrement de stages dans les classes enfantines et primaires (RSF 415.4.42) | 2 | oldest version available, then each consolidated version: 1 September 2002 to 1 February 2022 |
| `420-11-rfp/` | Règlement sur la formation professionnelle (RSF 420.11) | 4 | oldest version available, then each consolidated version: 1 January 2016 to 1 February 2022 |
| `420-16-otifp/` | Ordonnance sur les tarifs des taxes et des indemnités de la formation professionnelle (RSF 420.16) | 1 | one version (the oldest available), 1 September 2016 |
| `420-24-rpens-deef/` | Règlement relatif au personnel enseignant dépendant de la Direction de l'économie, de l'emploi et de la formation professionnelle (RSF 420.24) | 6 | oldest version available, then each consolidated version: 1 May 2018 to 1 October 2024 |
| `420-82-rsif-acpc/` | Règlement sur les subventions pour les infrastructures de la formation initiale en entreprise et de la formation continue financées par l'Association du Centre professionnel cantonal (RSF 420.82) | 1 | one version (the oldest available), 31 May 2022 |
| `422-12/` | Règlement sur la formation de technicien ou technicienne ES en conduite de travaux (RSF 422.12) | 2 | oldest version available, then each consolidated version: 1 September 2017 to 1 February 2022 |
| `422-16/` | Ordonnance sur les taxes perçues à l'Ecole technique de la construction (RSF 422.16) | 1 | one version (the oldest available), 1 June 2012 |
| `426-11-rcpi/` | Règlement du Centre de perfectionnement interprofessionnel (RSF 426.11) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 February 2022 |
| `430-11-opathe/` | Ordonnance concernant la protection des appellations et des titres du domaine des hautes écoles (RSF 430.11) | 1 | one version (the oldest available), 1 January 2026 |
| `431-0-16/` | Ordonnance concernant la taxe d'inscription des étudiants et étudiantes et des auditeurs et auditrices de l'Université de Fribourg (RSF 431.0.16) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 15 November 2024 |
| `431-1-12/` | Ordonnance limitant le nombre d'admissions à la formation francophone à l'enseignement au secondaire II pour l'année académique 2026/27 (RSF 431.1.12) | 9 | oldest version available, then each consolidated version: 9 January 2018 to 13 January 2026 |
| `431-1-13/` | Ordonnance concernant la capacité d'accueil et le test d'aptitudes pour le Bachelor of Medicine (BMed) à l'Université de Fribourg pour l'année académique 2026/27 (RSF 431.1.13) | 9 | oldest version available, then each consolidated version: 19 March 2018 to 10 March 2026 |
| `431-1-14/` | Ordonnance concernant l'admission des candidats et candidates étrangers aux études de médecine à l'Université de Fribourg pour l'année académique 2027/28 (RSF 431.1.14) | 9 | oldest version available, then each consolidated version: 11 December 2017 to 1 June 2026 |
| `431-1-15/` | Ordonnance limitant le nombre de places d'études au niveau bachelor en sciences du sport et de la motricité à l'Université de Fribourg pour l'année académique 2026/27 (RSF 431.1.15) | 10 | oldest version available, then each consolidated version: 16 January 2018 to 1 January 2026 |
| `431-1-16/` | Ordonnance limitant le nombre de places d'études en Master of Medicine (MMed) à l'Université de Fribourg pour l'année académique 2027/28 (RSF 431.1.16) | 8 | oldest version available, then each consolidated version: 25 September 2018 to 1 June 2026 |
| `431-1-17/` | Ordonnance limitant le nombre d'admissions au Master of Arts spécialisé en pédagogie spécialisée: orientation enseignement spécialisé francophone à l'Université de Fribourg pour l'année académique 2023/24 (RSF 431.1.17) | 1 | one version (the oldest available), 26 June 2023 |
| `431-1-18/` | Ordonnance limitant le nombre de places d'études en Master of Medicine (MMed) à l'Université de Fribourg pour l'année académique 2026/27 (RSF 431.1.18) | 2 | oldest version available, then each consolidated version: 1 June 2025 to 1 June 2027 |
| `431-1-19/` | Ordonnance concernant l'admission des candidats et candidates étrangers aux études de médecine à l'Université de Fribourg pour l'année académique 2026/27 (RSF 431.1.19) | 2 | oldest version available, then each consolidated version: 1 June 2025 to 1 June 2027 |
| `431-1-20/` | Ordonnance concernant l'admission à la formation à l'enseignement pour le degré primaire pour l'année académique 2026/27 (RSF 431.1.20) | 2 | oldest version available, then each consolidated version: 4 July 2025 to 27 January 2026 |
| `432-12-11/` | Règlement d'organisation de la Haute Ecole spécialisée de Suisse occidentale//Fribourg (RSF 432.12.11) | 1 | one version (the oldest available), 1 September 2015 |
| `432-12-16/` | Ordonnance concernant les taxes et les contributions dues par les étudiants et étudiantes immatriculés à la Haute Ecole spécialisée de Suisse occidentale//Fribourg (RSF 432.12.16) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 August 2025 |
| `460-11-rsport/` | Règlement sur le sport (RSF 460.11) | 2 | oldest version available, then each consolidated version: 1 August 2015 to 1 July 2022 |
| `464-12/` | Ordonnance sur les installations de tir sportif (RSF 464.12) | 2 | oldest version available, then each consolidated version: 1 March 2022 to 1 December 2022 |
| `464-16-opiscines/` | Ordonnance sur le subventionnement de piscines (RSF 464.16) | 2 | oldest version available, then each consolidated version: 1 October 2015 to 1 July 2022 |
| `480-11-reac/` | Règlement sur l'encouragement des activités culturelles (RSF 480.11) | 6 | oldest version available, then each consolidated version: 1 July 2017 to 1 October 2026 |
| `481-0-11-rice/` | Règlement sur les institutions culturelles de l'Etat (RSF 481.0.11) | 1 | one version (the oldest available), 1 October 2026 |
| `481-3-11/` | Ordonnance sur les objectifs et le fonctionnement de la Fondation du château de Gruyères (RSF 481.3.11) | 1 | one version (the oldest available), 1 December 2017 |
| `481-4-12/` | Ordonnance concernant les examens au Conservatoire (RSF 481.4.12) | 2 | oldest version available, then each consolidated version: 1 September 2012 to 1 February 2022 |
| `481-4-16/` | Ordonnance fixant les taxes de cours du Conservatoire applicables dès le 1er septembre 2014 (RSF 481.4.16) | 1 | one version (the oldest available), 1 September 2014 |
| `482-11-relpbc/` | Règlement d'exécution de la loi sur la protection des biens culturels (RSF 482.11) | 3 | oldest version available, then each consolidated version: 1 October 2012 to 1 December 2022 |
| `482-13/` | Ordonnance fixant le tarif des émoluments dans les domaines de la protection des biens culturels et de l'archéologie (RSF 482.13) | 1 | one version (the oldest available), 1 January 2026 |
| `513-11/` | Ordonnance concernant la taxe d'exemption de l'obligation de servir (RSF 513.11) | 3 | oldest version available, then each consolidated version: 1 July 2010 to 1 November 2026 |
| `550-12/` | Ordonnance sur les mesures visant au maintien de la sûreté intérieure et sur le renseignement (RSF 550.12) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 February 2023 |
| `551-12/` | Ordonnance instituant un Conseil cantonal de prévention et de sécurité (RSF 551.12) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 February 2022 |
| `551-13/` | Ordonnance concernant l'avancement et la promotion des agents et agentes de la Police cantonale (RSF 551.13) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 August 2023 |
| `551-14/` | Ordonnance sur le statut des aspirants et aspirantes de police et des policiers et policières en formation (RSF 551.14) | 1 | one version (the oldest available), 1 January 2020 |
| `551-15/` | Ordonnance relative à la gestion des menaces (RSF 551.15) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 February 2022 |
| `551-17/` | Ordonnance concernant les profils d'ADN (RSF 551.17) | 1 | one version (the oldest available), 1 January 2011 |
| `551-23/` | Ordonnance sur les agents et agentes auxiliaires de la Police cantonale (RSF 551.23) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 31 October 2023 |
| `551-24/` | Règlement concernant l'habillement, l'équipement et l'armement des agents de la Police cantonale (RSF 551.24) | 1 | one version (the oldest available), 1 January 1992 |
| `551-32/` | Ordonnance relative à l'indemnité de service versée aux agents et agentes de police (RSF 551.32) | 1 | one version (the oldest available), 1 January 2008 |
| `551-34/` | Ordonnance concernant les indemnités pour l'achat et l'entretien de chiens de police (RSF 551.34) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 July 2019 |
| `551-41/` | Ordonnance sur la surveillance de la correspondance par poste et télécommunication en cas de recherche de personnes condamnées (RSF 551.41) | 1 | one version (the oldest available), 15 June 2018 |
| `551-61/` | Ordonnance concernant les frais de la Police cantonale (RSF 551.61) | 3 | oldest version available, then each consolidated version: 1 October 2016 to 1 January 2026 |
| `559-72/` | Ordonnance organisant les mesures pour lutter contre la violence lors de manifestations sportives (RSF 559.72) | 1 | one version (the oldest available), 1 May 2014 |
| `610-11-rfe/` | Règlement d'exécution de la loi sur les finances de l'Etat (RSF 610.11) | 6 | oldest version available, then each consolidated version: 1 January 2015 to 1 July 2026 |
| `610-16/` | Ordonnance sur les modalités de perception des créances de l'Etat (RSF 610.16) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 January 2025 |
| `612-21/` | Ordonnance précisant certains montants liés aux derniers comptes de l'Etat (RSF 612.21) | 8 | oldest version available, then each consolidated version: 22 May 2019 to 9 June 2026 |
| `616-11-rsub/` | Règlement sur les subventions (RSF 616.11) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `616-12/` | Ordonnance relative à diverses subventions de moindre importance (RSF 616.12) | 2 | oldest version available, then each consolidated version: 1 July 2011 to 1 January 2026 |
| `631-13/` | Ordonnance concernant l'échéance et la perception des créances fiscales (RSF 631.13) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2023 |
| `631-14/` | Ordonnance concernant la consultation des registres de l'impôt (RSF 631.14) | 1 | one version (the oldest available), 1 July 2002 |
| `631-15/` | Ordonnance concernant le dépôt par voie électronique de la déclaration fiscale des personnes physiques (RSF 631.15) | 1 | one version (the oldest available), 1 January 2015 |
| `631-21/` | Ordonnance sur la mise en œuvre de la réforme fiscale (RSF 631.21) | 1 | one version (the oldest available), 1 January 2020 |
| `631-32/` | Ordonnance relative à la perception de l'impôt à la source (RSF 631.32) | 9 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `631-48/` | Ordonnance concernant la déduction des primes d'assurance-maladie et accidents (RSF 631.48) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2021 |
| `631-62/` | Ordonnance déterminant les incidences fiscales de la mise en place du Réseau hospitalier fribourgeois (RSF 631.62) | 1 | one version (the oldest available), 1 January 2007 |
| `631-131/` | Ordonnance DFIN relative à la perception des créances fiscales (RSF 631.131) | 6 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `631-411/` | Ordonnance DFIN sur la déduction des frais professionnels des personnes exerçant une activité lucrative dépendante (RSF 631.411) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2023 |
| `631-421/` | Ordonnance DFIN sur la déduction des frais relatifs aux immeubles privés ainsi que des investissements destinés à économiser l'énergie et à ménager l'environnement (RSF 631.421) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2020 |
| `634-2-11/` | Ordonnance d'exécution de la loi fédérale sur l'impôt anticipé (RSF 634.2.11) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2022 |
| `635-2-11-oisd/` | Ordonnance sur l'impôt sur les successions et les donations (RSF 635.2.11) | 1 | one version (the oldest available), 1 January 2008 |
| `635-2-14/` | Ordonnance concernant la déduction des dettes pour le calcul de l'impôt sur les successions (RSF 635.2.14) | 1 | one version (the oldest available), 1 October 2022 |
| `635-2-15/` | Ordonnance concernant la déduction des frais funéraires pour le calcul de l'impôt sur les successions (RSF 635.2.15) | 1 | one version (the oldest available), 1 January 2008 |
| `635-4-13/` | Ordonnance fixant les conditions d'exonération de l'impôt sur les véhicules automobiles et les remorques (RSF 635.4.13) | 1 | one version (the oldest available), 1 January 2022 |
| `635-6-12/` | Règlement concernant l'organe d'estimation en matière d'impôt destiné à compenser la diminution de l'aire agricole et en matière de droits de mutation (RSF 635.6.12) | 1 | one version (the oldest available), 1 January 2012 |
| `637-21/` | Ordonnance d'exécution de l'ordonnance fédérale relative à l'imputation forfaitaire d'impôts (RSF 637.21) | 2 | oldest version available, then each consolidated version: 1 May 1983 to 1 January 2020 |
| `710-11-relatec/` | Règlement d'exécution de la loi sur l'aménagement du territoire et les constructions (RSF 710.11) | 9 | oldest version available, then each consolidated version: 1 January 2018 to 1 November 2026 |
| `710-16/` | Ordonnance fixant le tarif des émoluments et des frais de procédure dans le domaine de l'aménagement du territoire et des constructions (RSF 710.16) | 3 | oldest version available, then each consolidated version: 1 July 2017 to 1 January 2026 |
| `710-31/` | Ordonnance portant adoption du plan directeur cantonal (RSF 710.31) | 3 | oldest version available, then each consolidated version: 1 January 2003 to 1 February 2022 |
| `710-61-ogf/` | Ordonnance relative aux garanties financières à fournir pour les exploitations de matériaux et les décharges (RSF 710.61) | 2 | oldest version available, then each consolidated version: 1 October 2015 to 1 February 2022 |
| `712-11-oarsec/` | Ordonnance d'application de la législation fédérale sur les résidences secondaires (RSF 712.11) | 2 | oldest version available, then each consolidated version: 1 September 2017 to 1 February 2022 |
| `721-0-11-rpnat/` | Règlement sur la protection de la nature et du paysage (RSF 721.0.11) | 5 | oldest version available, then each consolidated version: 1 July 2014 to 1 February 2022 |
| `721-0-16/` | Ordonnance fixant les émoluments du Service des forêts et de la nature (RSF 721.0.16) | 4 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `721-1-31/` | Ordonnance concernant la lutte contre la propagation du frelon asiatique à pattes jaunes (RSF 721.1.31) | 1 | one version (the oldest available), 1 July 2026 |
| `721-1-52/` | Ordonnance concernant la réserve mycologique La Chanéaz, sur le territoire de la commune de Montagny, forêt domaniale de la Chanéaz (RSF 721.1.52) | 2 | oldest version available, then each consolidated version: 1 July 2014 to 1 April 2019 |
| `721-2-31/` | Règlement concernant la réserve naturelle du lac de Pérolles (RSF 721.2.31) | 2 | oldest version available, then each consolidated version: 1 July 2014 to 1 April 2019 |
| `721-2-51/` | Règlement concernant la protection de la réserve du Vanil-Noir (RSF 721.2.51) | 2 | oldest version available, then each consolidated version: 1 July 2014 to 1 April 2019 |
| `721-3-13/` | Ordonnance concernant la réserve forestière de La Souche, sur le territoire de la commune d'Arconciel (RSF 721.3.13) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 April 2019 |
| `721-3-14/` | Ordonnance concernant la réserve forestière En Biffé, sur le territoire des communes de Botterens, Châtel-sur-Montsalvens et Villarbeney (RSF 721.3.14) | 2 | oldest version available, then each consolidated version: 1 July 2014 to 1 April 2019 |
| `721-3-15/` | Ordonnance concernant la réserve forestière En Allières, sur le territoire de la commune de Hauteville (RSF 721.3.15) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 April 2019 |
| `721-3-16/` | Ordonnance concernant la réserve forestière La Leyte–Motélon, sur le territoire de la commune de Charmey (RSF 721.3.16) | 2 | oldest version available, then each consolidated version: 1 November 2003 to 1 April 2019 |
| `721-3-17/` | Ordonnance concernant la réserve forestière Grand-Paine–Auta-Chia, sur le territoire de la commune de Cerniat (RSF 721.3.17) | 2 | oldest version available, then each consolidated version: 1 December 2003 to 1 April 2019 |
| `721-3-18/` | Ordonnance concernant la réserve forestière Galm Sud, sur le territoire des communes de Gurmels et de Jeuss et sur celui du Staatswald Galm (RSF 721.3.18) | 2 | oldest version available, then each consolidated version: 16 December 2003 to 1 April 2019 |
| `721-3-19/` | Ordonnance concernant la réserve forestière Tannholz–Remlitswilholz, sur le territoire de la commune de St. Ursen (RSF 721.3.19) | 2 | oldest version available, then each consolidated version: 11 February 2008 to 1 April 2019 |
| `721-3-20/` | Ordonnance concernant la réserve forestière des îles de Villeneuve, sur le territoire de la commune de Villeneuve (RSF 721.3.20) | 2 | oldest version available, then each consolidated version: 2 March 2010 to 1 April 2019 |
| `721-3-21/` | Ordonnance concernant la réserve forestière du Lapé, sur le territoire de la commune de Charmey (RSF 721.3.21) | 2 | oldest version available, then each consolidated version: 26 May 2010 to 1 April 2019 |
| `721-3-22/` | Ordonnance concernant la réserve forestière Les Preises–Le Barlattey–Goille-au-Cerf, sur le territoire de la commune de Châtel-Saint-Denis (RSF 721.3.22) | 2 | oldest version available, then each consolidated version: 21 December 2010 to 1 April 2019 |
| `721-3-23/` | Ordonnance concernant la réserve forestière Les Marais-de-Courtes-Poses, sur le territoire de la commune de Vuissens (RSF 721.3.23) | 2 | oldest version available, then each consolidated version: 19 February 2013 to 1 April 2019 |
| `721-3-24/` | Ordonnance concernant la réserve forestière Petite-Sarine, sur le territoire des communes d'Arconciel, de Rossens et de Treyvaux (RSF 721.3.24) | 2 | oldest version available, then each consolidated version: 1 September 2015 to 1 April 2019 |
| `721-3-25/` | Ordonnance concernant la réserve forestière de l'Hongrin, sur le territoire de la commune de Haut-Intyamon (RSF 721.3.25) | 2 | oldest version available, then each consolidated version: 1 March 2016 to 1 April 2019 |
| `721-3-26/` | Ordonnance concernant la réserve forestière Seiseflüe, sur le territoire des communes d'Ueberstorf, Heitenried et St. Antoni (RSF 721.3.26) | 1 | one version (the oldest available), 1 May 2019 |
| `721-3-27/` | Ordonnance concernant la réserve forestière Naturwaud Seiseflüe 2, sur le territoire des communes d'Alterswil et St. Antoni (RSF 721.3.27) | 1 | one version (the oldest available), 1 May 2020 |
| `721-3-28/` | Ordonnance concernant la réserve forestière Le Pralet, sur le territoire de la commune de Val-de-Charmey (RSF 721.3.28) | 1 | one version (the oldest available), 1 May 2020 |
| `721-3-29/` | Ordonnance concernant la réserve forestière spéciale Joux de Laisse, sur le territoire de la commune de Val-de-Charmey (RSF 721.3.29) | 1 | one version (the oldest available), 1 January 2021 |
| `721-3-30/` | Ordonnance concernant la réserve forestière Paccot-Caquerette, sur le territoire de la commune de Châtel-Saint-Denis (RSF 721.3.30) | 1 | one version (the oldest available), 1 January 2021 |
| `721-3-31/` | Ordonnance concernant la réserve forestière spéciale St. Ursenvorschis, sur le territoire de la commune de Planfayon (RSF 721.3.31) | 1 | one version (the oldest available), 1 December 2021 |
| `721-3-32/` | Ordonnance concernant la réserve forestière Spittel- und Chänel-Gantrisch, sur le territoire de la commune de Plaffeien (RSF 721.3.32) | 1 | one version (the oldest available), 1 May 2023 |
| `721-3-33/` | Ordonnance concernant la réserve forestière spéciale Tourbière du Niremont, sur le territoire de la commune de Semsales (RSF 721.3.33) | 1 | one version (the oldest available), 1 March 2023 |
| `721-3-34/` | Ordonnance concernant la réserve forestière spéciale Les Grèves de la Corbière, sur le territoire de la commune d'Estavayer (RSF 721.3.34) | 1 | one version (the oldest available), 1 March 2023 |
| `721-3-35/` | Ordonnance concernant la réserve forestière Cheyres-Font (RSF 721.3.35) | 1 | one version (the oldest available), 1 December 2025 |
| `721-3-36/` | Ordonnance concernant la réserve forestière Breccaschlund (RSF 721.3.36) | 1 | one version (the oldest available), 1 December 2025 |
| `721-3-37/` | Ordonnance concernant la réserve forestière spéciale Chablais de Sugiez (RSF 721.3.37) | 1 | one version (the oldest available), 1 December 2025 |
| `721-3-38/` | Ordonnance concernant la réserve forestière spéciale La Patta (RSF 721.3.38) | 1 | one version (the oldest available), 1 December 2025 |
| `721-3-39/` | Ordonnance concernant la réserve forestière Les Planeys (RSF 721.3.39) | 1 | one version (the oldest available), 1 December 2025 |
| `721-3-40/` | Ordonnance concernant la réserve forestière du Bois des Combes (RSF 721.3.40) | 1 | one version (the oldest available), 1 December 2025 |
| `721-3-41/` | Ordonnance concernant la réserve forestière Le Canada (RSF 721.3.41) | 1 | one version (the oldest available), 1 December 2025 |
| `721-3-42/` | Ordonnance concernant la réserve forestière La Crêta (RSF 721.3.42) | 1 | one version (the oldest available), 1 December 2025 |
| `725-11-rcpa/` | Règlement sur la protection des animaux (RSF 725.11) | 3 | oldest version available, then each consolidated version: 1 September 2014 to 1 January 2022 |
| `725-31-rdch/` | Règlement sur la détention des chiens (RSF 725.31) | 4 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `731-3-11-rdis/` | Règlement sur la défense incendie et les secours (RSF 731.3.11) | 2 | oldest version available, then each consolidated version: 1 July 2021 to 1 January 2023 |
| `732-1-11-recab/` | Règlement sur l'assurance immobilière, la prévention et les secours en matière de feu et d'éléments naturels (RSF 732.1.11) | 5 | oldest version available, then each consolidated version: 1 July 2018 to 1 January 2023 |
| `732-2-11/` | Règlement d'exécution de la loi du 3 février 1966 sur l'assurance obligatoire du mobilier contre l'incendie (RSF 732.2.11) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 February 2022 |
| `741-17/` | Ordonnance déléguant à la commune de Fribourg des compétences en matière d'infrastructure de mobilité (RSF 741.17) | 3 | oldest version available, then each consolidated version: 1 June 2012 to 1 February 2026 |
| `741-22/` | Ordonnance concernant le personnel d'entretien des routes (RSF 741.22) | 1 | one version (the oldest available), 1 January 2016 |
| `753-72/` | Ordonnance interdisant la navigation, la baignade et la plongée dans le lac des Joncs (RSF 753.72) | 1 | one version (the oldest available), 1 May 2016 |
| `770-11-ren/` | Règlement sur l'énergie (RSF 770.11) | 7 | oldest version available, then each consolidated version: 1 January 2017 to 1 September 2025 |
| `770-12-ooen/` | Ordonnance pour une subvention en faveur de mesures d'optimisation énergétique (RSF 770.12) | 1 | one version (the oldest available), 19 May 2025 |
| `770-21/` | Ordonnance relative au plan sectoriel de l'énergie (RSF 770.21) | 1 | one version (the oldest available), 1 January 2012 |
| `770-32-ocic/` | Ordonnance sur le contrôle obligatoire des installations de combustion (RSF 770.32) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 8 October 2021 |
| `772-0-21-raee/` | Règlement sur l'approvisionnement en énergie électrique (RSF 772.0.21) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2022 |
| `780-11-rmob/` | Règlement sur la mobilité (RSF 780.11) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2023 |
| `780-31/` | Ordonnance portant adoption du plan cantonal des transports (RSF 780.31) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 February 2022 |
| `780-32/` | Ordonnance portant adoption de modifications du plan cantonal des transports (RSF 780.32) | 2 | oldest version available, then each consolidated version: 1 April 2014 to 1 February 2022 |
| `781-51/` | Ordonnance concernant l'assurance responsabilité civile pour les cyclomoteurs (RSF 781.51) | 1 | one version (the oldest available), 1 January 2013 |
| `781-72/` | Ordonnance concernant les moniteurs et les écoles de conduite (RSF 781.72) | 1 | one version (the oldest available), 1 January 2011 |
| `781-82/` | Ordonnance concernant les marchandises dangereuses transportées par route (RSF 781.82) | 1 | one version (the oldest available), 1 January 2013 |
| `785-17-oodnb/` | Ordonnance sur l'obligation de déclaration et de nettoyage des bateaux (RSF 785.17) | 1 | one version (the oldest available), 1 August 2026 |
| `786-12-oaero/` | Ordonnance sur les aéronefs sans occupants d'un poids inférieur à 30 kg (RSF 786.12) | 3 | oldest version available, then each consolidated version: 1 January 2022 to 1 March 2024 |
| `810-13-occhim/` | Ordonnance sur les produits chimiques (RSF 810.13) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2022 |
| `810-15-oeiep/` | Ordonnance sur les études d'impact sur l'environnement et les procédures décisives (RSF 810.15) | 5 | oldest version available, then each consolidated version: 1 March 2018 to 1 January 2023 |
| `810-16/` | Ordonnance fixant les émoluments du Service de l'environnement (RSF 810.16) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2026 |
| `810-21-rgd/` | Règlement sur la gestion des déchets (RSF 810.21) | 4 | oldest version available, then each consolidated version: 1 July 2013 to 1 February 2022 |
| `810-24/` | Ordonnance modifiant le plan cantonal de gestion des déchets (RSF 810.24) | 1 | one version (the oldest available), 1 January 2010 |
| `810-25/` | Ordonnance portant adoption de la modification partielle du plan de gestion des déchets (chapitre «Décharges de type B») (RSF 810.25) | 2 | oldest version available, then each consolidated version: 1 October 2017 to 1 February 2022 |
| `810-31-rsites/` | Règlement sur les sites pollués (RSF 810.31) | 2 | oldest version available, then each consolidated version: 1 July 2013 to 1 February 2022 |
| `811-11/` | Ordonnance sur la protection des sols (RSF 811.11) | 4 | oldest version available, then each consolidated version: 1 March 2007 to 1 February 2022 |
| `812-11-rceaux/` | Règlement sur les eaux (RSF 812.11) | 6 | oldest version available, then each consolidated version: 1 May 2016 to 1 March 2024 |
| `813-12/` | Ordonnance portant adoption du plan de mesures pour la protection de l'air (RSF 813.12) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2020 |
| `813-21/` | Ordonnance sur le smog hivernal (RSF 813.21) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 February 2022 |
| `814-11-opbs/` | Ordonnance sur la protection contre le bruit et les dangers liés au son (RSF 814.11) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 February 2022 |
| `815-11-rclim/` | Règlement sur le climat (RSF 815.11) | 1 | one version (the oldest available), 1 July 2026 |
| `815-13/` | Ordonnance pour une subvention en faveur des actions énergétiques des communes (RSF 815.13) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 July 2026 |
| `815-14/` | Ordonnance pour soutenir l'action communale en faveur des projets d'adaptation aux fortes chaleurs (RSF 815.14) | 2 | oldest version available, then each consolidated version: 4 June 2024 to 1 July 2026 |
| `815-15/` | Ordonnance sur les contributions pour les mesures du Plan Climat cantonal dans l'agriculture (RSF 815.15) | 1 | one version (the oldest available), 1 April 2025 |
| `820-21-rpms/` | Règlement sur les prestations médico-sociales (RSF 820.21) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2019 |
| `820-61-orfs/` | Ordonnance sur le nouveau régime de financement des soins (RSF 820.61) | 3 | oldest version available, then each consolidated version: 1 September 2016 to 1 October 2026 |
| `820-62/` | Ordonnance fixant la part cantonale aux coûts des prestations de soins aigus et de transition pour l'année 2026 (RSF 820.62) | 8 | oldest version available, then each consolidated version: 1 January 2020 to 1 January 2027 |
| `821-0-11-rpsp/` | Règlement concernant la promotion de la santé et la prévention (RSF 821.0.11) | 4 | oldest version available, then each consolidated version: 7 March 2016 to 1 February 2026 |
| `821-0-12-ofs/` | Ordonnance concernant les fournisseurs de soins (RSF 821.0.12) | 1 | one version (the oldest available), 1 April 2010 |
| `821-0-13/` | Ordonnance sur le Conseil de santé (RSF 821.0.13) | 1 | one version (the oldest available), 1 January 2012 |
| `821-0-14/` | Ordonnance concernant la procédure à suivre en matière d'interruption non punissable de grossesse (RSF 821.0.14) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2022 |
| `821-0-15/` | Ordonnance concernant la protection contre la fumée passive (RSF 821.0.15) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 February 2022 |
| `821-0-16/` | Ordonnance sur la Commission de surveillance des professions de la santé et des droits des patients et patientes (RSF 821.0.16) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 October 2022 |
| `821-0-17/` | Règlement sur les services d'ambulance et les transports de patients et patientes (RSF 821.0.17) | 1 | one version (the oldest available), 1 January 2003 |
| `821-0-18/` | Ordonnance concernant les mesures sanitaires d'urgence en cas de catastrophe restreinte (ORCAF restreinte) à appliquer dans le cadre des hôpitaux du canton de Fribourg (RSF 821.0.18) | 1 | one version (the oldest available), 1 January 2003 |
| `821-0-19/` | Ordonnance concernant l'obligation d'annoncer les défibrillateurs externes automatiques (RSF 821.0.19) | 1 | one version (the oldest available), 1 April 2016 |
| `821-0-31/` | Ordonnance sur l'Organe de conduite sanitaire (RSF 821.0.31) | 1 | one version (the oldest available), 1 September 2013 |
| `821-0-32-ogisp/` | Ordonnance sur le groupe d'intervention sanitaire (RSF 821.0.32) | 1 | one version (the oldest available), 1 July 2024 |
| `821-0-41/` | Ordonnance sur la Centrale 144 d'appels d'urgence sanitaire (RSF 821.0.41) | 1 | one version (the oldest available), 1 July 2017 |
| `821-0-51/` | Ordonnance concernant la mise en service d'équipements techniques lourds et d'autres équipements de médecine de pointe (RSF 821.0.51) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 7 December 2021 |
| `821-0-61/` | Ordonnance fixant le tarif des émoluments relatifs à l'application de la loi sur la santé (RSF 821.0.61) | 1 | one version (the oldest available), 1 January 2013 |
| `821-0-81/` | Ordonnance sur la médecine scolaire (RSF 821.0.81) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 July 2021 |
| `821-11-11-oefs/` | Ordonnance sur l'encouragement de la formation dans le domaine des soins (RSF 821.11.11) | 1 | one version (the oldest available), 1 January 2026 |
| `821-20-21-opth/` | Ordonnance sur les produits thérapeutiques (RSF 821.20.21) | 1 | one version (the oldest available), 1 May 2014 |
| `821-20-211/` | Ordonnance DSAS concernant l'utilisation professionnelle de médicaments (RSF 821.20.211) | 1 | one version (the oldest available), 1 May 2016 |
| `821-22-11/` | Ordonnance sur les stupéfiants (RSF 821.22.11) | 2 | oldest version available, then each consolidated version: 1 April 2016 to 1 February 2022 |
| `821-30-11-rsal/` | Règlement sur la sécurité alimentaire (RSF 821.30.11) | 3 | oldest version available, then each consolidated version: 1 July 2016 to 1 January 2019 |
| `821-30-16-ofsaav/` | Ordonnance fixant le tarif des frais du Service de la sécurité alimentaire et des affaires vétérinaires (RSF 821.30.16) | 3 | oldest version available, then each consolidated version: 1 September 2014 to 1 March 2025 |
| `821-30-131/` | Ordonnance DIAF sur le personnel auxiliaire du Service de la sécurité alimentaire et des affaires vétérinaires (RSF 821.30.131) | 1 | one version (the oldest available), 1 January 2022 |
| `821-31-12/` | Ordonnance concernant le personnel du contrôle de l'abattage des animaux et de l'hygiène des viandes (RSF 821.31.12) | 1 | one version (the oldest available), 1 January 2013 |
| `821-31-16/` | Ordonnance sur la fixation des émoluments et des débours pour le contrôle de l'abattage des animaux et des viandes (RSF 821.31.16) | 1 | one version (the oldest available), 1 January 2013 |
| `821-32-11-rep/` | Règlement sur l'eau potable (RSF 821.32.11) | 1 | one version (the oldest available), 1 September 2014 |
| `821-40-76-oceica-covid-19/` | Ordonnance complémentaire sur les indemnités pour cas de rigueur accordées aux entreprises individuelles dans les cas de cessation d'activité (RSF 821.40.76) | 1 | one version (the oldest available), 1 August 2025 |
| `821-44-22/` | Ordonnance sur la Commission cantonale des addictions (RSF 821.44.22) | 2 | oldest version available, then each consolidated version: 1 July 2014 to 1 February 2022 |
| `821-44-41/` | Ordonnance sur l'utilisation du fonds pour la lutte contre les toxicomanies (RSF 821.44.41) | 2 | oldest version available, then each consolidated version: 1 July 2015 to 1 February 2022 |
| `821-45-21/` | Ordonnance concernant la vaccination contre le papillomavirus humain (RSF 821.45.21) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2019 |
| `821-45-112/` | Ordonnance DSAS concernant les vaccinations par les pharmaciens et pharmaciennes (RSF 821.45.112) | 3 | oldest version available, then each consolidated version: 1 July 2015 to 1 January 2024 |
| `822-0-21/` | Ordonnance fixant la liste des hôpitaux et des maisons de naissance (RSF 822.0.21) | 3 | oldest version available, then each consolidated version: 1 January 2017 to 1 March 2023 |
| `822-0-33/` | Ordonnance fixant la part cantonale à la rémunération des prestations hospitalières pour l'année 2026 (RSF 822.0.33) | 5 | oldest version available, then each consolidated version: 1 January 2023 to 1 January 2027 |
| `822-0-37/` | Ordonnance fixant les tarifs de référence des hôpitaux et des maisons de naissance (RSF 822.0.37) | 9 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `822-0-38/` | Ordonnance fixant un forfait provisoire pour l'utilisation de l'infrastructure lors d'accouchements ambulatoires en maison de naissance (RSF 822.0.38) | 1 | one version (the oldest available), 1 January 2012 |
| `822-2-12/` | Ordonnance relative aux médecins de l'Hôpital psychiatrique cantonal et des services de soins psychiatriques cantonaux (RSF 822.2.12) | 1 | one version (the oldest available), 1 January 2004 |
| `823-12/` | Ordonnance fixant le montant de l'indemnité forfaitaire en matière d'aide et de soins à domicile (RSF 823.12) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2024 |
| `823-112/` | Ordonnance DSAS fixant l'horaire d'intervention des services d'aide et de soins à domicile (RSF 823.112) | 1 | one version (the oldest available), 1 April 2006 |
| `831-0-11-relasoc/` | Règlement d'exécution de la loi sur l'aide sociale (RSF 831.0.11) | 3 | oldest version available, then each consolidated version: 1 August 2012 to 1 February 2025 |
| `831-0-12/` | Ordonnance fixant les normes de calcul de l'aide matérielle de la loi sur l'aide sociale (RSF 831.0.12) | 4 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2025 |
| `831-0-21/` | Ordonnance concernant la création d'un Fonds cantonal de l'action sociale (RSF 831.0.21) | 3 | oldest version available, then each consolidated version: 1 May 2010 to 1 January 2025 |
| `831-0-22/` | Ordonnance instituant un prix de l'Etat de Fribourg pour le travail social et pour le travail auprès de la jeunesse (RSF 831.0.22) | 1 | one version (the oldest available), 1 April 2009 |
| `831-0-51/` | Ordonnance concernant la création d'un Fonds de désendettement en faveur des personnes physiques (RSF 831.0.51) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2020 |
| `831-0-52/` | Ordonnance concernant les modalités d'utilisation du Fonds de désendettement en faveur des personnes physiques (RSF 831.0.52) | 1 | one version (the oldest available), 1 January 2006 |
| `831-0-61/` | Ordonnance concernant la création d'un Fonds cantonal de prévention et de lutte contre le jeu excessif (RSF 831.0.61) | 1 | one version (the oldest available), 1 January 2014 |
| `834-1-21-rifap/` | Règlement sur les institutions spécialisées et les familles d'accueil professionnelles (RSF 834.1.21) | 3 | oldest version available, then each consolidated version: 1 January 2003 to 1 February 2022 |
| `834-2-12/` | Ordonnance sur les besoins en soins et en accompagnement (RSF 834.2.12) | 1 | one version (the oldest available), 1 January 2018 |
| `834-2-41/` | Ordonnance fixant la liste des établissements médico-sociaux du canton de Fribourg (RSF 834.2.41) | 10 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `835-11-rste/` | Règlement sur les structures d'accueil extrafamilial de jour (RSF 835.11) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 August 2023 |
| `835-51-rej/` | Règlement sur l'enfance et la jeunesse (RSF 835.51) | 1 | one version (the oldest available), 1 January 2015 |
| `836-11-rafc/` | Règlement d'exécution de la loi du 26 septembre 1990 sur les allocations familiales (RSF 836.11) | 1 | one version (the oldest available), 1 January 2017 |
| `836-13/` | Ordonnance fixant le taux des cotisations dues à la Caisse cantonale de compensation pour allocations familiales (RSF 836.13) | 7 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `836-14/` | Ordonnance fixant les montants des allocations familiales (RSF 836.14) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2020 |
| `836-31-ramat/` | Règlement sur les allocations de maternité (RSF 836.31) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `836-41-rpcfam/` | Règlement d'application de la loi sur les prestations complémentaires pour les familles (RSF 836.41) | 1 | one version (the oldest available), 1 January 2026 |
| `838-32/` | Ordonnance concernant les services d'information et de conseil en matière d'analyse prénatale (RSF 838.32) | 1 | one version (the oldest available), 1 January 2012 |
| `841-1-11/` | Règlement d'exécution de la loi d'application de la loi fédérale sur l'assurance-vieillesse et survivants et de la loi fédérale sur l'assurance-invalidité (RSF 841.1.11) | 1 | one version (the oldest available), 1 January 2003 |
| `841-1-22/` | Règlement sur les agences communales de la Caisse cantonale de compensation AVS (RSF 841.1.22) | 2 | oldest version available, then each consolidated version: 1 October 2014 to 1 July 2019 |
| `841-3-21-ompcf/` | Ordonnance relative au remboursement des frais de maladie et d'invalidité en matière de prestations complémentaires (RSF 841.3.21) | 4 | oldest version available, then each consolidated version: 1 July 2012 to 11 May 2022 |
| `841-4-12/` | Ordonnance relative à la surveillance des institutions de prévoyance professionnelle (RSF 841.4.12) | 1 | one version (the oldest available), 1 January 2012 |
| `842-1-13-orp/` | Ordonnance concernant la réduction des primes d'assurance-maladie (RSF 842.1.13) | 5 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `842-1-15-olam/` | Ordonnance concernant la limitation de l'admission des médecins à pratiquer à charge de l'assurance obligatoire des soins (RSF 842.1.15) | 5 | oldest version available, then each consolidated version: 1 July 2016 to 1 July 2025 |
| `842-1-19/` | Ordonnance fixant le tarif provisoire applicable pour les prestations de psychothérapie psychologique (RSF 842.1.19) | 1 | one version (the oldest available), 1 July 2022 |
| `842-1-20/` | Ordonnance concernant l'application de l'article 37 de la loi fédérale sur l'assurance-maladie (RSF 842.1.20) | 1 | one version (the oldest available), 1 May 2023 |
| `842-1-21/` | Ordonnance fixant le tarif provisoire applicable pour les prestations ambulatoires de physiothérapie (RSF 842.1.21) | 2 | oldest version available, then each consolidated version: 1 January 2025 to 1 January 2026 |
| `842-1-23/` | Ordonnance fixant le tarif cadre conformément à l'article 48 LAMal pour la communauté d'achat HSK SA (RSF 842.1.23) | 1 | one version (the oldest available), 1 January 2016 |
| `842-1-24/` | Ordonnance fixant le tarif provisoire TARDOC et forfaits ambulatoires (RSF 842.1.24) | 1 | one version (the oldest available), 1 January 2026 |
| `842-1-72/` | Ordonnance fixant les modalités de perception des frais relatifs à l'assurance-maladie obligatoire ainsi que des loyers et des charges locatives pour les personnes du domaine de l'asile (RSF 842.1.72) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 January 2026 |
| `842-1-611/` | Ordonnance DSAS concernant la participation financière de l'Etat aux hospitalisations hors canton (RSF 842.1.611) | 1 | one version (the oldest available), 1 February 2012 |
| `842-2-41/` | Règlement sur l'utilisation du fonds résultant de la dissolution de l'assurance scolaire contre les accidents (RSF 842.2.41) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 September 2019 |
| `862-21/` | Règlement d'exécution de la loi instituant un Office de conciliation en matière de conflits collectifs de travail (RSF 862.21) | 1 | one version (the oldest available), 1 January 2012 |
| `864-7-31/` | Règlement concernant l'acétylène, l'oxygène et le carbure de calcium (RSF 864.7.31) | 1 | one version (the oldest available), 1 January 2003 |
| `866-1-11-remt/` | Règlement sur l'emploi et le marché du travail (RSF 866.1.11) | 4 | oldest version available, then each consolidated version: 1 August 2012 to 1 February 2022 |
| `866-2-12/` | Ordonnance concernant l'attribution de la main-d'oeuvre étrangère (RSF 866.2.12) | 3 | oldest version available, then each consolidated version: 1 August 2012 to 1 February 2022 |
| `866-2-16/` | Ordonnance fixant les émoluments pour l'octroi d'autorisations de travail à des étrangers (RSF 866.2.16) | 3 | oldest version available, then each consolidated version: 1 March 2013 to 1 July 2022 |
| `900-11-rpec/` | Règlement sur la promotion économique (RSF 900.11) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 February 2022 |
| `900-12/` | Règlement relatif au Fonds institué par la loi sur la promotion économique (RSF 900.12) | 2 | oldest version available, then each consolidated version: 1 July 2008 to 1 February 2022 |
| `910-11-ragri/` | Règlement sur l'agriculture (RSF 910.11) | 5 | oldest version available, then each consolidated version: 1 July 2014 to 1 January 2023 |
| `910-311/` | Ordonnance DIAF sur les préposés locaux à l'agriculture (RSF 910.311) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2022 |
| `911-10-11-rgn/` | Règlement sur Grangeneuve (RSF 911.10.11) | 3 | oldest version available, then each consolidated version: 1 July 2007 to 1 January 2022 |
| `911-10-16-oegn/` | Ordonnance fixant les écolages, les taxes et autres frais en matière de prestations de formation de Grangeneuve (RSF 911.10.16) | 2 | oldest version available, then each consolidated version: 1 July 2009 to 1 January 2022 |
| `912-4-111/` | Ordonnance DIAF sur la vigne et le vin (RSF 912.4.111) | 5 | oldest version available, then each consolidated version: 1 July 2018 to 1 January 2027 |
| `912-4-112/` | Ordonnance DIAF sur l'organisation et le fonctionnement de la Commission de dégustation des vins d'appellation d'origine contrôlée (RSF 912.4.112) | 2 | oldest version available, then each consolidated version: 1 October 2009 to 1 January 2022 |
| `912-5-112/` | Ordonnance DIAF instituant des mesures de lutte contre le feu bactérien (RSF 912.5.112) | 3 | oldest version available, then each consolidated version: 1 April 2007 to 1 January 2022 |
| `912-5-113/` | Ordonnance DIAF instituant des mesures de lutte contre le chardon des champs (RSF 912.5.113) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2022 |
| `912-5-114/` | Ordonnance DIAF instituant des mesures de lutte en cas d'attaque par le capricorne asiatique (RSF 912.5.114) | 3 | oldest version available, then each consolidated version: 1 February 2015 to 1 November 2024 |
| `913-4-311/` | Ordonnance DIAF concernant la zone de protection de la station de fécondation du Petit-Mont (RSF 913.4.311) | 1 | one version (the oldest available), 1 July 2012 |
| `913-4-312/` | Ordonnance DIAF concernant la zone de protection de la station de fécondation de l'Hongrin (VD) (RSF 913.4.312) | 1 | one version (the oldest available), 1 July 2012 |
| `913-4-313/` | Ordonnance DIAF concernant la zone de protection de la station de fécondation de la Dent-de-Lys (RSF 913.4.313) | 1 | one version (the oldest available), 1 July 2013 |
| `914-10-11-oepiz/` | Ordonnance sur les épizooties (RSF 914.10.11) | 5 | oldest version available, then each consolidated version: 1 September 2014 to 1 October 2026 |
| `914-10-17/` | Ordonnance fixant le tarif des indemnités versées aux vétérinaires pour la lutte contre les épizooties et les vacations officielles pour Sanima (RSF 914.10.17) | 1 | one version (the oldest available), 1 May 2014 |
| `914-10-66/` | Ordonnance fixant les primes et les taxes pour l'élimination des déchets animaux (RSF 914.10.66) | 2 | oldest version available, then each consolidated version: 1 May 2017 to 1 March 2023 |
| `914-10-67/` | Ordonnance modifiant le plan de couverture des besoins en centres collecteurs de déchets animaux (RSF 914.10.67) | 1 | one version (the oldest available), 1 December 2011 |
| `914-10-112/` | Ordonnance DIAF fixant le statut des membres de l'équipe d'intervention en cas d'épizootie (RSF 914.10.112) | 2 | oldest version available, then each consolidated version: 1 March 2015 to 1 October 2023 |
| `914-10-411/` | Ordonnance DIAF sur les conditions d'estivage (RSF 914.10.411) | 2 | oldest version available, then each consolidated version: 1 April 2016 to 1 July 2019 |
| `914-14-211/` | Ordonnance sur les inspecteurs et inspectrices des ruchers (RSF 914.14.211) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2020 |
| `914-20-11-oaar/` | Ordonnance d'exécution de la loi sur l'assurance des animaux de rente (RSF 914.20.11) | 1 | one version (the oldest available), 1 May 2017 |
| `914-20-15/` | Ordonnance fixant, pour la période annuelle d'assurance, les primes dues à Sanima et les montants maximaux de la valeur estimative des espèces assurées (RSF 914.20.15) | 3 | oldest version available, then each consolidated version: 1 May 2017 to 1 March 2021 |
| `915-11/` | Ordonnance pour le soutien des installations de récupération de chaleur dans l'agriculture (RSF 915.11) | 2 | oldest version available, then each consolidated version: 1 January 2023 to 1 July 2026 |
| `915-12/` | Ordonnance pour des contributions aux cultures de légumineuses destinées à l'alimentation humaine (RSF 915.12) | 1 | one version (the oldest available), 10 September 2024 |
| `917-11/` | Règlement d'exécution de la loi sur les améliorations foncières (RSF 917.11) | 4 | oldest version available, then each consolidated version: 1 March 2007 to 1 March 2024 |
| `921-11-rfcn/` | Règlement sur les forêts et la protection contre les catastrophes naturelles (RSF 921.11) | 7 | oldest version available, then each consolidated version: 1 March 2016 to 1 January 2025 |
| `921-12/` | Ordonnance concernant la lutte contre le bostryche (RSF 921.12) | 2 | oldest version available, then each consolidated version: 1 March 2005 to 1 April 2019 |
| `921-16/` | Ordonnance concernant les subventions cantonales aux forêts et à la protection contre les catastrophes naturelles (RSF 921.16) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `921-27/` | Règlement relatif aux indemnités spéciales versées au personnel du Service des forêts et de la nature (RSF 921.27) | 4 | oldest version available, then each consolidated version: 1 July 2014 to 1 January 2024 |
| `921-111/` | Ordonnance DIAF fixant la délimitation des arrondissements forestiers (RSF 921.111) | 3 | oldest version available, then each consolidated version: 1 April 2017 to 1 January 2026 |
| `922-11-ocha/` | Ordonnance concernant la chasse (RSF 922.11) | 11 | oldest version available, then each consolidated version: 1 July 2017 to 1 August 2025 |
| `922-12/` | Règlement concernant l'examen d'aptitude à la chasse (RSF 922.12) | 5 | oldest version available, then each consolidated version: 1 February 2015 to 1 March 2026 |
| `922-13-oprot/` | Ordonnance concernant la protection des mammifères, des oiseaux sauvages et de leurs biotopes (RSF 922.13) | 4 | oldest version available, then each consolidated version: 1 June 2019 to 1 April 2025 |
| `922-14/` | Ordonnance concernant la chasse du sanglier (RSF 922.14) | 8 | oldest version available, then each consolidated version: 1 June 2019 to 1 June 2026 |
| `922-15-otir/` | Ordonnance concernant les tirs de régulation dans les zones protégées (RSF 922.15) | 2 | oldest version available, then each consolidated version: 1 October 2022 to 1 July 2024 |
| `922-21-osurv/` | Ordonnance sur la surveillance de la faune et de la flore, de la chasse et de la pêche (RSF 922.21) | 4 | oldest version available, then each consolidated version: 1 July 2016 to 1 January 2024 |
| `922-31/` | Ordonnance concernant la zone de tranquillité de La Berra (RSF 922.31) | 4 | oldest version available, then each consolidated version: 1 December 2017 to 1 July 2027 |
| `922-111-oplan-2026/` | Ordonnance DIAF concernant la planification de la chasse pour la saison 2026 (RSF 922.111) | 10 | oldest version available, then each consolidated version: 1 July 2018 to 1 July 2026 |
| `922-112/` | Ordonnance DIAF concernant les limites des secteurs de faune (RSF 922.112) | 2 | oldest version available, then each consolidated version: 1 January 2004 to 1 April 2019 |
| `922-121/` | Ordonnance DIAF concernant les épreuves et les conditions de réussite de l'examen d'aptitude à la chasse (RSF 922.121) | 2 | oldest version available, then each consolidated version: 1 November 2021 to 1 March 2026 |
| `922-212/` | Ordonnance DIAF concernant la division du canton en régions de surveillance de la faune, de la flore, de la chasse et de la pêche (RSF 922.212) | 2 | oldest version available, then each consolidated version: 1 July 2009 to 1 April 2019 |
| `923-12-opeche/` | Ordonnance sur l'exercice de la pêche à permis en 2025, 2026 et 2027 (RSF 923.12) | 3 | oldest version available, then each consolidated version: 1 January 2022 to 1 January 2026 |
| `923-13/` | Ordonnance sur l'aide financière aux pêcheurs professionnels pour les années 2025, 2026 et 2027 (RSF 923.13) | 3 | oldest version available, then each consolidated version: 1 January 2020 to 1 January 2025 |
| `923-15-oaff/` | Ordonnance fixant les conditions de mise aux enchères et d'affermage des lots de pêche pour la période 2022-2027 (RSF 923.15) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2022 |
| `923-17-oelevage/` | Ordonnance déterminant les cours d'eau affectés à l'élevage pour la période 2022–2027 (RSF 923.17) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2022 |
| `923-171/` | Ordonnance DIAF concernant les cours d'eau mis à la disposition de sociétés de pêche pour l'élevage et le suivi du frai naturel durant les années 2022–2027 (RSF 923.171) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2022 |
| `940-11-rcom/` | Règlement sur l'exercice du commerce (RSF 940.11) | 5 | oldest version available, then each consolidated version: 16 February 2016 to 1 June 2024 |
| `940-15/` | Ordonnance permettant à certains types de commerces d'employer du personnel sans autorisation durant deux dimanches ou jours fériés par année (RSF 940.15) | 1 | one version (the oldest available), 1 October 2012 |
| `940-21/` | Ordonnance sur l'exercice de la prostitution (RSF 940.21) | 2 | oldest version available, then each consolidated version: 1 July 2015 to 1 February 2022 |
| `941-21/` | Règlement d'exécution de la loi du 6 novembre 1986 sur les réclames (RSF 941.21) | 1 | one version (the oldest available), 1 January 2003 |
| `947-6-11/` | Ordonnance sur les armes, les accessoires d'armes et les munitions (RSF 947.6.11) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 February 2022 |
| `951-11-rt/` | Règlement sur le tourisme (RSF 951.11) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2022 |
| `951-16-otls/` | Ordonnance fixant les taxes locales de séjour (RSF 951.16) | 1 | one version (the oldest available), 1 January 2007 |
| `952-11-repu/` | Règlement sur les établissements publics (RSF 952.11) | 4 | oldest version available, then each consolidated version: 1 January 2017 to 1 July 2024 |
| `957-11/` | Ordonnance d'application de la loi fédérale sur les guides de montagne et les organisateurs d'autres activités à risque (RSF 957.11) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 30 June 2025 |
| `958-11-oajar/` | Ordonnance sur les jeux d'argent (RSF 958.11) | 3 | oldest version available, then each consolidated version: 1 January 2003 to 1 November 2023 |
| `958-31/` | Ordonnance concernant la répartition des bénéfices nets de la Société de la Loterie de la Suisse romande (RSF 958.31) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2025 |

## Additional current texts

These 201 instruments each have one current consolidated corpus version, credited to the official publisher. Earlier wording is not asserted. RSF 122.91.3 is not included because four glyphs in the official PDF cannot be decoded reliably.

| Act | Title | Versions | Coverage |
| --- | --- | ---: | --- |
| `28-81/` | Traité entre le Grand-Duché de Bade et la Confédération suisse sur la réciprocité de droit en matière de concours (RSF 28.81) | 1 | current consolidated text, 1808-07-09 |
| `28-82/` | Convention entre la Confédération suisse et la Couronne de Wurtemberg sur les faillites et l’égalité qui doit être observée, en fait de collocation, entre les créanciers ressortissant à l’un ou à l’autre des deux pays (RSF 28.82) | 1 | current consolidated text, 1826-05-13 |
| `28-83/` | Convention entre des cantons suisses et le Royaume de Bavière portant que les ressortissants respectifs seront traités à droits égaux dans les cas de concours juridiques (RSF 28.83) | 1 | current consolidated text, 1834-06-27 |
| `28-84/` | Convention entre des cantons suisses et le Royaume de Saxe au sujet de l’égalité de droit des ressortissants respectifs dans les concours par suite des faillites (RSF 28.84) | 1 | current consolidated text, 1837-02-18 |
| `31-16/` | Tarif relatif à la participation financière des personnes astreintes à un programme de prévention de la violence (RSF 31.16) | 1 | current consolidated text, 2025-03-01 |
| `44-6/` | Accord intercantonal sur l’harmonisation des régimes de bourses d’études (RSF 44.6) | 1 | current consolidated text, 2013-03-01 |
| `76-16/` | Tarif des frais de procédure en matière d'expropriation (RSF 76.16) | 1 | current consolidated text, 2022-02-01 |
| `76-17/` | Tarif des dépens en matière d'expropriation (RSF 76.17) | 1 | current consolidated text, 2022-02-01 |
| `76-61/` | Arrêté relatif à l'exécution de la loi fédérale du 20 juin 1930 sur l'expropriation (RSF 76.61) | 1 | current consolidated text, 1992-01-01 |
| `87-27/` | Arrêté concernant le loyer des logements à caractère social construits par des personnes à l'étranger (RSF 87.27) | 1 | current consolidated text, 2003-01-01 |
| `112-8/` | Concordat sur la modification territoriale résultant du transfert de la commune municipale bernoise de Clavaleyres au canton de Fribourg (RSF 112.8) | 1 | current consolidated text, 2022-01-01 |
| `112-9/` | Convention d'exécution entre le canton de Berne et le canton de Fribourg relative au transfert de la commune de Clavaleyres au canton de Fribourg (RSF 112.9) | 1 | current consolidated text, 2022-01-01 |
| `113-31/` | Arrêté concernant la reconnaissance officielle des armoiries des districts et des communes (RSF 113.31) | 1 | current consolidated text, 1943-07-06 |
| `114-21-16/` | Arrêté fixant les émoluments en matière de contrôle des habitants (RSF 114.21.16) | 1 | current consolidated text, 2010-07-01 |
| `121-3/` | Loi concernant les conventions intercantonales (RSF 121.3) | 1 | current consolidated text, 2024-01-01 |
| `121-4/` | Convention relative à la participation des Parlements cantonaux dans le cadre de l’élaboration, de la ratification, de l’exécution et de la modification des conventions intercantonales et des traités des cantons avec l’étranger (RSF 121.4) | 1 | current consolidated text, 2011-01-01 |
| `121-5/` | Accord-cadre pour la collaboration intercantonale assortie d’une compensation des charges (RSF 121.5) | 1 | current consolidated text, 2007-05-11 |
| `122-0-11/` | Arrêté répartissant les Directions du Conseil d'Etat et formant ses délégations (RSF 122.0.11) | 1 | current consolidated text, 2023-03-14 |
| `122-0-16/` | Directive concernant la représentation de l'Etat au sein des entreprises (gouvernance d'entreprise publique) (RSF 122.0.16) | 1 | current consolidated text, 2017-01-01 |
| `122-0-511/` | Directives CHA relatives à l'information et à la communication (RSF 122.0.511) | 1 | current consolidated text, 2022-02-01 |
| `122-3-61/` | Tarif concernant les émoluments de préfecture (RSF 122.3.61) | 1 | current consolidated text, 1992-01-01 |
| `122-70-51/` | Directive concernant l'Annuaire téléphonique des collaborateurs et collaboratrices de l'Etat (RSF 122.70.51) | 1 | current consolidated text, 2016-11-01 |
| `122-72-15/` | Arrêté relatif à l'unification des dates de paie des traitements du personnel de l'Etat (RSF 122.72.15) | 1 | current consolidated text, 2003-01-01 |
| `122-72-16/` | Arrêté concernant le maintien de l'octroi de l'allocation pour personnes à charge, dans les situations de rigueur (RSF 122.72.16) | 1 | current consolidated text, 2003-01-01 |
| `122-72-23/` | Arrêté relatif à la fixation des traitements initiaux du personnel de l'Etat (RSF 122.72.23) | 1 | current consolidated text, 1994-03-01 |
| `122-72-24/` | Arrêté fixant le système d'évaluation des fonctions du personnel de l'Etat (RSF 122.72.24) | 1 | current consolidated text, 2003-01-01 |
| `122-91-2/` | Accord intercantonal de 1994 sur les marchés publics (RSF 122.91.2) | 1 | current consolidated text, 2010-07-01 |
| `122-93-16/` | Tarif des frais et honoraires perçus par la Commission d'acquisition des immeubles (RSF 122.93.16) | 1 | current consolidated text, 2012-01-01 |
| `122-98-11/` | Arrêté concernant l'attribution et la gestion des places de stationnement pour voitures (RSF 122.98.11) | 1 | current consolidated text, 2022-02-01 |
| `126-21/` | Tarif des émoluments administratifs (RSF 126.21) | 1 | current consolidated text, 2026-01-01 |
| `129-1-1/` | Décret relatif au serment des fonctionnaires de l'Etat (RSF 129.1.1) | 1 | current consolidated text, 2008-01-01 |
| `129-2-1/` | Décret déterminant les sceaux des autorités supérieures (RSF 129.2.1) | 1 | current consolidated text, 2008-01-01 |
| `129-3-1/` | Décret fixant le rang des autorités supérieures dans les cérémonies publiques (RSF 129.3.1) | 1 | current consolidated text, 2008-01-01 |
| `129-3-21/` | Arrêté fixant le rang des autorités subalternes dans les cérémonies publiques (RSF 129.3.21) | 1 | current consolidated text, 2011-01-01 |
| `129-3-31/` | Arrêté déclarant le Contingent des grenadiers fribourgeois garde d'honneur officielle des autorités supérieures du canton de Fribourg (RSF 129.3.31) | 1 | current consolidated text, 2022-02-01 |
| `129-3-41/` | Arrêté concernant la formation d'un corps de musique volontaire de Landwehr (RSF 129.3.41) | 1 | current consolidated text, 1879-02-10 |
| `129-4-11/` | Arrêté concernant les cartes de légitimation pour magistrats et collaborateurs de l'Etat (RSF 129.4.11) | 1 | current consolidated text, 2011-01-01 |
| `130-16/` | Tarif du Tribunal cantonal des émoluments pour les contestations portant sur des affaires pécuniaires (RSF 130.16) | 1 | current consolidated text, 2016-02-01 |
| `130-421/` | Directives du Tribunal cantonal sur le préarchivage des dossiers judiciaires et leur versement aux Archives (RSF 130.421) | 1 | current consolidated text, 2022-01-01 |
| `140-13/` | Arrêté désignant les préfets et préfètes suppléants chargés de la surveillance des associations de communes (RSF 140.13) | 1 | current consolidated text, 2023-10-01 |
| `150-1/` | Code de procédure et de juridiction administrative (RSF 150.1) | 1 | current consolidated text, 2026-10-01 |
| `150-12/` | Tarif des frais de procédure et des indemnités en matière de juridiction administrative (RSF 150.12) | 1 | current consolidated text, 2015-07-01 |
| `150-421/` | Directives du Tribunal administratif sur le préarchivage des dossiers judiciaires et leur versement aux Archives de l'Etat (RSF 150.421) | 1 | current consolidated text, 2002-07-01 |
| `190-5/` | Convention cadre sur l'exercice des aumôneries catholique romaine et évangélique réformée dans les établissements de l'Etat (RSF 190.5) | 1 | current consolidated text, 2008-07-01 |
| `191-0-11/` | Statut des corporations ecclésiastiques catholiques du canton de Fribourg (RSF 191.0.11) | 1 | current consolidated text, 2024-01-01 |
| `191-22-2/` | Convention relative à la propriété et à l'entretien de l'église collégiale de St-Nicolas (RSF 191.22.2) | 1 | current consolidated text, 1874-02-20 |
| `191-23-31/` | Arrêté concernant l'érection de la Fondation d'Hauterive (RSF 191.23.31) | 1 | current consolidated text, 2022-02-01 |
| `192-6/` | Convention réglant d’une manière plus précise les rapports ecclésiastiques des communes mixtes de Ferenbalm, Chiètres et Morat (RSF 192.6) | 1 | current consolidated text, 1959-03-13 |
| `192-11/` | Constitution ecclésiastique de l'Eglise évangélique réformée du canton de Fribourg (RSF 192.11) | 1 | current consolidated text, 2011-11-16 |
| `193-2/` | Convention cadre sur l'exercice de l'aumônerie israélite dans les établissements de l'Etat (RSF 193.2) | 1 | current consolidated text, 2009-06-01 |
| `193-11/` | Statut de la Communauté israélite du canton de Fribourg (RSF 193.11) | 1 | current consolidated text, 2008-01-01 |
| `193-16/` | Arrêté concernant le montant alloué à la Communauté israélite du canton de Fribourg en compensation de sa part annuelle à l'impôt sur les personnes morales et à l'impôt prélevé à la source (RSF 193.16) | 1 | current consolidated text, 2003-01-01 |
| `210-113/` | Directives DSJ sur la vente de choses trouvées (RSF 210.113) | 1 | current consolidated text, 2015-12-02 |
| `214-5-16/` | Tarif des émoluments fixes du registre foncier (RSF 214.5.16) | 1 | current consolidated text, 2018-12-01 |
| `214-12-13/` | Arrêté fixant les lieux à vocation touristique selon la législation sur l'acquisition d'immeubles par des personnes à l'étranger (RSF 214.12.13) | 1 | current consolidated text, 1999-10-05 |
| `222-5-92/` | Arrêté établissant le contrat-type de travail dans l'agriculture (RSF 222.5.92) | 1 | current consolidated text, 2011-01-01 |
| `261-16/` | Tarif des émoluments des notaires (RSF 261.16) | 1 | current consolidated text, 2016-07-01 |
| `261-162/` | Tarif de l'Association des notaires relatif aux honoraires dus pour les opérations annexes (RSF 261.162) | 1 | current consolidated text, 2005-07-01 |
| `342-1/` | Concordat sur l’exécution des peines privatives de liberté et des mesures concernant les adultes et les jeunes adultes dans les cantons latins (RSF 342.1) | 1 | current consolidated text, 2007-11-01 |
| `342-2/` | Convention entre le canton de Berne et les cantons de Fribourg, Vaud, Valais, Neuchâtel, Genève et Tessin concernant l’exécution des peines et mesures prononcées contre des femmes par les tribunaux de ces six derniers cantons aux Etablissements de Hindelbank (RSF 342.2) | 1 | current consolidated text, 1978-05-01 |
| `342-3/` | Concordat sur l’exécution de la détention pénale des personnes mineures des cantons romands (et partiellement du Tessin) (RSF 342.3) | 1 | current consolidated text, 2018-07-01 |
| `410-4/` | Accord intercantonal sur la reconnaissance des diplômes de fin d’études (RSF 410.4) | 1 | current consolidated text, 2017-01-01 |
| `410-5/` | Convention intercantonale réglant la fréquentation d’une école située dans un canton autre que celui de domicile (RSF 410.5) | 1 | current consolidated text, 2006-09-01 |
| `411-0-24/` | Convention sur l’exercice de l’enseignement religieux catholique romain dans la scolarité obligatoire (RSF 411.0.24) | 1 | current consolidated text, 2009-09-01 |
| `411-0-25/` | Convention sur l’exercice de l’enseignement religieux évangélique réformé dans la scolarité obligatoire (RSF 411.0.25) | 1 | current consolidated text, 2009-09-01 |
| `411-0-71/` | Arrêté sur l'éducation routière à l'école (RSF 411.0.71) | 1 | current consolidated text, 2022-02-01 |
| `412-0-17/` | Arrêté fixant les taxes d'examens finals des écoles du secondaire du deuxième degré (RSF 412.0.17) | 1 | current consolidated text, 2026-01-01 |
| `412-0-42/` | Arrêté sur les indemnités dues aux membres des jurys des examens finals des écoles du secondaire du deuxième degré (RSF 412.0.42) | 1 | current consolidated text, 2022-02-01 |
| `412-1-8/` | Convention intercantonale sur la création et l’exploitation du Gymnase intercantonal de la Broye (RSF 412.1.8) | 1 | current consolidated text, 2024-01-01 |
| `416-1/` | Concordat sur la coordination scolaire (RSF 416.1) | 1 | current consolidated text, 1971-07-06 |
| `416-2/` | Accord intercantonal sur l’harmonisation de la scolarité obligatoire (RSF 416.2) | 1 | current consolidated text, 2010-05-01 |
| `416-3/` | Convention scolaire romande adoptée par la Conférence intercantonale de l’instruction publique de la Suisse romande et du Tessin (RSF 416.3) | 1 | current consolidated text, 2009-08-01 |
| `416-4/` | Convention scolaire régionale concernant l’accueil réciproque d’élèves et le versement de contributions (RSF 416.4) | 1 | current consolidated text, 2009-08-01 |
| `416-5/` | Accord intercantonal sur la collaboration dans le domaine de la pédagogie spécialisée (RSF 416.5) | 1 | current consolidated text, 2011-01-01 |
| `416-6/` | Accord intercantonal sur les offres scolaires en milieu hospitalier (RSF 416.6) | 1 | current consolidated text, 2026-01-01 |
| `420-81/` | Statuts de l'Association du Centre professionnel cantonal (ACPC) (RSF 420.81) | 1 | current consolidated text, 2021-09-21 |
| `427-1/` | Accord intercantonal sur les contributions dans le domaine de la formation professionnelle initiale (RSF 427.1) | 1 | current consolidated text, 2007-08-01 |
| `427-2/` | Accord intercantonal sur les contributions dans le domaine des écoles supérieures (RSF 427.2) | 1 | current consolidated text, 2015-06-01 |
| `430-1/` | Accord intercantonal sur le domaine suisse des hautes écoles (concordat sur les hautes écoles) (RSF 430.1) | 1 | current consolidated text, 2015-01-01 |
| `431-0-18/` | Convention entre les Evêques suisses, d’une part, et le Conseil d’Etat du canton de Fribourg, d’autre part, relative au développement de l’Université de Fribourg et à sa consolidation financière (RSF 431.0.18) | 1 | current consolidated text, 1978-06-20 |
| `431-0-26/` | Arrêté relatif à la rémunération des collaborateurs scientifiques et des sous-assistants (RSF 431.0.26) | 1 | current consolidated text, 2003-01-01 |
| `431-0-32/` | Accord relatif à la Faculté de théologie de l’Université de Fribourg (RSF 431.0.32) | 1 | current consolidated text, 1985-07-08 |
| `431-5-6/` | Accord intercantonal sur les contributions aux coûts de formation des hautes écoles universitaires (RSF 431.5.6) | 1 | current consolidated text, 2022-07-01 |
| `432-0-3/` | Accord intercantonal sur les hautes écoles spécialisées (AHES) à partir de 2005 (RSF 432.0.3) | 1 | current consolidated text, 2005-11-01 |
| `432-11-1/` | Convention intercantonale sur la Haute Ecole spécialisée de Suisse occidentale (RSF 432.11.1) | 1 | current consolidated text, 2013-01-01 |
| `432-11-2/` | Convention intercantonale relative au contrôle parlementaire sur la Haute Ecole spécialisée de Suisse occidentale (HES-SO) (RSF 432.11.2) | 1 | current consolidated text, 2005-01-01 |
| `481-5-15/` | Arrêté concernant le Fonds Jean Tinguely–Niki de Saint Phalle (RSF 481.5.15) | 1 | current consolidated text, 2022-02-01 |
| `482-42/` | Arrêté instituant une commission du recensement du patrimoine artistique (RSF 482.42) | 1 | current consolidated text, 2022-02-01 |
| `482-43/` | Arrêté relatif à la conservation du patrimoine architectural alpestre (RSF 482.43) | 1 | current consolidated text, 2022-02-01 |
| `482-44/` | Arrêté instituant une commission du recensement des chalets d'alpage (RSF 482.44) | 1 | current consolidated text, 2022-02-01 |
| `511-52/` | Arrêté concernant l'attribution des compétences en matière de sanctions disciplinaires militaires (RSF 511.52) | 1 | current consolidated text, 2022-12-01 |
| `514-21/` | Arrêté sur l'aide financière accordée aux sociétés de tir (RSF 514.21) | 1 | current consolidated text, 2022-12-01 |
| `550-2/` | Convention entre la Confédération et les cantons relative à la mise en oeuvre, à l’application et au développement de l’acquis de Schengen et de Dublin (RSF 550.2) | 1 | current consolidated text, 2009-04-01 |
| `551-21/` | Décret fixant l'effectif des agents et agentes de la Police cantonale (RSF 551.21) | 1 | current consolidated text, 2022-01-01 |
| `551-78/` | Arrêté relatif à la participation de l'Etat aux frais de l'assurance-maladie des agents de la force publique (régime transitoire) (RSF 551.78) | 1 | current consolidated text, 2022-02-01 |
| `551-181/` | Directives DSJ sur la durée de conservation et l'élimination des données de police (RSF 551.181) | 1 | current consolidated text, 2009-05-01 |
| `559-2/` | Convention sur les engagements de police intercantonaux (RSF 559.2) | 1 | current consolidated text, 2025-01-01 |
| `559-3/` | Concordat réglant la coopération en matière de police en Suisse romande (RSF 559.3) | 1 | current consolidated text, 2017-01-01 |
| `559-4/` | Convention entre la Confédération et les cantons sur l’harmonisation et la mise à disposition commune de la technique et de l’informatique policières en Suisse (RSF 559.4) | 1 | current consolidated text, 2021-01-01 |
| `559-5/` | Convention relative aux transports de police (RSF 559.5) | 1 | current consolidated text, 1910-01-01 |
| `559-6/` | Concordat sur les entreprises de sécurité (RSF 559.6) | 1 | current consolidated text, 2025-01-04 |
| `559-7/` | Loi portant adhésion du canton de Fribourg au concordat instituant des mesures contre la violence lors de manifestations sportives (RSF 559.7) | 1 | current consolidated text, 2014-04-01 |
| `559-61/` | Arrêté d'exécution du concordat sur les entreprises de sécurité (RSF 559.61) | 1 | current consolidated text, 2022-02-01 |
| `559-71/` | Concordat instituant des mesures contre la violence lors de manifestations sportives (RSF 559.71) | 1 | current consolidated text, 2014-04-01 |
| `612-81/` | Arrêté relatif à la vérification des comptes des institutions de droit public (RSF 612.81) | 1 | current consolidated text, 1924-01-22 |
| `614-32/` | Tarif des honoraires perçus par l'Inspection des finances (RSF 614.32) | 1 | current consolidated text, 2009-01-01 |
| `631-16/` | Tarif des émoluments du Service cantonal des contributions (RSF 631.16) | 1 | current consolidated text, 2018-01-01 |
| `631-31/` | Arrêté sur l'imposition d'après la dépense (RSF 631.31) | 1 | current consolidated text, 2014-01-01 |
| `631-33/` | Arrêté concernant l'imposition des immeubles non agricoles (RSF 631.33) | 1 | current consolidated text, 2023-01-01 |
| `631-34/` | Arrêté concernant l’imposition des immeubles agricoles (RSF 631.34) | 1 | current consolidated text, 2001-01-01 |
| `631-36/` | Arrêté concernant l'imposition de la valeur locative du logement agricole (RSF 631.36) | 1 | current consolidated text, 2001-01-01 |
| `631-38/` | Arrêté sur l'inventaire fiscal au décès (RSF 631.38) | 1 | current consolidated text, 2016-01-01 |
| `634-1-11/` | Arrêté d'exécution de la loi fédérale sur l'impôt fédéral direct (RSF 634.1.11) | 1 | current consolidated text, 2016-01-01 |
| `635-1-11/` | Arrêté sur les droits de mutation et les droits sur les gages immobiliers (RSF 635.1.11) | 1 | current consolidated text, 1997-01-01 |
| `636-1/` | Concordat entre les cantons de la Confédération suisse sur l’interdiction des arrangements fiscaux (RSF 636.1) | 1 | current consolidated text, 1949-10-06 |
| `710-2/` | Décret fixant les principes généraux et les objectifs en matière d'aménagement du territoire (RSF 710.2) | 1 | current consolidated text, 2016-02-02 |
| `710-7/` | Accord intercantonal harmonisant la terminologie dans le domaine des constructions (RSF 710.7) | 1 | current consolidated text, 2015-05-01 |
| `710-12/` | Arrêté désignant les associations cantonales, non affiliées à une association d'importance nationale, habilitées à former opposition et recours (RSF 710.12) | 1 | current consolidated text, 2023-01-01 |
| `721-1-11/` | Arrêté concernant la protection de la faune et de la flore fribourgeoise (RSF 721.1.11) | 1 | current consolidated text, 2014-07-01 |
| `721-1-21/` | Arrêté relatif à la protection des escargots (RSF 721.1.21) | 1 | current consolidated text, 2019-04-01 |
| `721-1-53/` | Arrêté concernant la réserve mycologique Moosboden, sur le territoire de la commune de Cerniat, forêt domaniale du Höllbach (RSF 721.1.53) | 1 | current consolidated text, 2019-04-01 |
| `721-3-12/` | Arrêté concernant la réserve forestière des Vanils du Paradis et de la Fayère, sur le territoire de la commune d'Estavannens (RSF 721.3.12) | 1 | current consolidated text, 2019-04-01 |
| `731-3-12/` | Tarif des frais d'intervention des sapeurs-pompiers (RSF 731.3.12) | 1 | current consolidated text, 2024-01-01 |
| `741-9/` | Convention sur le Service intercantonal d’entretien du réseau autoroutier des cantons de Fribourg, de Vaud et de la République et canton de Genève (RSF 741.9) | 1 | current consolidated text, 2019-01-01 |
| `741-16/` | Tarif concernant l'utilisation des canalisations des routes cantonales pour l'évacuation des eaux (RSF 741.16) | 1 | current consolidated text, 2023-01-01 |
| `741-62/` | Décret relatif à l'application de l'article 66 de la loi du 15 décembre 1967 sur les routes (subventions) (RSF 741.62) | 1 | current consolidated text, 1988-10-04 |
| `743-7-2/` | Convention intercantonale concernant l’entretien et la surveillance en commun de l’oeuvre intercantonale de la IIe correction des eaux du Jura et la régularisation des eaux qui en font partie (RSF 743.7.2) | 1 | current consolidated text, 1986-02-04 |
| `743-7-3/` | Convention intercantonale entre les Etats de Fribourg et de Vaud pour l’entretien des corrections de la Glâne et du Fossé-Neuf (RSF 743.7.3) | 1 | current consolidated text, 1938-03-01 |
| `750-16/` | Ordonnance fixant les taxes et redevances pour l’utilisation du domaine public (RSF 750.16) | 1 | current consolidated text, 2026-01-01 |
| `750-21/` | Arrêté concernant l'utilisation du domaine public ou privé de l'Etat en vue de la construction de maisons de vacances (RSF 750.21) | 1 | current consolidated text, 2022-02-01 |
| `753-12/` | Arrêté concernant l'utilisation des rives des lacs par les particuliers (RSF 753.12) | 1 | current consolidated text, 2022-02-01 |
| `753-31/` | Arrêté instaurant des mesures concernant les maisons de vacances sur le domaine public et privé de l'Etat au bord du lac de Neuchâtel (RSF 753.31) | 1 | current consolidated text, 2022-02-01 |
| `773-11/` | Arrêté pour l'exécution de la loi fédérale sur l'utilisation des forces hydrauliques (RSF 773.11) | 1 | current consolidated text, 2022-02-01 |
| `775-2-11/` | Arrêté sur les installations de transport par conduites de combustibles ou carburants liquides ou gazeux non soumises à concession fédérale (RSF 775.2.11) | 1 | current consolidated text, 2012-01-01 |
| `775-2-12/` | Arrêté désignant l'organe de contrôle technique des installations de transport par conduites du gaz naturel non soumises à concession fédérale (RSF 775.2.12) | 1 | current consolidated text, 2012-01-01 |
| `781-11/` | Arrêté d'exécution de la loi d'application de la législation fédérale sur la circulation routière (RSF 781.11) | 1 | current consolidated text, 2022-07-01 |
| `781-16/` | Arrêté fixant les émoluments en matière de circulation routière (RSF 781.16) | 1 | current consolidated text, 2025-09-01 |
| `781-31/` | Arrêté concernant l'emploi de véhicules à moteur hors des routes (RSF 781.31) | 1 | current consolidated text, 2019-04-01 |
| `782-5/` | Décret concernant la constitution de la Compagnie des chemins de fer fribourgeois (RSF 782.5) | 1 | current consolidated text, 1949-11-25 |
| `784-2/` | Concordat concernant les installations de transport par câbles et skilifts sans concession fédérale (RSF 784.2) | 1 | current consolidated text, 1972-11-27 |
| `785-5/` | Convention intercantonale relative à l’organisation et à la gestion de la police du lac de Neuchâtel (RSF 785.5) | 1 | current consolidated text, 2014-08-15 |
| `785-13/` | Arrêté concernant la navigation sur les cours d'eau (RSF 785.13) | 1 | current consolidated text, 1992-01-01 |
| `785-16/` | Arrêté fixant les émoluments en matière de navigation (RSF 785.16) | 1 | current consolidated text, 2025-09-01 |
| `785-21/` | Arrêté limitant et interdisant la navigation sur certains lacs (RSF 785.21) | 1 | current consolidated text, 2019-04-01 |
| `786-11/` | Arrêté sur la navigation aérienne (RSF 786.11) | 1 | current consolidated text, 2012-01-01 |
| `810-14/` | Arrêté d'exécution de dispositions fédérales sur la protection contre les accidents majeurs (RSF 810.14) | 1 | current consolidated text, 2022-12-01 |
| `810-22/` | Arrêté approuvant le plan cantonal de gestion des déchets (RSF 810.22) | 1 | current consolidated text, 2022-02-01 |
| `810-23/` | Arrêté modifiant le plan cantonal de gestion des déchets (RSF 810.23) | 1 | current consolidated text, 2003-01-01 |
| `813-11/` | Arrêté d'exécution de dispositions fédérales sur la protection de l'air (RSF 813.11) | 1 | current consolidated text, 2022-02-01 |
| `820-8/` | Convention intercantonale relative à la médecine hautement spécialisée (RSF 820.8) | 1 | current consolidated text, 2009-01-01 |
| `821-5-11/` | Arrêté sur les sépultures (RSF 821.5.11) | 1 | current consolidated text, 2011-01-01 |
| `821-10-4/` | Convention entre les cantons et la Croix-Rouge suisse concernant la formation professionnelle du personnel infirmier, médico-technique et médico-thérapeutique (RSF 821.10.4) | 1 | current consolidated text, 1977-08-16 |
| `821-10-5/` | Convention intercantonale concernant la formation aux professions de la santé (professions médicales exceptées) et son financement (RSF 821.10.5) | 1 | current consolidated text, 1996-01-01 |
| `821-10-51/` | Arrêté approuvant la convention intercantonale concernant la formation aux professions de la santé (professions médicales exceptées) et son financement ainsi que ses annexes (RSF 821.10.51) | 1 | current consolidated text, 2022-02-01 |
| `821-17-42/` | Arrêté concernant la reconnaissance des écoles suisses de pédicures (RSF 821.17.42) | 1 | current consolidated text, 2003-01-01 |
| `821-41-11/` | Arrêté sur la lutte contre les maladies transmissibles et autres mesures de police sanitaire (RSF 821.41.11) | 1 | current consolidated text, 2014-05-01 |
| `821-41-12/` | Arrêté relatif à la fusion du laboratoire de l'hôpital fribourgeois et de l'Institut cantonal d'hygiène et de microbiologie (RSF 821.41.12) | 1 | current consolidated text, 2015-01-01 |
| `821-44-12/` | Arrêté concernant la prévention de l'alcoolisme et des autres toxicomanies (RSF 821.44.12) | 1 | current consolidated text, 2003-01-01 |
| `821-44-32/` | Arrêté instituant un Fonds de recherche en matière d'affections psychiques et de toxicodépendances (RSF 821.44.32) | 1 | current consolidated text, 2003-01-01 |
| `822-0-6/` | Convention sur les contributions des cantons aux hôpitaux relative au financement de la formation médicale postgrade et sur la compensation intercantonale des charges (RSF 822.0.6) | 1 | current consolidated text, 2022-01-25 |
| `822-0-7/` | Convention intercantonale sur l’Hôpital intercantonal de la Broye (HIB) Vaud-Fribourg (RSF 822.0.7) | 1 | current consolidated text, 2014-01-01 |
| `822-0-71/` | Règlement d'application de la Convention intercantonale du 21 août 2013 sur l'Hôpital intercantonal de la Broye (HIB) Vaud-Fribourg, relatif à l'exploitation de l'établissement (RSF 822.0.71) | 1 | current consolidated text, 2025-10-06 |
| `823-2/` | Convention concernant l’organisation des services de soins extra-hospitaliers dans le canton de Fribourg (RSF 823.2) | 1 | current consolidated text, 2003-01-01 |
| `823-16/` | Arrêté fixant les tarifs de l'aide familiale à domicile (RSF 823.16) | 1 | current consolidated text, 2001-07-01 |
| `824-1/` | Convention intercantonale en matière de santé numérique (RSF 824.1) | 1 | current consolidated text, 2024-02-01 |
| `834-0-4/` | Convention intercantonale relative aux institutions sociales (RSF 834.0.4) | 1 | current consolidated text, 2020-06-01 |
| `834-1-26/` | Arrêté fixant la contribution aux frais des personnes prises en charge dans les institutions spécialisées (RSF 834.1.26) | 1 | current consolidated text, 2026-01-01 |
| `838-11/` | Arrêté de reconnaissance d'un office de consultation conjugale (RSF 838.11) | 1 | current consolidated text, 2003-01-01 |
| `838-31/` | Arrêté concernant les centres de consultation en matière de grossesse (RSF 838.31) | 1 | current consolidated text, 2012-01-01 |
| `841-1-63/` | Arrêté concernant la mise en compte et la perception des parts communales aux charges financières incombant au canton pour l'assurance-vieillesse et survivants, l'assurance-invalidité, les prestations complémentaires à l'AVS/AI et les allocations familiales aux travailleurs agricoles et aux petits paysans (RSF 841.1.63) | 1 | current consolidated text, 2003-01-01 |
| `841-3-11/` | Arrêté d'exécution de la loi du 16 novembre 1965 sur les prestations complémentaires à l'assurance-vieillesse, survivants et invalidité, modifiée par celle du 11 novembre 1970 (RSF 841.3.11) | 1 | current consolidated text, 2026-01-01 |
| `841-4-13/` | Convention relative à la surveillance des institutions de prévoyance professionnelle ayant leur siège dans le canton de Fribourg (RSF 841.4.13) | 1 | current consolidated text, 2012-01-01 |
| `842-1-18/` | Arrêté fixant le tarif cadre médical (RSF 842.1.18) | 1 | current consolidated text, 1998-01-01 |
| `843-15/` | Arrêté concernant les contestations relatives à l'assurance militaire (RSF 843.15) | 1 | current consolidated text, 2008-01-01 |
| `864-1-16/` | Arrêté fixant les émoluments administratifs pour les autorisations et approbations données en application de la législation sur le travail dans l'industrie, l'artisanat et le commerce (RSF 864.1.16) | 1 | current consolidated text, 2026-01-01 |
| `865-51/` | Arrêté concernant la célébration de la Fête fédérale d'actions de grâces (RSF 865.51) | 1 | current consolidated text, 1930-09-06 |
| `910-61/` | Arrêté concernant l'exécution de l'ordonnance fédérale relative à la déclaration de produits agricoles issus de modes de production interdits en Suisse (RSF 910.61) | 1 | current consolidated text, 2013-01-01 |
| `914-10-65/` | Arrêté adoptant le plan de couverture des besoins en centres collecteurs de déchets animaux (RSF 914.10.65) | 1 | current consolidated text, 1999-01-01 |
| `917-16/` | Arrêté concernant les subventions cantonales en faveur d'améliorations foncières (RSF 917.16) | 1 | current consolidated text, 2023-03-01 |
| `921-4/` | Convention relative à la création et à l’exploitation de l’Ecole intercantonale de gardes forestiers de Lyss (RSF 921.4) | 1 | current consolidated text, 1969-03-28 |
| `921-17/` | Arrêté portant création d'un fonds d'investissement forestier (RSF 921.17) | 1 | current consolidated text, 2019-04-01 |
| `922-4/` | Concordat sur l’exercice et la surveillance de la chasse (RSF 922.4) | 1 | current consolidated text, 2017-05-01 |
| `922-5/` | Concordat concernant la chasse sur le lac de Neuchâtel (RSF 922.5) | 1 | current consolidated text, 2020-09-01 |
| `922-6/` | Concordat concernant la chasse sur le lac de Morat (RSF 922.6) | 1 | current consolidated text, 2020-09-01 |
| `923-4/` | Concordat sur l’exercice de la pêche (RSF 923.4) | 1 | current consolidated text, 1998-01-01 |
| `923-5/` | Concordat sur la pêche dans le lac de Neuchâtel (RSF 923.5) | 1 | current consolidated text, 2024-01-01 |
| `923-6/` | Concordat sur la pêche dans le lac de Morat (RSF 923.6) | 1 | current consolidated text, 2004-01-01 |
| `923-7/` | Convention entre les cantons de Berne et de Fribourg concernant la pêche dans les eaux limitrophes de la Singine et de la Sarine (RSF 923.7) | 1 | current consolidated text, 2010-01-01 |
| `923-51/` | Règlement d’exécution du concordat sur la pêche dans le lac de Neuchâtel en 2025, 2026 et 2027 (RSF 923.51) | 1 | current consolidated text, 2025-01-01 |
| `923-61/` | Règlement d’exécution du concordat sur la pêche dans le lac de Morat en 2025, 2026 et 2027 (RSF 923.61) | 1 | current consolidated text, 2025-01-01 |
| `940-3/` | Convention administrative sur les activités industrielles et artisanales réglementées (Espace Mittelland) (RSF 940.3) | 1 | current consolidated text, 1999-07-01 |
| `940-8/` | Accord intercantonal sur l’élimination des entraves techniques au commerce (RSF 940.8) | 1 | current consolidated text, 2003-02-04 |
| `940-72/` | Arrêté relatif aux collectes (RSF 940.72) | 1 | current consolidated text, 2022-02-01 |
| `942-11/` | Arrêté sur le contrôle des prix (RSF 942.11) | 1 | current consolidated text, 2022-01-01 |
| `947-2-1/` | Convention intercantonale sur la vente du sel en Suisse (RSF 947.2.1) | 1 | current consolidated text, 1974-08-12 |
| `947-7-11/` | Arrêté d'application de la loi fédérale du 25 mars 1977 sur les substances explosibles (RSF 947.7.11) | 1 | current consolidated text, 2022-02-01 |
| `952-81/` | Arrêté fixant définitivement la durée des mascarades (RSF 952.81) | 1 | current consolidated text, 1929-01-18 |
| `952-171/` | Directives pour la construction et l’aménagement des établissements publics (RSF 952.171) | 1 | current consolidated text, 2013-01-01 |
| `958-6/` | Concordat sur les jeux d’argent au niveau suisse (RSF 958.6) | 1 | current consolidated text, 2021-01-01 |
| `958-7/` | Convention romande sur les jeux d’argent (RSF 958.7) | 1 | current consolidated text, 2021-01-01 |
| `958-32/` | Arrêté concernant la désignation des membres fribourgeois de la Société de la loterie de la Suisse romande (RSF 958.32) | 1 | current consolidated text, 2016-01-01 |

## Source

The RSF (systematic collection) of the canton, published by the canton at <https://bdlf.fr.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (ROF). The additional current texts include the textual separate annexes of RSF 261.16 and 631.33 and the text layer of the map annex of RSF 785.21. Other separately published annexes in the earlier collection remain outside this corpus. The map in RSF 112.8 and the eleven maps in RSF 785.21 are absent; those two acts are incomplete for normative images.

## Dates

- The `In-force:` trailer records the day the collection says the version took effect. The author date uses noon in Europe/Zurich; appended commit dates preserve repository order. The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `futur` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

The 75 additional PDF-only acts use `texte-integral.md` for the complete official text layer, with printed line breaks in page order. Three additional acts use `annexe-001.md` for their separate annex text. These texts were not OCRed.

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (ROF), with an e-mail address that cannot exist (`<act key>@bdlf.fr.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. The tables above list all included instruments. Normative image limits are stated in the Source section.
