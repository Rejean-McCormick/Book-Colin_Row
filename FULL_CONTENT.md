# Colin Row — contenu intégral du repo documentaire v3

> Concaténation de tous les fichiers Markdown du repo optimisé. Les séparateurs indiquent le chemin original.



---

# FILE: `README.md`

# Colin Row — Repo documentaire de production v3

## Statut

Cette version est la **documentation consolidée et optimisée** du livre *Colin Row*. Elle réunit les versions longues récentes, les fiches spécialisées et les versions antérieures utiles, mais ne traite pas toutes les anciennes formulations comme du canon.

Le repo distingue quatre statuts :

- **CANON** : décision de travail à respecter dans les nouveaux chapitres ;
- **SOURCE FORTE** : matière existante à reprendre ou adapter ;
- **RÉSERVE** : idée intéressante, mais trop transformatrice ou insuffisamment alignée pour être intégrée sans décision d’auteur ;
- **OBSOLÈTE** : branche à ne plus réintroduire dans le manuscrit actuel.

## Principe directeur

Le roman doit fonctionner d’abord comme **une œuvre littéraire carcérale sur la parole, la responsabilité, la mémoire et la transmission**. KOA/Konnaxion apparaît ensuite comme la forme collective que prennent des besoins déjà vécus.

La mécanique fondamentale est :

**vie vécue → dysfonctionnement → réponse fautive ou limite → besoin formulable → fonction nécessaire → objection → nom éventuel.**

Le lecteur doit pouvoir pressentir la fonction avant que le groupe lui donne un nom.

## Canon de travail v3

1. Colin arrive avec une **intuition de coopération internationale** et un travail/projet confidentiel, mais pas avec l’écosystème Konnaxion déjà baptisé.
2. Son arrestation suit la branche **“motif confidentiel”** : surveillance soupçonnée, demande de recours, humiliation, coup au policier, responsabilité assumée. La surveillance n’est jamais confirmée comme conspiration certaine.
3. Matteo est un ancien **soudeur**, sobre en prison, protecteur; il donne à Colin le premier carnet. Son expérience pratique peut inclure le bricolage de machinerie agricole.
4. Nadia dirige l’APR avec la méthode **Faits / Pièces / Effets** et l’autographie. Colin est ensuite **banni de l’APR**, mais continue d’aider ailleurs par questions et structure, jamais en écrivant pour les autres.
5. KOA est d’abord un **geste / code / méthode de groupe**, pas une plateforme.
6. Konnaxion est le **nom tardif de la famille d’idées** et du lien entre les modules; le baptême doit rester collectif.
7. Kreative repose non seulement sur la visibilité des artistes, mais sur l’idée que **l’art est une forme de connaissance et de mémoire sensible**.
8. Ethikos doit naître d’un **désaccord moral réel** avant d’être nommé comme outil.
9. SmartVote reste une **hypothèse disputée**, jamais une vérité politique acquise.
10. Kristal Farms est une **synthèse collective**, pas la solution personnelle d’un détenu.
11. Le carnet sort à la fin; le succès extérieur n’est pas garanti.

## Architecture

- `core/` — canon, bible, personnages, voix, motifs, continuité, décisions, moteur de chapitre.
- `parts/` — fonction et transformation des trois mouvements.
- `chapter_briefs/` — briefs des 19 chapitres.
- `reference/` — alignement des versions, lexique, récupération des sources et anciennes versions.
- `material/` — réservoir non canon : fragments, scènes, motifs, variantes, legacy.
- `manuscript/` — futur texte canonique.
- `working/` — essais, coupes, restructurations.

## Ordre de consultation

Pour écrire un chapitre :

1. `core/00_CANONICAL_STATE.md`
2. `core/03_VOICE_AND_STYLE.md`
3. le brief du chapitre
4. `core/06_CONTINUITY_MAP.md`
5. `core/09_CHAINES_DE_NECESSITE.md`
6. seulement ensuite les matériaux de référence utiles

La documentation doit connaître plus de choses que le roman. Le manuscrit ne doit jamais essayer de tout expliquer.


---

# FILE: `INDEX.md`

# Index — Colin Row v3

## Noyau canonique
- `core/00_CANONICAL_STATE.md`
- `core/01_BOOK_BIBLE.md`
- `core/02_EDITORIAL_CONTRACT.md`
- `core/03_VOICE_AND_STYLE.md`
- `core/04_CHARACTER_BIBLE.md`
- `core/05_THEMES_MOTIFS.md`
- `core/06_CONTINUITY_MAP.md`
- `core/07_AMBIGUITIES_AND_DECISIONS.md`
- `core/08_WRITING_PROTOCOL.md`
- `core/09_CHAINES_DE_NECESSITE.md`
- `core/10_CHAPTER_ENGINE.md`
- `core/11_CANON_DECISIONS_V3.md`

## Parties
- `parts/PART_1_LA_CELLULE.md`
- `parts/PART_2_LES_VOIX_ENTERREES.md`
- `parts/PART_3_LE_MONDE_RECOMPOSE.md`

## Chapitres
19 briefs dans `chapter_briefs/`.

## Référence
- `reference/VERSION_ALIGNMENT.md`
- `reference/SOURCE_RECOVERY.md`
- `reference/LEGACY_RECOVERY.md`
- `reference/SOURCE_INDEX.md`
- `reference/ECOSYSTEM_LEXICON.md`
- `reference/LEGACY_CAST_FUNCTIONS.md`

## Matériaux non canoniques
- `material/legacy/README.md`
- `material/motifs/WHITE_PEARL.md`
- `material/characters/COLIN_SON_RESERVE.md`

## Manuscrit et travail
- `manuscript/README.md`
- `working/README.md`


---

# FILE: `REPO_MANIFEST.md`

# Manifest du repo v3

- `INDEX.md`
- `README.md`
- `chapter_briefs/01_l_arrivee.md`
- `chapter_briefs/02_lettres_clandestines.md`
- `chapter_briefs/03_le_code_d_arjun.md`
- `chapter_briefs/04_le_cercle_des_voix.md`
- `chapter_briefs/05_plus_que_de_l_or.md`
- `chapter_briefs/06_koa.md`
- `chapter_briefs/07_la_denonciation_enterree.md`
- `chapter_briefs/08_le_passage_a_l_acte.md`
- `chapter_briefs/09_la_fresque_effacee.md`
- `chapter_briefs/10_la_justice_ajournee.md`
- `chapter_briefs/11_les_chiffres_sans_langue.md`
- `chapter_briefs/12_le_tournoi_du_present.md`
- `chapter_briefs/13_le_siphon.md`
- `chapter_briefs/14_l_eglise_brûlee.md`
- `chapter_briefs/15_l_hydro_de_l_assiette.md`
- `chapter_briefs/16_la_tour.md`
- `chapter_briefs/17_resonances_exterieures.md`
- `chapter_briefs/18_baptême.md`
- `chapter_briefs/19_la_breche.md`
- `core/00_CANONICAL_STATE.md`
- `core/01_BOOK_BIBLE.md`
- `core/02_EDITORIAL_CONTRACT.md`
- `core/03_VOICE_AND_STYLE.md`
- `core/04_CHARACTER_BIBLE.md`
- `core/05_THEMES_MOTIFS.md`
- `core/06_CONTINUITY_MAP.md`
- `core/07_AMBIGUITIES_AND_DECISIONS.md`
- `core/08_WRITING_PROTOCOL.md`
- `core/09_CHAINES_DE_NECESSITE.md`
- `core/10_CHAPTER_ENGINE.md`
- `core/11_CANON_DECISIONS_V3.md`
- `manuscript/README.md`
- `material/README.md`
- `material/alternates/README.md`
- `material/characters/COLIN_SON_RESERVE.md`
- `material/fragments/README.md`
- `material/legacy/README.md`
- `material/motifs/WHITE_PEARL.md`
- `material/research/README.md`
- `material/scenes/README.md`
- `parts/PART_1_LA_CELLULE.md`
- `parts/PART_2_LES_VOIX_ENTERREES.md`
- `parts/PART_3_LE_MONDE_RECOMPOSE.md`
- `reference/ECOSYSTEM_LEXICON.md`
- `reference/LEGACY_CAST_FUNCTIONS.md`
- `reference/LEGACY_RECOVERY.md`
- `reference/SOURCE_INDEX.md`
- `reference/SOURCE_RECOVERY.md`
- `reference/VERSION_ALIGNMENT.md`
- `working/README.md`


---

# FILE: `core/00_CANONICAL_STATE.md`

# État canonique de travail — v3

## 1. Nature du livre

*Colin Row* est un **roman d’idées carcéral**, mais sa légitimité vient des personnes. Le livre montre comment des hommes enfermés apprennent à transformer des récits isolés en intelligence commune sans effacer les fautes individuelles.

Le centre du livre n’est pas la plateforme. Le centre est la question :

> **Que devient une parole lorsqu’aucune institution ne sait la recevoir avant qu’elle devienne cri, fuite, fraude, sabotage, incendie ou coup ?**

## 2. Séquence canonique de travail

1. L’arrivée
2. Lettres clandestines
3. Le code d’Arjun
4. Le cercle des voix
5. Plus que de l’or
6. KOA
7. La dénonciation enterrée
8. Le passage à l’acte
9. La fresque effacée
10. La justice ajournée
11. Les chiffres sans langue
12. Le tournoi du présent
13. Le siphon
14. L’église brûlée
15. L’Hydro de l’assiette
16. La tour
17. Résonances extérieures
18. Baptême
19. La brèche

## 3. Colin avant la prison

Colin possède déjà :

- une inquiétude politique forte;
- une proposition de coopération internationale;
- un projet confidentiel ou semi-confidentiel;
- l’intuition qu’une infrastructure collaborative pourrait relier inventeurs, savoir-faire et personnes au-delà des frontières.

Il **ne possède pas encore** :

- la famille finale des modules;
- la méthode KOA;
- les histoires qui donnent aux fonctions leur nécessité humaine;
- Konnaxion comme identité collective stabilisée.

Les anciennes versions où la plateforme s’appelle déjà Konnaxion sont interprétées comme une **préfiguration / nom de travail non canonique**, pas comme preuve que le système complet existait déjà.

## 4. Arrestation de Colin

Canon : branche **Motif confidentiel**.

- Colin soupçonne une filature ou une surveillance.
- Il ne peut ou ne veut pas révéler entièrement la nature de son travail.
- Il demande un moyen de vérifier que ses droits sont protégés sans exiger l’ouverture totale d’une enquête.
- Le policier lui oppose l’impossibilité de confirmer une surveillance et suggère une consultation psychiatrique.
- Colin répond mal, la tension monte, il frappe.
- Il reconnaît sans détour que frapper le policier est son crime.

Le roman **ne confirme pas** qu’un gouvernement, un juge et la police ont effectivement conspiré contre lui. Ce qui est certain est son expérience d’opacité et l’absence de recours qu’il perçoit.

Le besoin qui en sort : **séparer non seulement les pouvoirs, mais aussi les informations; créer un tiers de vérification et un chemin de recours accessible.**

## 5. Matteo

Canon :

- détenu expérimenté;
- ancien soudeur;
- sobriété retrouvée en prison;
- protecteur pragmatique;
- donne à Colin le premier carnet;
- croit que les gens doivent être “soudés” avant de pouvoir construire quelque chose ensemble;
- peut avoir bricolé ou travaillé autour de machinerie agricole, ce qui rend naturelle sa contribution aux serres de Kristal Farms.

## 6. Nadia et l’APR

Canon : Nadia dirige l’Atelier Parcours & Réinsertion.

Méthode : **Faits / Pièces / Effets**.

Principe : **autographie**. On peut aider à ordonner, clarifier et questionner; on n’écrit pas la phrase d’un autre.

Colin est d’abord participant. Après rumeurs et interprétation d’images partielles, il est **banni de l’APR pour préserver l’autographie**. Il continue d’aider ailleurs avec trois questions-pivots :

- Qui décide ?
- Qu’est-ce qui manque ?
- Et après ?

Nadia n’est ni bourreau ni sauveuse. Son cadre est réellement utile; sa limite est institutionnelle.

## 7. KOA et Konnaxion

### KOA

Un geste, une discipline et un code de groupe : ralentir, écouter, distinguer, reformuler, ne pas confisquer la parole.

### Konnaxion

Nom tardif de la famille d’idées et de la relation entre les personnes qui les ont produites. Le chapitre 18 est le **seul grand baptême**.

Le baptême récupère l’énergie des anciennes scènes — cellule serrée, dessins, rires, propositions de noms, K récurrent — mais abandonne la présentation “module 1, module 2…”.

## 8. Responsabilité

Aucune histoire n’innocente automatiquement le détenu.

Formule directrice :

> **Comprendre le chemin n’efface pas l’acte; comprendre le chemin peut empêcher qu’il se répète.**

## 9. Spatialité

Le roman reste presque entièrement en prison. Le dehors arrive par :

- récit;
- souvenir;
- document;
- musique;
- visite;
- message;
- carnet transmis.

La prison doit continuer à vivre pendant les récits : repas, attente, bruit, gardiens, portes, travail, bibliothèque, chapelle, cour, APR, atelier.

## 10. Fin

Le carnet franchit les murs. Colin reste dedans. Il accepte de perdre le contrôle du projet.

La fin contient : **espoir + dépossession + incertitude**.


---

# FILE: `core/01_BOOK_BIBLE.md`

# Bible du livre — v3

## Logline

Après avoir été emprisonné pour avoir frappé un policier lors d’une tentative maladroite de faire vérifier ses droits, Colin Row découvre que les détenus autour de lui portent chacun une histoire où une institution a cessé d’écouter avant que la situation ne bascule. En les écoutant, en se faisant lui-même corriger, et en consignant ce qui résiste, il participe à la naissance d’une méthode et d’un corpus collectif dont le carnet finira par quitter la prison sans lui.

## Sujet apparent

La genèse de KOA/Konnaxion et de plusieurs fonctions sociales : apprendre, délibérer, tracer, organiser, créer, protéger un commun, rendre visibles les flux et transmettre.

## Sujet réel

**La différence entre expliquer quelqu’un et l’écouter.**

Le livre demande comment une société peut recevoir une parole avant de la réduire à un dossier, un diagnostic, une faute, une catégorie ou un slogan.

## Question centrale

Comment transformer des expériences individuelles de rupture en intelligence commune sans :

- excuser les actes;
- voler la parole des personnes;
- convertir chaque vie en exemple;
- recréer une nouvelle hiérarchie;
- confondre transparence et surveillance;
- confondre expertise et pouvoir.

## Promesse émotionnelle

Le lecteur entre dans un lieu où chacun est déjà défini par ce qu’il a fait. Il en ressort en connaissant ce que ces hommes savent, regrettent, protègent, inventent et transmettent.

## Arc de Colin

### 1. Le système comme réponse
Il pense qu’une architecture bien conçue peut corriger un monde mal organisé.

### 2. Les personnes comme données
Il écoute mieux, mais risque encore de transformer les histoires en pièces de son projet.

### 3. La limite imposée
Nadia, les contradictions du groupe et son bannissement de l’APR lui enseignent qu’aider n’est pas formuler pour autrui.

### 4. La co-création
Il accepte que les modules soient nés de plusieurs voix et que certains restent contestés.

### 5. La dépossession
Il remet le carnet. La réussite n’est plus sous son contrôle.

## Arc du groupe

**coexistence forcée → gestes d’entraide → règles d’écoute → confiance → récits difficiles → désaccord → fonctions nécessaires → noms → mémoire → transmission.**

## Grande métaphore

La prison est un endroit où les corps ne circulent presque plus, mais où les histoires peuvent encore circuler. Le projet devient une tentative de construire des **portes pour la parole** avant de construire des plateformes.

## Ce que le livre refuse

- le héros persécuté qui avait raison depuis le début;
- la conspiration confirmée sans preuve;
- le détenu réduit à un trauma utile;
- le module qui apparaît avant le besoin;
- les solutions sans objection;
- l’institution entièrement malveillante;
- la technologie comme deus ex machina;
- la politique comme catéchisme;
- la prison abstraite sans quotidien;
- le triomphe final garanti.


---

# FILE: `core/02_EDITORIAL_CONTRACT.md`

# Contrat éditorial

## Contrat avec le lecteur

Le livre promet :

1. des personnages capables d'erreur, de beauté, de contradiction et de responsabilité ;
2. une prison crédible comme espace vécu, pas seulement comme métaphore ;
3. des idées compréhensibles par leurs conséquences humaines avant leur formulation abstraite ;
4. une progression réelle : chaque histoire modifie le groupe et ne sert pas uniquement à ajouter une fonctionnalité ;
5. une tension entre justice et méthode, plutôt qu'une réponse idéologique déjà fermée.

## Priorité de valeur

En cas de conflit :

**vérité du personnage > qualité de la scène > cohérence émotionnelle > cohérence narrative > clarté de l'idée > exactitude du nom d'un module.**

Les concepts peuvent être renommés ou déplacés. Une personne convaincante ne doit jamais être sacrifiée pour préserver un acronyme.

## Densité d'idées

Une scène ne doit généralement porter qu'**une question humaine principale** et éventuellement une conséquence conceptuelle.

Le concept n'est nommé que lorsque le lecteur pourrait presque le nommer lui-même.

## Règle de non-démonstration

Le personnage qui raconte une injustice ne doit pas être immédiatement transformé en exemple de politique publique. Après le récit, laisser un espace : silence, gêne, contradiction, humour, résistance, désaccord ou banalité carcérale.

## Règle du contrepoids

Pour toute idée importante, faire apparaître au moins une résistance crédible :

- coût ;
- risque d'abus ;
- contradiction morale ;
- expérience opposée ;
- question de pouvoir ;
- problème de mise en œuvre ;
- peur d'une nouvelle forme d'exclusion.

