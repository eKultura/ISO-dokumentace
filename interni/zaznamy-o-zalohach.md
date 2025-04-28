# interni/zaznamy-o-zalohach.md

# Záznamy o zálohách (vzor)

**Organizace:** eKultura, z. s.  
**Verze:** 1.0  
**Datum:** 2025-04-18  
**Norma:** ISO/IEC 27001:2022  

---

> ⚠️ **Upozornění:**  
> Tento dokument slouží jako **interní vzor** evidence zálohovacích aktivit organizace eKultura, z. s.  
> Plné záznamy včetně přesných umístění, přístupových údajů a časových razítek jsou uloženy na zabezpečeném interním úložišti. Tento soubor slouží pouze k ilustraci postupu.

---

## 1. Účel záznamu

Evidovat pravidelné zálohovací operace důležitých systémů a datových úložišť s cílem zajistit kontinuitu provozu a obnovu dat v případě incidentu.

---

## 2. Přehled zálohovaných systémů

| Název systému | Typ zálohy | Frekvence | Umístění zálohy | Odpovědná osoba |
|---------------|------------|-----------|-----------------|-----------------|
| VPS server DIV.cz | Snapshot + soubory | Denně | VPS Backup Storage | Administrátor |
| Nextcloud (interní dokumenty) | Plná záloha | Denně | Offsite disk | Administrátor |
| GitHub repozitáře | Replikace + export | Týdně | GitHub + lokální storage | Dokumentační tým |
| Účet Google Workspace | Export dat | Měsíčně | Interní disk | Dokumentační tým |

---

## 3. Postup provádění záloh

- **Automatizované zálohy:** Nastavené cron skripty na VPS serverech a v aplikacích.
- **Manuální kontroly:** Kontrola integrity záloh 1× týdně.
- **Offsite kopie:** Kritické zálohy jsou ukládány mimo primární servery.
- **Retence záloh:** Uchovávání dat po dobu minimálně 90 dnů.

---

## 4. Revize a testování obnovy

- Test obnovy dat probíhá 2× ročně.
- Výsledky testování jsou zaznamenány v rámci interního auditu.

---

*Schválil:* Předseda eKultura, z. s.  
*Datum schválení:* 2025-04-18
