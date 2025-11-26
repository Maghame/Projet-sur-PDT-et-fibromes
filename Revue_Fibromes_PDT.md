# La thérapie photodynamique appliquée aux fibromes utérins


Ce projet de recherche porte sur l' optimisation des fluorophores organiques pour une thérapie photodynamique appliquée aux fibromes uterins (des tumeurs qui se développent à partir des cellules musculaires lisses de l'utérus). L'objectif est de concevoir, modéliser et benchmarker des sondes photoactives capables d'une double action (imagerie et traitement) via des approches computationnelles avancées. 

## 1. Contexte generale 

### 1.1. Définition

Les **fibromes utérins** (léiomyomes ou myomes) sont la **tumeur gynécologique bénigne la plus fréquente** chez la femme . Ces tumeurs, formées par la prolifération de cellules musculaires lisses de l'utérus, sont fortement influencées par les **hormones stéroïdes ovariennes** (œstrogènes et progestérone) .

### 1.2. Prévalence et spécificités régionales
La prévalence est extrêmement élevée : les myomes se retrouvent chez **20 % à 50 %** des femmes en âge de procréer . Des variations significatives existent selon l'ethnicité, le risque à vie dépassant **80 % chez les femmes noires** contre $70 \%$ chez les femmes blanches .

En **Afrique subsaharienne**, les fibromes représentent un problème de santé publique majeur \cite{Hortence2021}.
*   Au Cameroun, à l'Hôpital Central de Yaoundé, les fibromes représentaient une fréquence de **14 % des cas d'hospitalisation gynécologique** entre 2013 et 2018. Ils touchent majoritairement les femmes jeunes, avec un âge médian de 37,47 ans .
*   Au Mali (Bamako), l'âge moyen des patientes est de 37 ans. L'incidence élevée dans ce contexte s'explique par la forte fréquence des **fibromes multiples** (86,8 % des cas au Cameroun).

### 1.3. Symptomatologie et conséquences
Bien que près de la moitié des femmes soient asymptomatiques, les myomes sont une cause importante de morbidité.
*   Le symptôme le plus fréquent est l'**hémorragie génitale** (ménorragies), observée dans 61 % des cas au Cameroun , pouvant entraîner une **anémie sévère** dans **72,4 %** des cas.
*   Les fibromes sont également une **cause majeure d'infertilité** , en particulier les types sous-muqueux qui compromettent la cavité utérine . L'infertilité était le motif de consultation dans 75,8 % des cas étudiés au Mali.
*   La présence de pathologies associées, telles que l'**adénomyose** ou le **cancer du col utérin** (retrouvées dans 53 % des cas étudiés à Abidjan), rend l'utilisation de l'**IRM multimodale** indispensable pour une exploration diagnostique et pré-thérapeutique complète .

### 1.4. Limites des thérapies standard et impératif de conservation de la fertilité

Les fibromes utérins sont la **première cause d'hystérectomie** pour lésions bénignes chez les femmes en âge de procréer. La nécessité de préserver la fertilité, face à l'augmentation de l'âge de la première grossesse, souligne les limites des options thérapeutiques invasives :