Le but n'est pas de réfuter le projet, mais d'empêcher la prose de devenir catéchétique.

## Règle de responsabilité

Les récits suivent autant que possible quatre temps :

1. ce qui manquait ou dysfonctionnait ;
2. ce que le personnage a tenté ;
3. l'acte qu'il a réellement posé ;
4. ce qu'il peut aujourd'hui reconnaître de sa propre responsabilité.

## Règle du dehors

Le dehors n'est jamais présenté comme un simple monde corrompu. Il contient aussi : familles, métiers, œuvres, institutions utiles, gens honnêtes, procédures nécessaires, souvenirs heureux. Sinon la prison devient artificiellement plus humaine que toute la société.

## Règle de fin de chapitre

Éviter de terminer systématiquement par « voilà le système qu'il faudrait construire ».

Les fins doivent varier :

- une image ;
- un geste ;
- une phrase inachevée ;
- une contradiction ;
- une décision relationnelle ;
- une note de Réjean ;
- un objet déplacé ;
- un silence.

## Règle de récupération historique

Lorsqu’un ancien passage est meilleur qu’un passage récent, récupérer **la scène ou la fonction**, pas automatiquement son système de personnages, sa causalité ou sa doctrine. Le canon v3 prime sur la chronologie des fichiers.


---

# FILE: `core/03_VOICE_AND_STYLE.md`

# Voix et style

## Ligne générale

Prose sobre, incarnée, québécoise sans caricature, capable de laisser les idées apparaître à travers une conversation concrète.

Le style doit donner l'impression que **des hommes parlent parce qu'ils ont quelque chose à perdre**, pas parce que l'auteur veut transmettre une thèse.

## Dialogue

Le dialogue est le moteur principal, mais il ne doit pas être platonicien au sens scolaire du terme. Les interlocuteurs :

- se coupent ;
- se trompent ;
- reformulent mal ;
- ont parfois honte ;
- refusent de répondre ;
- plaisantent au mauvais moment ;
- reviennent plus tard sur une idée ;
- peuvent comprendre une chose sans savoir la nommer.

Les meilleures idées doivent souvent émerger **entre** les répliques plutôt que dans une tirade parfaite.

## Description

Courte mais sensorielle. La prison doit avoir une présence :

- néons ;
- clés ;
- eau de Javel ;
- métal ;
- pluie aux fenêtres hautes ;
- plateaux ;
- ventilation ;
- chaussures ;
- portes ;
- files ;
- bruit des chaises ;
- moments rares de lumière ou de musique.

Ne pas supprimer toute description au nom de la rapidité. Quelques détails exacts donnent du poids aux idées.

## Registre

Éviter :

- le vocabulaire de brochure ;
- les listes de fonctionnalités dans le dialogue ;
- les personnages qui parlent tous avec la même syntaxe ;
- les métaphores grandioses à chaque fin de chapitre ;
- les conclusions systématiquement prophétiques.

Préférer :

- la précision concrète ;
- une image forte par scène ;
- des phrases plus simples après un moment émotionnel ;
- le sous-entendu ;
- les reprises de mots entre personnages ;
- le contraste entre jargon institutionnel et langage vécu.

## Voix repères

### Colin

Procédural, rapide, analytique. Il cherche spontanément « où ça casse ». Il doit progressivement apprendre à poser moins de solutions et davantage de questions.

### Matteo

Peu de théorie. Phrases de métier, pragmatiques, souvent un mot qui ramène au sol. C'est le poids du réel.

### Réjean

Mesuré, observateur, légèrement plus littéraire sans devenir omniscient. Ses notes cherchent la forme générale mais doivent conserver les incertitudes.

### Nadia

Professionnelle, claire, cadrante. Son langage est structuré : « une phrase, un fait », « on ordonne, on ne formule pas pour vous ». Quand elle se crispe, la rigidité apparaît d'abord dans le protocole.

### Will

Court, musical, lumineux. Il nomme plus qu'il n'explique. Un mot juste, un rythme, puis il se retire.

### Darius

Concret, chronologique, sec. Il parle de trajets, de papiers, de choses manquantes, de temps perdu.

### Samir

Visuel, retenu. Réserve, hachure, blanc, geste. Sa pensée morale passe par ce qu'il dessine et ce qu'il refuse.

### Arjun

Technique seulement quand nécessaire. Patient, précis, préfère expliquer par un objet ou une conséquence.

### Rami

Didactique calme, exemples avant principe. La langue, les chiffres et l'héritage du père doivent colorer sa voix.

### Marc-André

Énergique, joueur, aime transformer une règle en défi. Son enthousiasme peut devenir imprudence.

### François

Analytique, causal, mais son chapitre doit lui donner une vie au-delà des chiffres.

### Antoine

Gravité physique. Selon la version retenue : homme de métier attaché au lieu, ou érudit d'art sacré. Ne pas mélanger les deux registres sans décision claire.

### Jules

Civique, direct, préfère parler de ce qu'on peut changer plutôt que de lui-même. Son refus de raconter son crime peut être une force littéraire.

### Liang

Ingénieur du seuil : étapes, dispositifs, fonction. Affect retenu jusqu'au moment de la spoliation.

## Notes de Réjean

À utiliser avec parcimonie. Une note doit apporter une **résonance** que la scène ne pouvait pas dire, non répéter la morale déjà évidente.

Proposition : 6 à 10 notes fortes dans le livre plutôt qu'une note obligatoire à chaque chapitre.

## Réalité subjective

Le roman peut accueillir foi, intuition, synchronicité, impressions de surveillance ou signes personnels, mais distingue toujours **ce qu’un personnage ressent** de **ce que le récit affirme comme fait**. Cette règle est particulièrement importante pour Colin et tout matériau hérité de `sync music`.


---

# FILE: `core/04_CHARACTER_BIBLE.md`

# Bible des personnages — version consolidée à partir des sources

## Principe

Cette bible distingue quatre choses : **ce que les sources établissent**, **la fonction narrative**, **la chaîne de nécessité vers l’écosystème**, et **ce qui reste réellement contradictoire**. Une absence volontaire de biographie n’est pas traitée comme un trou.

## Colin Row

**Canon v3 :** environ 35 ans; travaille sur un projet confidentiel et porte déjà une intuition de coopération internationale; soupçonne une surveillance sans pouvoir la prouver; cherche une réponse institutionnelle; frappe un policier après une interaction humiliante; reconnaît son geste. La fiche `Colin — Justice` précise sa demande : tiers indépendant, contrôle de la légalité, recours abordable, séparation de l’information.

**Fonction :** catalyseur et assembleur. Il ne doit pas être la source de toutes les idées.

**Blessure :** opacité + impossibilité de vérifier ses droits.

**Faute :** violence impulsive.

**Arc :** de « je dois faire reconnaître/construire mon système » vers « nous avons produit quelque chose de transmissible dont je ne suis pas l’unique auteur ».

**Chaîne solution :** KOA / Ethikos / Orgo comme problème transversal de recours, écoute et procédure.

**Branche rejetée :** la variante `pot de fleur` reste en archive, mais n’est plus concurrente du canon de travail.

## Matteo

**Canon v3 :** détenu expérimenté, protecteur et pragmatique; **ancien soudeur**, sobre depuis son incarcération. Il donne à Colin le premier carnet et formule l’idée que, comme le métal, les gens doivent être soudés ensemble pour construire quelque chose de solide. Des notes plus récentes lui attribuent aussi du bricolage de machinerie agricole; les deux éléments sont compatibles.

**Fonction :** test de réalité, protection du groupe, contradiction pratique.

**Contribution :** premier carnet; métaphore de la soudure; serres locales dans Kristal Farms.

**À préserver :** crime non expliqué; il n’a pas besoin d’être rattaché à un module.

## Réjean

**Établi :** scribe/témoin qui tient son propre carnet et produit les notes de fin de chapitre.

**Fonction :** mémoire humaine parallèle au carnet plus conceptuel de Colin.

**Arc :** sa chronique passe d’une synthèse des idées à une mémoire du groupe et de ses limites.

**Écho solution :** EkoH, mais sans réduire Réjean à une démonstration produit.

**À renforcer :** le nommer tôt pour que ses notes n’apparaissent pas ex nihilo.

## Nadia

**Établi :** responsable de l’Atelier Parcours & Réinsertion; méthode « Faits / Pièces / Effets »; principe d’autographie : aider à structurer sans écrire la parole de l’autre.

**Fonction :** apprendre au livre sa propre méthode d’écoute.

**Limite institutionnelle :** le dossier peut être exact et néanmoins rester sans portée hors de la commission.

**Chaîne solution :** méthode de KOA : écoute, distinction, reformulation, non-appropriation.

**Canon v3 :** elle bannit Colin de l’APR pour protéger l’autographie après rumeur et images ambiguës. Les chapitres suivants doivent respecter cette conséquence : Colin aide hors APR et ne formule pas les textes des autres.

## Will

**Établi :** parle peu, nomme bien, lyriciste, rythme/reformule; présence lumineuse; participe au concert et à la sortie du carnet.

**Fonction :** transformer les idées en mots qui voyagent.

**Chaîne solution :** Kreative + baptême/liaison de Konnaxion.

**À préserver :** cause d’incarcération non donnée; mystère volontaire.

## Samir

**Établi par synthèse compatible :** illustrateur au trait/encre, économiquement précaire. Dans la fiche v15, il a recours à la prostitution pour survivre mais refuse la violence demandée par un client; une arrestation suit. Dans v16, une œuvre murale engagée est effacée/repeinte et il est accusé de dégradation; en prison, il continue de créer et signe discrètement.

**Fonction :** dignité, création, frontière morale et persistance de la voix.

**Motif :** réserve blanche / ce que l’on refuse de remplir; signature minuscule; œuvre effacée.

**Chaîne solution :** Kreative — créer, signer, montrer et conserver hors des gatekeepers; écho EkoH pour la trace.

**Règle :** ne pas traiter prostitution + fresque comme deux modules. Elles peuvent former une seule trajectoire de précarité, limite et effacement.

## Darius

**Établi :** fermeture d’entrepôt; parcours administratif fait de preuves d’adresse, codes SMS, rendez-vous manqués par courrier tardif, dossiers fermés, Hydro, aide alimentaire inaccessible; finit par voler des aliments; reconnaît le vol.

**Formulation clé de la source :** il lui fallait une porte, un fil, un parcours visible et quelqu’un qui sache qui fait quoi et quand.

**Fonction :** incarner le coût humain de la fragmentation administrative et tester toutes les solutions contre le terrain.

**Chaîne solution :** Orgo.

**Statut :** personnage-référence pour la chaîne causalement la plus nette.

## Arjun

**Établi :** développe avec d’autres une innovation médicale à bas coût en open source; captation/brevet par une entreprise; republie malgré la pression juridique; sanction.

**Fonction :** générosité du commun confrontée à la capture.

**Besoins formulés :** dépôt ouvert, versionnage, attribution, licence commune.

**Chaîne solution :** keenKonnect, première étape.

**Boucle :** Liang doit démontrer plus tard qu’ouvrir et attribuer ne suffit pas.

## Robert

**Établi :** cadre/fonctionnaire au ministère de l’Éducation; voit favoritisme et promotions de complaisance; documente, produit un rapport, voit le dossier enterré; fuit vers un journaliste; source découverte; poursuivi pour divulgation/secret professionnel.

**Blessure :** son travail utile disparaît alors que sa faute de divulgation reste.

**Fonction :** vérité effaçable et mérite institutionnellement invisible.

**Chaîne solution :** EkoH; en v17, son récit est aussi l’un des deux déclencheurs explicites de SmartVote.

## Gabriel

**Établi :** militant écologiste; pétitions, lettres, manifestations et consultations jugées factices; passe au sabotage d’un pipeline.

**Fonction :** montrer qu’une cause légitime ne légitime pas automatiquement la méthode.

**Chaîne solution :** Ethikos.

## Frank

**Établi :** contradicteur de Gabriel; soutient que le sabotage a nui à la cause et ne peut pas être excusé par sa justesse.

**Fonction :** rendre la contradiction interne réelle.

**Règle :** il ne doit jamais être réduit à la phrase qui permet ensuite d’introduire Ethikos.

## Alexandre

**Établi :** multiples reports d’audience, erreurs de formulaire/cases, convocations discordantes, changements d’avocats, lettre au greffe sans réponse.

**Fonction :** déplacer la fragmentation de Darius vers la justice.

**Chaîne solution :** Orgo — état partagé du dossier, responsable, échéance, continuité.

## Rami

**Établi :** père comptable à l’étranger dont le diplôme n’est pas reconnu; Rami a un talent réel pour les chiffres mais une barrière de langue/écriture; se forme seul; finit par “arranger” des états financiers pour de l’argent; sanction pour fraude/falsification; sa compétence technique peut être reconnue sans excuser l’acte.

**Fonction :** distinguer compétence, reconnaissance et permission.

**Chaîne solution :** KonnectED + trace EkoH.

## Marc-André

**Établi :** DEP, DEC, AEC, BAC; veut mélanger les niveaux et travailler sur des projets réels; IA supervisée et traçable; compétition/tournoi public; contributions par commits/journaux/tests. Rejet hiérarchique; geste spectaculaire (course nue); coup porté lors de l’intervention, assumé.

**Fonction :** apprentissage dans le présent, preuve par réalisation, danger de l’enthousiasme qui force l’attention.

**Chaîne solution :** KonnectED + EkoH.

**Règle :** il arrive déjà avec une architecture; il faut la faire tester, pas feindre qu’elle vient d’être inventée en prison.

## François

**Établi :** ancien cadre d’une grande institution financière décrite comme une « coopérative devenue banque ». Il observe des flux de fonds publics et d’avantages vers le sommet, documente sur plusieurs années, questionne en interne, tente de parler à un journaliste, puis est pris avec une clé USB contenant des documents qu’il pouvait consulter mais pas sortir. Chefs d’accusation évoqués : confidentialité, fraude, abus de confiance.

**Fonction :** rendre visibles les chemins de l’argent et le déplacement du risque.

**Propositions sources :** conditions mesurables sur les fonds publics, limites de primes/rémunérations, récupération automatique, transparence lisible, « vannes » sur les flux. Réjean parle de « cardiologie économique ».

**Chaîne solution :** EkoH pour la trace + Orgo pour les flux/conditions + couche économique non encore nommée.

**Risque :** l’histoire existe; le danger n’est donc plus “absence de perte personnelle”, mais la surcharge d’exposé macroéconomique.

## Antoine Dubois

**Établi :** lié à une ou deux églises/patrimoine local; décision de fermeture/vente perçue comme opaque; démarches et arguments sans effet; incendie volontaire d’un bâtiment; regret d’avoir détruit ce qu’il voulait sauver.

**Fonction :** décision opaque, expertise, participation, violence au nom de la protection.

**Chaîne solution :** Ethikos; puis SmartVote en combinaison avec Robert dans v17.

**Contradiction restante :** homme de métier/bénévole dans une version; docteur en art sacré dans une autre.

## Jules

**Établi :** v16 le présente comme ancien élu municipal déchu; la fiche v15 lui fait dire explicitement qu’il ne racontera pas pourquoi il est en prison. Il pense la nourriture comme infrastructure commune et développe « Hydro de l’assiette » : contrats, conditions sur l’argent public, travail, emballages, réemploi, cuisines mutualisées, réduction du gaspillage.

**Fonction :** subsistance et service commun.

**Chaîne solution :** logique d’orchestration alimentaire; dans v17, son chapitre devient le noyau collectif de Kristal Farms avec François, Matteo, Samir et Darius.

**À préserver :** son droit à l’opacité. Ne pas inventer son crime.

## Liang

**Établi :** ingénieur; publie librement la « Tour de garde »; une entreprise reprend/brevète l’assemblage; mise en demeure/injonction; Liang continue de diffuser et est sanctionné.

**Fonction :** révéler que l’ouverture sans garde-fou peut être capturée.

**Chaîne solution :** keenKonnect, seconde étape : protection juridique/collective contre la re-fermeture.

## T-Mo et B-Ice

**Établi :** artistes/présences du dehors au concert; T-Mo devient relais de la transmission du carnet et reçoit le message lié à Richard Desjardins/Kristal Farms.

**Fonction :** première interface avec le dehors, pas sauveurs.

## Lucas

**Établi :** jeune détenu qui lit difficilement, honte de l’analphabétisme, apprentissage clandestin/solidaire, lettres tracées même lorsque le matériel manque.

**Fonction :** rendre sensible la liberté d’apprendre avant toute théorie éducative.

**Chaîne solution :** KonnectED.
## Héritage non canonique à ne pas fusionner silencieusement

- **Matthias** : utile uniquement pour un motif subjectif de synchronicité musicale; ne pas confirmer ses interprétations comme réalité objective.
- **Félix / Marc-Étienne / Simon / ancien Dubois** : leurs fonctions peuvent être transférées, mais le casting récent prévaut.
- **Mort du fils de Colin** : matériau très puissant du tableur v9, mais en réserve car il redéfinit tout le protagoniste.


---

# FILE: `core/05_THEMES_MOTIFS.md`

# Thèmes et motifs — v3

## Thèmes centraux

### 1. Écoute vs classement
Une institution doit classer pour agir. Le danger commence lorsque la catégorie remplace la personne.

### 2. Responsabilité sans réduction
Les personnages peuvent avoir été mal servis et avoir néanmoins commis un acte condamnable.

### 3. Trace vs oubli
Rapports perdus, œuvres repeintes, compétences sans diplôme, dossiers reportés : ce qui n’a pas de trace reconnue devient socialement fragile.

