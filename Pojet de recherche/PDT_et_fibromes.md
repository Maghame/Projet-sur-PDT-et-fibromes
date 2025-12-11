

## Thérapie photodynamique ciblée pour le traitement des fibromes utérins


## 1. Introduction et Objectifs : Vers une Révolution Thérapeutique en Gynécologie

Ce projet de thèse vise à développer une approche thérapeutique innovante pour les fibromes utérins (léiomyomes), affection touchant 70-80% des femmes en âge de procréer, en répondant à des interrogations scientifiques et cliniques fondamentales. Cette recherche s'inscrit dans un domaine totalement inexploré.

### Interrogation 1 : Les fibromes utérins, un défi thérapeutique nécessitant une approche moléculaire ?

Le choix des **fibromes utérins** comme cible thérapeutique est **stratégique et urgent** pour plusieurs raisons :

#### **A. Un problème de santé publique mondiale**

- **Prévalence** : 70-80% des femmes développent des fibromes durant leur vie
- **Impact économique** : >20 milliards USD/an (traitements, absentéisme)
- **Qualité de vie** : Saignements abondants, douleurs pelviennes, infertilité, complications obstétricales
- **Disparités ethniques** : Incidence 2-3× plus élevée chez les femmes afro-descendantes

#### **B. Limitations des traitements actuels**

Les thérapies existantes présentent des inconvénients majeurs :

| **Traitement** | **Limitations** | **Impact fertilité** |
|---------------|----------------|---------------------|
| **Myomectomie chirurgicale** | Invasive, cicatrices utérines, récidive 15-20% | ⚠️ Risque rupture utérine grossesse |
| **Hystérectomie** | Perte définitive fertilité | ❌ Stérilité |
| **Embolisation (UAE)** | Ischémie utérine, récidive 20-30% | ⚠️⚠️ Réserve ovarienne diminuée |
| **HIFU** | Coût élevé, accès limité, récidive 15-25% | ⚠️ Données limitées |
| **Traitements hormonaux** | Temporaires, effets secondaires, récidive post-arrêt | ⚠️ Contraceptif pendant traitement |

**Besoin médical non satisfait** : Une thérapie **sélective**, **minimalement invasive**, **préservant la fertilité** et **ciblant spécifiquement les cellules léiomyomateuses**.

#### **C. Les fibromes comme modèle biologique unique**

Contrairement aux cancers, les fibromes sont des **tumeurs bénignes hormono-dépendantes** avec une biologie distincte :

- **Absence d'effet EPR** (Enhanced Permeability and Retention) : pas d'angiogenèse anarchique comme les cancers malins
- **Nécessité d'un ciblage actif** : Les approches passives (nanoparticules accumulées via EPR) ne fonctionneront pas
- **Biomarqueurs spécifiques identifiés** : GPR10, récepteurs hormonaux (ER/PR), intégrine β1
- **Métabolisme différent** : Dépendance aux œstrogènes et progestérone

**Hypothèse centrale** : En développant une PDT ciblée pour les fibromes, nous établissons une **plateforme technologique** potentiellement applicable à d'autres tumeurs bénignes hormono-dépendantes (adénomes, hyperplasies) et nous validons une stratégie de **ciblage moléculaire actif** pour tissus non-cancéreux.

---

### Interrogation 2 : Comment intégrer trois défis majeurs au sein d'une approche thérapeutique unique ?

Le succès d'une PDT pour les fibromes repose sur la résolution **simultanée et intégrée** de trois défis :

#### **1. Le défi biologique : Cibler sélectivement les fibromes**

##### **Problématique**
Les fibromes et le myomètre normal sont composés des mêmes cellules musculaires lisses. Comment distinguer la cible (fibrome) du tissu sain adjacent ?

##### **Notre solution (validée par la littérature)**

Exploiter les **biomarqueurs surexprimés** dans les fibromes :

**CIBLE #1 : GPR10 (Prolactin-Releasing Peptide Receptor)** ⭐⭐⭐⭐⭐

