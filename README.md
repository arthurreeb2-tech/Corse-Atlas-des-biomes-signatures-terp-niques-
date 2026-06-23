# Atlas des biomes et terpènes Corse

**Atlas interactif des biomes, étages altitudinaux et signatures terpéniques de l'île.**

Atlas web autonome qui cartographie la Corse selon ses milieux naturels et les met en relation avec leur identité botanique, forestière et olfactive (composés terpéniques). On explore l'île depuis une carte cliquable et une coupe altitudinale, puis on croise les données via plusieurs fiches et un comparateur A / B.

<img width="1889" height="946" alt="image" src="https://github.com/user-attachments/assets/8ebb9f5b-ed64-4d01-9bcd-51a8e0522635" />


## Voir en ligne

- [▶ Les cours (6 modules)](https://arthurreeb2-tech.github.io/Corse-Atlas-des-biomes-signatures-terp-niques-/index.html)
- [▶ L'atlas interactif](https://arthurreeb2-tech.github.io/Corse-Atlas-des-biomes-signatures-terp-niques-/atlas_corse.html)

# Genèse du projet — une question née en mouvement

Ce projet n'a pas commencé devant un écran. Il a commencé sur les routes et les sentiers du sud de la Corse, en courant.
À l'effort, quelque chose s'impose qu'on ignore au repos : l'odeur du paysage. La garrigue chauffée, la résine des pins, l'immortelle, le myrte — des bouffées qui changent à chaque virage, à chaque versant.

Une question s'est posée : ces odeurs que j'avale à pleins poumons, est-ce qu'elles me font quelque chose ? Est-ce que la forêt que je traverse agit sur mon corps, au-delà du simple plaisir de respirer ?
Je veux être honnête sur le statut de cette question. C'est une intuition, pas une découverte. Une sensation forte n'est pas une preuve — la science est même pleine de pièges sur ce point : à l'effort, le corps amplifie ce qu'il ressent et l'esprit interprète, si bien qu'on peut attribuer à une odeur ce qui vient de la fatigue, ou l'inverse. C'est précisément cette frontière — entre ce que je ressens et ce qui est démontré — que ce projet explore.

Le point de départ formel était un Speed Défi : un exercice de conception sous contrainte, qu'on m'a proposé de mener quand j'éttais étudiant en école et que je veux réinterpréter aujourd'hui à ma façon. Plutôt que de traiter un sujet imposé, j'ai choisi de le détourner vers cette question qui me tenait au corps. Le défi est devenu : transformer une intuition de coureur en un objet plus rigoureux — un atlas qui cartographie les forêts corses, leurs essences et les molécules odorantes qu'elles émettent, pour donner une base concrète à l'enquête.

J'ai organiser l'Atlas autour de modules qui explique mon raisonnement. Il part de la molécule (qu'est-ce qu'un terpène ?), traverse ce que la science sait vraiment de l'air des forêts sur le corps humain — ni plus, ni moins — présente l'atlas construit, et aboutit à trois hypothèses sur des « cocktails » terpéniques corses. 

À aucun moment il ne prétend conclure ce qui n'est pas prouvé. Son ambition est plus juste, et plus utile : montrer comment une sensation personnelle peut devenir une hypothèse de recherche défendable.

## Contenu

Trois échelles de lecture du territoire :

- **6 biomes géographiques** — Littoral Nord · Plaine Orientale · Macchia intérieure · Haute Montagne · Alta Rocca · Extrême-Sud — positionnés sur une carte SVG de la Corse, chacun avec sa zone (villes / massifs), sa couleur et son profil sensoriel.
- **5 étages altitudinaux** (classification de Gamisans) — thermo-, méso-, supraméditerranéen, montagnard, subalpin / alpin.
- **Les forêts** corses et leur filière — chronologie, sylviculture, tensions.

## Vues

| Onglet | Rôle |
|---|---|
| **Fiche étage** | Sélection d'un étage (menu ou clic carte / coupe) → fiche détaillée |
| **Forêts** | Fiches forestières détaillées |
| **Biomes** | Fiche par biome géographique |
| **Comparaison** | Comparateur deux colonnes (étage / forêt / biome) avec radar terpénique superposé et étages communs / exclusifs |
| **Sonde** | Exploration ciblée des signatures |

L'UI est unifiée entre les fiches : menu déroulant + bouton **Comparer →** + raccourci par la carte. Carte interactive, coupe altitudinale et graphiques radar des profils terpéniques.


## Sources

L'atlas s'appuie exclusivement sur des données ouvertes officielles et sur la littérature scientifique. Aucune donnée n'est inventée.

### Données & cartographie (webographie)

| Source | Usage dans l'atlas | Accès |
|---|---|---|
| **IGN — Géoplateforme** | Contour réel de l'île, fonds topographiques | <https://geoservices.ign.fr> |
| **BD Forêt® v2** (IGN, licence Étalab 2.0) | 64 785 polygones d'essences forestières | <https://geoservices.ign.fr/bdforet> |
| **RGE ALTI®** (IGN) | 422 points d'altimétrie mesurée (coupe altitudinale) | <https://geoservices.ign.fr/rgealti> |
| **GBIF** — Global Biodiversity Information Facility | 25 068 occurrences d'espèces géolocalisées | <https://www.gbif.org> |

### Bibliographie scientifique

**Phytosociologie & flore de Corse**
- **Gamisans, J. (1991)** — *La végétation de la Corse.* Référence des 5 étages altitudinaux (thermo-, méso-, supraméditerranéen, montagnard, subalpin / alpin).
- **Paradis, G. (2004)** — Travaux sur la flore et les milieux corses.

**Terpènes — chimie & effets sensoriels**
- **Satou et al. (2014)** — PMID [25340185](https://pubmed.ncbi.nlm.nih.gov/25340185/)
- **Moss & Oliver (2012)** — Effets cognitifs des composés aromatiques volatils.
- **Fukutani et al. (2023)** — PMC [10394640](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10394640/)
- PMC [9983847](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9983847/)
- PMC [12249661](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12249661/)

**Filière bois & matériau**
- **Belloncle / LIMBHA** — École Supérieure du Bois (ESB), Nantes.