### 4. Expertise vs pouvoir
Savoir quelque chose ne donne pas automatiquement le droit de décider pour les autres.

### 5. Le commun et la capture
Une idée ouverte peut être partagée, attribuée, puis capturée. L’ouverture a besoin de mémoire et de garde-fous.

### 6. Art comme connaissance
L’art n’est pas seulement une décoration morale. Il conserve une vérité sensorielle, existentielle et collective que les tableaux de données ne captent pas.

### 7. Transmission et perte de contrôle
Une idée devient vraiment commune lorsque son initiateur accepte qu’elle circule sans lui.

## Motifs canoniques

### Le carnet
Colin : architecture, questions, schémas.
Réjean : mémoire humaine, détails, contradictions.
Le carnet final : objet qui relie ces deux fonctions.

### Le K
D’abord griffonné, ludique, presque accidentel. Il devient progressivement un signe de reconnaissance. Ne jamais en faire immédiatement un logo parfait.

### Les portes
Porte de cellule, guichet, portail, porte d’église, seuil administratif, accès à un dossier. Question sous-jacente : **qui peut entrer, qui reste dehors, qui détient la clé ?**

### Les mains
Main qui frappe; main qui tend un carnet; main qui écrit; main qui efface; main qui passe le carnet. L’arc de Colin peut être lu par ce que ses mains font.

### La soudure
Motif Matteo : unir ne signifie pas fusionner. Une bonne soudure garde les pièces distinctes tout en leur permettant de porter ensemble.

### La réserve blanche
Associée à Samir : espace qu’on refuse de remplir, droit de ne pas tout raconter, place laissée au regardeur.

### Le bruit et le rythme
Prison = bruit subi. Will transforme le bruit en rythme choisi. KOA transforme le brouhaha en tour de parole.

### La chaleur
Repas, serres, serveurs, proximité humaine. Dans Kristal Farms, une perte thermique devient ressource; métaphore du livre : **ce qui était considéré comme déchet peut devenir lien**.

## Motifs réservés

### La perle blanche
Récupérable uniquement comme image : une chose pure ou précieuse peut être tellement protégée, interprétée ou entourée qu’elle devient invisible. Ne pas récupérer l’intrigue ancienne d’agente infiltrée.

### La musique “qui parle”
Peut exister comme expérience subjective d’un personnage. Le roman ne confirme jamais qu’un réseau occulte de chansons transmet objectivement un message destiné à Colin.


---

# FILE: `core/06_CONTINUITY_MAP.md`

# Carte de continuité — version consolidée

## Ligne globale

### Partie I — Former un espace d’écoute et faire apparaître les premières fonctions

La prison est d’abord un monde de contraintes concrètes. Colin n’a pas encore le droit narratif de transformer chaque personne en architecture. Les premiers chapitres installent trois apprentissages : survivre par la trace, transmettre sans statut, et protéger ce qui est partagé.

**Boucles ouvertes :**

- Colin : opacité/recours non résolu;
- Lucas : apprentissage → KonnectED;
- Arjun : commun ouvert → keenKonnect incomplet;
- Nadia : autographie → méthode KOA;
- Darius : parcours fragmenté → Orgo;
- groupe : la valeur et le mérite sont plus complexes que l’argent/statut.

**État de sortie :** KOA existe comme mot/méthode du cercle; plusieurs fonctions existent, mais l’écosystème n’est pas encore un système achevé.

### Partie II — Tester l’écoute contre la faute, l’effacement et la procédure

Les histoires deviennent moralement moins confortables. Le livre doit montrer que le groupe peut entendre sans blanchir : Robert transgresse le secret; Gabriel sabote; Samir survit dans une zone grise et garde une limite; Alexandre est broyé par une procédure sans continuité.

**Boucles ouvertes/renforcées :**

- Robert → EkoH : une preuve/contribution ne doit pas disparaître;
- Gabriel + Frank → Ethikos : une cause ne suffit pas à justifier l’acte;
- Samir → Kreative : une voix créative doit pouvoir rester visible;
- Alexandre → Orgo : la continuité vaut aussi dans la justice.

**État de sortie :** le groupe sait désormais qu’une bonne architecture doit conserver la mémoire, organiser la contradiction et suivre les parcours sans effacer la responsabilité personnelle.

### Partie III — Composer les fonctions en formes communes

La troisième partie élargit l’échelle : compétence, apprentissage par projet, flux économiques, décision collective, subsistance, protection des communs, création publique, sortie du carnet.

**État de sortie :** les idées ne sont plus une série de réactions aux blessures; elles commencent à former un corpus transmissible et contestable.

---

## Continuité de Colin

1. **Arrivée** — il a subi l’opacité et a répondu par un coup. Sa question de fond est le recours crédible.
2. **Lucas** — première correction à son réflexe d’architecte : parfois aider quelqu’un à lire compte plus que convaincre.
3. **Arjun** — découvre qu’un commun sans attribution peut être capturé.
4. **Nadia/cercle** — apprend que structurer la parole n’autorise pas à parler à la place de l’autre.
5. **Plus que de l’or** — valeur, mérite et reconnaissance deviennent des problèmes collectifs.
6. **KOA** — le groupe fixe une méthode minimale d’écoute/lien.
7. **Robert** — mémoire des contributions et preuves.
8. **Gabriel/Frank** — Colin rencontre le danger de sa propre pente : frustration → passage à l’acte.
9. **Samir** — découvre une autre forme d’effacement, celle de la création et de la dignité.
10. **Alexandre** — Orgo devient transversal, pas seulement social.
11. **Rami** — compétence ≠ statut et compétence ≠ permission.
12. **Marc-André** — les idées peuvent être testées par réalisation, mais l’urgence de forcer l’attention peut recréer la faute.
13. **François** — la trace doit aussi suivre les flux et engagements collectifs.
14. **Antoine** — la légitimité d’une décision exige des raisons visibles; ouvre explicitement la question SmartVote avec Robert dans v17.
15. **Jules** — plusieurs fonctions se combinent pour une infrastructure de subsistance; Kristal Farms naît collectivement.
16. **Liang** — retour à Arjun : ouvrir ne suffit pas, il faut empêcher la capture juridique.
17. **Concert / Will** — une idée peut voyager par la forme et l’émotion, pas seulement par l’explication.
18. **Baptême** — les noms se relient en corpus.
19. **Brèche** — Colin cède le carnet; transmission sans contrôle total.

---

## Boucles de nécessité

### Lucas → Rami → Marc-André — KonnectED/EkoH

- **Lucas :** accéder à l’apprentissage sans honte ni statut.
- **Rami :** reconnaître une compétence réelle sans nier les règles ni blanchir son usage.
- **Marc-André :** apprendre/prouver par projets réels, avec trace individuelle des contributions.

**Progression :** accès → reconnaissance → démonstration publique/traçable.

### Arjun → Liang — keenKonnect

- **Arjun :** ouvrir + attribuer.
- **Liang :** l’ouverture peut elle-même être capturée; il faut une protection juridique/collective.

**Progression :** commun → provenance → anti-reclosure.

### Darius → Alexandre — Orgo

- **Darius :** services sociaux qui recommencent à chaque guichet.
- **Alexandre :** justice qui recommence à chaque acteur/date/document.

**Progression :** parcours social → dossier judiciaire → fonction d’orchestration générale.

### Robert → Antoine — EkoH + SmartVote

v17 met explicitement leurs deux histoires en miroir :

- **Robert :** le fait et la contribution peuvent être effacés.
- **Antoine :** la voix locale peut être ignorée.
- **Darius :** objection immédiate — pondérer la voix peut recréer l’élitisme.
- **Arjun/Colin :** tentative de distinguer prestige hérité et mérite/expérience pertinente.

**Progression :** mémoire des faits → portée de la voix → objection sur la hiérarchie. SmartVote doit rester une hypothèse disputée.

### Gabriel → Antoine — Ethikos

- **Gabriel :** une cause juste se dégrade lorsqu’elle bascule dans le sabotage.
- **Antoine :** une décision opaque peut produire une violence qui détruit précisément l’objet aimé.

**Progression :** contradiction morale → méthode de décision/justification.

### Samir → Will → concert — Kreative

- **Samir :** création précaire/effacée, mais signature persistante.
- **Will :** nom, rythme, formulation juste.
- **Concert :** la voix franchit symboliquement les murs avant que le carnet ne les franchisse matériellement.

**Progression :** créer → nommer → rendre public/transmettre.

### Robert → François → Jules — trace des flux et infrastructure

- **Robert :** faits effacés.
- **François :** chemins de l’argent rendus invisibles.
- **Jules :** conditions et orchestration appliquées à une infrastructure vitale.

**Progression :** mémoire → transparence des flux → gouvernance d’un commun concret.

### Jules + François + Matteo + Samir + Darius — Kristal Farms

Cette chaîne est **collective** :

- Jules : nourriture comme infrastructure;
- François : fonds publics conditionnels + récupération de chaleur de centres de données;
- Matteo : serres locales;
- Samir : objection pratique sur le chauffage;
- Darius : image/nomenclature « fermes de cristal »;
- Jules : reprend « Kristal Farms ».

**Progression :** besoin alimentaire → contraintes matérielles → énergie/chaleur → image commune → nom.

---

## Continuité de Nadia

Les notes v15 fournissent une ligne cohérente :

1. cadre « Faits / Pièces / Effets »;
2. autographie : ne pas écrire à la place de l’autre;
3. Colin aide trop / franchit une limite;
4. bannissement ou éloignement de l’APR;
5. la méthode survit hors de l’atelier et devient partagée;
6. question finale implicite : un dossier bien écrit ne suffit pas si personne ne le lit.

**Décision encore requise :** si le bannissement est conservé, les chapitres ultérieurs doivent respecter matériellement l’absence de Colin de l’APR.

## Continuité de Réjean

- présence préparée dès les premiers chapitres;
- carnet distinct de celui de Colin;
- notes d’abord descriptives, puis de plus en plus attentives aux limites et aux contradictions;
- au chapitre 19, il ne connaît pas exactement le message de Colin à T-Mo : sa mémoire reste humaine, donc partielle.

## Continuité des carnets

- **Carnet de Colin :** schémas, liens, noms, corpus en formation, objet transmis au dehors.
- **Carnet de Réjean :** mémoire des personnes, des scènes, de ce qui a été ressenti/compris depuis sa position.

La distinction protège un thème central : une architecture peut sortir, mais aucune architecture ne remplace le témoin humain.


---

# FILE: `core/07_AMBIGUITIES_AND_DECISIONS.md`

# Ambiguïtés et décisions restantes — v3

## Décisions désormais fermées

### Arrestation de Colin
**Fermé :** branche “motif confidentiel” + coup au policier. La surveillance reste soupçonnée et non confirmée.

### Nadia
**Fermé :** Colin est banni de l’APR au milieu du livre. La continuité ultérieure doit en tenir compte.

### Matteo
**Fermé :** ancien soudeur, sobre, premier carnet; bricolage agricole compatible.

### Konnaxion avant prison
**Fermé par compromis :** Colin possède déjà une proposition collaborative, mais pas l’écosystème final ni son identité collective. Le nom Konnaxion, s’il apparaît dans un document ancien cité, doit être traité comme préfiguration ou nom de travail, pas comme système accompli.

## Décisions encore ouvertes

### 1. Métier exact d’Antoine
Sources : homme de métier/bénévole lié au patrimoine vs docteur/chargé de cours en art ou philosophie morale.

**Recommandation actuelle :** privilégier un homme de métier ou un profil hybride, plus complémentaire au reste du casting. La fonction du chapitre ne dépend pas du titre.

### 2. Couche économique de François
Les fonctions sont stables : flux visibles, conditions sur fonds publics, corrections/clawbacks, rémunération/avantages, responsabilité. Le **nom de module** n’est pas stabilisé.

**Règle :** ne pas inventer un nom dans le roman tant qu’il n’émerge pas naturellement.

### 3. Mort du fils de Colin
Le tableur v9 contient une branche où le fils de Colin meurt à sept ans après une défaillance de protocole hospitalier et où Colin traverse ensuite un épisode psychotique.

**Statut : RÉSERVE MAJEURE.**

Si adopté, il faut réécrire : arrestation, rapport à la psychiatrie, rapport à l’efficacité, motifs de deuil, probablement plusieurs chapitres. Ne jamais l’insérer comme simple anecdote.

### 4. Matthias / synchronicité / King Klown
Le matériau existe, mais son traitement littéral change le genre du livre.

**Option autorisée :** un détenu vit les chansons comme des messages; Colin respecte l’expérience sans confirmer l’explication surnaturelle ou conspiratoire.

### 5. Perle blanche
Image récupérable; intrigue ancienne rejetée.

### 6. Causes d’incarcération non données
Jules, Will, Matteo, Réjean : ne pas combler par invention si la scène n’en a pas besoin.

### 7. Plausibilité juridique et carcérale
Avant publication, vérifier les accusations, procédures, droits de propriété intellectuelle, détails de détention et usages institutionnels. La documentation narrative ne tient pas lieu de validation juridique.


---

# FILE: `core/08_WRITING_PROTOCOL.md`

# Protocole d'écriture

## Avant un chapitre

Lire seulement :

1. le brief du chapitre ;
2. la fiche des personnages présents ;
3. les 2 ou 3 éléments de continuité qui entrent dans la scène ;
4. la matière source correspondante.

Ne pas relire toute la bible juste avant d'écrire : cela produit une prose trop consciente de sa propre architecture.

## Première passe — scène

Écrire la scène sans insérer les noms de modules sauf s'ils sont absolument nécessaires à ce moment du récit.

Questions :

- qui veut quoi dans cette scène ?
- qui résiste ?
- qu'est-ce qui ne peut pas être dit facilement ?
- quel détail de prison empêche la scène de devenir une conversation abstraite ?
- qu'est-ce qui change entre deux personnes ?

## Deuxième passe — idée

Vérifier que l'idée émerge du conflit vécu.

Supprimer ou déplacer tout passage qui ressemble à :

- une page produit ;
- un cahier des charges ;
- une conclusion de consultant ;
- une liste de fonctionnalités ;
- un manifeste placé dans la bouche d'un personnage qui vient d'être bouleversé.

## Troisième passe — voix

Lire uniquement les répliques de chaque personnage. Si plusieurs peuvent être échangées sans qu'on s'en rende compte, les voix ne sont pas assez différenciées.

## Quatrième passe — continuité

Vérifier :

- qui connaît quel nom ?
- qui était présent à quel récit ?
- où se trouve chaque carnet ?
- Colin est-il encore autorisé à l'APR ?
- la scène de Baptême n'est-elle pas préjouée ?
- un personnage ne raconte-t-il pas une seconde version incompatible de sa biographie ?

## Cinquième passe — résonance

Chercher un retour discret d'un motif : porte, papier, silence, trace, lumière, K, voix, écho.

Un seul suffit.

## Règle du carnet de Réjean

Ajouter une note seulement si elle accomplit l'une de ces fonctions :

- relier deux histoires éloignées ;
- conserver une contradiction ;
- remarquer un motif que Colin ne voit pas ;
- témoigner d'un changement du groupe ;
- préparer une question future.

Ne pas utiliser la note pour résumer le chapitre ou annoncer un module.

## Règle de coupe

À la révision, chaque chapitre doit pouvoir perdre 10 à 20 % de son explication sans perdre son sens. Si ce n'est pas possible, l'idée n'est probablement pas encore suffisamment incarnée.

## Règle d'incertitude

Quand deux versions sources se contredisent et que la décision n'est pas structurante pour la scène, **ne pas inventer un faux canon**. Écrire autour du point ou le signaler dans le registre des ambiguïtés.

## Contrôle legacy avant validation d’une scène

Avant de reprendre un passage ancien, vérifier :

1. Est-ce la **fonction** ou le **fait** qui vaut la peine ?
2. Le personnage existe-t-il encore dans le casting actuel ?
3. La causalité ancienne contredit-elle le canon v3 ?
4. Le passage confirme-t-il comme fait ce qui doit rester subjectif ?
5. Peut-on récupérer le geste, l’image ou la tension sans restaurer l’ancien chapitre ?


---

# FILE: `core/09_CHAINES_DE_NECESSITE.md`

# Chaînes de nécessité — personnages → besoins → solutions

## Statut de ce document

Ce document recolle les chaînes causales **à partir du contenu déjà présent dans les versions fournies**. Il ne cherche pas à inventer une justification rétrospective pour chaque nom de l’écosystème.

Le `Colin Row big plan v18` donne le principe directeur : le roman fonctionne comme un **reverse engineering fictif**. La prison sert de microcosme; les récits des détenus exposent les défauts des systèmes existants, puis le groupe déduit progressivement des fonctions qui deviendront KOA/Konnaxion et ses composantes.

Trois formes de genèse existent déjà dans les sources :

1. **Genèse individuelle** — une histoire rend une fonction presque inévitable. Exemple : Darius → continuité de parcours → Orgo.
2. **Genèse en boucle** — un premier récit produit une solution incomplète, un second révèle son garde-fou. Exemple : Arjun → ouverture/attribution; Liang → protection contre la re-fermeture → keenKonnect.
3. **Genèse collective** — aucune biographie seule ne “prouve” la solution; plusieurs expériences se combinent. Exemple : Jules + François + Matteo + Samir + Darius → Kristal Farms.

La règle littéraire reste : **la vie précède le nom**. Le lecteur doit pouvoir formuler « il nous faudrait quelque chose qui… » avant que le module ne soit baptisé.

---

## 1. Colin Row — recours, opacité, séparation de l’information

### Matière source récupérée

