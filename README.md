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

| Paramètre                 | Réglage | Notes                                                             |
|---------------------------|---------|-------------------------------------------------------------------|
| **Volume Potentiometer**  | 14h     | Compense signal actif Ibanez, grain optimal                       |
| **Tone Potentiometer**    | 21h     | Clair/transparent, son définition nette (TESTÉ)                   |
| **Sustain Potentiometer** | 21h     | Sustain modéré, moins de Larsen feedback (TESTÉ)                  |
| **Switch Position**       | DRY     | Mode Dry (transparent), son net sans saturation excessive (TESTÉ) |

✅ **CES RÉGLAGES NE CHANGENT JAMAIS** (brancher et oublier)

---

## 🎛️ 3. Presets VF-1 - Config Équilibrée

**Architecture:** Big Muff en **post-effect** (après VF-1). VF-1 reçoit signal propre, Big Muff fournit la texture finale.

**Stratégie d'équilibre:**

- **Beatdown, Darkglass, Breach:** Drive optimisé pour Basskick (50, 8, 16) + Big Muff texture = agressivité contrôlée
- **Dangle:** Drive **réduit à 0** = Big Muff remplace la saturation, son brillant et subtil sans excès

**Résultat:** Aucun preset trop "dégueulasse", Dangle pas sur-saturé, Big Muff colore tout sans déborder.

### 🎸 UA1: DANGLE

- **Fonction:** Groovy/subtile clean (brillance, chorus léger)
- **Drive:** 0 (réduit de 2 original → Big Muff remplace la saturation)
- **Key Settings:** Chorus: ON (Mode Mono, Rate 10, Depth 30), Sustain: 60
- ✅ **Note:** Chorus espacé + **Big Muff = seule saturation** = brillant subtil sans excès
- ⚙️ **Référence live:** Dangle = son de base, tous les autres se comparent à celui-ci

| Paramètre                | Basskick | Notes                     |
|--------------------------|----------|---------------------------|
| **COMPRESSOR**           |          |                           |
| Sustain                  | 60       | Modéré, moins serré       |
| Attack                   | 40       | Attaque moyenne           |
| ENH Freq                 | 0        | Stable                    |
| ENH Level                | 10       | Subtil                    |
| Level                    | 90       | Stable                    |
| **OCTAVE**               |          |                           |
| Oct Level                | 25       | Subtil groovy             |
| Dir Level                | 100      | Stable                    |
| **DISTORTION**           | OFF      | Big Muff suffit           |
| **4BAND EQ**             |          |                           |
| Low EQ                   | +6dB     | Stable                    |
| High EQ                  | +10dB    | Brillance maximale        |
| Level                    | +2dB     | Stable                    |
| Low-mid F                | 630 Hz   | Stable                    |
| Low-mid Q                | 1.0      | Stable                    |
| Low-mid EQ               | -2dB     | Clarté                    |
| Hi-mid F                 | 2.5 kHz  | Stable                    |
| Hi-mid Q                 | 2.0      | Stable                    |
| Hi-mid EQ                | +4dB     | Présence et attaque       |
| **PREAMP**               | OFF      | Stable                    |
| **NOISE SUPPRESSOR**     |          |                           |
| Threshold                | 100      | Coupe parasites           |
| Release                  | 13       | Relâche rapide            |
| **DELAY**                | OFF      | Stable                    |
| **MOD (CHORUS)**         |          |                           |
| Mode                     | Mono     | Compatible scène          |
| Rate                     | 10       | Modulation lente          |
| Depth                    | 30       | Profondeur modérée        |
| Predelay                 | 20.5ms   | Légère temporisation      |
| Low Cut                  | 340 Hz   | Coupe basses du chorus    |
| Fx Level                 | 20       | Discret, en soutien       |
| **REVERB**               | OFF      | Stable                    |
| **MASTER**               |          |                           |
| Master Level             | 90       | Stable                    |
| Foot Level               | 100      | Stable                    |
| BPM                      | 120      | Stable                    |

