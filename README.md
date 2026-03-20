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

- **Fonction:** Groovy/subtile clean (brillance, chorus léger)
- **Drive:** 0 (réduit de 2 original → Big Muff remplace la saturation)
- **Key Settings:** Chorus: ON (Mode Mono, Rate 10, Depth 30), Sustain: 60
- ✅ **Note:** Chorus espacé + **Big Muff = seule saturation** = brillant subtil sans excès
- ⚙️ **Référence live:** Dangle = son de base, tous les autres se comparent à celui-ci

| Paramètre                | Basskick | 10W     | Notes                     |
|--------------------------|----------|---------|---------------------------|
| **COMPRESSOR**           |          |         |                           |
| Sustain                  | 60       | 60      | Stable                    |
| Attack                   | 40       | 40      | Stable                    |
| ENH Freq                 | 0        | 0       | Stable                    |
| ENH Level                | 10       | 8       | -20% 10W                  |
| Level                    | 90       | 85      | -5% 10W                   |
| **OCTAVE**               |          |         |                           |
| Oct Level                | 25       | 15      | -40% 10W, subtil          |
| Dir Level                | 100      | 100     | Stable                    |
| **DISTORTION (Bass OD)** |          |         |                           |
| Type                     | Bass OD  | Bass OD | Stable                    |
| Drive                    | 0        | 0       | Big Muff seule saturation |
| Bass                     | 0        | 0       | Stable                    |
| Treble                   | +10      | +10     | Stable                    |
| Fx Level                 | 20       | 20      | Stable                    |
| Dir Level                | 100      | 100     | Stable                    |
| **4BAND EQ**             |          |         |                           |
| Low EQ                   | +6dB     | +6dB    | Stable                    |
| High EQ                  | +10dB    | +10dB   | Stable                    |
| Level                    | +2dB     | +2dB    | Stable                    |
| Low-mid EQ               | -2dB     | -2dB    | Stable                    |
| Hi-mid EQ                | +4dB     | +4dB    | Stable                    |
| **PREAMP**               | OFF      | OFF     | Stable                    |
| **NOISE SUPPRESSOR**     |          |         |                           |
| Threshold                | 100      | 100     | Stable                    |
| Release                  | 13       | 13      | Stable                    |
| **DELAY**                | OFF      | OFF     | Stable                    |
| **MOD (CHORUS)**         |          |         |                           |
| Mode                     | Mono     | Mono    | Stable                    |
| Rate                     | 10       | 10      | Stable                    |
| Depth                    | 30       | 30      | Stable                    |
| Predelay                 | 20.5ms   | 20.5ms  | Stable                    |
| Fx Level                 | 18       | 16      | -11% 10W                  |
| **MASTER**               |          |         |                           |
| Master Level             | 90       | 75      | -17% 10W                  |
| Foot Level               | 100      | 100     | Stable                    |
| BPM                      | 120      | 120     | Stable                    |

**Signature sonore:** Brillant subtil avec chorus spatial. Drive = 0 car Big Muff fournit la saturation. Groovy clean.

### 🎸 UA2: SUBWOOFER - BEATDOWN

- **Fonction:** Heavy breakdown, lourd et massif (contexte hardcore)
- **Drive:** 40 (valeur originale, inchangée)
- **Key Settings:** Oct Level: 90, Sustain compresseur: 40
- ✅ **Note:** VF-1 travaille sur signal propre, Big Muff ajoute le grain final
- ⚙️ **Si sonne trop fort en live:** ajuster Master 100 → 95-98 (cf. CORRECTION-LIVE-BASSKICK.txt)

| Paramètre                | Basskick | 10W     | Notes                   |
|--------------------------|----------|---------|-------------------------|
| **COMPRESSOR**           |          |         |                         |
| Sustain                  | 40       | 40      | Stable, court/percussif |
| Attack                   | 70       | 70      | Stable                  |
| ENH Freq                 | 0        | 0       | Stable                  |
| ENH Level                | 30       | 25      | -17% 10W                |
| Level                    | 100      | 95      | -5% 10W                 |
| **OCTAVE**               |          |         |                         |
| Oct Level                | 90       | 60      | -33% 10W, sub lourd     |
| Dir Level                | 45       | 45      | Stable                  |
| **DISTORTION (Bass OD)** |          |         |                         |
| Type                     | Bass OD  | Bass OD | Stable                  |
| Drive                    | 40       | 36      | -10% 10W, agressif      |
| Bass                     | +15      | +15     | Stable                  |
| Treble                   | -5       | -5      | Stable                  |
| Fx Level                 | 20       | 20      | Stable                  |
| Dir Level                | 100      | 100     | Stable                  |
| **4BAND EQ**             |          |         |                         |
| Low EQ                   | +4dB     | +3dB    | -1dB 10W                |
| High EQ                  | -2dB     | -1dB    | +1dB 10W                |
| Level                    | +12dB    | +10dB   | -2dB 10W                |
| Low-mid EQ               | -4dB     | -4dB    | Stable                  |
| Hi-mid EQ                | +4dB     | +4dB    | Stable                  |
| **PREAMP**               | OFF      | OFF     | Stable                  |
| **NOISE SUPPRESSOR**     |          |         |                         |
| Threshold                | 100      | 100     | Stable                  |
| Release                  | 13       | 13      | Stable                  |
| **DELAY**                | OFF      | OFF     | Stable                  |
| **MOD**                  | OFF      | OFF     | Stable                  |
| **MASTER**               |          |         |                         |
| Master Level             | 100      | 80      | -20% 10W, maximal       |
| Foot Level               | 100      | 100     | Stable                  |
| BPM                      | 120      | 120     | Stable                  |