La version spécialisée `Colin — Justice` donne une chaîne très précise. Colin travaille sur un projet confidentiel et soupçonne une surveillance. Il va au poste de police non pour “prouver un complot”, mais pour demander comment vérifier que ses droits sont respectés. On lui répond qu’une surveillance autorisée resterait opaque, on le renvoie vers une lecture psychiatrisante de sa peur, puis un rire déclenche son coup de poing. Colin reconnaît son geste.

Le même texte formule ensuite ce qui lui manquait :

- un **tiers indépendant** pouvant vérifier la motivation et la légalité sans tout lui révéler;
- un **recours rapide et abordable**;
- une séparation non seulement des pouvoirs, mais des **informations**;
- une réponse ou attestation limitée : « vos droits sont protégés » ou « voici le recours ».

### Chaîne de nécessité

**Peur/opacité → institution incapable de donner une vérification crédible → humiliation → mauvaise réponse de Colin (violence) → besoin d’un tiers, d’un parcours de recours et d’une méthode de justification.**

### Fonctions de solution déjà présentes

- Ethikos : critères, raisons, contradiction, légitimité procédurale.
- Orgo : porte d’entrée et continuité d’un recours.
- KOA : apprendre à séparer fait, interprétation, effet et action avant le passage à l’acte.

### Statut

**SOLIDE, mais multi-module.** L’histoire de Colin doit lancer le problème transversal plutôt que “vendre” un seul produit.

### Source

`v15/Colin — Justice`; cette branche est désormais le canon v3. L’épisode du pot de fleurs est archivé comme variante rejetée.

---

## 2. Lucas — apprendre sans honte

### Matière source récupérée

Lucas lit difficilement et cache sa honte. Il a quitté l’école tôt; sa petite délinquance est évoquée mais non développée. Colin l’aide à la bibliothèque. Quand le matériel d’écriture est confisqué, Lucas continue en traçant des lettres avec un clou tordu. Le groupe protège cet apprentissage.

La matière `konnectED` formule déjà l’intuition : bibliothèque libre, enseignement pair-à-pair, possibilité d’enseigner sans diplôme officiel et d’apprendre sans honte, validation par l’usage et par la communauté plutôt que par le seul statut.

### Chaîne de nécessité

**Honte + barrière scolaire → apprentissage empêché malgré le désir → entraide directe → besoin d’un espace où apprendre et transmettre sans statut préalable.**

### Solution

**KonnectED** — accès, pair-à-pair, apprentissage comme capacité présente.

### Statut

**SOLIDE.** Il ne manque pas une histoire criminelle complète pour que la fonction du chapitre opère.

---

## 3. Arjun — ouvrir sans perdre l’attribution

### Matière source récupérée

Arjun développe avec d’autres un dispositif médical à bas coût destiné notamment à des usages dans le Sud global. Le code est ouvert. Une grande entreprise récupère l’innovation, la verrouille juridiquement et la brevète. Arjun republie malgré les menaces et se retrouve poursuivi/incarcéré pour la transgression liée à la propriété intellectuelle.

Il formule déjà plusieurs exigences :

- dépôt central ouvert;
- historique de versions;
- attribution automatique de chaque contribution;
- licence empêchant l’appropriation exclusive du travail commun.

### Chaîne de nécessité

**Don ouvert → capture par un acteur plus puissant → disparition de l’auteur collectif → besoin de mémoire des contributions et de règles du commun.**

### Solution

**keenKonnect**, première moitié : ouverture + attribution + historique.

### Statut

**TRÈS SOLIDE**, volontairement incomplet jusqu’à Liang.

---

## 4. Nadia — l’autographie comme méthode

### Matière source récupérée

Nadia dirige l’Atelier Parcours & Réinsertion. Sa règle est nette : une autobiographie doit rester **autographique**. On peut aider quelqu’un à ordonner, dater, distinguer, mais pas écrire ses phrases à sa place. Son cadre « Faits / Pièces / Effets » oblige à distinguer l’événement, ce qui peut l’étayer et ce qu’il a produit chez la personne.

La limite de l’APR apparaît aussi : même une parole mieux structurée peut rester enfermée dans un dossier que peu de gens liront.

### Chaîne de nécessité

**Vie chaotique → récit confus ou confisqué par d’autres → méthode d’écoute structurée → parole rendue plus exacte, mais toujours enfermée institutionnellement → besoin de porter cette méthode hors du seul dossier.**

### Solution

**KOA** comme méthode relationnelle avant d’être une architecture : écouter, distinguer, reformuler sans s’approprier.

### Statut

**TRÈS SOLIDE.** Nadia n’est pas un “module humain”; elle fournit la grammaire qui rend possibles les autres récits.

---

## 5. Darius — une demande doit avoir un trajet

### Matière source récupérée

La fiche `Orgo_` contient une biographie complète. Après la fermeture de son entrepôt, Darius passe par une succession de blocages : numéro A142, mauvaise catégorie de demande, preuve d’adresse impossible, validation par SMS sans forfait, session de bibliothèque verrouillée, rendez-vous postal reçu après la date, relevé d’emploi d’un employeur disparu, Hydro, organismes alimentaires qui redemandent les mêmes preuves, déplacements qu’il ne peut plus payer.

Il finit par voler des pâtes, du lait, du beurre et des œufs. Il ne nie pas le vol. Il décrit plutôt « la suite de nœuds avant le dernier ».

Sa formulation source est déjà presque une spécification : une seule porte, quelqu’un qui tient le fil, une demande visible comme un parcours, savoir où ça bloque, qui fait quoi et quand, sans recommencer à chaque guichet.

### Chaîne de nécessité

**Perte d’emploi → services fragmentés → répétition et délais → épuisement matériel → vol assumé → besoin d’une continuité de parcours.**

### Solution

**Orgo** — orchestration, routage, responsabilité, état visible d’une démarche.

### Statut

**EXCELLENT / MODÈLE DE RÉFÉRENCE.** C’est la chaîne que les autres histoires devraient égaler, sans l’imiter mécaniquement.

---

## 6. Samir — créer, survivre, laisser une trace

### Matière source récupérée

Les deux lignes existantes peuvent être **compatibles** si elles sont hiérarchisées au lieu d’être traitées comme deux biographies exclusives.

Dans `Kreative samir prostitution_`, Samir est illustrateur, travaille au trait et à l’encre, vit de commandes mal payées ou de “visibilité”, n’arrive plus à couvrir ses besoins et a recours à la prostitution. Il fixe une limite : pas de violence. Un client exige cette violence; Samir refuse. Une arrestation liée à la prostitution suit. La fiche insiste sur ce qui le définit : la limite qu’il ne franchit pas, et son motif plastique de la **réserve blanche**.

Dans v16, son versant public apparaît : une fresque engagée est repeinte/effacée, il est accusé de dégradation, et son travail disparaît. En prison, il continue de dessiner et signe discrètement son œuvre. Colin imagine alors un lieu de création où une œuvre sans galerie ni statut peut rester visible.

### Chaîne de nécessité

**Précarité de l’artiste → compromis de survie mais limite morale maintenue → création publique effacée → création carcérale persistante → besoin d’un lieu où créer, signer, montrer et conserver sans gatekeeper.**

### Solution

**Kreative**, avec un écho vers **EkoH** pour la mémoire de l’œuvre.

### Statut

**SOLIDE PAR SYNTHÈSE COMPATIBLE.** Ne pas présenter la prostitution et la fresque comme deux “cas produits”; la précarité et l’effacement sont deux faces d’une même lutte pour conserver une voix.

---

## 7. Robert — une preuve ne doit pas pouvoir être effacée

### Matière source récupérée

Robert travaille au ministère de l’Éducation. Il voit des promotions de complaisance et des personnes compétentes écartées. Il rassemble courriels, faits et preuves. Son rapport disparaît dans la hiérarchie. Il finit par transmettre à un journaliste; la fuite est retracée jusqu’à lui. Il est poursuivi pour violation du secret professionnel/divulgation de documents confidentiels.

Sa blessure finale est double : il a été puni, et ce qu’il avait produit de valable a été effacé comme s’il n’avait jamais contribué.

### Chaîne de nécessité

**Contribution compétente → preuve documentée → effacement institutionnel → fuite illégale/risquée → punition du messager → besoin d’une mémoire résistante et d’une trace des contributions.**

### Solution

**EkoH** — mémoire des faits, des actes, des contributions et de leur provenance.

### Extension source v17

Dans `La voix qui compte`, l’histoire de Robert est combinée à celle d’Antoine pour faire émerger explicitement un registre public de compétence/mérite puis **SmartVote**. Cette extension est source-supported, mais elle doit conserver l’objection de Darius sur l’élitisme.

### Statut

**TRÈS SOLIDE pour EkoH; SOURCE EXPLICITE mais CONTESTÉE pour SmartVote.**

---

## 8. Gabriel + Frank — une cause juste ne rend pas un acte juste

### Matière source récupérée

Gabriel lutte contre un projet de pipeline. Il essaie pétitions, lettres, manifestations et consultations, qu’il perçoit comme jouées d’avance. Il passe au sabotage. Frank le confronte : l’acte violent n’a pas fait gagner la cause et l’a peut-être discréditée.

La scène est forte parce que Frank n’est pas un adversaire extérieur; il conteste de l’intérieur du cercle.

### Chaîne de nécessité

**Cause légitime → canaux de participation ressentis comme factices → radicalisation → sabotage → contradiction interne → besoin d’un lieu/mécanisme où raisons, objections et conséquences soient réellement travaillées avant l’irréversible.**

### Solution

**Ethikos** — contradiction structurée, raisons visibles, décision qui ne confond pas conviction et légitimité.

### Statut

**TRÈS SOLIDE.** Ne pas faire de Frank un simple marchepied vers le produit : sa critique doit pouvoir rester vraie même après l’apparition d’Ethikos.

---

## 9. Alexandre — la justice comme dossier vivant

### Matière source récupérée

Alexandre accumule les audiences reportées; une date saute pour une case cochée au mauvais endroit; des convocations se contredisent; deux avocats commis ou assignés se succèdent et chacun reprend le dossier; une lettre au greffe reste sans réponse.

Darius reconnaît immédiatement le même problème que dans son propre parcours : personne ne possède le fil de bout en bout.

### Chaîne de nécessité

**Dossier judiciaire → délais + acteurs multiples + informations discordantes → chaque changement réinitialise la personne → besoin d’un état partagé, visible et daté.**

### Solution

**Orgo** — tableau de parcours : étape faite/en attente, responsable, échéance, même information courante pour les acteurs concernés.

### Statut

**EXCELLENT.** Alexandre approfondit Darius au lieu de le répéter : Orgo passe du service social à la justice procédurale.

---

## 10. Rami — compétence réelle ≠ reconnaissance ≠ permission

### Matière source récupérée

Le père de Rami était comptable à l’étranger; son diplôme n’est pas reconnu et il finit dans des emplois de nuit/entrepôt. Rami hérite d’une aisance réelle avec les chiffres, mais ses difficultés de langue et d’écriture le bloquent dans un parcours officiel. Il apprend seul comptabilité, fiscalité et droit des affaires.

Il finit par monnayer ce savoir dans des pratiques illégales, notamment en “arrangeant” des états financiers. Au procès, un expert reconnaît la qualité technique de certains travaux tout en maintenant qu’ils étaient illégaux et trompeurs.

### Chaîne de nécessité

**Compétence réelle → absence de reconnaissance institutionnelle → autoformation → usage illégal de la compétence → sanction légitime de la fraude → besoin de reconnaître ce que quelqu’un sait faire sans confondre compétence et droit d’agir.**

### Solution

**KonnectED** — apprentissage et démonstration de compétence; **EkoH** peut porter la trace des travaux/contributions.

### Statut

**EXCELLENT.** Le garde-fou est déjà dans l’histoire : reconnaître une compétence ne blanchit pas son usage.

---

## 11. Marc-André — apprendre et prouver dans le présent

### Matière source récupérée

Marc-André accumule DEP, DEC, AEC, BAC et veut casser les silos entre niveaux. Il imagine des équipes mixtes (DEP/DEC/BAC/maîtrise/doctorat) travaillant sur des livrables réels, avec IA supervisée, sources visibles, tournoi public, évaluation par pairs et traces de contributions (commits, journaux, tests).

La direction rejette son initiative et le réduit à son statut. Il force ensuite l’attention de façon spectaculaire : site web, course nue dans l’université; lors de l’intervention de sécurité, son réflexe de boxeur mène à un coup et à son arrestation. Il ne nie pas sa faute.

### Chaîne de nécessité

**Accumulation de titres sans espace de coopération réel → projet inter-niveaux rejeté par hiérarchie → démonstration provocatrice → faute → besoin d’un espace où l’on apprend par réalisation et où la contribution de chacun est traçable.**

### Solution

**KonnectED** — apprentissage par projet et pairs; **EkoH** — preuve de contribution.

### Statut

**SOLIDE.** Ici le personnage arrive déjà avec un prototype de solution; c’est assumé par la source. Le chapitre doit surtout tester son idée contre les autres, pas faire croire qu’elle naît de zéro.

---

## 12. François — rendre visibles les chemins de l’argent

### Matière source récupérée

v16 fournit la biographie qui manquait à la première bible. François est un ancien cadre d’une grande institution financière décrite comme une « coopérative devenue banque ». En montant dans l’organisation, il voit les flux de subventions, allégements, intérêts et rémunérations converger vers le sommet alors que les risques sont socialisés.

Il commence à tracer les flux sur plusieurs années, rassemble rapports, budgets et communications, soulève le problème en interne, est marginalisé puis tente de passer par un journaliste. Il est pris avec une clé USB contenant des documents qu’il pouvait consulter mais pas emporter. Les chefs d’accusation mentionnés sont violation de confidentialité, fraude et abus de confiance.

Il propose déjà des « vannes » :

- argent public lié à des livrables mesurables;
- limites aux primes/rémunérations lorsque des fonds publics sont engagés;
- mécanismes de récupération si les promesses ne sont pas tenues;
- visibilité citoyenne des flux dans une forme lisible;
- dans la branche v10, gouvernance coopérative et participation directe des membres apparaissent aussi.

Le carnet de Réjean nomme le besoin : une **cardiologie économique**, un organe qui mesure, affiche et corrige la circulation de l’argent collectif.

### Chaîne de nécessité

**Participation au système → observation de la boucle → tentative de documentation interne → silence → fuite de documents → sanction → besoin de transparence continue et de règles automatiques attachées aux fonds collectifs.**

### Solution

Il n’existe pas, dans les sources récentes, un nom de module unique aussi net qu’Orgo ou EkoH. Les fonctions se placent naturellement à l’intersection de :

- **EkoH** : trace/provenance des faits et engagements;
- **Orgo** : circulation, conditions, responsabilités, étapes;
- couche économique/gouvernance de Konnaxion : règles de flux et corrections.

### Statut

**HISTOIRE SOLIDE; NOM DE MODULE NON FIXÉ.** C’est une vraie nuance : le trou biographique est rempli, mais l’architecture produit n’est pas entièrement nommée. Ne pas inventer un nom.

---

## 13. Antoine — la décision doit être explicable avant d’être acceptable

### Matière source récupérée

Les versions divergent sur son métier, mais convergent sur la structure morale. Antoine est profondément lié à un patrimoine religieux/local. Une autorité décide de fermer/vendre ou privilégier une église sans processus qu’il juge transparent. Il tente pétitions, dossiers, réunions ou arguments. Il finit par incendier un bâtiment lié à ce qu’il voulait protéger. Sa phrase morale est claire : **il a détruit ce qu’il voulait sauver**.

La fiche `Ethikos` développe un processus précis : séparer faits et peurs, reformuler honnêtement les arguments adverses, classer les raisons, distinguer expertise et choix communautaire, recommencer lorsque les deux divergent.

### Chaîne de nécessité

**Décision venue d’en haut → raisons/critères non partageables → mobilisation ignorée → violence symbolique devenue réelle → regret → besoin d’un processus où faits, expertise, valeurs et décision sont visibles.**

### Solutions

- **Ethikos** : méthode de délibération et justification.
- **SmartVote** : dans v17, son cas est combiné à Robert pour poser la question du poids relatif de l’expérience locale et de l’expertise pertinente.

### Statut

**TRÈS SOLIDE pour la fonction.** Le métier d’Antoine reste à arbitrer, mais il n’est pas nécessaire pour justifier Ethikos/SmartVote.

---

## 14. Jules — la nourriture comme infrastructure, puis synthèse Kristal Farms

### Matière source récupérée

Jules refuse explicitement de raconter pourquoi il est incarcéré : « Je ne dirai pas pourquoi je suis ici. Parlons de ce qu’on peut changer pour vrai. » Ce n’est donc **pas un trou biographique à remplir**. v16 le présente aussi comme ancien élu municipal déchu, ce qui explique son réflexe de penser en contrats, infrastructures et responsabilité collective.

Sa proposition « Hydro de l’assiette » part de l’idée que la nourriture, comme l’énergie, est une infrastructure de subsistance. Les notes existantes parlent de contrats publics avec conditions, réduction des emballages, équité du travail, horaires prévisibles, consigne/réemploi, mutualisation de cuisines, lutte contre le gaspillage et contre la capture des fonds publics.

### Chaîne de nécessité propre à Jules

**Repas ordinaire + expérience municipale → constat que la subsistance est traitée comme une somme de transactions → besoin d’un cadre commun pour les circuits alimentaires.**

### Genèse collective de Kristal Farms — source v17

La scène de v17 fournit déjà la chaîne exacte :

1. Jules ouvre la question alimentaire.
2. François rattache les fonds publics à des conditions.
3. Matteo, qui bricolait en mécanique agricole, propose des serres locales.
4. Samir demande comment les chauffer en hiver.
5. François propose d’associer centres de données près des barrages et récupération de chaleur vers les serres.
6. Darius imagine des « fermes de cristal ».
7. Jules reprend le nom : **Kristal Farms**.
8. Réjean résume explicitement l’idée comme combinaison de barrages, serveurs et serres.

