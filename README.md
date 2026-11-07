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

- **B7K VF-1, Darkglass, Breach:** Drive optimisé pour Basskick (50, 8, 16) + Big Muff texture = agressivité contrôlée
- **Dangle:** Drive **réduit à 0** = Big Muff remplace la saturation, son brillant et subtil sans excès

**Résultat:** Aucun preset trop "dégueulasse", Dangle pas sur-saturé, Big Muff colore tout sans déborder.

### 🎸 UA1: DANGLE

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

### 🎸 UA2: B7K VF-1

| Paramètre                | Basskick  | Notes                     |
|--------------------------|-----------|---------------------------|
| **COMPRESSOR**           | OFF       |                           |
| **OCTAVE**               | OFF       |                           |
| **DISTORTION**           | OFF       |                           |
| **4BAND EQ**             |           |                           |
| Low EQ                   | +2dB      |                           |
| High EQ                  | 0dB       |                           |
| Level                    | 0dB       |                           |
| Low-mid F                | 1.0 kHz   |                           |
| Low-mid Q                | 2.0       |                           |
| Low-mid EQ               | +4dB      |                           |
| Hi-mid F                 | 2.5 kHz   |                           |
| Hi-mid Q                 | 2.0       |                           |
| Hi-mid EQ                | 0dB       |                           |
| **POSITION**             | EQ→AMP→NS | Ordre de routage          |
| **PREAMP/SP.SIM**        | ON        |                           |
| Type                     | AMG       |                           |
| Volume                   | 80        |                           |
| Bass                     | +25       |                           |
| Middle                   | +35       |                           |
| Treble                   | +45       |                           |
| Master                   | 80        |                           |
| Bright                   | OFF       |                           |
| Gain                     | Mid       |                           |
| **PREAMP MIC SETTINGS**  |           |                           |
| MIC Setting              | Center    |                           |
| MIC Level                | 75        |                           |
| DIR Level                | 0         |                           |
| **NOISE SUPPRESSOR**     | ON        |                           |
| Threshold                | 75        |                           |
| Release                  | 15        |                           |
| **DELAY**                | OFF       |                           |
| **MOD**                  | OFF       |                           |
| **REVERB**               | OFF       |                           |
| **MASTER**               |           |                           |
| Master Level             | 100       |                           |
| Foot Level               | 100       |                           |
| BPM                      | 120       |                           |

**Signature sonore:** Préamp AMG chaud (Bass +25, Middle +35, Treble +45), médium-bas boosté (+4dB @1kHz), aigus neutres. Pas de compression/octave/distorsion : le préamp fait tout le travail.

**🎛️ Visualisation EQ B7K VF-1 (Basskick):**

```ascii
          ███
          ███
███       ███
███   ███ ███   ███
━━━━━━━━━━━━━━━━━━━━
Low  1kHz 2.5k High
+2dB +4dB 0dB  0dB

GRIFFE: Boost médium-bas (+4dB @1kHz) + Low léger (+2dB) = corps chaud via AMG, aigus neutres
```

### UA3: B7K-LOUD

| Paramètre                | Basskick  | Notes |
|--------------------------|-----------|-------|
| **COMPRESSOR**           | OFF       |       |
| **OCTAVE**               | OFF       |       |
| **DISTORTION**           | ON        |       |
| Type                     | Bass OD   |       |
| Drive                    | 4         |       |
| Bass                     | +10       |       |
| Treble                   | 0dB       |       |
| Fx Level                 | 5         |       |
| Dir Level                | 65        |       |
| **4BAND EQ**             | ON        |       |
| Low EQ                   | +4dB      |       |
| High EQ                  | +4dB      |       |
| Level                    | 0dB       |       |
| Low-mid F                | 500 Hz    |       |
| Low-mid Q                | 1.0       |       |
| Low-mid EQ               | +6dB      |       |
| Hi-mid F                 | 2.5 kHz   |       |
| Hi-mid Q                 | 2.0       |       |
| Hi-mid EQ                | -2dB      |       |
| **POSITION**             | EQ→AMP→NS |       |
| **PREAMP/SP.SIM**        | ON        |       |
| Type                     | AMG       |       |
| Volume                   | 65        |       |
| Bass                     | +30       |       |
| Middle                   | +55       |       |
| Treble                   | +20       |       |
| Master                   | 90        |       |
| Bright                   | OFF       |       |
| Gain                     | Mid       |       |
| **PREAMP MIC SETTINGS**  |           |       |
| MIC Setting              | Center    |       |
| MIC Level                | 75        |       |
| DIR Level                | 0         |       |
| **NOISE SUPPRESSOR**     | ON        |       |
| Threshold                | 90        |       |
| Release                  | 30        |       |
| **DELAY**                | OFF       |       |
| **MOD**                  | OFF       |       |
| **REVERB**               | OFF       |       |
| **MASTER**               |           |       |
| Master Level             | 90        |       |
| Foot Level               | 100       |       |
| BPM                      | 120       |       |

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

### UA4: B7K-FAT