- **Rationalité scientifique** : GPR10 est fortement surexprimé dans les tissus léiomyomateux et sert de médiateur central de la signalisation pathologique. Les souris transgéniques surexprimant PRLHR développent une hyperplasie myométriale avec dépôt excessif de matrice extracellulaire.
- **Avantage sélectivité** : Expression quasi-nulle dans le myomètre normal
- **Accessibilité** : Récepteur membranaire (GPCR) → facilement accessible aux ligands externes
- **Stratégie de ciblage** : Conjugaison photosensibilisateur-PrRP (Prolactin-Releasing Peptide, ligand endogène de GPR10)

**CIBLE #2 : Récepteurs hormonaux (ER/PR)** ⭐⭐⭐⭐⭐

- **Rationalité scientifique** : Les œstrogènes et la progestérone stimulent directement la croissance des fibromes. Les récepteurs ER et PR sont surexprimés dans les fibromes comparés au myomètre.
- **Avantage clinique** : Stratégie validée en oncologie (cancers du sein ER+)
- **Chimie établie** : Conjugaison hormone-photosensibilisateur déjà documentée
- **Stratégie de ciblage** : Photosensibilisateur conjugué à estradiol/progestérone modifiés

**CIBLE #3 : Intégrine β1** ⭐⭐⭐⭐

- **Rationalité scientifique** : L'intégrine β1 est surexprimée dans les cellules de léiomyomes et impliquée dans la mécanotransduction et la fibrose excessive.
- **Ligands disponibles** : Peptides RGD (Arg-Gly-Asp) cycliques
- **Applications** : Déjà utilisés en imagerie tumorale (PET scan)

**Design moléculaire intégré** :
```
Photosensibilisateur (Chlorine e6 / ICG / Verteporfin)
        ↓ [Linker PEG]
Ligand de ciblage (PrRP / Hormone / cRGD)
        ↓ [Accumulation sélective]
Fibromes (ratio 10:1 vs myomètre)
        ↓ [Irradiation lumineuse]
Génération ROS → Mort cellulaire sélective
```

---

#### **2. Le défi physique : Atteindre les fibromes profonds**

##### **Problématique**

La **profondeur** est le défi majeur :

| **Localisation fibrome** | **Profondeur** | **Accessibilité lumière** |
|-------------------------|---------------|--------------------------|
| **Sous-muqueux** | 0-5 mm | ✅ Lumière rouge (630 nm) suffisante |
| **Intramuraux superficiels** | 5-20 mm | ⚠️ NIR-I (800 nm) nécessaire |
| **Intramuraux profonds** | 20-80 mm | ❌ NIR-II (1000 nm) insuffisant |
| **Sous-séreux** | >80 mm | ❌ Nécessite délivrance directe |

Les tissus biologiques absorbent fortement la lumière visible :
- **Hémoglobine** : Absorption maximale <600 nm
- **Mélanine** : Absorption décroissante vers NIR
- **Eau** : Absorption minimale 600-950 nm, augmente >1000 nm

**Fenêtre thérapeutique optique** : 600-850 nm (compromis pénétration/énergie pour O₂ singulet)

##### **Notre solution (approche multi-niveaux)**

**STRATÉGIE COURT TERME : Fibres Optiques Interstitielles (ILP)** ✅

- **Principe** : Insertion percutanée de fibres optiques directement dans le fibrome sous guidage échographique 3D ou IRM
- **Pénétration** : Illimitée (lumière délivrée au cœur du fibrome)
- **Précédent clinique** : Technologie Acessa® (ablation par radiofréquence) déjà FDA-approuvée pour fibromes
- **Avantages** :
  - ✅ Minimalement invasif (ambulatoire, anesthésie locale)
  - ✅ Contrôle précis dosimétrie
  - ✅ Traitement fibromes multiples (insertion multiple fibres)
- **Innovation** : Adapter la plateforme ILP existante pour PDT au lieu de thermothérapie pure

**STRATÉGIE MOYEN TERME : Nanoparticules à Conversion Ascendante (UCNPs)** ✨

- **Principe** : Nanoparticules lanthanides (NaYF₄:Yb³⁺,Er³⁺) convertissent lumière NIR-II (980/1064 nm) → lumière visible (540/660 nm) *in situ*
- **Pénétration** : 20-50 mm (NIR-II transcutané)
- **Avantages** :
  - ✅ Non-invasif (irradiation externe)
  - ✅ Active photosensibilisateurs approuvés (Photofrin, 5-ALA)
  - ✅ Imaging simultané (fluorescence NIR)
