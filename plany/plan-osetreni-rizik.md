# Plán ošetření rizik (Risk Treatment Plan)
<!-- # plany/plan-osetreni-rizik.md -->

**Organizace:** eKultura, z. s.  
**Verze:** 1.0  
**Datum vytvoření:** 2025-04-18  
**Norma:** ISO/IEC 27001:2022 – kapitola 6, příloha A

---

## 1. Účel dokumentu

Cílem plánu ošetření rizik je popsat způsob, jakým eKultura, z. s. reaguje na identifikovaná bezpečnostní rizika, a definovat odpovědnosti, opatření a termíny k jejich řízenému snižování nebo eliminaci.

---

## 2. Proces řízení rizik

1. **Identifikace rizik** – na základě aktiv, hrozeb a zranitelností.
2. **Vyhodnocení rizik** – pomocí metody pravděpodobnost × dopad.
3. **Ošetření rizik** – výběr vhodné strategie:  
   - přijetí (akceptace)
   - zmírnění (snížení)
   - přenos (např. pojištění)
   - eliminace (zrušení činnosti)
4. **Realizace opatření** – zavedení technických a organizačních kontrol.
5. **Monitorování** – sledování účinnosti opatření a opakované vyhodnocení.

---

## 3. Odpovědnosti

- **Předseda spolku** – schválení plánu a přidělení zdrojů.
- **Odpovědná osoba ISMS** – koordinace a implementace opatření.
- **Správci systémů** – provedení technických opatření.
- **Auditor** – ověření účinnosti přijatých kontrol.

---

## 4. Seznam doporučených opatření

| ID | Riziko | Dopad | Pravděpodobnost | Úroveň | Opatření | Typ kontroly | Stav | Termín |
|----|--------|-------|-----------------|--------|----------|---------------|------|--------|
| R-001 | Slabá hesla na sdílených účtech | Vysoký | Střední | Vysoká | Zavedení správce hesel a 2FA | Technické | Aktivní | 2025-05-01 |
| R-002 | Nezálohovaná data na VPS | Vysoký | Nízká | Střední | Automatizované zálohy + test obnovy | Technické / Procesní | Implementováno | 2025-04-01 |
| R-003 | Únik osobních údajů z formulářů | Vysoký | Nízká | Střední | Šifrování + kontrola přístupů | Organizační | Plánováno | 2025-05-10 |
| R-004 | Nejasná odpovědnost za incidenty | Střední | Střední | Střední | Zavedení incident response plánu | Procesní | Probíhá | 2025-06-01 |

> ⚠️ Plný seznam rizik a jejich hodnocení je veden interně: `interni/analyza-rizik.xlsx`

---

## 5. Sledování a aktualizace

- Tento plán je aktualizován po každém zásadním incidentu nebo min. **1× ročně**.
- Stav opatření je pravidelně sledován zodpovědnou osobou ISMS.
- Vyhodnocení účinnosti opatření je součástí **interního auditu**.

---

*Schválil:* Předseda eKultura, z. s.  
*Datum schválení:* 2025-04-18