**Signature sonore:** Brillant subtil avec chorus spatial. Drive = 0 car Big Muff fournit la saturation. Groovy clean.

**🎛️ Visualisation EQ DANGLE (Basskick):**

```ascii
                                       ███   ███   ███   ███
                                       ███   ███   ███   ███
                                       ███   ███   ███   ███
                  ███     ███          ███   ███   ███   ███
███       ███     ███     ███     ███  ███   ███   ███   ███
███   ███ ███ ███ ███ ███ ███ ███ ███  ███   ███   ███   ███
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

GRIFFE: Brillant aigus massif (+10dB 12kHz) / Bass+Hi-mid boost = Groovy sparkle  
```

### 🎸 UA2: SUBWOOFER - BEATDOWN

- **Fonction:** Heavy breakdown, lourd et massif (contexte hardcore)
- **Drive:** 50 (optimisé Basskick)
- **Key Settings:** Oct Level: 90, Sustain compresseur: 40
- ✅ **Note:** VF-1 travaille sur signal propre, Big Muff ajoute le grain final
- ⚙️ **Si sonne trop fort en live:** ajuster Master 100 → 95-98 (cf. CORRECTION-LIVE-BASSKICK.txt)

| Paramètre                | Basskick | Notes                     |
|--------------------------|----------|---------------------------|
| **COMPRESSOR**           |          |                           |
| Sustain                  | 40       | Court, attaque percussive |
| Attack                   | 70       | Lente, laisse transitoire |
| ENH Freq                 | 0        | Stable                    |
| ENH Level                | 30       | Boost grain               |
| Level                    | 100      | Maximal                   |
| **OCTAVE**               |          |                           |
| Oct Level                | 90       | Sub dominant              |
| Dir Level                | 45       | Stable, octave dominant   |
| **DISTORTION (Bass OD)** |          |                           |
| Type                     | Bass OD  | Stable                    |
| Drive                    | 50       | Agressif                  |
| Bass                     | +15      | Boost basses lourd        |
| Treble                   | -5       | Coupe aigus, son sombre   |
| Fx Level                 | 20       | Signal direct dominant    |
| Dir Level                | 100      | Stable                    |
| **4BAND EQ**             |          |                           |
| Low EQ                   | +4dB     | Stable                    |
| High EQ                  | -2dB     | Coupe légère aigus        |
| Level                    | +12dB    | Ultra-grave dominant      |
| Low-mid F                | 400 Hz   | Stable, corps grave       |
| Low-mid Q                | 1.0      | Stable                    |
| Low-mid EQ               | -4dB     | Coupe mud bas-médium      |
| Hi-mid F                 | 2.5 kHz  | Stable                    |
| Hi-mid Q                 | 2.0      | Stable                    |
| Hi-mid EQ                | +4dB     | Boost présence/mix        |
| **PREAMP**               | OFF      | Stable                    |
| **NOISE SUPPRESSOR**     |          |                           |
| Threshold                | 100      | Coupure maximale          |
| Release                  | 13       | Relâche rapide            |
| **DELAY**                | OFF      | Stable                    |
| **MOD**                  | OFF      | Stable                    |
| **REVERB**               | OFF      | Stable                    |
| **MASTER**               |          |                           |
| Master Level             | 100      | Maximal                   |
| Foot Level               | 100      | Stable                    |
| BPM                      | 120      | Stable                    |
| Foot Level               | 100      | Stable                    |
| BPM                      | 120      | Stable                    |

**Signature sonore:** Breakdown ultra-lourd avec sub dominant. Cristallin + poids extrême.

**🎛️ Visualisation EQ BEATDOWN (Basskick):**

```ascii
███        ███                 ███              
███        ███                 ███              
███        ███                 ███              
███   ███  ███      ███   ███  ███   ███       
███   ███  ███  ███ ███   ███  ███   ███   ███
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
100  300   400  2.5k 4k   6k   10k   12k

GRIFFE: Creux BRUTAL à 400Hz (-4dB) + Grave/Mid dominant = Sous-basse massive  
```