- **Défis à résoudre** :
  - Efficacité conversion faible (1-5%) → optimiser design UCNPs
  - Échauffement local (980 nm) → utiliser 1064 nm
  - Clairance hépatique → coating PEG, ciblage actif

**STRATÉGIE LONG TERME : X-PDT (Rayons X + Scintillateurs)** 🚀

- **Principe** : Rayons X (pénétration illimitée) excitent nanoparticules scintillatrices (LaF₃:Ce,Tb) → lumière visible active photosensibilisateur
- **Pénétration** : Illimitée (>10 cm)
- **Avantages** :
  - ✅ Fibromes très profonds/multiples
  - ✅ Guidage radiographique temps réel
- **Défis réglementaires** :
  - Radiation ionisante (1-5 Gy)
  - Balance bénéfice-risque pour pathologie bénigne

**Tableau comparatif stratégies de pénétration** :

| **Approche** | **Profondeur** | **Invasivité** | **Maturité** | **Recommandation phase** |
|-------------|---------------|---------------|--------------|-------------------------|
| **Fibres ILP** | Illimitée | ⚠️ Percutané | ⭐⭐⭐⭐ Mature | **Phase 1-2 (Années 1-3)** |
| **UCNPs** | 20-50 mm | ✅ Minimale | ⭐⭐⭐ Émergent | **Phase 2-3 (Années 3-5)** |
| **X-PDT** | Illimitée | ✅ Minimale | ⭐⭐ Recherche | **Phase 4 (Années 5-8)** |

---

#### **3. Le défi technique : Optimiser la dosimétrie et l'efficacité thérapeutique**

##### **Problématique**

La "dose PDT" dépend de **trois paramètres interdépendants** :

```
Dose PDT = [Photosensibilisateur] × Fluence lumineuse × [O₂]
```

**Défis spécifiques aux fibromes** :

1. **Hypoxie potentielle** : Fibromes volumineux peuvent être mal vascularisés
2. **Hétérogénéité tissulaire** : Zones fibreuses (collagène) vs cellulaires
3. **Fibromes multiples** : Nécessité traitement simultané (dosimétrie complexe)

##### **Notre solution (protocoles optimisés)**

**Paramètres à optimiser** :

| **Paramètre** | **Plage initiale** | **Méthode optimisation** |
|--------------|-------------------|-------------------------|
| [Photosensibilisateur] | 0.5-5 mg/kg IV | Courbe dose-réponse in vitro (hLMSC) |
| Fluence lumineuse | 50-200 J/cm² | Modélisation Monte-Carlo + validation ex vivo |
| Irradiance | 50-150 mW/cm² | Éviter hyperthermie (>41°C) |
| Longueur d'onde | 630-800 nm | Selon PS et profondeur |
| Oxygénation | >10 mmHg | PDT fractionnée + monitoring |

**PDT fractionnée pour améliorer oxygénation** :

```
Protocole optimisé :
Fraction 1 : 20 J/cm² (déplète O₂ initial)
    ↓
Pause : 15-30 min (ré-oxygénation vasculaire)
    ↓
Fraction 2 : 80 J/cm² (effet PDT maximal sur tissu ré-oxygéné)

Résultat : Efficacité ×2 vs irradiation continue
```

---

### Synthèse des trois défis intégrés

| **Défi** | **Solution** | **Innovation clé** | **Validation** |
|---------|------------|-------------------|---------------|
| **Biologique (Ciblage)** | Conjugués PS-GPR10/ER/PR | Ciblage actif vs passif | In vitro (Année 1) |
| **Physique (Pénétration)** | ILP fibres → UCNPs → X-PDT | Approche multi-échelle | Ex vivo → Souris (Années 2-3) |
| **Technique (Dosimétrie)** | PDT fractionnée + monitoring | Optimisation temps-réel | Souris Eker (Année 3) |