### Solutions

- logique **Orgo** pour orchestrer les circuits;
- règles économiques héritées de François;
- **Kristal Farms** comme synthèse infrastructurelle collective.

### Statut

**SOLIDE ET COLLECTIF.** Kristal Farms ne doit pas être artificiellement rattaché à un seul trauma de prisonnier. Sa force vient précisément de la combinaison de plusieurs voix.

---

## 15. Liang — rendre l’ouverture juridiquement résistante

### Matière source récupérée

Liang, ingénieur, développe une architecture de prévention/santé appelée « Tour de garde » : seuils, filtration, hygiène, circulation d’objets, etc. Il publie librement sans brevet. Une multinationale reprend l’ensemble, le brevète/intègre et lui adresse des mises en demeure. Liang continue de répliquer, traduire et diffuser malgré l’injonction; il finit incarcéré pour outrage/non-respect de l’ordonnance dans la version spécialisée.

### Chaîne de nécessité

**Don sans brevet → acteur puissant privatise l’assemblage → l’ouverture seule devient une vulnérabilité → désobéissance de Liang → besoin d’une structure juridique/collective empêchant la re-fermeture.**

### Solution

**keenKonnect**, seconde moitié : licence anti-capture, co-signature/gouvernance du commun, continuité de provenance.

### Statut

**TRÈS SOLIDE.** Liang est le garde-fou qu’Arjun ne pouvait pas fournir au chapitre 3.

---

## 16. Will — la voix qui traverse les murs

### Matière source récupérée

Will parle peu mais trouve les mots/noms justes. Il est lyriciste, joue avec répétition et rythme, et devient un vecteur de baptême des idées. Sa cause d’incarcération n’est pas donnée et n’a pas besoin de l’être pour sa fonction. Au concert, la parole créative transforme momentanément l’espace carcéral; Samir en est profondément touché. Will participe ensuite au passage du carnet vers l’extérieur.

### Chaîne de nécessité

**Paroles dispersées → besoin de forme, de rythme et de nom → création partagée → transmission au-delà du cercle.**

### Solution

**Kreative** comme expression/visibilité; **Konnaxion** comme capacité de relier des noms et des récits en corpus transmissible.

### Statut

**SOLIDE COMME PERSONNAGE-PONT**, pas comme “cas social”. Son opacité biographique doit être conservée.

---

## 17. Matteo et Réjean — fonctions structurales, pas modules à justifier

### Matteo

Les sources lui donnent une expérience ouvrière/pratique; v17 précise qu’il bricolait dans la mécanique agricole avant sa peine. Il protège, contredit, ramène les idées au terrain et fournit la proposition des serres locales dans la genèse de Kristal Farms. Son crime n’est pas détaillé.

**Fonction :** test de réalité, lien pratique, confiance.

### Réjean

Il tient le carnet parallèle qui conserve les récits et relie les chapitres. Son rôle est une incarnation humaine de la mémoire que l’écosystème cherchera ensuite à formaliser, sans qu’il faille transformer sa vie en démonstration d’EkoH.

**Fonction :** témoin limité, mémoire, continuité.

### Statut

**VOLONTAIREMENT NON RÉDUITS À UN MODULE.** Ce n’est pas un trou.

---

# Couverture des solutions par la fiction existante

| Solution / fonction | Origine narrative existante | Force de justification | Remarque |
|---|---|---:|---|
| **KOA** | Nadia + cercle des voix + nécessité d’écouter sans confisquer | Très forte | Méthode avant marque |
| **KonnectED** | Lucas → Rami → Marc-André | Très forte | Accès → reconnaissance → projet réel |
| **EkoH** | Robert + traces de Rami/Marc-André + mémoire de Réjean | Très forte | Faits, actes, provenance, contribution |
| **Ethikos** | Colin + Gabriel/Frank + Antoine | Très forte | Recours, contradiction, justification |
| **keenKonnect** | Arjun → Liang | Très forte | Ouverture → attribution → anti-capture |
| **Kreative** | Samir → Will → concert | Forte | Création, visibilité, transmission |
| **Orgo** | Darius → Alexandre | Très forte | Service social → justice procédurale |
| **SmartVote** | Robert + Antoine, avec objection de Darius, v17 | Source explicite mais politiquement contestée | À présenter comme hypothèse débattue, pas évidence |
| **Kristal Farms** | Jules + François + Matteo + Samir + Darius, v17 | Forte et collective | Ne pas chercher un “prisonnier propriétaire” |
| **Couche économique** | François + Jules; branche v10 coopérative | Histoire forte, module moins nommé | Ne pas inventer le nom absent |
| **Konnaxion** | Synthèse/baptême du corpus | Structurellement forte | Contradiction sur l’existence du nom avant prison |

---

# Trous réellement restants après récupération des sources

## 1. Konnaxion avant ou après l’incarcération

v16/v17 présentent parfois Colin comme ayant déjà écrit un manifeste nommé Konnaxion avant d’entrer. Le cadrage v18 et plusieurs scènes de baptême rendent plus forte une naissance collective en prison. **C’est une vraie décision d’auteur, pas une lacune récupérable automatiquement.**

## 2. Arrestation de Colin

Le canon v3 retient `Colin — Justice` + coup de poing au policier. La branche `pot de fleur` est conservée uniquement comme archive.

## 3. Métier d’Antoine

Homme de métier/bénévole dans une version; docteur en art sacré dans une autre. La fonction du récit reste la même. Décision esthétique/sociale à prendre.

## 4. Cause d’incarcération de Jules, Will, Matteo, Réjean

Elle n’est pas donnée ou est explicitement refusée. **Ne pas remplir par invention.** Leur rôle narratif ne l’exige pas actuellement.

## 5. Couche économique

François possède désormais une chaîne humaine complète, mais la solution économique n’a pas un nom/module stabilisé dans les versions récentes. Conserver l’intersection Orgo/EkoH + règles de flux tant que l’auteur n’a pas tranché.

## 6. Plausibilité juridique et factuelle

Plusieurs chefs d’accusation, scénarios de propriété intellectuelle, droit de la prostitution, procédures carcérales et exemples d’entreprises réelles demandent une vérification documentaire avant publication. Ce n’est pas une lacune de personnage.

---

# Test de réécriture à appliquer à chaque chapitre

Avant qu’un nom de solution apparaisse, la scène doit permettre au lecteur de compléter mentalement :

> **« Il nous faudrait quelque chose qui… »**

Puis seulement :

1. le groupe formule la fonction;
2. quelqu’un la conteste;
3. le nom peut émerger;
4. le chapitre conserve ce que la solution **ne résout pas**.

C’est la mécanique déjà présente dans les meilleurs passages sources; la documentation doit désormais la protéger explicitement.


---

# FILE: `core/10_CHAPTER_ENGINE.md`

# Moteur de chapitre — continuité littéraire

Chaque chapitre doit faire avancer **quatre fils simultanément** :

1. **présent carcéral** — quelque chose arrive maintenant, même si le chapitre contient un long récit;
2. **mouvement humain** — relation, honte, confiance, conflit ou responsabilité;
3. **mouvement de Colin** — il apprend ou désapprend quelque chose;
4. **nécessité fonctionnelle** — une fonction devient pensable sans devenir une publicité.

| Ch. | Présent carcéral dominant | Mouvement de Colin | Fonction qui devient nécessaire |
|---:|---|---|---|
| 1 | arrivée, cellule, carnet de Matteo | rage → observation | recours / écoute |
| 2 | apprentissage discret | supériorité implicite → aide sans honte | KonnectED |
| 3 | atelier / vieux ordinateurs | partager suffit → partager exige trace | keenKonnect I |
| 4 | APR | organiser → ne pas écrire pour l’autre | KOA |
| 5 | repas/cour, discussion de valeur | valeur = statut → valeur multiple | EkoH/SmartVote en germe |
| 6 | nuit / code du groupe | projet personnel → signe collectif | KOA nommé |
| 7 | bibliothèque / dossier Robert | vérité dite → vérité conservée | EkoH |
| 8 | débat moral / tension de groupe | bonne cause → méthode compte | Ethikos en germe |
| 9 | art dans la prison | art = décoration → art = connaissance | Kreative |
| 10 | dossiers judiciaires / bibliothèque | système abstrait → parcours concret | Orgo justice |
| 11 | chiffres / langage / tutorat | compétence = diplôme → compétence démontrable | KonnectED + EkoH |
| 12 | tournoi/projet | enthousiasme → preuve + responsabilité | KonnectED/EkoH |
| 13 | récit financier / documents | opacité publique → flux visibles | Orgo/EkoH/économie |
| 14 | patrimoine / délibération | décision juste → processus explicable | Ethikos + SmartVote disputé |
| 15 | repas / infrastructure | module séparé → synthèse physique collective | Kristal Farms |
| 16 | propriété intellectuelle | ouvrir → protéger l’ouverture | keenKonnect II |
| 17 | musique / visite | idée écrite → voix incarnée | Kreative/transmission |
| 18 | cellule / baptême | auteur → co-auteur | Konnaxion |
| 19 | passage du carnet | contrôle → dépossession | transmission |

## Règle de scène

Avant de nommer une solution, le chapitre doit pouvoir produire naturellement :

> **Il nous faudrait quelque chose qui…**

Puis immédiatement :

> **Oui, mais qu’est-ce que ça ne règle pas ?**

La seconde phrase protège le roman contre le discours promotionnel.


---

# FILE: `core/11_CANON_DECISIONS_V3.md`

# Décisions canoniques v3

Ce fichier enregistre les arbitrages effectués après comparaison des versions récentes et anciennes.

| Sujet | Décision v3 | Statut |
|---|---|---|
| Projet de Colin avant prison | Il existe déjà une intuition/proposition collaborative; Konnaxion n’est pas encore l’écosystème final | CANON |
| Arrestation | Motif confidentiel + recours impossible + humiliation + coup au policier | CANON |
| Surveillance | Soupçonnée, jamais confirmée comme conspiration objective | CANON |
| Matteo | Ex-soudeur, sobre, mentor pragmatique, premier carnet | CANON |
| Nadia | APR, Faits/Pièces/Effets, autographie, bannissement de Colin | CANON |
| KOA | Code/méthode de groupe avant d’être un nom de système | CANON |
| Baptême | Une seule grande scène tardive, collective | CANON |
| Kreative | Art = expression + connaissance + mémoire sensible | CANON |
| Ethikos | Doit être précédé par un désaccord moral vécu | CANON |
| SmartVote | Hypothèse contestée, jamais doctrine finale | CANON |
| Kristal Farms | Synthèse collective Jules/François/Matteo/Samir/Darius | CANON |
| Réjean | Scribe parallèle, visible tôt | CANON |
| Will | Voix/rythme/transmission; crime non requis | CANON |
| Jules | Droit à l’opacité sur son incarcération | CANON |
| Mort du fils de Colin | Trop structurante pour intégration automatique | RÉSERVE MAJEURE |
| Matthias / synchronicité musicale | Ressenti subjectif possible; aucune confirmation de messages cachés objectifs | RÉSERVE TRANSFORMÉE |
| Perle blanche | Image métaphorique possible; intrigue d’infiltration/romance rejetée | MOTIF RÉSERVÉ |
| Félix, Marc-Étienne, Simon, Dubois anciens | Personnages non restaurés automatiquement; fonctions récupérables | LEGACY |
| IA juge / médecine automatique | Trop solutionniste sous forme ancienne; matériau de débat seulement | LEGACY / À RECADRER |


---

# FILE: `parts/PART_1_LA_CELLULE.md`

# Partie I — La Cellule

## Chapitres 1 à 6

### État d'entrée

Colin arrive comme individu isolé, blessé dans son rapport aux institutions et encore convaincu que sa capacité à analyser le système est sa principale force.

### Mouvement

La prison lui apprend d'abord quelque chose de plus élémentaire : **tenir, écouter, apprendre les noms, noter, respecter les limites**.

Les six chapitres doivent progressivement transformer une cellule en lieu de circulation de parole sans donner l'impression que le groupe fonde déjà une organisation formelle.

### Étapes

1. recevoir le carnet ;
2. aider quelqu'un à apprendre ;
3. entendre Arjun et la question de l'appropriation ;
4. découvrir la méthode de Nadia et le cercle ;
5. comprendre que la valeur circule entre eux ;
6. donner un mot minimal à cette pratique : KOA.

### Température

Étroite, concrète, nocturne, prudente. Peu de grandes déclarations. La fraternité naît par petits services.

### État de sortie

Le lecteur doit croire qu'un groupe existe avant même que le groupe sache exactement ce qu'il est. KOA est un secret, pas encore une doctrine.

### Héritage v3 intégré

Matteo donne le premier carnet à Colin et sa métaphore de la soudure donne une base humaine au thème de la connexion. L’APR de Nadia doit être installé comme une méthode réellement utile avant que sa rigidité n’apparaisse.


---

# FILE: `parts/PART_2_LES_VOIX_ENTERREES.md`

# Partie II — Les voix enterrées

## Chapitres 7 à 10

### État d'entrée

Le groupe sait écouter. Il croit encore implicitement que rendre les faits visibles suffira peut-être à rendre les choses justes.

### Mouvement

Les récits de Robert, Gabriel, Samir et Alexandre compliquent cette croyance. La vérité peut être effacée ; une cause juste peut produire un acte injuste ; une création peut disparaître ; un parcours administratif peut s'effondrer sans qu'aucun acteur individuel soit monstrueux.

### Question de partie

**Que vaut une voix si personne n'est obligé de la recevoir, de la garder ou de répondre ?**

### Conflit central

Le groupe doit apprendre que « donner une voix » n'est pas suffisant. Il faut aussi : mémoire, contradiction, procédure, relais, continuité.

### Température

Plus conflictuelle que la partie I. Faire entrer le désaccord réel, surtout avec Frank, Nadia et les limites morales des gestes racontés.

### État de sortie

Le projet cesse d'être seulement une communauté d'écoute. Il devient une recherche sur les conditions qui permettent à une parole de compter sans devenir violence.

### Héritage v3 intégré

Le passage à l’acte doit contenir un désaccord moral vécu avant toute formulation d’Ethikos. La fresque de Samir prépare Kreative par l’idée que l’art conserve une connaissance sensible que les dossiers ne savent pas porter.


---

# FILE: `parts/PART_3_LE_MONDE_RECOMPOSE.md`

# Partie III — Le monde recomposé

## Chapitres 11 à 19

### État d’entrée

Le groupe possède une méthode rudimentaire et plusieurs fonctions déjà nées de récits concrets. Il commence maintenant à tester si ces fonctions peuvent se combiner à une échelle plus vaste sans perdre leur origine humaine.

### Mouvement

La progression source est désormais claire :

1. **Rami** — compétence réelle sans reconnaissance → KonnectED/EkoH ;
2. **Marc-André** — apprentissage par projet et trace des contributions → KonnectED/EkoH ;
3. **François** — flux d’argent rendus invisibles → transparence + conditions + orchestration économique ;
4. **Antoine**, en écho à Robert — décision opaque et voix ignorée → Ethikos + question SmartVote ;
5. **Jules et le groupe** — subsistance + flux + énergie + serres → genèse collective de Kristal Farms ;
6. **Liang** — l’ouverture peut être recapturée → seconde étape de keenKonnect ;
7. **Will / concert** — les idées deviennent voix publique ;
8. **Baptême** — les fonctions dispersées deviennent corpus ;
9. **Brèche** — le corpus quitte la prison.

### Règle de partie

La partie III est celle où le risque d’exposé est maximal. Mais les sources fournissent déjà une **matière biographique suffisante**, notamment pour François. La solution n’est donc pas de supprimer mécaniquement les chapitres d’idées; elle est de faire sortir l’idée de la faute, du coût et de la contradiction propres à chaque histoire.

### Genèses non individuelles à protéger

Deux composantes ne suivent pas le modèle « un détenu → un module » :

- **SmartVote** naît du croisement Robert + Antoine et doit conserver l’objection de Darius sur l’élitisme ;
- **Kristal Farms** naît d’une composition Jules + François + Matteo + Samir + Darius.

Les forcer sur un seul personnage appauvrirait le matériau existant.

### Deuxième moitié

À partir de Résonances extérieures, le livre cesse d’ajouter des cas. Il passe de l’analyse à la **transmission** : musique, nom, carnet, porte.

### État de sortie

Le groupe n’a pas prouvé un système parfait. Il a produit un ensemble de fonctions nées de vies concrètes, avec leurs objections, puis un langage permettant de les relier. Le carnet quitte la prison; le futur du projet reste hors de leur contrôle.

### Compression éventuelle

Si une réduction est nécessaire, compresser d’abord **les explications techniques ou macroéconomiques à l’intérieur des chapitres**, pas les chaînes humaines elles-mêmes. Les sources donnent maintenant une justification narrative utile à François, Antoine/SmartVote, Jules/Kristal Farms et Liang.

### Héritage v3 intégré

Dans les chapitres 17–18, privilégier l’expérience corporelle de la musique et l’énergie collective du baptême. Le lecteur doit sentir les fonctions avant d’entendre leurs noms; le baptême relie, il n’enseigne plus.


---

# FILE: `chapter_briefs/01_l_arrivee.md`

# Chapitre 1 — L’arrivée

## Personnages centraux

Colin, Matteo, Réjean

## Tension humaine

L’enfermement et le premier carnet

## Fonction du chapitre

Faire passer Colin du statut de victime convaincue d’avoir été réduit au silence à celui d’homme obligé de regarder et d’écouter.

## Mouvement de scène proposé

