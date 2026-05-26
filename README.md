# AI pro komunální politiku — SLP 2026

Interaktivní kurz pro volební tým **Starostové pro Liberec** (koalice s TOP 09 a KDU-ČSL).  
Připraveno pro AI workshop před komunálními volbami 2026.

🔗 **Live:** [slp-ai-workshop.github.io](https://slp-ai-workshop.github.io) *(doplň URL po nasazení)*

---

## Co kurz obsahuje

| Sekce | Obsah | Čas |
|---|---|---|
| 📖 Jak promptovat | 3 lekce + 3 praktická cvičení pro začátečníky | 15 min |
| ⚡ 10 promptů | Knihovna šablon pro kampaň, zastupitelstvo, program a krizovku | ihned použít |
| 📋 Dotazník | Předworkshopový průzkum znalostí, výsledky na e-mail | 2 min |

## Použité technologie

- Čistý HTML + CSS + JavaScript — žádný framework, žádné závislosti
- Google Fonts (Syne + DM Sans)
- [Formspree](https://formspree.io) pro odesílání dotazníku e-mailem
- Hostování: GitHub Pages

## Nasazení

```bash
# 1. Klonuj repozitář
git clone https://github.com/tvuj-username/slp-ai-workshop.git

# 2. Uprav Formspree endpoint v index.html (řádek ~530)
const FORMSPREE = 'https://formspree.io/f/TVUJ_KOD';

# 3. Pushn na GitHub — Pages se nasadí automaticky
git add .
git commit -m "deploy"
git push
```

GitHub Pages nastavení: **Settings → Pages → Deploy from branch → main → / (root)**

## Struktura souboru

```
index.html        # Celý kurz v jednom souboru
README.md         # Tento soubor
```

## Úpravy před sdílením

- **Datum workshopu** — hledej `Červen 2026`, nahraď konkrétním datem (3 výskyty)
- **Formspree ID** — nahraď `VLOZ_SEM_ID` kódem z formspree.io
- **E-mail** — v patičce je `j_podsednik@icloud.com`, uprav dle potřeby

## Kontakt

Jakub Podšedník · [j_podsednik@icloud.com](mailto:j_podsednik@icloud.com)  
Starostové pro Liberec · [starostoveproliberec.cz](https://www.starostoveproliberec.cz)

---

*Materiály jsou interní — připraveno pro tým SLP 2026*