1.  **Chirurgie Radical (Hystérectomie)** : Elle représente souvent le traitement définitif, mais elle impose une **stérilité irréversible** \cite{Choi2013}.
2.  **Chirurgie Conservatrice (Myomectomie)** : La myomectomie a été la méthode chirurgicale la plus utilisée dans certaines séries africaines (42,5 % au Mali) \cite{fibr.pdf}. Cependant, elle est grevée d'un risque non négligeable de **récidive des myomes** \cite{fibr.pdf}, un antécédent de récidive ayant été observé chez 9,2 % des patientes au Mali \cite{fibr.pdf}.
3.  **Embolisation de l’Artère Utérine (UAE)** : Bien que l'UAE soit une option pour les femmes cherchant à préserver leur fertilité, son application est limitée par l'incertitude quant à ses **effets sur la conception et la grossesse** \cite{Krishnan2024}. Des complications graves, notamment la **rupture utérine lors de l'accouchement**, ont été signalées après l'UAE \cite{Krishnan2024}.
4.  **Ultrasons Focalisés de Haute Intensité (HIFU)** : Le HIFU nécessite souvent des **sessions multiples** (jusqu'à 50 % des femmes) et présente un risque de complications telles que les brûlures cutanées ou la sciatalgie \cite{Krishnan2024}.
5.  **Thérapies Médicales** : Les analogues de la **GnRH** sont recommandés pour une période restreinte en raison de leurs **effets indésirables** sur la masse osseuse \cite{Krishnan2024}.

Face à ces limites qui compromettent soit la fonction, soit la sécurité, le développement de **traitements conservateurs minimaux et hautement sélectifs** est impératif.
***

## 2. Contexte scientifique et technologique : La thérapie photodynamique comme stratégie théranostique

### 2.1. Introduction et mécanisme de la thérapie photodynamique
La thérapie photodynamique est une approche basée sur l’action sélective par la lumière de médicaments, dits photosensibilisateurs. Ces molécules, non toxiques en absence d’une lumière de longueur d’onde appropriée, génèrent, après irradiation lumineuse et en présence d’oxygène, des espèces très réactives entraînant la destruction du tissu cible. Elle est  reconnue pour son potentiel dans le traitement des maladies oncologiques (maladies liées au cancer) et non-oncologiques (maladies qui ne sont pas liées au cance). Elle constitue une alternative innovante.

Le mécanisme est basé sur une interaction de trois éléments non toxiques :
1.  Un **photosensibilisateur (PS)** ;
2.  L'**oxygène moléculaire** ($\text{O}_2$) ;
3.  L'**illumination** par une lumière de longueur d'onde spécifique.


### 2.2. Preuves de concept PDT dans les pathologies utérines

L'accessibilité endoscopique à l'utérus place la PDT au premier plan pour le traitement des lésions endométriales.

*   **Préservation de la fertilité dans le cancer endométrial** : La PDT a été évaluée comme une stratégie conservatrice pour les jeunes patientes atteintes de cancer de l'endomètre de stade précoce \cite{Choi2013, CorreiaBarros2022}. Une étude de suivi à long terme a montré que l'application de TPD après injection intraveineuse d'un photosensibilisateur, suivie d'une illumination au laser rouge (630 nm), a permis une **préservation de la fertilité** avec des taux de réponse complète pathologique \cite{Choi2013}.
*   **Adénomyose et endométriose** : Le traitement de l'**adénomyose** est difficile, car les approches chirurgicales conservatrices (adénomyomectomie) présentent un **risque élevé de rupture utérine** pendant la grossesse \cite{CorreiaBarros2022a}. Cependant, la TPD utilisant le précurseur **5-Aminolévulinique (5-ALA)** est prometteuse car les cellules d'adénomyose présentent une susceptibilité et une absorption du 5-ALA supérieures au tissu environnant \cite{CorreiaBarros2022a}. Le 5-ALA est également utilisé pour l'**ablation endométriale** et le traitement de l'**endométriose** \cite{CorreiaBarros2022}.


### 2.3. Avancées technologiques et conception de sondes photoactives

Pour que la PDT soit efficace contre les fibromes, qui sont des tumeurs myométriales potentiellement profondes, il est crucial d'utiliser des photosensibilisateurs (PS) capables d'être activés par des **longueurs d'onde plus longues**.

*   **PS de Nouvelle Génération et Pénétration Tissulaire** : La recherche se concentre sur des agents qui absorbent dans la **fenêtre thérapeutique du proche infrarouge (NIR-I, 600–900 nm)** pour maximiser la pénétration de la lumière \cite{Correia2021}.
    *   Les **Chlorines à cycle fusionné** (*Ring-fused chlorins*) sont étudiées précisément pour leur **forte absorption dans la région spectrale 600–800 nm** et leur phototoxicité élevée \cite{Correia2021}.
*   **Théranostique et Sélectivité** : L'approche théranostique (diagnostic + thérapie) est clé pour **augmenter la sélectivité aux tumeurs** \cite{Correia2021}. Les **dérivés de Platine(II) des Chlorines** sont un exemple de ces agents, combinant l'**imagerie par luminescence** et la TPD \cite{Correia2021}.
*   **Mécanismes Quantiques (SOC)** : L'efficacité de la TPD est liée au **Couplage Spin-Orbite (SOC)** du PS, qui contrôle la vitesse de passage de l'état singulet (S1, excité par la lumière) à l'état triplet (T1, producteur de ROS) \cite{Correia2021}. L'ajout d'**atomes lourds** (comme l'iode ou le brome) est une stratégie courante pour augmenter le SOC.