Colin arrive, Matteo lui donne un carnet et lui apprend implicitement les règles du lieu. Réjean doit être aperçu assez tôt pour préparer son rôle de scribe.

## Motifs disponibles

Le carnet gris ; clés ; première porte ; silence.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Ne pas nommer Konnaxion comme projet déjà achevé. L’arrestation est fixée par le canon v3 : motif confidentiel, recours impossible, coup assumé; surveillance non confirmée.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Colin

**Chaîne :** Opacité institutionnelle et impossibilité de vérifier ses droits → humiliation → coup assumé → besoin d’un tiers/recours et d’une méthode qui ralentit le passage à l’acte.

**Fonction(s) / solution(s) justifiée(s) :** KOA (méthode), Ethikos (raisons/recours), Orgo (parcours de recours).

**Provenance / garde-fou :** `Colin — Justice` + v16/v17. La variante du pot de fleurs est archivée comme branche rejetée.

## État de sortie

Colin possède une méthode de survie minimale : noter, observer, ne pas se précipiter.

## Dernière résonance recherchée

Le lecteur doit vouloir connaître Matteo et les autres plus que comprendre le programme politique de Colin.

## Optimisation v3

Matteo est **ancien soudeur**, sobre en prison, et donne le premier carnet à Colin. Utiliser sa métaphore de la soudure sans en faire une maxime trop parfaite. L’arrestation suit désormais la branche “motif confidentiel”; ne jamais confirmer une conspiration.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/02_lettres_clandestines.md`

# Chapitre 2 — Lettres clandestines

## Personnages centraux

Colin, Lucas, Matteo, Will

## Tension humaine

La honte de ne pas savoir lire et la solidarité concrète

## Fonction du chapitre

Montrer que le savoir est une liberté avant d’être un système éducatif.

## Mouvement de scène proposé

Colin découvre Lucas en difficulté, l’aide sans l’humilier et le groupe protège peu à peu l’apprentissage. Le geste compte plus que la théorie.

## Motifs disponibles

Clou, bois, lettres, mot « apprendre ».

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Vérifier la plausibilité carcérale du matériel et des interdictions. Éviter de conclure par une fiche complète KonnectED.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Lucas

**Chaîne :** Honte de ne pas savoir lire → apprentissage empêché par le statut et même le matériel → entraide pair-à-pair → besoin d’apprendre/transmettre sans honte ni titre préalable.

**Fonction(s) / solution(s) justifiée(s) :** KonnectED.

**Provenance / garde-fou :** v16 ch.2 + matière `konnectED`.

## État de sortie

Le groupe découvre qu’une compétence peut circuler horizontalement.

## Dernière résonance recherchée

La première victoire du livre doit être minuscule : une phrase lue ou écrite.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/03_le_code_d_arjun.md`

# Chapitre 3 — Le code d’Arjun

## Personnages centraux

Colin, Arjun, Matteo

## Tension humaine

Donner sans perdre la trace

## Fonction du chapitre

Faire sentir la blessure de voir une contribution ouverte capturée par plus puissant que soi.

## Mouvement de scène proposé

Arjun raconte un projet ouvert repris/verrouillé. La conversation introduit attribution, communs et mémoire sans transformer Arjun en professeur de propriété intellectuelle.

## Motifs disponibles

Vieux ordinateurs, code, fichier, nom effacé.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Les mécanismes juridiques doivent être vérifiés. Ne pas surcharger de détails de brevet.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Arjun

**Chaîne :** Innovation offerte → capture/appropriation → besoin de versionnage, attribution et licence commune.

**Fonction(s) / solution(s) justifiée(s) :** keenKonnect, première étape.

**Provenance / garde-fou :** v16 ch.3 + matière keenKonnect; la boucle n’est complète qu’avec Liang au ch.16.

## État de sortie

Colin comprend que partager suppose aussi de préserver l’origine et la contribution.

## Dernière résonance recherchée

Préparer Liang : la question restera incomplète jusqu’au chapitre 16.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/04_le_cercle_des_voix.md`

# Chapitre 4 — Le cercle des voix

## Personnages centraux

Nadia, Colin, Réjean, plusieurs détenus

## Tension humaine

Apprendre à raconter sans se faire voler son récit

## Fonction du chapitre

Installer la méthode d’écoute et la règle d’autographie qui structurent le reste du livre.

## Mouvement de scène proposé

Nadia impose un cadre simple : faits, pièces, effets ; chacun écrit son texte. Colin découvre une discipline qui limite son réflexe de formuler pour autrui.

## Motifs disponibles

Cercle, feuilles A4, stylo rouge, trois questions.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Préparer le bannissement désormais canonique de Colin : l’autographie doit être assez claire pour que l’exclusion soit compréhensible sans faire de Nadia une antagoniste.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Nadia / groupe

**Chaîne :** Récits confus ou écrits par d’autres → Faits/Pièces/Effets + autographie → parole plus exacte mais institutionnellement enfermée.

**Fonction(s) / solution(s) justifiée(s) :** KOA comme méthode d’écoute/non-appropriation.

**Provenance / garde-fou :** `nadia` + v16/v17.

## État de sortie

Le groupe possède une grammaire commune de récit.

## Dernière résonance recherchée

Le lecteur doit sentir que la méthode vient aussi de Nadia, pas seulement de Colin.

## Optimisation v3

Le bannissement de Colin de l’APR est désormais canon. Ce chapitre doit planter très clairement l’autographie afin que l’exclusion ultérieure soit comprise comme une décision institutionnelle défendable, même si elle est imparfaite.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/05_plus_que_de_l_or.md`

# Chapitre 5 — Plus que de l’or

## Personnages centraux

Colin, Samir, Darius, Matteo, Flamel

## Tension humaine

Qu’est-ce qui a réellement de la valeur ?

## Fonction du chapitre

Faire émerger la confiance et la reconnaissance mutuelle sans déclarer encore une méritocratie complète.

## Mouvement de scène proposé

Une conversation de cour ou de réfectoire met en opposition argent, savoir, réputation, expérience et survie matérielle.

## Motifs disponibles

Lumière dorée, métal/barreaux, or, carnet.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Ne pas romanticiser la pauvreté. L’information ne nourrit pas Samir ou Darius.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** groupe

**Chaîne :** Les récits font apparaître que valeur, compétence, contribution et statut ne coïncident pas.

**Fonction(s) / solution(s) justifiée(s) :** Préfiguration EkoH/SmartVote, sans les figer ici.

**Provenance / garde-fou :** Conserver ce chapitre comme problème partagé, pas comme catalogue de modules.

## État de sortie

Le groupe commence à se reconnaître une richesse commune.

## Dernière résonance recherchée

La notion de valeur doit rester ambiguë et incarnée.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/06_koa.md`

# Chapitre 6 — KOA

## Personnages centraux

Colin, Samir, Will, Darius, Matteo

## Tension humaine

Donner un nom au geste d’écoute

## Fonction du chapitre

Créer un premier symbole collectif, intime et fragile.

## Mouvement de scène proposé

Dans la nuit, un K griffonné et les mots du groupe conduisent à KOA. La scène doit être brève, chuchotée, presque enfantine plutôt que solennelle.

## Motifs disponibles

K, ventilation, chuchotement, page sous oreiller.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Ne pas rejouer ici le Baptême complet de Konnaxion. KOA = alliance/méthode provisoire.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** groupe / Will / Colin

**Chaîne :** Besoin d’un rituel court qui protège l’écoute et relie les voix → un mot commun devient pratique.

**Fonction(s) / solution(s) justifiée(s) :** KOA.

**Provenance / garde-fou :** Le nom doit condenser une pratique déjà vécue.

## État de sortie

Le groupe possède un signe secret qui lui appartient à tous.

## Dernière résonance recherchée

Conserver de l’inachevé : ils ne savent pas encore ce que KOA deviendra.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/07_la_denonciation_enterree.md`

# Chapitre 7 — La dénonciation enterrée

## Personnages centraux

Robert, Colin, Matteo, Réjean

## Tension humaine

Que reste-t-il d’une vérité qu’une institution peut faire disparaître ?

## Fonction du chapitre

Déplacer le problème de la parole vers celui de la mémoire et du coût de dénoncer.

## Mouvement de scène proposé

Robert raconte les preuves accumulées, le rapport perdu, la fuite et la sanction. Le groupe ne doit pas conclure trop vite qu’il était juridiquement ou moralement irréprochable.

## Motifs disponibles

Dossier, copie, tiroir, poussière, carnet parallèle.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Éviter le cliché du lanceur d’alerte martyr parfait. Vérifier le cadre légal si des détails précis restent.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Robert

**Chaîne :** Travail compétent + preuves → rapport enterré → fuite → sanction → besoin d’une mémoire/provenance impossible à effacer discrètement.

**Fonction(s) / solution(s) justifiée(s) :** EkoH; graine de SmartVote plus tard.

**Provenance / garde-fou :** v16 ch.7 + v17 `La voix qui compte`.

## État de sortie

Le groupe comprend qu’une parole sans trace résistante peut être annulée.

## Dernière résonance recherchée

Préparer EkoH sans le nommer forcément.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/08_le_passage_a_l_acte.md`

# Chapitre 8 — Le passage à l’acte

## Personnages centraux

Gabriel, Frank, Colin, Matteo

## Tension humaine

Quand une cause juste devient-elle une mauvaise action ?

## Fonction du chapitre

Faire entrer le vrai désaccord moral dans le livre.

## Mouvement de scène proposé

Gabriel raconte son militantisme et le sabotage. Frank refuse de valider le geste. Colin doit écouter les deux et ne pas résoudre immédiatement le débat.

## Motifs disponibles

Cartes, table, mains, pièce retournée.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Ne pas fournir de détails opératoires inutiles sur le sabotage. Ne pas faire de Frank un idiot réactionnaire.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Gabriel / Frank

**Chaîne :** Cause juste → canaux perçus comme factices → sabotage → contradiction interne → besoin de travailler raisons/objections avant l’irréversible.

**Fonction(s) / solution(s) justifiée(s) :** Ethikos.

**Provenance / garde-fou :** v16 ch.8.

## État de sortie

Le groupe découvre qu’écouter signifie aussi supporter la contradiction.

## Dernière résonance recherchée

Ethikos doit naître comme besoin de méthode, pas comme réponse parfaite.

## Optimisation v3

Récupérer la mécanique de v6 : un **désaccord moral spontané** doit exister avant que le groupe ne parle d’Ethikos. Le besoin naît de l’impossibilité de réduire justice/vengeance/responsabilité à un slogan.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/09_la_fresque_effacee.md`

# Chapitre 9 — La fresque effacée

## Personnages centraux

Samir, Colin, Réjean

## Tension humaine

Créer quelque chose que d’autres peuvent effacer

## Fonction du chapitre

Donner au thème de la mémoire une forme artistique et intime.

## Mouvement de scène proposé

Colin surprend Samir en train de dessiner. Samir raconte ce qui a été effacé de son travail et ce que créer lui permet de préserver.

## Motifs disponibles

Carton, hachures, réserve de blanc, mur recouvert.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Résoudre la biographie concurrente « prostitution de survie ». Ne pas empiler deux traumatismes pour produire deux fonctions.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Samir

**Chaîne :** Précarité artistique + limite morale de survie + œuvre publique effacée → besoin d’un lieu où créer, signer, montrer et conserver.

**Fonction(s) / solution(s) justifiée(s) :** Kreative; écho EkoH.

**Provenance / garde-fou :** Synthèse compatible entre `Kreative samir prostitution_` et v16 ch.9.

## État de sortie

La création devient une autre forme de preuve de vie.

## Dernière résonance recherchée

Laisser le dessin lui-même faire une partie de la conclusion.

## Optimisation v3

Ajouter la découverte que l’art est une **forme de connaissance** : poétique, sensorielle, existentielle. Kreative ne sert donc pas seulement à publier des œuvres; il protège une mémoire sensible que les rapports officiels ne savent pas porter.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/10_la_justice_ajournee.md`

# Chapitre 10 — La justice ajournée

## Personnages centraux

Alexandre, Darius, Colin, Matteo

## Tension humaine

Le système peut échouer sans qu’une seule personne décide de l’échec

## Fonction du chapitre

Montrer l’usure produite par les parcours fragmentés.

## Mouvement de scène proposé

Une audience est reportée ; un détail administratif recommence la chaîne. Darius relie cela à sa propre expérience de guichets et de dossiers.

## Motifs disponibles

Banc métallique, numéro, formulaire, fil, porte.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Éviter de présenter toute procédure comme absurdité. Montrer pourquoi certaines étapes existent tout en faisant sentir leur fragmentation.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Alexandre + Darius

**Chaîne :** Reports, convocations discordantes, changements d’avocat → dossier qui recommence → besoin d’un état partagé, responsable et daté.

**Fonction(s) / solution(s) justifiée(s) :** Orgo.

**Provenance / garde-fou :** v16 ch.10; approfondit Darius plutôt que le répéter.

## État de sortie

Le groupe identifie le besoin de continuité de parcours — futur Orgo.

## Dernière résonance recherchée

Sortir de la partie II avec une question d’organisation, pas une solution.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/11_les_chiffres_sans_langue.md`

# Chapitre 11 — Les chiffres sans langue

## Personnages centraux

Rami, Nadia ou le groupe, Colin

## Tension humaine

Savoir quelque chose sans être autorisé à le savoir

## Fonction du chapitre

Distinguer compétence, diplôme, langue, reconnaissance et droit d’exercer.

## Mouvement de scène proposé

Rami raconte son père comptable non reconnu, ses propres difficultés et le moment où il utilise ses compétences dans l’illégalité.

## Motifs disponibles

Diplôme encadré, chiffres, formulaires, traduction.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Ne pas conclure que les professions réglementées sont inutiles. La fraude de Rami doit rester une vraie faute.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Rami

**Chaîne :** Compétence réelle + diplôme/langue non reconnus → autoformation → usage frauduleux du savoir → besoin de reconnaître la compétence sans confondre reconnaissance et permission.

**Fonction(s) / solution(s) justifiée(s) :** KonnectED + EkoH.

**Provenance / garde-fou :** v15 `konnectED` + v16 ch.11.

## État de sortie

La notion de compétence réelle gagne une dimension sociale et migratoire.

## Dernière résonance recherchée

Très bon pont vers Marc-André : savoir démontré plutôt que statut seul.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/12_le_tournoi_du_present.md`

# Chapitre 12 — Le tournoi du présent

## Personnages centraux

Marc-André, Colin, Darius, Will

## Tension humaine

Apprendre dans le présent

## Fonction du chapitre

Donner une incarnation énergique de l’apprentissage par l’action tout en montrant l’imprudence de Marc-André.

## Mouvement de scène proposé

Marc-André décrit son tournoi pilote, l’enthousiasme des équipes, le conflit avec la hiérarchie et son propre geste de violence.

## Motifs disponibles

Gymnase imaginé, défi, chrono, rythme frappé par Will.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Utiliser la réécriture v17 comme base, mais réduire les listes. L’IA reste un outil visible, non un argument promotionnel.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Marc-André

**Chaîne :** Hiérarchies scolaires → projet inter-niveaux rejeté → provocation/faute → besoin d’apprendre par réalisation avec trace des contributions.

**Fonction(s) / solution(s) justifiée(s) :** KonnectED + EkoH.

**Provenance / garde-fou :** `Ekoh nu` + v16/v17 tournoi.

## État de sortie

Le groupe comprend qu’une réalisation peut devenir une preuve de compétence.

## Dernière résonance recherchée

La joie du tournoi doit être plus mémorable que son architecture.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/13_le_siphon.md`

# Chapitre 13 — Le siphon

## Personnages centraux

François, Colin, Matteo, Jules

## Tension humaine

Voir où va l’argent et qui supporte le risque

## Fonction du chapitre

Donner une dimension économique sans sortir du roman.

## Mouvement de scène proposé

François raconte son propre parcours de cadre : il croit d’abord à l’utilité de l’institution, découvre les flux, les documente, est marginalisé puis tente de passer par un journaliste avant l’épisode de la clé USB. Les chiffres doivent sortir de cette trajectoire, pas la remplacer. Quelqu’un peut contester l’interprétation ou la portée de ses conclusions.

## Motifs disponibles

Pluie, table, flèches, boucle.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Chapitre à haut risque d’exposé. Les exemples d’entreprises réelles exigent vérification ou fictionalisation.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** François

**Chaîne :** Cadre financier → trace les flux → alerte sans effet → tente journaliste → clé USB/sanction → besoin de transparence continue et de règles attachées aux fonds collectifs.

**Fonction(s) / solution(s) justifiée(s) :** EkoH + Orgo + couche économique non nommée.

**Provenance / garde-fou :** v16 ch.13. La matière humaine est déjà présente; ne pas inventer une nouvelle perte.

## État de sortie

Le groupe ajoute la transparence des flux à sa réflexion.

## Dernière résonance recherchée

La matière humaine existe déjà dans v16. Compresser l’exposé macro si nécessaire, mais conserver l’arc : participation → découverte → documentation → isolement → faute/transgression → besoin de transparence structurelle.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/14_l_eglise_brûlee.md`

# Chapitre 14 — L’église brûlée

## Personnages centraux

Antoine, Nadia/le groupe, Colin

## Tension humaine

Détruire ce qu’on voulait sauver

## Fonction du chapitre

Porter à son maximum le paradoxe moral du livre : l’absence de méthode peut nourrir le désespoir, sans innocenter l’incendie.

## Mouvement de scène proposé

Antoine raconte la fermeture opaque d’un lieu auquel il tenait et son incendie volontaire. Colin lui demande s’il aurait pu accepter une décision contraire si le processus avait été transparent.

## Motifs disponibles

Pierre, bois, feu, lettre de décision, deux églises.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Le métier exact reste ouvert; privilégier un profil de métier/bénévole ou hybride afin de différencier Antoine des profils académiques legacy.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Antoine + Robert en écho

**Chaîne :** Décision opaque → démarches ignorées → incendie et regret → besoin de raisons visibles, expertise et participation; combiné à Robert, ouvre le poids de la voix.

**Fonction(s) / solution(s) justifiée(s) :** Ethikos + SmartVote (hypothèse contestée).

**Provenance / garde-fou :** v16 ch.14 + v15 `Ethikos` + v17 `La voix qui compte`. Garder l’objection d’élitisme de Darius.

## État de sortie

Le groupe comprend que la justice tient aussi au chemin de décision.

## Dernière résonance recherchée

Écho de Gabriel, mais plus tragique : Antoine détruit l’objet même de son attachement.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/15_l_hydro_de_l_assiette.md`

