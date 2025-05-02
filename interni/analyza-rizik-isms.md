# Analýza rizik ISMS (vzor)
<!--# interni/analyza-rizik-isms.md-->

**Organizace:** [eKultura, z. s.](https://ekultura.eu)  
**Verze:** 1.0  
**Norma:** ISO/IEC 27001:2022  
**Datum:** 2025-04-18  

---

> ⚠️ **Upozornění:**  
> Tento dokument slouží jako **interní vzor** analýzy rizik informační bezpečnosti (ISMS).  
> Plná verze s konkrétními hodnotami, zranitelnostmi a opatřeními je uložena na zabezpečeném interním úložišti eKultura, z. s.  
> Tento soubor je pouze ukázkový.

---

## 1. Účel analýzy rizik

Cílem analýzy rizik je identifikovat, vyhodnotit a řídit hrozby, které mohou ovlivnit důvěrnost, integritu a dostupnost informací a systémů [organizace eKultura, z. s.](https://ekultura.eu)

---

## 2. Metodika

Použitá metodika:
- Identifikace aktiv
- Identifikace hrozeb a zranitelností
- Hodnocení dopadu a pravděpodobnosti
- Stanovení úrovně rizika
- Návrh opatření ke snížení rizika

Rizika jsou hodnocena na škále Nízké / Střední / Vysoké.

---

## 3. Identifikace rizik (příklad)

| Aktivum | Hrozba | Zranitelnost | Dopad | Pravděpodobnost | Úroveň rizika | Opatření |
|---------|--------|--------------|-------|-----------------|---------------|----------|
| VPS server DIV.cz | Útok DDoS | Nedostatečné ochrany na síti | Vysoký | Střední | Vysoké | Firewall, monitoring |
| Nextcloud úložiště | Ztráta dat | Chyba zálohování | Vysoký | Nízká | Střední | Automatické zálohování |
| GitHub repozitář | Neoprávněný přístup | Slabé heslo | Vysoký | Nízká | Střední | 2FA, audit práv |
| Účet Google Workspace | Phishing útok | Nedostatečné školení uživatelů | Střední | Střední | Střední | Školení bezpečnosti |

---

## 4. Opatření ke snížení rizik

- Zavedení vícefaktorového ověřování (2FA)
- Pravidelné testování obnovy záloh
- Nastavení ochrany proti DDoS útokům
- Školení uživatelů na phishing a bezpečnost hesel

---

## 5. Závěr

Analýza rizik je pravidelně revidována alespoň 1× ročně nebo při významných změnách infrastruktury.

Úplný dokument včetně vyhodnocení všech aktiv a plánů ošetření rizik je dostupný pouze interně.

---

*Schválil:* Předseda eKultura, z. s.  
*Datum schválení:* 2025-04-18