**L'objectif de cette thèse** est de mener une **mission de conception et validation préclinique** d'une plateforme PDT ciblée pour fibromes. Cette plateforme sera **théranostique** (diagnostic par fluorescence + thérapie) et modulable selon la profondeur du fibrome (ILP pour profonds, UCNPs pour moyens, lumière directe pour superficiels).

---

## 2. Fondements Théoriques et Méthodologiques : Boîte à Outils du Chercheur en Nanomédecine

Cette thèse s'appuie sur une approche **multidisciplinaire** intégrant chimie, photophysique, biologie cellulaire, nanotechnologie et imagerie biomédicale.

---

### A. Chimie des Photosensibilisateurs et Conjugaison

#### **1. Sélection du photosensibilisateur**

**Critères de sélection** :

| **Critère** | **Objectif** | **PS candidats** |
|-----------|------------|-----------------|
| Absorption NIR-I | 650-800 nm | Chlorine e6, ICG, Verteporfin |
| Approbation clinique | FDA/EMA | Verteporfin (Visudyne®), ICG |
| Rendement quantique ¹O₂ | Φ_Δ > 0.4 | Chlorine e6 (0.52), ICG (0.01) |
| Solubilité aqueuse | >1 mg/mL | ICG (excellent), Chlorine e6 (modéré) |
| Photostabilité | Résistance photobleaching | Chlorine e6 > ICG |

**Photosensibilisateurs recommandés pour Phase 1** :

1. **Verteporfin** (689 nm) ✅
   - FDA-approuvé (DMLA)
   - Excellente pénétration (6-8 mm)
   - Chimie conjugaison établie

2. **Chlorine e6** (660 nm) ✅
   - Φ_Δ élevé (0.52)
   - Groupes COOH pour conjugaison
   - Coût abordable

3. **ICG (Indocyanine Green)** (780-800 nm)
   - Pénétration maximale (10-15 mm)
   - FDA-approuvé (imagerie)
   - Limitation : Φ_Δ faible → combinaison PTT+PDT

#### **2. Chimie de conjugaison**

**Stratégie générale** :

```
Photosensibilisateur-COOH
        ↓ [Activation EDC/NHS]
NH₂-PEG-Ligand (PrRP / Estradiol / cRGD)
        ↓ [Couplage amide]
PS-PEG-Ligand (Conjugué final)
        ↓ [Purification HPLC]
Caractérisation (MS, NMR, UV-Vis)
```

**Linkers à utiliser** :

| **Linker** | **Longueur** | **Avantage** | **Application** |
|-----------|-------------|-------------|----------------|
| PEG₄-₆ | 1.5-2.5 nm | Solubilité, flexibilité | Conjugués hormonaux |
| PEG₁₂ | ~5 nm | Circulation prolongée | Nanoparticules |
| Clivable (disulfure) | Variable | Libération intracellulaire | Si besoin activation GSH |

**Contrôle qualité** :

- **Ratio PS:Ligand** : 1:1 (caractériser par MALDI-TOF MS)
- **Pureté** : >95% (HPLC)
- **Solubilité** : >1 mg/mL PBS pH 7.4
- **Stabilité** : 6 mois à -20°C

---

### B. Photophysique et Caractérisation Optique

#### **1. Propriétés d'absorption et émission**

**Mesures spectroscopiques** :

| **Technique** | **Information** | **Paramètre mesuré** |
|--------------|----------------|---------------------|
| **UV-Vis** | Absorption | λ_max, ε (coefficient extinction) |
| **Fluorescence** | Émission | λ_em, Φ_F (rendement quantique fluorescence) |
| **Oxymètre ¹O₂** | Production ROS | Φ_Δ (rendement quantique oxygène singulet) |

**Validation fenêtre thérapeutique** :

- ✅ λ_max ∈ [650-800 nm]
- ✅ ε > 50,000 M⁻¹cm⁻¹ (absorption efficace)
- ✅ Φ_Δ > 0.4 (génération ¹O₂ suffisante)

#### **2. Détection de l'oxygène singulet**

**Méthodes directes** :

```
PS + lumière (λ_max) → ¹O₂
¹O₂ + SOSG (Singlet Oxygen Sensor Green) → Fluorescence (525 nm)

Mesure : Cinétique fluorescence (t = 0-30 min)
```

**Méthodes indirectes** :