| Paramètre                | Basskick  | Notes |
|--------------------------|-----------|-------|
| **COMPRESSOR**           | OFF       |       |
| **OCTAVE**               | ON        |       |
| Oct Level                | 20        |       |
| Dir Level                | 100       |       |
| **DISTORTION**           | ON        |       |
| Type                     | Bass OD   |       |
| Drive                    | 2         |       |
| Bass                     | +5        |       |
| Treble                   | -5        |       |
| Fx Level                 | 20        |       |
| Dir Level                | 60        |       |
| **4BAND EQ**             | ON        |       |
| Low EQ                   | +8dB      |       |
| High EQ                  | +5dB      |       |
| Level                    | 0dB       |       |
| Low-mid F                | 500 Hz    |       |
| Low-mid Q                | 1.0       |       |
| Low-mid EQ               | +6dB      |       |
| Hi-mid F                 | 2.5 kHz   |       |
| Hi-mid Q                 | 2.0       |       |
| Hi-mid EQ                | -2dB      |       |
| **POSITION**             | EQ→AMP→NS |       |
| **PREAMP/SP.SIM**        | ON        |       |
| Type                     | AMG       |       |
| Volume                   | 60        |       |
| Bass                     | +25       |       |
| Middle                   | +40       |       |
| Treble                   | +20       |       |
| Master                   | 90        |       |
| Bright                   | OFF       |       |
| Gain                     | Mid       |       |
| **PREAMP MIC SETTINGS**  |           |       |
| MIC Setting              | Center    |       |
| MIC Level                | 75        |       |
| DIR Level                | 0         |       |
| **NOISE SUPPRESSOR**     | ON        |       |
| Threshold                | 90        |       |
| Release                  | 30        |       |
| **DELAY**                | OFF       |       |
| **MOD**                  | OFF       |       |
| **REVERB**               | OFF       |       |
| **MASTER**               |           |       |
| Master Level             | 100       |       |
| Foot Level               | 100       |       |
| BPM                      | 120       |       |

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

### UA5: DJENT

| Paramètre                | Basskick  | Notes |
|--------------------------|-----------|-------|
| **COMPRESSOR**           | OFF       |       |
| **OCTAVE**               | OFF       |       |
| **DISTORTION**           | OFF       |       |
| **4BAND EQ**             | ON        |       |
| Low EQ                   | 0dB       |       |
| High EQ                  | +4dB      |       |
| Level                    | 0dB       |       |
| Low-mid F                | 1.0 kHz   |       |
| Low-mid Q                | 1.0       |       |
| Low-mid EQ               | +4dB      |       |
| Hi-mid F                 | 2.5 kHz   |       |
| Hi-mid Q                 | 2.0       |       |
| Hi-mid EQ                | +2dB      |       |
| **POSITION**             | EQ→AMP→NS |       |
| **PREAMP/SP.SIM**        | ON        |       |
| Type                     | AMG       |       |
| Volume                   | 80        |       |
| Bass                     | +25       |       |
| Middle                   | +10       |       |
| Treble                   | +45       |       |
| Master                   | 95        |       |
| Bright                   | OFF       |       |
| Gain                     | Mid       |       |
| **PREAMP MIC SETTINGS**  |           |       |
| MIC Setting              | Center    |       |
| MIC Level                | 75        |       |
| DIR Level                | 0         |       |
| **NOISE SUPPRESSOR**     | OFF       |       |
| **DELAY**                | OFF       |       |
| **MOD**                  | OFF       |       |
| **REVERB**               | OFF       |       |
| **MASTER**               |           |       |
| Master Level             | 100       |       |
| Foot Level               | 100       |       |
| BPM                      | 120       |       |

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
| **1**      | B7K VF-1   | 50    | Basskick 515W haute-fi |
| **2**      | darkglass  | 18    | Basskick 515W haute-fi |
| **3**      | Breach     | 15    | Basskick 515W haute-fi |
| **4**      | Djent      | -     | Basskick 515W haute-fi |
| **5**      | Dangle     | 0     | Basskick 515W haute-fi |

**Big Muff:** Volume 14h, Tone 13-14h, Sustain 22-23h, NORM

---

## 📁 Fichiers Presets

### 🎸 BANQUE 1: BASSKICK 515W (UA1-UA5)

| UA      | Preset     | Fichier                         |
|---------|------------|---------------------------------|
| **UA1** | Dangle     | *Contenu dans README section 3* |
| **UA2** | B7K VF-1   | *Contenu dans README section 3* |
| **UA3** | Darkglass  | *Contenu dans README section 3* |
| **UA4** | Breach     | *Contenu dans README section 3* |
| **UA5** | Djent      | *Contenu dans README section 3* |

**Big Muff:** Volume 14h, Tone 13-14h, Sustain 22-23h, NORM

| UA       | Preset         | Fichier                                            |
|----------|----------------|----------------------------------------------------|
| **UA6**  | Dangle 10W     | [UA6-Dangle-10W.txt](UA6-Dangle-10W.txt)           |
| **UA7**  | B7K VF-1 10W   | [UA7-B7K-VF-1-10W.txt](UA7-B7K-VF-1-10W.txt)       |
| **UA8**  | Darkglass 10W  | [UA8-Darkglass-10W.txt](UA8-Darkglass-10W.txt)     |
| **UA9**  | Breach 10W     | [UA9-Breach-10W.txt](UA9-Breach-10W.txt)           |
| **UA10** | Punchycore 10W | [UA10-Punchycore-10W.txt](UA10-Punchycore-10W.txt) |

**Big Muff:** Volume 14h, Tone 13-14h, Sustain 22-23h, NORM (même réglages)

---

### 📚 Documentation Technique

- [CORRECTION-LIVE-BASSKICK.txt](CORRECTION-LIVE-BASSKICK.txt) - **Guide test Basskick 515W + compensation live si différences perçues**
