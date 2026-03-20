# VF-1 Setup - Configuration

## Overview

**Setup Final:** VF-1 + Big Muff Electro Harmonix 9V

**Band Context:** Breach / Refused / Days Spent

**Bassiste:** jeu au médiator/pick

**Bass:** Ibanez SR 905 (5 cordes, tuning B-D-A-D-G)

---

## 🔌 1. Setup Physique

### Signal Chain

```txt
Ibanez SR 905 (5 cordes, tuning B-D-A-D-G, active)
    ↓
Boss VF-1 (Input L/MONO, level -20dB)
    ↓
VF-1 Output MONO
    ↓
Big Muff Electro Harmonix USA 9V (INPUT → EFFECT OUT)
    ↓
H&K Basskick 515 4Ω (Input) + Cabinet 300W 8Ω (série)
```

**🔑 Point clé:** Big Muff est en **POST-EFFECT** (après VF-1). Le VF-1 reçoit un signal propre, puis la Big Muff colore le résultat final.

### Pedalboard

- **Roland FC-200** (MIDI OUT du FC-200 → MIDI IN du VF-1)

---

## ⚙️ 2. Réglages Big Muff (FIXES - "Set & Forget")

| Paramètre                 | Réglage | Notes                                       |
|---------------------------|---------|---------------------------------------------|
| **Volume Potentiometer**  | 14h     | Compense signal actif Ibanez, grain optimal |
| **Tone Potentiometer**    | 13-14h  | Brillant/clair, laisse passer les HF        |
| **Sustain Potentiometer** | 22-23h  | MAXIMUM saturation                          |
| **Switch Position**       | NORM    | Mode standard (pas Turbo), grain contrôlé   |

✅ **CES RÉGLAGES NE CHANGENT JAMAIS** (brancher et oublier)

---

## 🎛️ 3. Presets VF-1 - Config Équilibrée

**Architecture:** Big Muff en **post-effect** (après VF-1). VF-1 reçoit signal propre, Big Muff fournit la texture finale.

**Stratégie d'équilibre:**

- **Beatdown, darkglass, Breach, Punchycore:** Drive original conservé (50, 18, 15, 6) + Big Muff texture = agressivité contrôlée
- **Dangle:** Drive **réduit à 0** (au lieu de 2) = Big Muff remplace la saturation, son brillant et subtil sans excès

**Résultat:** Aucun preset trop "dégueulasse", Dangle pas sur-saturé, Big Muff colore tout sans déborder.

### 🎸 UA1: DANGLE

- **Fonction:** Groovy/subtle clean (brillance, chorus léger)
- **Drive:** 0 (réduit de 2 original → Big Muff remplace la saturation)
- **Key Settings:** Chorus: ON (Mode Mono, Rate 10, Depth 30), Sustain: 60
- ✅ **Note:** Chorus espacé + **Big Muff = seule saturation** = brillant subtil sans excès
- ⚙️ **Référence live:** Dangle = son de base, tous les autres se comparent à celui-ci

```txt
COMPRESSOR
  Sustain: 60      Sustain modéré, moins serré que Darkglass
  Attack: 40       Attaque moyenne, laisse passer le transitoire
  Enh Level: 10    Léger boost des harmoniques
  Level: 90        Volume sortie compresseur

OCTAVE
  Oct Level: 25    Légère couleur sub, effet subtil et groovy
  Dir Level: 100   100% du signal direct passe

DISTORTION (Bass OD)
  Drive: 0         ⭐ SANS SATURATION (Big Muff remplace)
  Bass: 0          Basses neutres
  Treble: +10      Brillance et définition
  Fx Level: 20     Effet discret, en soutien du son propre

4BAND EQ
  Low EQ: +6dB       Boost basses nettes
  High EQ: +10dB     Aigus brillants et présents
  Level: +2dB        Léger boost global de l'EQ
  Low-mid EQ: -2dB   Légère coupe médiums-bas (clarté)
  Hi-mid EQ: +4dB    Boost présence et attaque (tranche dans le mix)

CHORUS ON
  Mode: Mono         Chorus mono (compatible basse en scène)
  Rate: 10           Modulation lente, effet subtil
  Depth: 30          Profondeur modérée, son légèrement élargi
  Low Cut: 340Hz     Coupe les basses du chorus (garde fondamentale propre)
  Fx Level: 18       Chorus discret, juste une couleur

NOISE SUPPRESSOR
  Threshold: 100     Coupure maximale des bruits parasites
  Release: 13        Relâche rapide

MASTER
  Master Level: 90
  BPM: 120
```