## 3. Problématique

Les fibromes utérins représentent un problème majeur de santé publique et les traitements actuels restent limités.  
Bien que prometteuse, la thérapie photodynamique actuellement ne dispose pas de photosensibilisateur spécifiquement optimisé pour cibler les cellules de fibrome, d’où la nécessité d’une conception de **photosensibilisateurs de 3ᵉ génération**.

**Problématique :**  
*Comment concevoir, modéliser et évaluer un photosensibilisateur de 3ᵉ génération capable de cibler efficacement les fibromes utérins tout en préservant le myomètre sain ?


## 4. Hypothèses de recherche

### Hypothèse principale
Un photosensibilisateur de 3ᵉ génération, optimisé par modélisation moléculaire et adapté aux propriétés optiques du tissu utérin, permettra une destruction sélective et efficace des cellules myomateuses via la thérapie photodynamique.

### Hypothèses secondaires
1. Les fibromes présentent une signature moléculaire exploitable pour le ciblage sélectif d’un PS.  
2. L’optimisation des propriétés photophysiques du PS (absorption proche infrarouge, solubilité, stabilité) améliore la pénétration tissulaire.  
3. La modélisation in silico permet de prédire l'affinité, la stabilité et la toxicité potentielle du PS.  
4. La PDT pourrait représenter une alternative accessible et moins invasive pour les systèmes de santé, notamment en Afrique.

---


## 3. Justification du Projet et Objectifs

### 3.1. Justification : La Nécessité de la Conception Moléculaire *In Silico*

Malgré le potentiel de la TPD, son application aux fibromes intramuraux est limitée par le manque de photosensibilisateurs dotés des propriétés physico-chimiques optimales (bonne solubilité, fort rendement quantique en oxygène singulet et absorption profonde).

La **modélisation moléculaire** et la **chimie computationnelle** constituent des outils fondamentaux pour le développement rationnel d'agents photoactifs de troisième génération \cite{Correia2021}. Ces outils permettent de **prédire l'efficacité photodynamique** (par l'estimation du SOC et du rendement en oxygène singulet) et d'**optimiser l'absorption dans la fenêtre NIR** avant la synthèse expérimentale.

L'objectif de ce projet est d'exploiter les avancées théoriques (telles que l'utilisation de méthodes comme l'**ADC(2)** pour les énergies d'excitation, le calcul du **SOC** par TD-DFT pour les tendances \cite{accuracy-of-spin-component-scaled-adc(2)-excitation-energies-and-potential-energy-surfaces.pdf}) pour concevoir des sondes sélectives qui ciblent spécifiquement les cellules musculaires lisses du fibrome, garantissant ainsi un traitement qui **préserve l'intégrité fonctionnelle du myomètre sain**.

### 3.2. Objectif du Projet

L'objectif principal du projet est de mener une **mission de conception *in silico*** d'agents photoactifs. Cette démarche vise à :
1.  **Concevoir et modéliser moléculairement** de nouvelles sondes photoactives ciblant les fibromes.
2.  **Augmenter le rendement quantique en oxygène singulet** et la **sélectivité** du photosensibilisateur pour les cellules musculaires lisses constituant le fibrome, afin d'assurer un traitement **conservateur, efficace et récurrentiel** \cite{PDT_Fibrome.txt}.

---



## 5. Objectifs

### Objectif général
Concevoir, modéliser et évaluer un photosensibilisateur de 3ᵉ génération adapté à la thérapie photodynamique des fibromes utérins afin de proposer une stratégie thérapeutique innovante et applicable en santé publique.

