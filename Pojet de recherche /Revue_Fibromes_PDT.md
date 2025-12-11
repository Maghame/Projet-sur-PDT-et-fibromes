# La thérapie photodynamique appliquée aux fibromes utérins


Ce projet de recherche porte sur l' optimisation des fluorophores organiques pour une thérapie photodynamique appliquée aux fibromes uterins (des tumeurs qui se développent à partir des cellules musculaires lisses de l'utérus), affection touchant 70-80% des femmes en âge de procréer. L'objectif est de concevoir, modéliser et benchmarker des sondes photoactives pour la théranothérapie (imagerie et traitement) des fibromes utérins via des approches computationnelles avancées. 

## Interrogation 1 : Les fibromes utérins, un défi thérapeutique unique nécessitant une approche moléculaire ?

### Interrogation 1 : Les fibromes utérins, un défi thérapeutique nécessitant une approche moléculaire ?

Les fibromes utérins (également appelés léiomyomes ou myomes) représentent la tumeur gynécologique bénigne la plus fréquente chez la femme. Leur développement est fortement hormono-dépendant, en particulier des œstrogènes, ce qui explique leur rareté avant la puberté et leur tendance à régresser après la ménopause.

Le choix des fibromes utérins comme cible thérapeutique pour ce travail de recherche apparaît particulièrement pertinent pour plusieurs raisons :

### ** 1. Un problème de santé publique mondiale**

###  Prévalence et spécificités régionales
La prévalence est extrêmement élevée : les myomes se retrouvent chez **20 % à 50 %** des femmes en âge de procréer . Des variations significatives existent selon l'ethnicité, le risque à vie dépassant **80 % chez les femmes noires** contre **$70 \%$ chez les femmes blanche**s .

En **Afrique subsaharienne**, les fibromes représentent un problème de santé publique majeur \cite{Hortence2021}.
* Au Cameroun, environ 15 à 20 % des patientes hospitalisées pour troubles gynécologiques au Cameroun présentent des fibromes utérins. Ils touchent majoritairement les femmes jeunes, avec un âge médian de 37 à 47 ans .
*   Au Mali (Bamako), l'âge moyen des patientes est de 37 ans. L'incidence élevée dans ce contexte s'explique par la forte fréquence des **fibromes multiples** (86,8 % des cas au Cameroun).



### 2.  Limitations des traitements actuels

Les thérapies existantes présentent des inconvénients majeurs :

| **Traitement** | **Limitations** | **Impact fertilité** |
|---------------|----------------|---------------------|
| **Myomectomie chirurgicale** | Invasive, cicatrices utérines, récidive 15-20% | ⚠️ Risque rupture utérine grossesse |
| **Hystérectomie** | Perte définitive fertilité | ❌ Stérilité |
| **Embolisation (UAE)** | Ischémie utérine, récidive 20-30% | ⚠️⚠️ Réserve ovarienne diminuée |
| **HIFU** | Coût élevé, accès limité, récidive 15-25% | ⚠️ Données limitées |
| **Traitements hormonaux** | Temporaires, effets secondaires, récidive post-arrêt | ⚠️ Contraceptif pendant traitement |

**Besoin médical non satisfait** : Une thérapie **sélective**, **minimalement invasive**, **préservant la fertilité** et **ciblant spécifiquement les cellules léiomyomateuses**.

#### **3. Les fibromes comme modèle biologique unique**

Contrairement aux cancers, les fibromes sont des **tumeurs bénignes hormono-dépendantes** avec une biologie distincte :

- **Absence d'effet EPR** (Enhanced Permeability and Retention) : pas d'angiogenèse anarchique comme les cancers malins.
- **Nécessité d'un ciblage actif** : Les approches passives (nanoparticules accumulées via EPR) ne fonctionneront pas.
- **Biomarqueurs spécifiques identifiés** : GPR10, récepteurs hormonaux (ER/PR), intégrine β1.
- **Métabolisme différent** : Dépendance aux œstrogènes et progestérone.

**Hypothèse centrale** : En développant une PDT ciblée pour les fibromes, nous établissons une **plateforme technologique** potentiellement applicable à d'autres tumeurs bénignes hormono-dépendantes (adénomes, hyperplasies). 

## 2. Contexte scientifique et technologique : La thérapie photodynamique comme stratégie théranostique

### 2.1. Introduction et mécanisme de la thérapie photodynamique
La thérapie photodynamique est une approche basée sur l’action sélective par la lumière de médicaments, dits photosensibilisateurs. Ces molécules, non toxiques en absence d’une lumière de longueur d’onde appropriée, génèrent, après irradiation lumineuse et en présence d’oxygène, des espèces très réactives entraînant la destruction du tissu cible. Elle est  reconnue pour son potentiel dans le traitement des maladies oncologiques (maladies liées au cancer) et non-oncologiques (maladies qui ne sont pas liées au cance). Elle constitue une alternative innovante.

Le mécanisme est basé sur une interaction de trois éléments non toxiques :
1.  Un **photosensibilisateur (PS)** ;
2.  L'**oxygène moléculaire** ($\text{O}_2$) ;
3.  L'**illumination** par une lumière de longueur d'onde spécifique.


### 2.2. Preuves de concept PDT dans les pathologies utérines

L'accessibilité endoscopique à l'utérus place la PDT au premier plan pour le traitement des lésions endométriales.

