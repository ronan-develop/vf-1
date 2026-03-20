# VF-1 Setup - Days Spent Band Configuration

## Overview

**Setup Final:** VF-1 + Big Muff Electro Harmonix 9V

**Band Context:** Raised Fist / Breach / Refused (hardcore mélodique)  
**Bassiste:** Ronan (jeu au médium/pick)  
**Bass:** Ibanez SR 905 (5 cordes, tuning B-D-A-D-G)

---

## 🔌 1. Setup Physique

### Signal Chain

```
Ibanez SR 905 (5 cordes, tuning B-D-A-D-G)
    ↓
Big Muff Electro Harmonix USA 9V (INPUT → EFFECT OUT)
    ↓
Boss VF-1 tête d'ampli (instrument IN L/MONO, level -20dB)
    ↓
H&K Basskick 515 4Ω + Cabinet 300W 8Ω en série
```

### Pedalboard

- **Roland FC-200** (connecté en MIDI IN au VF-1)

---

## ⚙️ 2. Réglages Big Muff (FIXES - "Set & Forget")

| Paramètre | Réglage | Notes |
|-----------|---------|-------|
| **Tone Potentiometer** | 13-14h | Brillant/clair, laisse passer les HF |
| **Sustain Potentiometer** | 22-23h | MAXIMUM saturation |
| **Switch Position** | NORM | Mode standard (pas Turbo), grain contrôlé |

✅ **CES RÉGLAGES NE CHANGENT JAMAIS** (brancher et oublier)

---

## 🎛️ 3. Presets VF-1 - Versions Adaptées "MUFF"

Le Big Muff fournit ~50% de la saturation, donc les Drive VF-1 sont réduits pour éviter la double saturation.

### PRESET 1: BEATDOWN-MUFF

- **Fonction:** Heavy breakdown, lourd et massif (contexte hardcore)
- **Drive:** 20 (réduit de 50 dans l'original)
- **Key Settings:** Oct Level: 90, Sustain compresseur: 40
- ✅ **Validation:** Drive adapté pour Big Muff saturation max

### PRESET 2: DARKGLASS-MUFF

- **Fonction:** Transparent technique, agressif mais clair (Darkglass-like)
- **Drive:** 10 (réduit de 18 dans l'original)
- **Key Settings:** Preamp/SP.SIM: ON (Ampeg coloration), Sustain 65
- ✅ **Validation:** Preamp + Big Muff + Drive réduit = grain transparent

### PRESET 3: BREACH-MUFF

- **Fonction:** Hardcore mélodique agressif (Raised Fist/Breach style)
- **Drive:** 8 (réduit de 15 dans l'original)
- **Key Settings:** Hi-mid EQ: +5dB (clé pour couper guitare), Sustain: 48
- ✅ **Validation:** Drive réduit + Hi-mid préservé = clarté mid aggressive

### PRESET 4: PUNCHYCORE-MUFF

- **Fonction:** Switching rapide vers clean mélodique (post-hardcore)
- **Drive:** 1 (réduit de 6 dans l'original)
- **Key Settings:** Lo-mid EQ: +6dB (boost midrange = punch), Sustain: 55
- ✅ **Validation:** Drive quasi-zéro + Big Muff texture = ultra percussif

### PRESET 5: DANGLE-MUFF

- **Fonction:** Groovy/subtle clean (brillance, chorus léger)
- **Drive:** 0 (réduit de 2 dans l'original)
- **Key Settings:** Chorus: ON (Mode Mono, Rate 10, Depth 30), Sustain: 60
- ✅ **Validation:** Drive 0 + Big Muff = clair brillant, Chorus pour espacer

---

## 📊 4. Résumé des Réductions Drive

| Preset | Original Drive | Muff Drive | Réduction | Raison |
|--------|---|---|---|---|
| **Beatdown** | 50 | 20 | -60% | Big Muff lourdeur |
| **darkglass** | 18 | 10 | -44% | Big Muff saturation |
| **Breach** | 15 | 8 | -47% | Big Muff gras |
| **Punchycore** | 6 | 1 | -83% | Big Muff couleur |
| **Dangle** | 2 | 0 | -100% | Big Muff brillance |

✅ **Réductions proportionnées à l'agressivité originale**

---

## 🎮 5. Workflow Live

```
Début de song → FC-200 switche preset (ex: Beatdown-Muff)
    ↓
Big Muff déjà ON (réglages fixes 13-14h tone, 22-23h sustain)
    ↓
VF-1 charge preset adapté
    ↓
Drive réduit + Big Muff = son final cohérent
    ↓
Pas de manipulation à l'oreille, pas de footswitch supplémentaire
```

✅ **BASSISTE-FRIENDLY:** Un seul footswitch (FC-200 pour presets)

---

## 📝 6. Notes pour l'Ingénieur Son

### Configuration testée pour

- ✓ Hardcore mélodique (Raised Fist/Breach/Refused style)
- ✓ Jeu au médium/pick (attaque percussive)
- ✓ Tuning: Ibanez SR 905 en B standard
- ✓ Amplification: H&K Basskick 515 (transparence haute fidélité)

### Paramètres critiques immuables

- **Big Muff Tone:** 13-14h (NE PAS CHANGER)
- **Big Muff Sustain:** 22-23h (NE PAS CHANGER)
- **Big Muff Switch:** NORM (NE PAS CHANGER)

### Flexibilité d'ajustement possible

- Drive chaque preset ±2-3 points selon salle (test en live)
- Hi-mid EQ (Breach/Breach-Muff) ±2dB si trop/peu de présence
- Noise Suppressor Threshold selon niveau amplification

---

## ✅ 7. Checklist Préchargement

- [ ] Big Muff branché INPUT → EFFECT OUT
- [ ] Big Muff réglages: Tone 13-14h, Sustain 22-23h, NORM
- [ ] VF-1 Level input: -20dB (Ibanez passive)
- [ ] VF-1 OUTPUT L → H&K Basskick INPUT
- [ ] FC-200 MIDI IN connecté au VF-1
- [ ] 5 presets -Muff chargés en mémoire VF-1
- [ ] FC-200 programmé pour switcher entre presets -Muff
- [ ] Tous cables audio jack testés (pas de buzz/hum)

---

## 📁 Fichiers du Repo

### Presets (versions Big Muff adapter)

- `Beatdown-Muff.txt` - Heavy breakdown
- `darkglass-Muff.txt` - Transparent technique
- `Breach-Muff.txt` - Hardcore agressif
- `Punchycore-Muff.txt` - Clean mélodique
- `Dangle-Muff.txt` - Groovy subtle clean

### Presets Originaux (sans Big Muff)

- `Beatdown.txt`
- `darkglass.txt`
- `Breach.txt`
- `Punchycore.txt`
- `Dangle.txt`

### Documentation Technique

- `TRANSPOSITION-GUIDE.txt` - Guide général transposition sans reaccordage
- `ANTHEMS-TRANSPOSITION.txt` - Solution spécifique pour "Anthems" (C key)
- `KEY-TRANSPOSITION.txt` - Configuration VF-1 KEY parameter

---

## 🎵 Band Context

**Band Name:** Days Spent  
**Style:** Raised Fist / Breach / Refused (hardcore mélodique / math-rock)  
**Bass Role:** Percussif, définition, attaque courte, sustain contrôlé

---

*Setup finalisé et prêt pour présentation technique*
