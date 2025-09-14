# MonuGuide — Support & Legal Hub

Sito di supporto ufficiale per **MonuGuide (iOS)** pubblicato con **GitHub Pages**.  
Qui trovi contatti/assistenza, Informativa Privacy e Termini di Servizio.

- 🌐 **Sito live:** https://nicobulich.github.io/monuguide-support/
- 📮 **Supporto / Contatti:** https://nicobulich.github.io/monuguide-support/contact
- 🔐 **Privacy Policy:** https://nicobulich.github.io/monuguide-support/privacy
- 📜 **Termini di Servizio:** https://nicobulich.github.io/monuguide-support/terms

> Questo repository contiene solo le pagine di supporto/legali.  
> Il codice dell’app iOS non è incluso qui.

---

## Contenuti del repository

| File/Cartella  | Descrizione |
| --- | --- |
| `index.md`   | Home del centro assistenza (link a contatti, privacy, termini). |
| `contact.md` | Pagina contatti/assistenza (email, modulo/istruzioni). |
| `privacy.md` | Informativa sulla privacy. |
| `terms.md`   | Termini di Servizio. |
| `README.md`  | Questo file. |

Tutte le pagine sono scritte in **Markdown** e pubblicate automaticamente da GitHub Pages.

---

## Pubblicazione (GitHub Pages)

- **Branch:** `main`  
- **Cartella:** root (`/`)  
- Ogni commit su `main` attiva un nuovo deploy (1–2 minuti).  
- Impostazioni: **Repository → Settings → Pages**.

Se dopo un commit non vedi gli aggiornamenti:
1. Attendi 1–2 minuti.
2. Fai hard refresh del browser (⌘⇧R / Ctrl+F5).
3. Controlla **Actions** per eventuali errori di build.

---

## Come modificare i contenuti

1. Apri il file che vuoi aggiornare (`index.md`, `privacy.md`, ecc.).
2. Clicca **Edit**, modifica in Markdown.
3. **Commit changes** su `main` (o apri una PR se preferisci).
4. Verifica online dopo il deploy.

> Puoi aggiungere un titolo SEO per ogni pagina con front-matter:
> ```markdown
> ---
> title: Privacy Policy — MonuGuide
> ---
> ```

---

## Link da usare su App Store Connect

- **URL assistenza (Support URL):**  
  `https://nicobulich.github.io/monuguide-support/contact`
- **Privacy Policy URL:**  
  `https://nicobulich.github.io/monuguide-support/privacy`
- **Termini di Servizio (facoltativo in App Store):**  
  `https://nicobulich.github.io/monuguide-support/terms`

---

## 404 personalizzata (opzionale)

Per una pagina 404 più pulita, aggiungi `404.md`:

```markdown
---
permalink: /404.html
title: Pagina non trovata
---
# 404 — Pagina non trovata
Torna alla [home del supporto](./).