**Signature sonore:** Brillant subtil avec chorus spatial. Drive = 0 car Big Muff fournit la saturation. Groovy clean.

### 🎸 UA2: SUBWOOFER - BEATDOWN

- **Fonction:** Heavy breakdown, lourd et massif (contexte hardcore)
- **Drive:** 50 (valeur originale, inchangée)
- **Key Settings:** Oct Level: 90, Sustain compresseur: 40
- ✅ **Note:** VF-1 travaille sur signal propre, Big Muff ajoute le grain final
- ⚙️ **Si sonne trop fort en live:** ajuster Master 100 → 95-98 (cf. CORRECTION-LIVE-BASSKICK.txt)

```txt
COMPRESSOR
  Sustain: 40    Sustain court, attaque percussive et punchy
  Attack: 70     Attaque lente, laisse passer le transitoire
  Enh Level: 30  Boost harmoniques modéré (plus de grain)
  Level: 100     Volume sortie compresseur au max

OCTAVE
  Oct Level: 90     Sub très présent, son lourd et massif
  Dir Level: 45     Signal direct réduit, l'octave domine

DISTORTION (Bass OD)
  Drive: 50       Saturation poussée, son agressif
  Bass: +15       Boost basses important, son lourd et dense
  Treble: -5      Légère coupe aigus, évite l'agressivité excessive
  Fx Level: 20    Distorsion en soutien sans écraser le sub

4BAND EQ
  Low EQ: +4dB      Boost basses modéré (le sub de l'octave fait le reste)
  High EQ: -2dB     Légère coupe aigus, son sombre et lourd
  Level: +12dB      Boost fort du niveau global (compensation)
  Low-mid EQ: -4dB  Coupe médiums-bas (évite le mud)
  Hi-mid EQ: +4dB   Boost présence pour couper dans le mix

NOISE SUPPRESSOR
  Threshold: 100    Coupure maximale des bruits parasites
  Release: 13       Relâche rapide

MASTER
  Master Level: 100
  BPM: 120
```

**Signature sonore:** Breakdown ultra-lourd avec sub dominant. Cristallin + poids extrême.

### UA3: DARKGLASS

- **Fonction:** Transparent technique, agressif mais clair (Darkglass-like)
- **Drive:** 18 (valeur originale, inchangée)
- **Key Settings:** Preamp/SP.SIM: ON (Ampeg coloration), Sustain 65
- ✅ **Note:** Clarité VF-1 + texture Big Muff = grain vintage transparent
- ⚙️ **Si sonne plus faible en live:** ajuster Master 80 → 82-85 ou Preamp Volume ↑ (cf. CORRECTION-LIVE-BASSKICK.txt)

```txt
COMPRESSOR
  Sustain: 65      Agression/maintien pour clarté aggressive
  Attack: 25       Rapide, laisse passer l'attaque
  Enh Level: 10    Léger boost des harmoniques
  Level: 90        Volume sortie compresseur

OCTAVE
  Oct Level: 0     OFF (pas de sub, juste grain pur)
  Dir Level: 100   100% du signal direct passe

DISTORTION (Bass OD)
  Drive: 18        Agressif mais transparent
  Bass: +8         Boost basses modéré
  Treble: +10      Crisp et définition
  Fx Level: 45     Présence sans écrasement

4BAND EQ
  Low EQ: +6dB       Boost basses nettes
  High EQ: +8dB      Aigus présents (crisp)
  Level: +2dB        Léger boost global
  Low-mid EQ: -2dB   Légère coupe médiums-bas (clarté)
  Hi-mid EQ: -2dB    COUPE médiums-hauts (zéro concurrence guitare!)

PREAMP/SP.SIM ON
  Preamp Type: AMG AMP (Ampeg - définition aggressive)
  Volume: 90       Niveau sortie préamp
  Bass: +25        Boost basses (grain lourd)
  Middle: -5       COUPE médiums (laisse guitare dominer)
  Treble: +5       Aigus contrôlés
  Master: 70       Volume général préamp
  Gain: High       Saturation présente
  Dir Level: 50    Mix 50/50 préamp+signal

NOISE SUPPRESSOR
  Threshold: 70    Niveau de coupure du bruit
  Release: 15      Temps de relâche rapide

MASTER
  Master Level: 80 (Basskick 515W) / 75 (Combo 10W)
  BPM: 120
```