# Chapitre 15 — L’Hydro de l’assiette

## Personnages centraux

Jules, Colin, Matteo, Réjean

## Tension humaine

Traiter la subsistance comme un commun sans effacer le désir ni le métier

## Fonction du chapitre

Élargir les idées au quotidien le plus matériel : manger.

## Mouvement de scène proposé

À partir d’un repas de prison, Jules développe l’intuition de la nourriture comme infrastructure. La scène devient ensuite collective : François apporte les conditions financières et l’idée de chaleur récupérée, Matteo les serres locales, Samir la contrainte hivernale, Darius l’image des « fermes de cristal », et Jules reprend le nom Kristal Farms. Son refus de raconter pourquoi il est incarcéré doit être respecté.

## Motifs disponibles

Plateau, maïs, chaleur, vaisselle, table.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Énorme risque de manifeste programmatique. Garder quelques principes et laisser le reste à la documentation hors roman.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Jules + François + Matteo + Samir + Darius

**Chaîne :** Nourriture comme infrastructure → conditions sur fonds → serres locales → contrainte de chauffage → chaleur des serveurs près des barrages → « fermes de cristal ».

**Fonction(s) / solution(s) justifiée(s) :** Orgo/logique de flux + Kristal Farms, genèse collective.

**Provenance / garde-fou :** v15 Jules + v17 Hydro. Le refus de Jules de raconter son crime est volontaire.

## État de sortie

Le groupe comprend que certaines infrastructures sont des relations sociales avant d’être des marchés.

## Dernière résonance recherchée

Le lecteur doit se souvenir d’un repas, pas d’un cahier des charges.

## Optimisation v3

La contribution de Matteo devient encore plus naturelle : ex-soudeur ayant aussi bricolé de la machinerie agricole, il pense en chaleur, structures et serres. Kristal Farms doit conserver une naissance réellement collective.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/16_la_tour.md`

# Chapitre 16 — La tour

## Personnages centraux

Liang, Colin, Arjun, Nadia ou le groupe

## Tension humaine

Ouvrir sans se faire capturer

## Fonction du chapitre

Fermer la boucle ouverte au chapitre 3 : le commun a besoin de garde-fous.

## Mouvement de scène proposé

Liang raconte une invention conçue comme don, puis appropriée/verrouillée juridiquement. Arjun reconnaît sa propre histoire mais la conclusion doit être plus mature.

## Motifs disponibles

Seuil, carillon, plan, fichier, lettre juridique.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Vérifier la plausibilité brevet/publication. Réduire la spécification technique de la Tour de garde.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Liang

**Chaîne :** Don ouvert → brevet/capture par un acteur puissant → diffusion malgré injonction → besoin d’empêcher juridiquement la re-fermeture du commun.

**Fonction(s) / solution(s) justifiée(s) :** keenKonnect, seconde étape.

**Provenance / garde-fou :** `Keen konnect tour de garde` + v16/v17.

## État de sortie

Le groupe distingue ouverture, attribution et protection du commun.

## Dernière résonance recherchée

Préparer la synthèse finale des noms sans encore tout relier.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/17_resonances_exterieures.md`

# Chapitre 17 — Résonances extérieures

## Personnages centraux

Will, T-Mo, B-Ice, Colin, groupe

## Tension humaine

Être entendu par quelqu’un qui vient du dehors

## Fonction du chapitre

Changer de registre : moins d’analyse, plus de corps, musique et émotion.

## Mouvement de scène proposé

Un concert/atelier culturel fait entrer le dehors. Will, habituellement bref, prend de l’espace. T-Mo devient la première preuve qu’une voix peut franchir le cercle.

## Motifs disponibles

Basse, vibration, foule, rythme, regard des gardiens.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Ne pas en faire un triomphe hollywoodien. Le dehors n’est qu’une ouverture temporaire.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Will / Samir / T-Mo

**Chaîne :** Voix enfermées → création publique dans la prison → parole qui franchit symboliquement les murs.

**Fonction(s) / solution(s) justifiée(s) :** Kreative + transmission.

**Provenance / garde-fou :** v16/v17 concert + `Will`.

## État de sortie

Le groupe sent que ses voix peuvent voyager autrement que par des dossiers.

## Dernière résonance recherchée

Préparer la décision de transmettre le carnet.

## Optimisation v3

