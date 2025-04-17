# Plán kontinuity provozu (BCP)

**Organizace:** eKultura, z. s.  
**Verze:** 1.0  
**Platnost od:** 2025-04-17  

---

## 1. Účel

Tento dokument popisuje plán pro zachování a rychlé obnovení klíčových činností eKultura, z. s. v případě výpadku, havárie nebo jiné mimořádné události.

---

## 2. Kritické oblasti

| Oblast | Kritičnost | Poznámka |
|--------|------------|----------|
| Webové platformy (DIV.cz, digitální muzea) | Vysoká | Přístup veřejnosti |
| Datové úložiště (Nextcloud, VPS zálohy) | Vysoká | Obsahuje hlavní obsah |
| ERP, GitHub, pracovní nástroje | Střední | Interní provoz organizace |
| Komunikace (emaily, Meet) | Střední | Koordinace týmů |

---

## 3. Plán obnovy

- Všechny servery jsou pravidelně zálohovány (denně, offsite).
- V případě havárie serveru bude použit nejnovější záložní snapshot z cloudu.
- Výměna nebo přesun služby na jiný VPS do 12 hodin.

---

## 4. Zodpovědnosti

| Role | Odpovědnost |
|------|-------------|
| Admin (server) | Obnova služeb VPS |
| Dokumentační tým | Obnova Google Drive a sdílených složek |
| Koordinátor projektů | Informování veřejnosti, plán krizové komunikace |

---

## 5. Testování a přezkum

- BCP se přezkoumává 1× ročně.
- Test obnovy dat se provádí minimálně 1× za 12 měsíců.

---

*Schválil:* Předseda eKultura, z. s.  
*Datum schválení:* 2025-04-17