**Signature sonore:** Transparent agressif. Préamp Ampeg = couleur vintage distincte. Clé technique.

### UA4: BREACH

- **Fonction:** Hardcore mélodique agressif (Raised Fist/Breach style)
- **Drive:** 15 (valeur originale, inchangée)
- **Key Settings:** Hi-mid EQ: +5dB (clé pour couper guitare), Sustain: 48
- ✅ **Note:** Présence mid préservée, Big Muff ajoute la couleur
- ⚙️ **Si manque de coupure guitare en live:** Hi-mid EQ +5dB → +6-7dB (signature de Breach) (cf. CORRECTION-LIVE-BASSKICK.txt)

```txt
COMPRESSOR
  Sustain: 48      Sustain court, notes définies et percussives
  Attack: 28       Rapide, laisse s'exprimer le transitoire
  Enh Level: 15    Boost modéré des harmoniques (grain transparent)
  Level: 92        Volume sortie compresseur

OCTAVE
  Oct Level: 5     Minimal, juste une trace sub (discrétion)
  Dir Level: 100   100% du signal direct passe

DISTORTION (Bass OD)
  Drive: 15        Saturation légère, notes restent claires
  Bass: +6         Boost basses modéré (structure)
  Treble: +6       Brillance sans agressivité
  Fx Level: 25     Effet en soutien discret

4BAND EQ
  Low EQ: +5dB       Boost basses net et défini
  High EQ: +6dB      Aigus présents (croustillant)
  Level: +5dB        Léger boost global (punch sans saturation)
  Low-mid EQ: -3dB   Légère coupe (clarté mids/bass)
  Hi-mid EQ: +5dB    BOOST PRÉSENCE (tranche du dans le mix) ⭐ CLÉ

NOISE SUPPRESSOR
  Threshold: 75      Coupure modérée
  Release: 12        Relâche rapide (fluidité)

MASTER
  Master Level: 88
  BPM: 120
```

**Signature sonore:** Agressif mélodique. Hi-mid boostée = coupe guitare proprement. Raising Fist / Refused style.

### UA5: PUNCHYCORE

- **Fonction:** Switching rapide vers clean mélodique (post-hardcore)
- **Drive:** 6 (valeur originale, inchangée)
- **Key Settings:** Lo-mid EQ: +6dB (boost midrange = punch), Sustain: 55
- ✅ **Note:** Percussif du VF-1 + saturation textural Big Muff
- ⚙️ **Si manque de punch en live:** Lo-mid EQ +6dB → +7-8dB (signature de Punchycore) (cf. CORRECTION-LIVE-BASSKICK.txt)

```txt
COMPRESSOR
  Sustain: 55      Sustain modéré-court pour attaque percussive
  Attack: 18       Très rapide, ne compresse pas le transitoire
  Enh Level: 5     Boost minimal des harmoniques
  Level: 95        Volume sortie compresseur

OCTAVE
  Oct Level: 8     Très subtil, juste couleur sub
  Dir Level: 100   100% du signal direct passe

DISTORTION (Bass OD)
  Drive: 6         Quasi-propre, juste transparence timbrale
  Bass: 0          Basses neutres
  Treble: +8       Brillance douce
  Fx Level: 15     Effet très discret

4BAND EQ
  Low EQ: +4dB       Boost basses modéré (pas de saturation)
  High EQ: +4dB      Aigus nets et définis
  Level: +8dB        Boost global solid (punch dans le mix)
  Low-mid EQ: +6dB   BOOST MIDRANGE ⭐ CLÉ DU PUNCH
  Hi-mid EQ: +3dB    Boost léger présence/attaque

NOISE SUPPRESSOR
  Threshold: 75      Coupure modérée du bruit
  Release: 12        Relâche rapide mais stable

MASTER
  Master Level: 92
  BPM: 120
```