### UA3: DARKGLASS

- **Fonction:** Transparent technique, agressif mais clair (Darkglass-like)
- **Drive:** 8 (optimisé Basskick)
- **Key Settings:** Preamp/SP.SIM: ON (Ampeg coloration), Sustain 70
- ✅ **Note:** Clarité VF-1 + texture Big Muff = grain vintage transparent
- ⚙️ **Si sonne plus faible en live:** ajuster Master 80 → 82-85 ou Preamp Volume ↑ (cf. CORRECTION-LIVE-BASSKICK.txt)

| Paramètre                | Basskick | Notes                        |
|--------------------------|----------|------------------------------|
| **COMPRESSOR**           |          |                              |
| Sustain                  | 70       | Stable, agressif/technique   |
| Attack                   | 25       | Stable                       |
| ENH Freq                 | 0        | Stable                       |
| ENH Level                | 10       | Subtil                       |
| Level                    | 90       | Stable                       |
| **OCTAVE**               |          |                              |
| Oct Level                | 0        | OFF, stable                  |
| Dir Level                | 100      | Stable                       |
| **DISTORTION (Bass OD)** |          |                              |
| Type                     | Bass OD  | Stable                       |
| Drive                    | 8        | Transparent                  |
| Bass                     | +10      | Stable                       |
| Treble                   | +10      | Stable                       |
| Fx Level                 | 45       | Stable, réduit pour Larsen   |
| Dir Level                | 100      | Stable                       |
| **4BAND EQ**             |          |                              |
| Low EQ                   | +6dB     | Aligné BEATDOWN              |
| High EQ                  | +8dB     | Aligné BEATDOWN              |
| Level                    | +2dB     | Stable                       |
| Low-mid F                | 630 Hz   | Stable                       |
| Low-mid Q                | 1.0      | Stable                       |
| Low-mid EQ               | -2dB     | Coupe bouillie               |
| Hi-mid F                 | 2.5 kHz  | Stable                       |
| Hi-mid Q                 | 2.0      | Stable                       |
| Hi-mid EQ                | -2dB     | Coupe médiums hauts/guitare  |
| **PREAMP/SP.SIM**        | ON       | Stable                       |
| Type                     | Ampeg    | Couleur vintage              |
| Volume                   | 50       | Agressif, testé              |
| Bass                     | +25      | Stable                       |
| Middle                   | -5       | Stable                       |
| Treble                   | +5       | Stable                       |
| Master                   | 70       | Stable                       |
| Bright                   | OFF      | Pas de boost aigus extrême   |
| Gain                     | High     | Saturation présente          |
| **PREAMP MIC SETTINGS**  |          |                              |
| MIC Setting              | 10 cm    | Anti-Larsen, distance        |
| MIC Level                | 65       | Anti-Larsen, testé           |
| DIR Level                | 50       | Anti-Larsen, testé           |
| **NOISE SUPPRESSOR**     |          |                              |
| Threshold                | 100      | Coupe parasites              |
| Release                  | 10       | Stable                       |
| **DELAY**                | OFF      | Stable                       |
| **MOD**                  | OFF      | Stable                       |
| **MASTER**               |          |                              |
| Master Level             | 90       | Stable                       |
| Foot Level               | 100      | Stable                       |
| BPM                      | 120      | Stable                       |

**Signature sonore:** Transparent agressif. Préamp Ampeg = couleur vintage distincte. Clé technique.

Foot level actif pour éviter larsen en live (préamp + Big Muff = gain élevé, noise suppressor réglé pour couper parasites sans écrêter le signal).

**🎛️ Visualisation EQ DARKGLASS (Basskick):**

```ascii
                                            ███
                                            ███
                                    ███     ███
                            ███     ███     ███
███       ███               ███     ███     ███     ███
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
100  300  630  2.5k 4k   6k  10k  12k

GRIFFE: Coupe Mids (-2dB 630Hz et 2.5kHz) + Aigus montant (+8dB) = Transparent agressif  
```

