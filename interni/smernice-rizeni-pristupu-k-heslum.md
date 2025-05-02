# Směrnice řízení přístupů k heslům (vzor)
<!-- # interni/smernice-rizeni-pristupu-k-heslum.md -->

**Organizace:** eKultura, z. s.  
**Verze:** 1.0  
**Datum:** 2025-05-02  
**Norma:** ISO/IEC 27001:2022 – A.5.15, A.5.16, A.5.17

---

> ⚠️ Tento dokument slouží jako rámec. Plné záznamy a hesla jsou uloženy na interním úložišti.

---

## 1. Účel

Zajistit bezpečné nakládání s přihlašovacími údaji a řízení přístupu k digitálním účtům, serverům a dalším systémům.

---

## 2. Obecné zásady

- Hesla nejsou nikdy ukládána v otevřeném textu v běžných dokumentech.
- Všichni správci účtů používají dvoufázové ověření, kde je to možné.
- Hesla jsou sdílena pouze mezi oprávněnými osobami, ideálně prostřednictvím správce hesel (Bitwarden, KeepassXC apod.).

---

## 3. Ukládání a správa hesel

| Typ účtu | Nástroj pro správu | Přístup mají |
|----------|--------------------|---------------|
| E-mailové schránky (např. kontakt@) | Bitwarden cloud / šifrovaný soubor | předseda, odpovědná osoba |
| Servery (VPS, SSH) | Bitwarden / KeepassXC | admin tým |
| Externí služby (GitHub, FIO, Google) | správce hesel + 2FA | správce systému / účetnictví |

---

## 4. Obměna a revize

- Hesla se mění alespoň 1× ročně nebo po změně personálu.
- Přístupová práva se kontrolují při každé změně rolí.
- Po ukončení spolupráce se přístupy ruší nebo mění bez odkladu.

---

## 5. Uložení reálných údajů

> Veškerá skutečná hesla, klíče a přihlašovací údaje jsou uložena na šifrovaném a zálohovaném interním úložišti. Přístup je řízen podle rolí.

---

*Schválil:* Předseda eKultura, z. s.  
*Datum schválení:* 2025-04-18