**Signature sonore:** Percussif midrange-forward. Switching rapide Beatdown/Darkglass vers clean mélodique. Post-hardcore transitions.

---

## 4. Structure Finale - Confirmée ✅

| Élément                | Config                    | Détail                                      |
|------------------------|---------------------------|---------------------------------------------|
| **Basse**              | Ibanez SR 905 Active      | Batterie 9V interne                         |
| **VF-1 Input**         | -20dB                     | Signal actif élevé                          |
| **VF-1 Presets**       | Équilibrés (1 ajustement) | Drive: 50, 18, 15, 6, **0** (Dangle réduit) |
| **Big Muff Position**  | POST-VF-1 (après)         | Colore le signal finalisé                   |
| **Big Muff Volume**    | 14h                       | Optimal pour signal actif                   |
| **Big Muff Tone**      | 13-14h                    | Brillant, transparent                       |
| **Big Muff Sustain**   | 22-23h                    | Maximum saturation                          |
| **Connexion Basskick** | Input mono                | Via EFFECT OUT Muff                         |
| **Pedalboard**         | Roland FC-200             | Switching presets VF-1                      |

✅ **Presets ORIGINAUX (pas de versions -Muff nécessaires)**

✅ **Zéro conflit double-saturation (Big Muff en post)**

---

## � 4b. Structure FC-200 & Mémoire VF-1

**Roland FC-200** = 10 footswitches + navigation

**Organisation proposée (3 banques de 5 presets):**

### BANQUE 1: Basskick 515W (UA1-UA5)

| Footswitch | Preset     | Drive | Config                 |
|------------|------------|-------|------------------------|
| **1**      | Beatdown   | 50    | Basskick 515W haute-fi |
| **2**      | darkglass  | 18    | Basskick 515W haute-fi |
| **3**      | Breach     | 15    | Basskick 515W haute-fi |
| **4**      | Punchycore | 6     | Basskick 515W haute-fi |
| **5**      | Dangle     | 0     | Basskick 515W haute-fi |

**Big Muff:** Volume 14h, Tone 13-14h, Sustain 22-23h, NORM

---

### BANQUE 2: Big Muff Adapté (UA6-UA10)

| Footswitch | Preset         | Drive | Config                   |
|------------|----------------|-------|--------------------------|
| **6**      | Beatdown-Opt   | 50    | Basskick + Muff optimisé |
| **7**      | darkglass-Opt  | 18    | Basskick + Muff optimisé |
| **8**      | Breach-Opt     | 15    | Basskick + Muff optimisé |
| **9**      | Punchycore-Opt | 6     | Basskick + Muff optimisé |
| **10**     | Dangle-Opt     | 0     | Basskick + Muff optimisé |

**Big Muff:** Volume 14h, Tone 13-14h, Sustain 22-23h, NORM (même réglages)

---

### BANQUE 3: Combo 10W (UA11-UA15) - À tester

| User Array | Preset         | Drive | Config           |
|------------|----------------|-------|------------------|
| **UA11**   | Beatdown-10W   | 50    | Combo 10W (test) |
| **UA12**   | darkglass-10W  | 18    | Combo 10W (test) |
| **UA13**   | Breach-10W     | 15    | Combo 10W (test) |
| **UA14**   | Punchycore-10W | 6     | Combo 10W (test) |
| **UA15**   | Dangle-10W     | 0     | Combo 10W (test) |

**Big Muff:** À ajuster après test (potentiellement Volume 12h, Tone 15h, Sustain 21h)

---

## �🎮 5. Workflow Live

```txt
Début de song → FC-200 switche preset (ex: Beatdown)
    ↓
Big Muff déjà ON (réglages fixes: Volume 14h, Tone 13-14h, Sustain 22-23h)
    ↓
VF-1 charge preset avec Drive équilibré (50, 18, 15, 6, ou 0 pour Dangle)
    ↓
Signal propre VF-1 + Big Muff texturité = son final cohérent, ni trop saturé ni trop faible
    ↓
Pas de manipulation à l'oreille, pas de footswitch supplémentaire
```

✅ **BASSISTE-FRIENDLY:** Un seul footswitch (FC-200 pour presets)

---

## 📝 6. Notes pour l'Ingénieur Son

### Configuration testée pour