### UA4: BREACH

- **Fonction:** Hardcore mélodique agressif (Raised Fist/Breach style) - Base lourde + clarté notes
- **Drive:** 16 (optimisé Basskick)
- **Key Settings:** Hi-mid EQ: +5dB (clé pour clarifier notes), Sustain: 50, Low EQ/Low-mid aligned DARKGLASS
- ✅ **Note:** Base EQ cohérente avec DARKGLASS (graves+poids identiques) | Hi-mid +5dB différencie pour clarté
- ⚙️ **Si manque de coupure guitare en live:** Hi-mid EQ +5dB → +6-7dB renforce clarté (cf. CORRECTION-LIVE-BASSKICK.txt)

| Paramètre                | Basskick | Notes                            |
|--------------------------|----------|----------------------------------|
| **COMPRESSOR**           |          |                                  |
| Sustain                  | 50       | Court, notes définies            |
| Attack                   | 30       | Rapide, transitoire libre        |
| ENH Freq                 | 0        | Stable                           |
| ENH Level                | 15       | Subtil, grain                    |
| Level                    | 92       | Stable                           |
| **OCTAVE**               |          |                                  |
| Oct Level                | 5        | Minimal, subtil                  |
| Dir Level                | 100      | Stable                           |
| **DISTORTION (Bass OD)** |          |                                  |
| Type                     | Bass OD  | Stable                           |
| Drive                    | 16       | Transparent                      |
| Bass                     | +5       | Boost basses modéré              |
| Treble                   | +5       | Brillance sans agressivité       |
| Fx Level                 | 25       | Effet discret                    |
| Dir Level                | 100      | Stable                           |
| **4BAND EQ**             |          |                                  |
| Low EQ                   | +6dB     | Aligné DARKGLASS                 |
| High EQ                  | +8dB     | Aligné DARKGLASS                 |
| Level                    | +6dB     | Boost présence                   |
| Low-mid F                | 400 Hz   | Stable, médiums-bas              |
| Low-mid Q                | 1.0      | Stable                           |
| Low-mid EQ               | -2dB     | Aligné DARKGLASS, coupe bouillie |
| Hi-mid F                 | 2.5 kHz  | Stable, CLÉ du preset            |
| Hi-mid Q                 | 2.0      | Stable                           |
| Hi-mid EQ                | +5dB     | ⭐ SIGNATURE coupe guitare       |
| **PREAMP**               | OFF      | Stable                           |
| **NOISE SUPPRESSOR**     |          |                                  |
| Threshold                | 75       | Coupure modérée                  |
| Release                  | 12       | Relâche rapide                   |
| **DELAY**                | OFF      | Stable                           |
| **MOD**                  | OFF      | Stable                           |
| **REVERB**               | OFF      | Stable                           |
| **MASTER**               |          |                                  |
| Master Level             | 100      | Aligné BEATDOWN                  |
| Foot Level               | 100      | Stable                           |
| BPM                      | 120      | Stable                           |

**Signature sonore:** Agressif mélodique. Hi-mid boostée = coupe guitare proprement. Raised Fist / Refused style.
**🎛️ Visualisation EQ BREACH (Basskick):**

```ascii
                                            ███
                                            ███
                                    ███     ███
                            ███     ███     ███
███       ███               ███     ███     ███     ███
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

## 4. Structure Finale - Confirmée ✅

| Élément                | Config                    | Détail                                      |
|------------------------|---------------------------|---------------------------------------------|
| **Basse**              | Ibanez SR 905 Active      | Batterie 9V interne                         |
| **VF-1 Input**         | -20dB                     | Signal actif élevé                          |
| **VF-1 Presets**       | Équilibrés Basskick       | Drive: 50, 8, 16, **0** (Dangle réduit)     |
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

- [CORRECTION-LIVE-BASSKICK.txt](CORRECTION-LIVE-BASSKICK.txt) - **Guide test Basskick 515W + compensation live si différences perçues**