Récupérer l’idée de v11 : **la chanson doit d’abord changer l’état du groupe** avant toute explication de Kreative. Le corps comprend avant le concept. La musique peut sembler “parler” à certains, mais le texte n’en confirme jamais une origine surnaturelle ou cachée.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/18_baptême.md`

# Chapitre 18 — Baptême

## Personnages centraux

Colin, Samir, Will, Darius, Matteo, Réjean, groupe

## Tension humaine

Relier les noms sans transformer la scène en branding

## Fonction du chapitre

Faire converger les motifs et donner un nom tardif à la famille d’idées.

## Mouvement de scène proposé

Après les expériences accumulées et la résonance extérieure, les noms épars sont reliés. Konnaxion devient moins une marque qu’une façon de dire : ceci vient de nous tous.

## Motifs disponibles

K, page, souffle, murmure, noms écrits puis barrés/reliés.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Une seule scène de Baptême dans le livre. Éviter d’expliquer l’étymologie complète de chaque nom.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** groupe

**Chaîne :** Fonctions dispersées déjà éprouvées → besoin de les relier sans effacer leur provenance humaine.

**Fonction(s) / solution(s) justifiée(s) :** Konnaxion comme synthèse.

**Provenance / garde-fou :** Attention à l’ambiguïté : si Konnaxion préexiste, le baptême devient réappropriation/re-définition.

## État de sortie

Le groupe possède une identité transmissible.

## Dernière résonance recherchée

L’émotion doit venir de la mémoire des personnes derrière chaque nom.

## Optimisation v3

Récupérer l’énergie de v9 : cellule trop pleine, Samir dessine, propositions de noms, mauvais jeux de mots, rires étouffés, K qui circule. Supprimer toute présentation “module numéro un / deux / trois”. Le lecteur connaît déjà les fonctions; ici, on ne fait que **les relier et les nommer**.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `chapter_briefs/19_la_breche.md`

# Chapitre 19 — La brèche

## Personnages centraux

Colin, Will, T-Mo, Réjean, Nadia/Bastien

## Tension humaine

Laisser partir ce qu’on a construit

## Fonction du chapitre

Achever l’arc de Colin par une perte volontaire de contrôle.

## Mouvement de scène proposé

La question « qui nous lira ? » révèle la limite du dossier institutionnel. Plus tard, Colin profite du départ de T-Mo pour lui confier le carnet. Réjean ne sait pas exactement ce qui a été dit.

## Motifs disponibles

Pluie, fourgon, portail, carnet absent, mains vides.

## Ce qu'il ne faut pas résoudre ici

Ne pas expliquer l'ensemble de KOA/Konnaxion. Ne nommer que ce qui a réellement émergé à ce stade. Garder au moins une part de contradiction ou d'inachevé.

## Risques / alignement

Si Colin a été banni de l’APR, ajuster sa présence au début. Richard Desjardins/Kristal Farms doivent rester énigmatiques si la suite n’est pas écrite.

## Chaîne de nécessité récupérée des sources

**Porteur(s) :** Colin / Will / T-Mo / Réjean

**Chaîne :** Corpus enfermé → carnet confié au dehors → perte de contrôle en échange de transmission.

**Fonction(s) / solution(s) justifiée(s) :** Déploiement de Konnaxion; crochet Kristal Farms.

**Provenance / garde-fou :** Le message Richard Desjardins/Kristal Farms reste mystérieux quant à sa portée extérieure, pas nécessairement quant au concept interne.

## État de sortie

Le carnet est dehors ; Colin reste dedans. L’idée cesse d’être sa propriété.

## Dernière résonance recherchée

Fin sur l’incertitude. « KOA est libre » fonctionne si elle n’est pas suivie d’une promesse de réussite.

## Optimisation v3

Le bannissement de Colin de l’APR doit être respecté : il ne revient pas simplement dans l’atelier comme si rien ne s’était passé. La transmission finale doit naître d’un circuit parallèle, notamment Will/T-Mo/Réjean.

## Continuité du présent carcéral

Même si le chapitre contient un récit du dehors, maintenir au moins un événement observable dans la prison : déplacement, repas, travail, bruit, règle, gardien, objet, attente ou interaction qui modifie la scène. Le récit ne doit pas suspendre le présent carcéral.


---

# FILE: `reference/ECOSYSTEM_LEXICON.md`

# Lexique de l’écosystème — origine narrative et fonction

## Règle principale

Un nom n’a le droit d’apparaître que lorsque le lecteur a déjà rencontré le besoin auquel il répond. Le nom **condense** une découverte; il ne doit pas la remplacer.

## KOA

**Origine narrative :** Nadia et l’APR fournissent la grammaire d’écoute : faits, pièces, effets, autographie. Le cercle transforme ensuite cette pratique en rituel/langage partagé.

**Besoin :** pouvoir écouter et structurer sans confisquer la parole; ralentir le passage de la perception à l’action.

**Fonction :** méthode relationnelle, premier lien du groupe.

**Sources :** `nadia`, chapitres 4–6, `branding`.

## Konnaxion

**Origine narrative :** synthèse tardive des fonctions/noms du corpus.

**Besoin :** relier les solutions locales sans effacer leur origine humaine.

**Fonction :** famille/architecture qui met les composantes en relation.

**Ambiguïté :** certaines versions font préexister le nom avant la prison. Si cette option reste, le “baptême” doit devenir une réappropriation collective plutôt qu’une invention.

## KonnectED

**Origines :**

- Lucas : apprendre sans honte ni statut;
- Rami : compétence réelle sans reconnaissance officielle;
- Marc-André : apprendre par projet et prouver par contribution.

**Besoin :** accès + transmission pair-à-pair + démonstration de compétence.

**Garde-fou :** compétence reconnue ne signifie pas permission automatique d’exercer ni effacement des fautes.

## EkoH

**Origines :**

- Robert : rapport et contribution effacés;
- Rami/Marc-André : besoin de tracer les réalisations réelles;
- Réjean : mémoire humaine du groupe.

**Besoin :** provenance, mémoire des faits/actions/contributions.

**Garde-fou :** droit à l’opacité, contestation d’une trace, risque de réputation permanente.

## Ethikos

**Origines :**

- Colin : besoin d’un recours dont les raisons peuvent être vérifiées;
- Gabriel + Frank : contradiction avant passage à l’acte;
- Antoine : décision locale/patrimoniale non justifiée;
- Nadia : discipline de distinction et reformulation.

**Besoin :** rendre une décision explicable, contestable et moralement examinable.

**Garde-fou :** une procédure propre ne garantit pas une décision juste; le désaccord doit pouvoir subsister.

## keenKonnect

**Origines en deux temps :**

1. Arjun : ouvrir, versionner, attribuer.
2. Liang : empêcher qu’un acteur puisse refermer juridiquement le commun.

**Besoin :** collaboration ouverte avec provenance et protection anti-capture.

## Kreative

**Origines :**

- Samir : précarité, création effacée, besoin de signer et conserver;
- Will : nom, rythme, voix;
- concert : rendre la parole publique et transmissible.

**Besoin :** espace de création/visibilité qui ne dépend pas entièrement des gatekeepers institutionnels.

## Orgo

**Origines :**

- Darius : parcours social qui recommence à chaque guichet;
- Alexandre : dossier judiciaire qui recommence à chaque acteur;
- François/Jules : extension vers orchestration de flux/conditions collectives.

**Besoin :** tenir le fil d’un parcours : état, responsable, prochaine étape, délai, passage entre acteurs.

**Étymologie source :** « Organise and Go » dans le matériel de branding.

## SmartVote

**Origine narrative explicite :** v17 `La voix qui compte` après les récits de Robert et Antoine. Le groupe imagine une mémoire de compétence/contribution; Darius objecte que pondérer les voix peut recréer l’élitisme; Arjun nomme SmartVote comme pondération par expérience/réputation pertinente.

**Besoin :** distinguer droit de parole, connaissance pertinente et décision collective.

**Statut littéraire :** **hypothèse contestée**, pas solution acquise.

**Objections à conserver :** reproduction des privilèges, définition du mérite, surveillance/réputation, égalité citoyenne, capture du système de notation.

## Kristal Farms

**Origine narrative explicite et collective :** v17 `L’Hydro de l’assiette`.

- Jules : alimentation comme infrastructure;
- François : conditions sur fonds publics + récupération de chaleur des centres de données près des barrages;
- Matteo : serres locales;
- Samir : contrainte du chauffage;
- Darius : image des « fermes de cristal »;
- Jules : nom « Kristal Farms ».

Réjean résume l’assemblage comme **barrages + serveurs + serres**.

**Fonction :** synthèse physique de plusieurs principes : énergie, chaleur, alimentation, infrastructures locales et orchestration.

**Crochet final :** le message « Richard Desjardins – Kristal Farms » peut rester mystérieux quant à son **déploiement extérieur**, même si le groupe connaît déjà l’idée.

## Couche économique / gouvernance des flux

**Origine :** François, prolongé par Jules; branche plus ancienne v10 sur la gouvernance coopérative.

**Besoin :** rendre visibles les flux de fonds publics, attacher les fonds à des engagements mesurables, déclencher récupération/correction lorsque les engagements échouent.

**Statut :** fonctions nettes, **nom de module non stabilisé dans les sources récentes**. Ne pas en inventer un dans la documentation.

## Règle de nommage de scène

Avant le nom :

> « Il nous faudrait quelque chose qui… »

Après le nom :

> « Oui, mais qu’est-ce que ça ne règle pas ? »

La seconde question empêche l’écosystème de devenir une publicité à l’intérieur du roman.


---

# FILE: `reference/LEGACY_CAST_FUNCTIONS.md`

# Fonctions récupérables de l’ancien casting

| Ancien personnage | Fonction utile | Destinataire actuel / traitement |
|---|---|---|
| Matteo ancien | soudeur, sobriété, carnet, mentor | Matteo actuel — intégré |
| Dr Antoine Dubois | éthique communicationnelle, protocole de débat | Antoine + Nadia + Gabriel/Frank |
| Simon Beaulieu | initiative, technique, relais extérieur | Marc-André / Arjun / Will / T-Mo |
| Félix Bélanger | critique des brevets, voix antipathique mais parfois juste | principe à redistribuer; ne pas restaurer automatiquement |
| Marc-Étienne Gauthier | traçabilité/secret industriel, expertise technique | Arjun / Liang / EkoH |
| Yanis | faille santé mentale / déjudiciarisation | réserve; pas nécessaire au squelette actuel |
| Matthias | expérience de synchronicité musicale | réserve subjective seulement |
| ancien Jules hacktiviste | urgence écologique, colère, territoire | tonalité possible de Jules, pas son crime canonique |
| ancien Will rappeur | art comme lien et diffusion | Will actuel — fonction conservée |
| ancien Samir persécuté | vulnérabilité, solidarité | ne pas écraser le Samir actuel; certains gestes de protection peuvent survivre |


---

# FILE: `reference/LEGACY_RECOVERY.md`

# Récupération des anciennes versions

## Principe

Les versions v4–v11 et documents isolés sont traités comme un **réservoir de fonctions, scènes, gestes et motifs**, non comme un second canon concurrent.

## À récupérer dans le canon

### Matteo : soudure + carnet + sobriété
Les anciennes versions donnent à Matteo une cohérence forte : ancien soudeur, sobriété retrouvée, premier carnet donné à Colin, métaphore de la soudure humaine. **Intégré en v3.**

### Nadia : APR et bannissement
Le document spécialisé est très bien aligné avec le réalisme carcéral : Faits/Pièces/Effets, autographie, Colin participant puis banni. **Intégré en v3.**

### Art = forme de connaissance
v5 formule une idée précieuse : connaissance scientifique, technique, empirique, mais aussi poétique, sensorielle et existentielle. Les œuvres deviennent des “bibliothèques vivantes”. **Intégré à Kreative et aux motifs.**

### Ethikos né d’un désaccord
v6 contient un débat nocturne sur vengeance, justice et meurtre d’un détenu. Le groupe découvre qu’un désaccord moral riche existe avant toute plateforme. **Mécanique intégrée; événement précis adaptable.**

### Baptême collectif
v9 donne une bonne énergie : cellule pleine, Samir dessine, propositions de noms, rires, K récurrent. **Énergie intégrée; séquence “module 1, 2, 3…” rejetée.**

### Will et l’effet de la musique
v11 montre une chanson qui modifie réellement l’état du groupe avant qu’on parle de Kreative. **Intégré.**

## À fusionner sans restaurer l’ancien casting

### Ancien Dr Antoine Dubois
Fonction utile : tours de parole, classement des arguments, reformulation, vote après clarification. À distribuer entre Nadia, Antoine actuel, Gabriel/Frank et le groupe.

### Félix et Marc-Étienne
Bonne idée : des personnages antipathiques peuvent énoncer une critique valable des brevets et de la capture de l’innovation. Ne pas les restaurer nécessairement; garder le principe que **la vérité ne vient pas seulement des personnages sympathiques**.

### Simon Beaulieu
Ancienne fonction technique et de transmission. Plusieurs de ses fonctions ont été redistribuées à Marc-André, Arjun, Liang, Will et T-Mo.

### Ancien Jules militant écologiste
Peut nourrir ses connaissances et son ton, mais sa version actuelle garde le droit de ne pas raconter son crime.

## À conserver en réserve

### Mort du fils de Colin
Puissante, mais trop structurante. Voir `material/characters/COLIN_SON_RESERVE.md`.

### Synchronicité musicale / Matthias
Conserver seulement comme expérience subjective ou motif. Ne pas transformer les chansons en preuves objectives d’un réseau caché.

### Perle blanche
Conserver l’image, abandonner l’intrigue.

## Obsolète dans le canon actuel

- conspiration gouvernementale explicitement confirmée;
- Colin objectivement “ennemi du système” et héros sacrifié;
- IA juge comme solution certaine et neutre;
- démonstration “un problème social = une réforme KOA”;
- présentation séquentielle de tous les modules comme pitch;
- intrigue de l’agente pastorale infiltrée, romance, proxénétisme et victoire judiciaire;
- King Klown comme marionnettiste objectivement derrière les artistes;
- récupération de tout l’ancien casting au lieu de fusionner les fonctions.


---

# FILE: `reference/SOURCE_INDEX.md`

# Index des sources utilisées

## Sources récentes / principales

- **v16** — squelette narratif de 19 chapitres; source principale de structure.
- **v17** — réécritures locales, SmartVote, genèse collective de Kristal Farms; numérotation de partie III non fiable.
- **big plan v18** — intention du livre : prison-microcosme, fiction philosophique, reverse engineering des fonctions à partir des vies.
- **fiches v15** — biographies, voix, Orgo, Ethikos, KonnectED, keenKonnect, Kreative, EkoH, Jules, Nadia, Will.

## Anciennes versions étudiées

### `Colin — Jsutice.docx`
Source canonique retenue pour l’arrestation : motif confidentiel, surveillance soupçonnée, besoin d’un tiers indépendant et d’un recours accessible, coup assumé.

### `Colin espionné frappe policier.docx`
Conserve l’atmosphère et la scène du poste; rejeter les affirmations de conspiration certaine.

### `Colin v4, outline.docx`
Réservoir d’anciennes fonctions : Matteo, Samir, Jules, santé mentale, justice, éducation, culture. Architecture trop démonstrative pour être restaurée.

### `Colin Row v5.docx`
Apport majeur : art comme forme de connaissance, bibliothèques vivantes; Matteo et premiers moteurs.

### `Colin Row v6.docx`
Apport majeur : débat moral spontané avant Ethikos; formulation ancienne de plusieurs modules à ne pas reprendre comme exposé.

### `Colin Row v9.docx`
Réservoir de scènes : baptême collectif, Matteo soudeur, transmission extérieure, Kristal Farms ancienne, Dubois, personnages legacy.

### `Colin Row v9.xlsx`
Carte de continuité : fils “Confidence / Péripéties carcérales / Rencontres / Évolution de Konnaxion / Psychologique de Colin / Lieu”, biographies anciennes, scènes et possibilités. À utiliser comme outil de continuité, pas comme canon de faits.

### `Colin Row, infiltré v10.docx`
Source de plusieurs récits développés, notamment Robert et transmission; branche ancienne utile mais souvent plus solutionniste.

### `Colin row v11.docx`
Apports : quotidien carcéral, Will/Kreative, transmission par Taktika, certains mécanismes d’apprentissage et débat.

### `Colin, sync music.docx`
Réserve poétique seulement. L’interprétation littérale des chansons comme messages objectifs est incompatible avec le contrat actuel.

### `nadia.docx`
Source forte devenue canonique pour l’APR, l’autographie et le bannissement de Colin.

### `scene additionnelle Colin Row agente pastorale.md`
Intrigue rejetée. Seule l’image de la perle blanche est conservée comme motif possible.


---

# FILE: `reference/SOURCE_RECOVERY.md`

# Récupération des contenus existants — ce qui a comblé les trous

Ce fichier trace les corrections apportées à la documentation après une seconde lecture ciblée des sources.

## Corrections majeures

### François

**Avant :** décrit comme surtout théorique, histoire personnelle insuffisante.

**Après récupération :** v16 ch.13 fournit déjà une trajectoire complète (cadre financier → découverte/documentation des flux → mise à l’écart → tentative journaliste → clé USB → accusations). Le chapitre peut donc rester profondément incarné sans inventer de nouvelle perte.

### SmartVote

**Avant :** considéré comme insuffisamment justifié.

**Après récupération :** v17 `La voix qui compte` contient sa genèse explicite : Robert + Antoine → mémoire/voix → objection de Darius sur l’élitisme → SmartVote formulé par Arjun. Le point faible n’est plus l’origine narrative, mais la nécessité de garder le débat ouvert.

### Kristal Farms

**Avant :** considéré comme crochet ou solution insuffisamment reliée aux vies.

**Après récupération :** v17 `L’Hydro de l’assiette` donne une genèse collective complète : Jules + François + Matteo + Samir + Darius. Il ne faut surtout pas inventer un prisonnier unique qui “justifie” Kristal Farms.

### Samir

**Avant :** deux biographies mises en opposition.

**Après récupération :** elles peuvent fonctionner comme deux plans d’une même vie : précarité/prostitution/limite morale (v15) + effacement public de l’œuvre (v16). La synthèse est compatible si elle reste sobre et si l’incarcération exacte n’est pas artificiellement réattribuée.

### Colin

**Avant :** motif d’arrestation très ouvert.

**Après récupération :** `Colin — Justice` renforce fortement la branche du coup au policier déjà utilisée par v16/v17 et, surtout, fournit la fonction recherchée : tiers indépendant + recours + séparation des informations. `Pot de fleur` est désormais une branche archivée et non canonique.

### Jules

**Avant :** absence de crime vue comme potentiel manque.

**Après récupération :** la fiche source refuse explicitement de raconter le crime. L’opacité est donc un choix de personnage déjà écrit, à préserver.

## Trous qui ne peuvent pas être comblés sans décision/invention

- Konnaxion nommé avant la prison vs baptisé collectivement;
- profession d’Antoine;
- bannissement de Colin par Nadia et ses conséquences de continuité;
- nom final de la couche économique autour de François;
- détails criminels de Will/Matteo/Réjean/Jules lorsque les sources les taisent;
- plausibilité juridique de plusieurs scénarios.

Ces points restent dans `core/07_AMBIGUITIES_AND_DECISIONS.md`.

## Ajout v3 — récupération legacy

Les anciennes versions ont permis de fermer plusieurs décisions : Matteo ex-soudeur et premier carnet; Nadia et le bannissement; art comme connaissance; Ethikos précédé d’un débat moral; baptême collectif débarrassé du pitch de modules; Will comme preuve sensible de Kreative.

Les éléments trop transformateurs restent en réserve : mort du fils de Colin, synchronicité musicale littérale, perle blanche comme intrigue.


---

# FILE: `reference/VERSION_ALIGNMENT.md`

# Alignement des versions — v3

## Règle supérieure

Le canon n’est plus choisi par numéro de version seulement. On retient la **structure la plus stable**, puis la **meilleure incarnation humaine** de chaque fonction. Les anciennes versions servent de réservoir local.

## Hiérarchie

1. v16 — squelette de 19 chapitres.
2. v17 — scènes locales et synthèses manquantes.
3. fiches spécialisées v15 — biographies, voix, méthodes.
4. big plan v18 — intention globale.
5. v4–v11 — récupération locale, jamais canon automatique.
6. décisions v3 — arbitrages documentaires qui priment pour les nouveaux textes.

---


## Hiérarchie utilisée

1. **v16** — squelette narratif principal : 19 chapitres, séquence la plus complète et stable.
2. **v17** — réécritures locales et scènes nouvelles, mais partie III désalignée.
3. **v15 spécialisé** — biographies détaillées, voix, genèse des modules, branding.
4. **big plan v18** — intention : fiction philosophique/sociétale, prison-microcosme, reverse engineering des solutions par les récits.
5. **v10** — branche ancienne utile pour récupérer certaines intentions économiques/structurelles, mais non canon automatique.

Une version plus récente n’annule pas mécaniquement une version plus complète.

## Squelette v16

1. L’arrivée
2. Lettres clandestines
3. Le code d’Arjun
4. Le cercle des voix
5. Plus que de l’or
6. KOA
7. La dénonciation enterrée
8. Le passage à l’acte
9. La fresque effacée
10. La justice ajournée
11. Les chiffres sans langue
12. Le tournoi du présent
13. Le siphon
14. L’église brûlée
15. L’Hydro de l’assiette
16. La tour
17. Résonances extérieures
18. Baptême
19. La brèche

## Apports v17 à récupérer sans reprendre sa numérotation

### `La voix qui compte`

Apport majeur : **genèse explicite de SmartVote** à partir de Robert + Antoine.

Chaîne : preuve effacée + voix locale ignorée → registre public de contribution/compétence → objection de Darius sur l’élitisme → proposition d’Arjun d’un vote pondéré par expérience/réputation pertinente.

À intégrer de préférence autour des chapitres 7/14 ou dans le chapitre 14, sans supprimer l’histoire complète de Robert ni celle d’Antoine.

### `L’Hydro de l’assiette`

Apport majeur : **genèse explicite de Kristal Farms**.

Chaîne : Jules ouvre la nourriture comme infrastructure → François ajoute conditions/énergie et récupération de chaleur → Matteo propose les serres → Samir pose la contrainte de chauffage → Darius invente l’image « fermes de cristal » → Jules reprend « Kristal Farms ».

À conserver dans le chapitre 15.

### Partie III

Numéros répétés, deux Baptême, résonances déplacées, fusion de chapitres. **Ne pas utiliser comme plan.**

## Apports v15 à réinjecter

### `Colin — Justice`

Complète l’arrestation dominante : surveillance soupçonnée, demande de protection des droits, humiliation, coup au policier; surtout, formule le besoin d’un tiers indépendant, d’un recours abordable et d’une séparation des informations.

### `Orgo_`

Biographie complète de Darius : entrepôt fermé, A142, preuve d’adresse, SMS, rendez-vous postal tardif, Hydro, aide alimentaire, vol d’épicerie. Spécification humaine d’Orgo : une porte, un fil, un trajet visible.

### `Kreative samir prostitution_`

Donne l’intimité de Samir : illustrateur précaire, prostitution de survie, refus de la violence, limite morale. Compatible avec la fresque effacée de v16 si les deux sont hiérarchisés.

### `konnectED`

Détaille Rami : héritage comptable, diplôme du père non reconnu, barrière linguistique, autoformation, usage frauduleux du savoir, distinction compétence/permission.

### `Ekoh nu`

Détaille Marc-André : équipes inter-niveaux, projets réels, IA supervisée, tournoi, trace des contributions, provocation et faute lors de l’intervention.

### `Keen konnect tour de garde`

Détaille Liang : invention ouverte, capture/brevet, diffusion malgré injonction, nécessité de protéger juridiquement le commun.

### `Ethikos`

Détaille le processus de décision d’Antoine : faits/peurs, reformulation loyale, expertise et communauté, divergence à retravailler.

### `Jules — L’Hydro de l’assiette`

Confirme son droit à l’opacité sur son crime et développe les conditions sociales/environnementales de l’infrastructure alimentaire.

### `nadia`

Autographie, Faits/Pièces/Effets, limite du dossier institutionnel, bannissement de Colin comme branche forte.

### `Will`, `Voix`, `branding`

Différenciation des voix, rôle de Will, sens des noms. À utiliser comme guide de prose/continuité, pas comme exposition.

## Trou corrigé : François

La première documentation le traitait à tort comme insuffisamment biographié. **v16 ch.13 contient déjà sa trajectoire complète** : cadre financier, observation des flux, documentation, tentative d’alerte, clé USB, accusations. Son problème n’est pas l’absence d’histoire, mais le risque que l’analyse macro prenne le dessus sur cette histoire.

## Branche v10 à garder comme matériau non canon automatique

Le texte ancien contient une branche économique/cooperative plus explicite : « 1 membre = 1 voix », plafonds de rémunération votés, participation des membres via outils bancaires, budgets/transparence participatifs. Ces éléments peuvent nourrir François ou un volume ultérieur, mais ne doivent pas être injectés silencieusement dans le squelette v16 s’ils n’ont pas de scène actuelle.

## Principe de fusion

Pour chaque scène :

1. garder la fonction du squelette v16;
2. récupérer la meilleure incarnation humaine des fiches v15;
3. importer les inventions v17 lorsqu’elles **résolvent une fonction manquante** (SmartVote, Kristal Farms);
4. garder les objections déjà écrites;
5. ne pas transformer toute variante en accumulation biographique;
6. laisser explicitement ouverte toute contradiction qu’aucune source ne résout.


---

# FILE: `material/README.md`

# Material

Ce dossier reçoit la matière qui nourrit le roman sans devenir canon automatiquement.

- `fragments/` : phrases, images, dialogues isolés.
- `scenes/` : scènes complètes ou variantes.
- `research/` : vérifications juridiques, carcérales, économiques, techniques.
- `alternates/` : biographies ou versions incompatibles conservées sans les fusionner.

Règle : déplacer ici tout passage intéressant qui surcharge le manuscrit. Couper n'est pas perdre.


---

# FILE: `material/alternates/README.md`

# Alternates

Réservoir non canonique. Rien ici ne doit entrer dans le manuscrit sans validation contre `core/00_CANONICAL_STATE.md`.


---

# FILE: `material/characters/COLIN_SON_RESERVE.md`

# Réserve majeure — le fils de Colin

## Source
Le tableur `Colin Row v9.xlsx` et une scène v9 indiquent que le fils de Colin serait mort à sept ans à la suite d’une défaillance de protocole hospitalier, puis que Colin aurait traversé un épisode psychotique et une prise en charge qu’il juge inadéquate.

## Pourquoi ce matériau est puissant
Il pourrait expliquer :

- l’obsession de Colin pour les processus et les erreurs de système;
- sa colère devant l’inefficacité institutionnelle;
- sa sensibilité au mot “paranoïa” au poste;
- son rapport à la santé mentale;
- sa volonté de construire des mécanismes qui ne laissent personne tomber entre deux responsabilités.

## Pourquoi il n’est pas canon v3
Ce détail deviendrait probablement **la blessure centrale du protagoniste**. Il ne peut pas être ajouté comme simple flashback sans réécrire l’ensemble de son arc.

## Condition d’adoption
Si l’auteur le retient, effectuer une révision transversale de :

- chapitre 1;
- arrestation;
- rapport à Nadia et à l’APR;
- rapport aux institutions;
- motifs de deuil;
- toute scène de santé/IA;
- fin et transmission.

## Statut
**RÉSERVE MAJEURE — NE PAS INSÉRER SANS REFONTE.**


---

# FILE: `material/fragments/README.md`

# Fragments

Réservoir non canonique. Rien ici ne doit entrer dans le manuscrit sans validation contre `core/00_CANONICAL_STATE.md`.


---

# FILE: `material/legacy/README.md`

# Legacy — réservoir non canon

Ce dossier sert à conserver les éléments intéressants des versions anciennes sans les réinjecter automatiquement dans le manuscrit.

Règle : **récupérer la fonction avant de récupérer le fait.**

Un ancien personnage peut être supprimé alors que sa scène, sa question ou sa métaphore reste utile.

Voir :
- `reference/LEGACY_RECOVERY.md`
- `reference/LEGACY_CAST_FUNCTIONS.md`
- `core/11_CANON_DECISIONS_V3.md`


---

# FILE: `material/motifs/WHITE_PEARL.md`

# Motif réservé — La perle blanche

## Source
Ancienne scène “La Perle Blanche”.

## Ce qui est conservé
Une perle blanche est entourée d’une masse grise qui cherche à la protéger mais finit par la cacher.

## Utilité littéraire possible
Image de systèmes qui protègent au point d’étouffer :

- secret d’enquête qui protège mais exclut le citoyen;
- procédure qui garantit l’autographie mais peut exclure Colin;
- brevet qui protège mais capture;
- institution qui protège un dossier mais perd sa finalité humaine;
- architecture qui protège une idée au point de ne plus laisser vivre les personnes.

## Ce qui est rejeté
Toute l’intrigue ancienne d’agente pastorale infiltrée, romance, révélation surnaturelle, accusation de proxénétisme et victoire judiciaire.

## Statut
**MOTIF RÉSERVÉ.** Ne pas utiliser si le livre n’a pas besoin d’une image spirituelle supplémentaire.


---

# FILE: `material/research/README.md`

# Research

Réservoir non canonique. Rien ici ne doit entrer dans le manuscrit sans validation contre `core/00_CANONICAL_STATE.md`.


---

# FILE: `material/scenes/README.md`

# Scenes

Réservoir non canonique. Rien ici ne doit entrer dans le manuscrit sans validation contre `core/00_CANONICAL_STATE.md`.


---

# FILE: `manuscript/README.md`

# Manuscript

Le futur manuscrit canonique doit être séparé de la documentation.

Proposition de structure :

- `part_1/`
- `part_2/`
- `part_3/`

Chaque chapitre est réécrit à partir de son brief et non copié depuis les versions sources sans révision de continuité.


---

# FILE: `working/README.md`

# Working

Versions intermédiaires, essais de fusion, réécritures temporaires et coupes.

Aucun fichier de ce dossier n'est canonique par défaut.
