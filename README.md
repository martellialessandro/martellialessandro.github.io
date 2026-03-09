# Meridiano Capitale — Guida al sito

## Come pubblicare un nuovo articolo

1. Vai sulla cartella `_posts` su GitHub
2. Clicca **"Add file" → "Create new file"**
3. Nomina il file così: `ANNO-MESE-GIORNO-titolo-breve.md`
   - Esempio: `2026-03-15-fed-tassi-marzo.md`
4. Incolla questo template e compilalo:

```
---
layout: post
title: "Il titolo del tuo articolo"
date: 2026-03-15
category: Mercati
tags: [Fed, Tassi, USA]
reading_time: "5 min"
author: Alessandro Martelli
excerpt: "Un breve riassunto dell'articolo (1-2 righe)."
---

Testo dell'articolo qui.

## Titolo sezione

Altro testo...

> Citazione in evidenza

**Testo in grassetto** e *testo in corsivo*

- Punto elenco 1
- Punto elenco 2
```

5. Clicca **"Commit changes"** → online in 30 secondi!

## Categorie disponibili
- Mercati
- Geopolitica
- Macro
- Macro Italia

## Struttura file
- `_config.yml` → impostazioni generali del sito
- `_layouts/` → template delle pagine
- `_posts/` → tutti gli articoli
- `index.html` → homepage
- `consulenza.html` → pagina consulenza
- `archivio.html` → archivio articoli