*   **Préservation de la fertilité dans le cancer endométrial** : La PDT a été évaluée comme une stratégie conservatrice pour les jeunes patientes atteintes de cancer de l'endomètre de stade précoce \cite{Choi2013, CorreiaBarros2022}. Une étude de suivi à long terme a montré que l'application de PDT après injection intraveineuse d'un photosensibilisateur, suivie d'une illumination au laser rouge (630 nm), a permis une **préservation de la fertilité** avec des taux de réponse complète pathologique \cite{Choi2013}.
*   **Adénomyose et endométriose** : Le traitement de l'**adénomyose** est difficile, car les approches chirurgicales conservatrices (adénomyomectomie) présentent un **risque élevé de rupture utérine** pendant la grossesse \cite{CorreiaBarros2022a}. Cependant, la TPD utilisant le précurseur **5-Aminolévulinique (5-ALA)** est prometteuse car les cellules d'adénomyose présentent une susceptibilité et une absorption du 5-ALA supérieures au tissu environnant \cite{CorreiaBarros2022a}. Le 5-ALA est également utilisé pour l'**ablation endométriale** et le traitement de l'**endométriose** \cite{CorreiaBarros2022}.


### 2.3. Avancées technologiques et conception de sondes photoactives

Pour que la PDT soit efficace contre les fibromes, qui sont des tumeurs myométriales potentiellement profondes, il est crucial d'utiliser des photosensibilisateurs (PS) capables d'être activés par des **longueurs d'onde plus longues**.

*   **PS de Nouvelle Génération et Pénétration Tissulaire** : La recherche se concentre sur des agents qui absorbent dans la **fenêtre thérapeutique du proche infrarouge (NIR-I, 600–900 nm)** pour maximiser la pénétration de la lumière \cite{Correia2021}.
    *   Les **Chlorines à cycle fusionné** (*Ring-fused chlorins*) sont étudiées précisément pour leur **forte absorption dans la région spectrale 600–800 nm** et leur phototoxicité élevée \cite{Correia2021}.
*   **Théranostique et Sélectivité** : L'approche théranostique (diagnostic + thérapie) est clé pour **augmenter la sélectivité aux tumeurs** \cite{Correia2021}. Les **dérivés de Platine(II) des Chlorines** sont un exemple de ces agents, combinant l'**imagerie par luminescence** et la PDT \cite{Correia2021}.
*   **Mécanismes Quantiques (SOC)** : L'efficacité de la PDT est liée au **Couplage Spin-Orbite (SOC)** du PS, qui contrôle la vitesse de passage de l'état singulet (S1, excité par la lumière) à l'état triplet (T1, producteur de ROS) \cite{Correia2021}. L'ajout d'**atomes lourds** (comme l'iode ou le brome) est une stratégie courante pour augmenter le SOC.



## 3. Problématique

Les fibromes utérins constituent un enjeu majeur de santé publique, et les options thérapeutiques actuellement disponibles demeurent limitées, en particulier pour les patientes souhaitant préserver leur fertilité.
La (PDT), bien qu’elle ait montré un fort potentiel dans le traitement de cancer en gynécologie, ne dispose encore d’aucun photosensibilisateur spécifiquement conçu pour cibler les cellules de fibrome, ce qui limite son application clinique.

De plus, la mise en œuvre de la PDT dans les myomes se heurte à deux types de défis :

*  **Biologiques**, liés aux particularités cellulaires et moléculaires du fibrome ;

* **Physiques**, en particulier la pénétration limitée de la lumière dans les tissus utérins profonds.

Dans ce contexte, se pose la **question centrale** :  Comment surmonter les defis biologiques et physiques (pénétration lumineuse) de la PDT dans le diagnostique et le traitement des fibromes utérin, afin d’assurer un traitement sélectif des fibromes tout en préservant le myomètre sain ?

## 3. Justification du projet et objectifs

### 3.1. Justification : La nécessité de la conception moléculaire *In Silico*

Malgré le potentiel de la PDT, son application aux fibromes intramuraux est limitée par le manque de photosensibilisateurs dotés des propriétés physico-chimiques optimales (bonne solubilité, fort rendement quantique en oxygène singulet et absorption profonde).

La **modélisation moléculaire** et la **chimie computationnelle** constituent des outils fondamentaux pour le développement rationnel d'agents photoactifs de troisième génération \cite{Correia2021}. Ces outils permettent de **prédire l'efficacité photodynamique** (par l'estimation du SOC et du rendement en oxygène singulet) et d'**optimiser l'absorption dans la fenêtre NIR** avant la synthèse expérimentale.


## 4. Objectifs

### Objectif général
L'objectif de ce projet est d'exploiter les avancées théoriques (telles que l'utilisation de méthodes comme l'**ADC(2)** pour les énergies d'excitation, le calcul du **SOC** par TD-DFT pour les tendances \cite{accuracy-of-spin-component-scaled-adc(2)-excitation-energies-and-potential-energy-surfaces.pdf}) pour concevoir, modéliser et évaluer des photosensibilisateurs de 3ᵉ génération adapté à la thérapie photodynamique des fibromes utérins afin de proposer une stratégie thérapeutique innovante et applicable en santé publique.


## 5. Hypothèses de recherche

### Hypothèse principale
Un photosensibilisateur de 3ᵉ génération, optimisé par modélisation moléculaire et adapté aux propriétés optiques du tissu utérin, permettra une destruction sélective et efficace des cellules myomateuses via la thérapie photodynamique.

### Hypothèses secondaires
1. Les fibromes présentent une signature moléculaire exploitable pour le ciblage sélectif d’un PS.  
2. L’optimisation des propriétés photophysiques du PS (absorption proche infrarouge, solubilité, stabilité) améliore la pénétration tissulaire.  
3. La PDT pourrait représenter une alternative accessible et moins invasive pour les systèmes de santé, notamment en Afrique.