- ✓ Hardcore / postharcore (Breach/Refused style, Days spent)
- ✓ Jeu au médium/pick (attaque percussive)
- ✓ Tuning: Ibanez SR 905 en B standard
- ✓ Amplification: H&K Basskick 515 (transparence haute fidélité)

### Paramètres critiques immuables

- **Big Muff Volume:** 14h (NE PAS CHANGER)
- **Big Muff Tone:** 13-14h (NE PAS CHANGER)
- **Big Muff Sustain:** 22-23h (NE PAS CHANGER)
- **Big Muff Switch:** NORM (NE PAS CHANGER)

### Flexibilité d'ajustement possible

- Drive chaque preset ±2-3 points selon salle (test en live, sauf Dangle Drive 0 qui peut monter à 1 si besoin)
- Hi-mid EQ (Breach) ±2dB si trop/peu de présence
- Noise Suppressor Threshold selon niveau amplification

---

## ✅ 7. Checklist Préchargement

- [ ] Big Muff branché APRÈS VF-1 (INPUT → EFFECT OUT)
- [ ] Big Muff réglages: Volume 14h, Tone 13-14h, Sustain 22-23h, NORM (immuable)
- [ ] VF-1 Level input: -20dB (Ibanez active)
- [ ] VF-1 OUTPUT MONO → Big Muff INPUT
- [ ] Big Muff EFFECT OUT → H&K Basskick INPUT
- [ ] FC-200 MIDI IN connecté au VF-1
- [ ] 5 presets chargés en mémoire VF-1: Beatdown (Drive 50), darkglass (Drive 18), Breach (Drive 15), Punchycore (Drive 6), **Dangle (Drive 0)**
- [ ] FC-200 programmé pour switcher entre 5 presets
- [ ] Tous cables audio jack testés (pas de buzz/hum)

---

## 📁 Fichiers Presets

### 🎸 BANQUE 1: BASSKICK 515W (UA1-UA5)

| UA      | Preset     | Fichier                         |
|---------|------------|---------------------------------|
| **UA1** | Dangle     | *Contenu dans README section 3* |
| **UA2** | Beatdown   | *Contenu dans README section 3* |
| **UA3** | Darkglass  | *Contenu dans README section 3* |
| **UA4** | Breach     | *Contenu dans README section 3* |
| **UA5** | Punchycore | *Contenu dans README section 3* |

**Big Muff:** Volume 14h, Tone 13-14h, Sustain 22-23h, NORM

---

### 🎸 BANQUE 2: COMBO 10W (UA6-UA10)

| UA       | Preset         | Fichier                                            |
|----------|----------------|----------------------------------------------------|
| **UA6**  | Dangle 10W     | [UA6-Dangle-10W.txt](UA6-Dangle-10W.txt)           |
| **UA7**  | Beatdown 10W   | [UA7-Beatdown-10W.txt](UA7-Beatdown-10W.txt)       |
| **UA8**  | Darkglass 10W  | [UA8-Darkglass-10W.txt](UA8-Darkglass-10W.txt)     |
| **UA9**  | Breach 10W     | [UA9-Breach-10W.txt](UA9-Breach-10W.txt)           |
| **UA10** | Punchycore 10W | [UA10-Punchycore-10W.txt](UA10-Punchycore-10W.txt) |

**Big Muff:** Volume 14h, Tone 13-14h, Sustain 22-23h, NORM (même réglages)

---

### 📚 Documentation Technique

- [AFFINAGE-10W.txt](AFFINAGE-10W.txt) - **Adaptations complètes pour 10W (maison, affinage)**
- [CORRECTION-LIVE-BASSKICK.txt](CORRECTION-LIVE-BASSKICK.txt) - **Guide test Basskick 515W + compensation live si différences perçues**
- [TRANSPOSITION-GUIDE.txt](TRANSPOSITION-GUIDE.txt) - Guide général transposition sans reaccordage
- [ANTHEMS-TRANSPOSITION.txt](ANTHEMS-TRANSPOSITION.txt) - Solution spécifique pour "Anthems" (C key)
- [KEY-TRANSPOSITION.txt](KEY-TRANSPOSITION.txt) - Configuration VF-1 KEY parameter
- [README.md](README.md) - Ce fichier
- [SETUP-VERIFICATION.txt](SETUP-VERIFICATION.txt) - Checklist de setup complet