**Signature sonore:** Breakdown ultra-lourd avec sub dominant. Cristallin + poids extrême.

### UA3: DARKGLASS

- **Fonction:** Transparent technique, agressif mais clair (Darkglass-like)
- **Drive:** 18 (valeur originale, inchangée)
- **Key Settings:** Preamp/SP.SIM: ON (Ampeg coloration), Sustain 65
- ✅ **Note:** Clarité VF-1 + texture Big Muff = grain vintage transparent
- ⚙️ **Si sonne plus faible en live:** ajuster Master 80 → 82-85 ou Preamp Volume ↑ (cf. CORRECTION-LIVE-BASSKICK.txt)

| Paramètre                | Basskick | 10W     | Notes                      |
|--------------------------|----------|---------|----------------------------|
| **COMPRESSOR**           |          |         |                            |
| Sustain                  | 65       | 65      | Stable, agressif/technique |
| Attack                   | 25       | 25      | Stable                     |
| ENH Freq                 | 0        | 0       | Stable                     |
| ENH Level                | 10       | 8       | -20% 10W                   |
| Level                    | 90       | 85      | -5% 10W                    |
| **OCTAVE**               |          |         |                            |
| Oct Level                | 0        | 0       | OFF, stable                |
| Dir Level                | 100      | 100     | Stable                     |
| **DISTORTION (Bass OD)** |          |         |                            |
| Type                     | Bass OD  | Bass OD | Stable                     |
| Drive                    | 18       | 14      | -22% 10W, transparent      |
| Bass                     | +8       | +8      | Stable                     |
| Treble                   | +10      | +10     | Stable                     |
| Fx Level                 | 45       | 45      | Stable                     |
| Dir Level                | 100      | 100     | Stable                     |
| **4BAND EQ**             |          |         |                            |
| Low EQ                   | +6dB     | +5dB    | -1dB 10W                   |
| High EQ                  | +8dB     | +6dB    | -2dB 10W                   |
| Level                    | +2dB     | +2dB    | Stable                     |
| Low-mid EQ               | -2dB     | -2dB    | Stable                     |
| Hi-mid EQ                | -2dB     | -2dB    | Stable                     |
| **PREAMP/SP.SIM**        | ON       | ON      | Stable                     |
| Type                     | Ampeg    | Ampeg   | Couleur fixture            |
| Volume                   | 90       | 80      | -11% 10W                   |
| Bass                     | +25      | +25     | Stable                     |
| Middle                   | -5       | -5      | Stable                     |
| Treble                   | +5       | +5      | Stable                     |
| Master                   | 70       | 65      | -7% 10W                    |
| Gain                     | High     | High    | Stable                     |
| Dir Level                | 50       | 45      | -10% 10W                   |
| **NOISE SUPPRESSOR**     |          |         |                            |
| Threshold                | 70       | 70      | Stable                     |
| Release                  | 15       | 15      | Stable                     |
| **DELAY**                | OFF      | OFF     | Stable                     |
| **MOD**                  | OFF      | OFF     | Stable                     |
| **MASTER**               |          |         |                            |
| Master Level             | 80       | 75      | -6% 10W                    |
| Foot Level               | 100      | 100     | Stable                     |
| BPM                      | 120      | 120     | Stable                     |

**Signature sonore:** Transparent agressif. Préamp Ampeg = couleur vintage distincte. Clé technique.

### UA4: BREACH

- **Fonction:** Hardcore mélodique agressif (Raised Fist/Breach style)
- **Drive:** 15 (valeur originale, inchangée)
- **Key Settings:** Hi-mid EQ: +5dB (clé pour couper guitare), Sustain: 48
- ✅ **Note:** Présence mid préservée, Big Muff ajoute la couleur
- ⚙️ **Si manque de coupure guitare en live:** Hi-mid EQ +5dB → +6-7dB (signature de Breach) (cf. CORRECTION-LIVE-BASSKICK.txt)

