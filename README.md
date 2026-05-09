<h1 align="center">📱 APKNOWLEDGE</h1>

<p align="center">
  <strong>APK Batch Analysis & Forensic Pipeline</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/GUI-CustomTkinter-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Features-Scan%20|%20Decompile%20|%20Report-orange?style=flat-square" />
</p>

---

## 🧭 Features

- 🔍 System-wide APK Scan mit Include/Exclude
- 🔁 Duplikat-Erkennung und Batch-Selektion
- 🔬 Forensic Pipeline: Decompile (apktool), Code Harvest, Image Harvest
- 📊 Overview.md mit Permission-Klassifikation und Threat-Hinweisen

---

## ⚡ Quick Start

```bash
pip install -r requirements.txt
python apk_master.py
```

---

## 📁 Output pro APK

```
MY_APP_LIBRARY/<pkg>_v<ver>/
├── COMPARE_IMAGES/   # Semantisch gruppierte Bilder
├── _CODE/            # Core App Smali
├── _SDK/             # Third-Party SDK
├── _THREATS/         # Threat-Matches
└── Overview.md       # Permission + Netzwerk + Threats
```

---

## 🚪 Gates

Siehe [`GATES.md`](GATES.md).

---

## 🔗 Relevante Projekte

| Projekt | Relevanz |
|---------|----------|
| [OutrageousStorm/android-forensics-guide](https://github.com/OutrageousStorm/android-forensics-guide) | Android Forensics Guide |
| [androguard/androguard](https://github.com/androguard/androguard) | APK Analyse Library |
| [ibotpeaches/Apktool](https://github.com/iBotPeaches/Apktool) | APK Reverse Engineering |

---

<p align="center"><em>Scan. Decompile. Understand. Report.</em></p>
