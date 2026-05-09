# 🚪 GATES — APKNOWLEDGE

---

## 🔜 Nächste Gates

### Gate AK-011: Malware Signature DB
- **Branch:** `gate/ak-011-malware-db`
- **To-Dos:**
  - [ ] YAML-basierte Signatur-Datenbank
  - [ ] Auto-Update-Mechanismus
  - [ ] Severity-Levels pro Signatur
  - [ ] Custom-Signatur-Support
- **Akzeptanz:** DB mit ≥50 Signaturen
- **Kill:** Hardcoded Signaturen

### Gate AK-012: Comparison Engine
- **Branch:** `gate/ak-012-comparison`
- **To-Dos:**
  - [ ] APK-Version-Diff (was hat sich geändert?)
  - [ ] Permission-Diff zwischen Versionen
  - [ ] Neuer Code-/SDK-Detection
  - [ ] Visual Diff der Image-Assets
- **Akzeptanz:** Diff zwischen 2 APK-Versionen
- **Kill:** Diff ohne visuelle Darstellung

### Gate AK-013: Batch Report Generator
- **Branch:** `gate/ak-013-batch-report`
- **To-Dos:**
  - [ ] HTML-Report für alle analysierten APKs
  - [ ] Risk-Score pro APK
  - [ ] Aggregierte Permission-Matrix
  - [ ] PDF-Export
- **Akzeptanz:** Report mit allen APKs + Risk-Score
- **Kill:** Report ohne Scoring

### Gate AK-014: Network Analysis
- **Branch:** `gate/ak-014-network`
- **To-Dos:**
  - [ ] Domain-Extraktion aus Code
  - [ ] Tracker-Erkennung (Exodus-kompatibel)
  - [ ] IP-Geolocation (offline-DB)
  - [ ] Network-Report pro APK
- **Akzeptanz:** Tracker-Liste + Domains
- **Kill:** Online-Dependency für Tracker-DB