| Paramètre                | Basskick | 10W     | Notes                  |
|--------------------------|----------|---------|------------------------|
| **COMPRESSOR**           |          |         |                        |
| Sustain                  | 48       | 48      | Stable, court          |
| Attack                   | 28       | 28      | Stable                 |
| ENH Freq                 | 0        | 0       | Stable                 |
| ENH Level                | 15       | 12      | -20% 10W               |
| Level                    | 92       | 88      | -4% 10W                |
| **OCTAVE**               |          |         |                        |
| Oct Level                | 5        | 3       | -40% 10W, minimal      |
| Dir Level                | 100      | 100     | Stable                 |
| **DISTORTION (Bass OD)** |          |         |                        |
| Type                     | Bass OD  | Bass OD | Stable                 |
| Drive                    | 15       | 12      | -20% 10W               |
| Bass                     | +6       | +6      | Stable                 |
| Treble                   | +6       | +6      | Stable                 |
| Fx Level                 | 25       | 25      | Stable                 |
| Dir Level                | 100      | 100     | Stable                 |
| **4BAND EQ**             |          |         |                        |
| Low EQ                   | +5dB     | +5dB    | Stable                 |
| High EQ                  | +6dB     | +6dB    | Stable                 |
| Level                    | +5dB     | +4dB    | -1dB 10W               |
| Low-mid EQ               | -3dB     | -3dB    | Stable                 |
| Hi-mid EQ                | +5dB     | +5dB    | ⭐ SIGNATURE (immuable) |
| **PREAMP**               | OFF      | OFF     | Stable                 |
| **NOISE SUPPRESSOR**     |          |         |                        |
| Threshold                | 75       | 75      | Stable                 |
| Release                  | 12       | 12      | Stable                 |
| **DELAY**                | OFF      | OFF     | Stable                 |
| **MOD**                  | OFF      | OFF     | Stable                 |
| **MASTER**               |          |         |                        |
| Master Level             | 88       | 82      | -7% 10W                |
| Foot Level               | 100      | 100     | Stable                 |
| BPM                      | 120      | 120     | Stable                 |

**Signature sonore:** Agressif mélodique. Hi-mid boostée = coupe guitare proprement. Raised Fist / Refused style.

### UA5: PUNCHYCORE

- **Fonction:** Switching rapide vers clean mélodique (post-hardcore)
- **Drive:** 6 (valeur originale, inchangée)
- **Key Settings:** Lo-mid EQ: +6dB (boost midrange = punch), Sustain: 55
- ✅ **Note:** Percussif du VF-1 + saturation textural Big Muff
- ⚙️ **Si manque de punch en live:** Lo-mid EQ +6dB → +7-8dB (signature de Punchycore) (cf. CORRECTION-LIVE-BASSKICK.txt)

| Paramètre                | Basskick | 10W     | Notes                  |
|--------------------------|----------|---------|------------------------|
| **COMPRESSOR**           |          |         |                        |
| Sustain                  | 55       | 55      | Stable, percussif      |
| Attack                   | 18       | 18      | Stable, rapide         |
| ENH Freq                 | 0        | 0       | Stable                 |
| ENH Level                | 5        | 4       | -20% 10W               |
| Level                    | 95       | 90      | -5% 10W                |
| **OCTAVE**               |          |         |                        |
| Oct Level                | 8        | 5       | -38% 10W, subtil       |
| Dir Level                | 100      | 100     | Stable                 |
| **DISTORTION (Bass OD)** |          |         |                        |
| Type                     | Bass OD  | Bass OD | Stable                 |
| Drive                    | 6        | 4       | -33% 10W, minimal      |
| Bass                     | 0        | 0       | Stable                 |
| Treble                   | +8       | +8      | Stable                 |
| Fx Level                 | 15       | 15      | Stable                 |
| Dir Level                | 100      | 100     | Stable                 |
| **4BAND EQ**             |          |         |                        |
| Low EQ                   | +4dB     | +3dB    | -1dB 10W               |
| High EQ                  | +4dB     | +3dB    | -1dB 10W               |
| Level                    | +8dB     | +7dB    | -1dB 10W               |
| Low-mid EQ               | +6dB     | +6dB    | ⭐ SIGNATURE (immuable) |
| Hi-mid EQ                | +3dB     | +3dB    | Stable                 |
| **PREAMP**               | OFF      | OFF     | Stable                 |
| **NOISE SUPPRESSOR**     |          |         |                        |
| Threshold                | 75       | 75      | Stable                 |
| Release                  | 12       | 12      | Stable                 |
| **DELAY**                | OFF      | OFF     | Stable                 |
| **MOD**                  | OFF      | OFF     | Stable                 |
| **MASTER**               |          |         |                        |
| Master Level             | 92       | 85      | -8% 10W                |
| Foot Level               | 100      | 100     | Stable                 |
| BPM                      | 120      | 120     | Stable                 |

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