- **DPBF (1,3-Diphénylisobenzofurane)** : Photobleaching proportionnel à [¹O₂]
- **Comparaison standard** : Rose Bengal (Φ_Δ = 0.75 dans EtOH)

---

### C. Biologie Cellulaire et Tests In Vitro

#### **1. Cultures cellulaires primaires**

**Cellules humaines de fibromes (hLMSC)** :

- **Source** : Biopsies chirurgicales (myomectomie, hystérectomie)
- **Collaboration** : Services gynéco-obstétrique (consentement éthique obligatoire)
- **Culture** : DMEM + 10% FBS + hormones (17β-estradiol 10 nM + progestérone 100 nM)
- **Passages** : P3-P8 (pour maintenir phénotype)

**Cellules myométriales normales (hMMSC)** :

- **Source** : Myomètre adjacent (même patiente = contrôle interne idéal)
- **Culture** : Identique hLMSC (pour comparaison équitable)

**Validation expression biomarqueurs** :

| **Biomarqueur** | **Technique** | **Ratio attendu (hLMSC/hMMSC)** |
|----------------|--------------|--------------------------------|
| GPR10 | Western blot, qPCR | >10:1 |
| ER/PR | Immunofluorescence | >3:1 |
| Intégrine β1 | Cytométrie de flux | >2:1 |

#### **2. Tests de liaison sélective**

**Protocole cytométrie de flux** :

```
1. Incubation cellules + PS-conjugué (0.1-10 μM, 4h, 37°C)
2. Lavages PBS (×3, éliminer PS non-lié)
3. Analyse cytomètre (fluorescence PS)
4. Comparaison hLMSC vs hMMSC

Critère succès : Fluorescence hLMSC ≥10× hMMSC
```

**Imagerie confocale** :

- Co-marquage : PS-conjugué (rouge) + MitoTracker (vert, si ciblage mitochondrial)
- Objectif : Vérifier localisation intracellulaire

#### **3. Tests de phototoxicité (PDT)**

**Protocole MTT assay** :

```
1. Incubation cellules + PS-conjugué (0-10 μM, 4-24h)
2. Irradiation (λ = λ_max du PS, fluence 0-100 J/cm²)
3. Incubation post-PDT (24h)
4. Test viabilité MTT
5. Calcul IC₅₀ (concentration létale 50%)

Critère succès : IC₅₀(hLMSC) ≤ 0.2 × IC₅₀(hMMSC)
```

**Détection ROS intracellulaire** :

- **DCFDA** (2',7'-dichlorodihydrofluorescéine diacétate) : Fluorescence verte proportionnelle aux ROS
- **CellROX Deep Red** : Détection superoxyde
- **Mesure** : Cytométrie ou imagerie temps réel (0-60 min post-irradiation)

#### **4. Mécanismes de mort cellulaire**

**Apoptose vs Nécrose** :

| **Technique** | **Marqueurs** | **Information** |
|--------------|--------------|----------------|
| Annexin V / PI | Cytométrie | Apoptose précoce/tardive, nécrose |
| Caspase-3/7 | Luminescence | Activation apoptose |
| LDH release | Colorimétrie | Perte intégrité membranaire |

---

### D. Modèles Tridimensionnels (Sphéroïdes)

#### **Pourquoi les sphéroïdes ?**

Les cultures 2D ne reproduisent pas :
- Architecture tissulaire 3D
- Hypoxie centrale (distance diffusion O₂ > 100 μm)
- Gradient pénétration PS et lumière
- Interactions cellule-matrice extracellulaire (ECM)

#### **Génération de sphéroïdes**

**Méthode Hanging Drop** :

```
1. Suspendre hLMSC (500-1000 cellules/goutte, 20 μL)
2. Inverser couvercle boîte Petri (48-72h)
3. Formation sphéroïde par gravité
4. Transfert plaque ultra-low attachment (Corning)
5. Croissance jusqu'à 300-500 μm diamètre (7-10 jours)
```

**Tests PDT sur sphéroïdes** :

- **Pénétration PS** : Imagerie confocale (sections optiques z-stack)
- **Viabilité** : Live/Dead staining (Calcein-AM vert / Ethidium homodimer rouge)
- **Nécrose centrale** : Quantification volume nécrotique (logiciel Imaris, ImageJ)

