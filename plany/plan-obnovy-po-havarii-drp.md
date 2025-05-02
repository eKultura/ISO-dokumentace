# Plán obnovy po havárii (Disaster Recovery Plan – DRP)
<!-- # plany/plan-obnovy-po-havarii-drp.md -->

**Organizace:** [eKultura, z. s.](https://ekultura.eu)    
**Verze:** 1.1  
**Norma:** ISO 27001  
**Platnost od:** 2025-04-18  

---

## 1. Účel

Tento plán stanovuje kroky k obnovení činnosti organizace eKultura, z. s. po technické havárii, výpadku nebo kybernetickém incidentu, který ovlivní dostupnost služeb.

---

## 2. Rozsah

Plán se vztahuje na:
- VPS servery provozující veřejné projekty 
- Datová úložiště a zálohovací systémy
- Pracovní systémy jako GitHub, Nextcloud, Google Workspace

---

## 3. Kritické systémy

| Systém | Kritičnost | Max. doba obnovení |
|--------|------------|---------------------|
| DIV.cz (produkce) | Vysoká | 24 hod |
| Datový disk (Nextcloud) | Vysoká | 24 hod |
| GitHub repozitáře | Střední | 48 hod |
| Google Workspace | Střední | 48 hod |

---

## 4. Zodpovědnosti

| Role | Úkol |
|------|------|
| Admin | Obnovení VPS a databází ze záloh |
| Dokumentační tým | Obnova sdílené dokumentace |
| Předseda | Koordinace krizové komunikace |

---

## 5. Obnova ze záloh

- Zálohy se vytvářejí automaticky 1× denně.
- Snapshoty jsou uchovávány offsite (jiné úložiště VPS).
- Obnova probíhá pomocí připravených skriptů (`restore.sh`).

---

## 6. Testování a revize

Plán je přezkoumáván a testován minimálně 1× ročně. Výsledky testu jsou evidovány v auditní dokumentaci.

---

*Schválil:* Předseda eKultura, z. s.  
*Datum schválení:* 2025-04-18