**Critères de succès** :

- ✅ Pénétration PS-conjugué > 200 μm (depuis surface)
- ✅ Nécrose post-PDT > 80% volume sphéroïde
- ✅ Sélectivité maintenue (sphéroïdes hLMSC > hMMSC)

---

### E. Modèles Animaux Précliniques

#### **1. Modèle souris nude (xénogreffe sous-cutanée)**

**Objectif** : Validation ciblage et biodistribution

**Protocole** :

```
1. Souris nude athymiques (8 semaines, femelles)
2. Implantation SC hLMSC (5×10⁶ cellules dans Matrigel, flanc)
3. Croissance tumeur (2-4 semaines → 5-8 mm diamètre)
4. Injection IV PS-conjugué ciblé (2 mg/kg)
5. Imagerie optique in vivo (IVIS) : 4, 24, 48, 72h post-injection
6. Traitement PDT (fibres ILP ou irradiation transcutanée)
7. Monitoring tumeur (caliper 2×/semaine, 4 semaines)
8. Sacrifice : Histologie, immunohistochimie

Groupes (n=6-8/groupe) :
- Contrôle (pas de traitement)
- PS-conjugué seul (pas de lumière)
- Lumière seule (pas de PS)
- PDT (PS-conjugué + lumière)
- PDT ciblée vs non-ciblée (PS libre)
```

**Analyses** :

| **Analyse** | **Objectif** | **Critère succès** |
|-----------|------------|-------------------|
| Biodistribution (ex vivo) | Accumulation sélective | Ratio tumeur/muscle >5:1 |
| Volume tumoral | Efficacité thérapeutique | Réduction >70% vs contrôle |
| Histologie (H&E) | Nécrose tumorale | >80% nécrose sans dommages adjacents |
| Immunohistochimie | Ki-67 (prolifération), TUNEL (apoptose) | Ki-67↓, TUNEL↑ dans tumeur |

---

#### **2. Modèle souris Eker (fibromes spontanés)** ⭐⭐⭐⭐⭐

**Pourquoi ce modèle est OPTIMAL ?**

- **Souris Eker** (mutation germinale Tsc2⁺/⁻) développent léiomyomes utérins spontanés (~80% pénétrance)
- **Environnement hormonal intact** (vs xénogreffe)
- **Histologie similaire** aux fibromes humains
- **Les cellules souches/progénitrices myométriales offrent des cibles thérapeutiques nouvelles**

**Protocole** :

```
Semaines 0-4 :
- Souris Eker femelles (8-12 semaines)
- Implantation pellets hormonaux SC (17β-estradiol + progestérone)
  → Accélération croissance fibromes

Semaines 4-24 :
- Monitoring échographique mensuel (détection fibromes ≥3 mm)
- Développement fibromes multiples (3-6 mois)

Semaine 24 :
- Randomisation groupes traitement (n=10-12/groupe)
- Injection IV PS-conjugué ciblé (1-5 mg/kg)
- Fenêtre thérapeutique (24-48h selon PS)

Traitement PDT :
- Approche 1 : Laparotomie mini-invasive + fibres ILP
- Approche 2 : Irradiation transcutanée (si UCNPs)

Suivi post-PDT :
- Échographie hebdomadaire (volume fibromes)
- Sacrifice échelonné : 1 semaine, 1 mois, 3 mois
```

**Analyses histopathologiques** :

| **Paramètre** | **Méthode** | **Objectif** |
|--------------|-----------|------------|
| Volume fibrome | Échographie 3D + histomorphométrie | Réduction ≥50% |
| Nécrose sélective | H&E, Trichrome Masson | Fibrome nécrotique, myomètre intact |
| Fibrose résiduelle | Trichrome, Picrosirius Red | Quantifier collagène résiduel |
| Apoptose | TUNEL, Caspase-3 activée | Mécanisme mort cellulaire |
| Inflammation | CD45, F4/80 (macrophages) | Réponse immunitaire locale |

**Critères de succès** :

- ✅ Réduction volume fibrome ≥50% à 1 mois
- ✅ Nécrose fibrome sans 
