# 🚀 Guida per Configurare una Community Spettacolare su GitHub

> *"GitHub non è solo per il codice. È una piattaforma potente per costruire una community spettacolare."*

---

## 📋 Sommario

- [Attivare Funzionalità GitHub](#attivare-funzionalità-github)
- [Configurare GitHub Discussions](#configurare-github-discussions)
- [Configurare GitHub Projects](#configurare-github-projects)
- [Configurare GitHub Wiki](#configurare-github-wiki)
- [Configurare GitHub Actions](#configurare-github-actions)
- [Configurare GitHub Pages](#configurare-github-pages)
- [Configurare GitHub Sponsors](#configurare-github-sponsors)
- [Configurare GitHub Teams](#configurare-github-teams)

---

## ✅ Attivare Funzionalità GitHub

### 1. Vai alle Impostazioni del Repository

1. Vai al repository su GitHub
2. Clicca su "Settings" in alto a destra
3. Scorri alla sezione "Features"

### 2. Attiva le Funzionalità

Attiva le seguenti funzionalità:

- **Discussions**: Per forum e discussioni
- **Wiki**: Per documentazione collaborativa
- **Projects**: Per gestione progetti
- **Actions**: Per automazione
- **Pages**: Per sito web
- **Sponsors**: Per finanziamenti (se disponibile)

### 3. Salva le Modifiche

Clicca su "Save changes" per applicare le modifiche.

---

## 💬 Configurare GitHub Discussions

### Creare Categorie

1. Vai alla scheda "Discussions"
2. Clicca su "New discussion"
3. Clicca su "Categories"
4. Crea le seguenti categorie:

**Categorie Principali**:
- 🎮 **Sessioni di Gioco** - Condividi le tue sessioni
- 📝 **Proposte e Suggerimenti** - Suggerisci miglioramenti
- 🤔 **Domande e Aiuto** - Chiedi aiuto
- 🎨 **Creazioni della Community** - Mostra le tue creazioni
- 📚 **Strategie e Tattiche** - Discuti strategie

**Categorie Secondarie**:
- 🌍 **Traduzioni** - Discuti traduzioni
- 👨‍🏫 **Mentorship** - Programma di mentorship
- 🎪 **Eventi** - Annunci e discussioni eventi
- 📧 **Newsletter** - Discussi la newsletter

### Configurare Announcements

1. Vai a "Settings" → "Discussions"
2. Abilita "Announcements"
3. Imposta le regole per gli annunci
4. Designa maintainer e moderatori

### Pinnare Discussioni Importanti

Pinnare discussioni importanti:
- Regole della community
- Guide essenziali
- Annunci importanti
- Eventi in arrivo

---

## 📋 Configurare GitHub Projects

### Creare Progetto Principale

1. Vai alla scheda "Projects"
2. Clicca su "New project"
3. Scegli "Table" o "Board"
4. Nomina il progetto: "Shadowbound Community"

### Creare Colonne

Crea le seguenti colonne:

**Per Avventure**:
- 📝 Proposte
- ✅ In Revisione
- 🎨 In Sviluppo
- ✅ Approvate
- 📚 Pubblicate

**Per Bug**:
- 🐛 Nuovi
- 🔍 In Analisi
- 🔧 In Corso
- ✅ Risolti
- ❌ Non riproducibili

**Per Features**:
- 💡 Idee
- 📝 Specifiche
- 🔧 In Sviluppo
- ✅ Completate
- ❌ Rifiutate

### Configurare Automazioni

Usa GitHub Actions per automatizzare:

- Spostare card automaticamente
- Assegnare maintainer
- Notificare contributori
- Chiudere issue inattive

---

## 📖 Configurare GitHub Wiki

### Creare Struttura Wiki

1. Vai alla scheda "Wiki"
2. Clicca su "Create first page"
3. Crea la home page

### Pagine Principali

Crea le seguenti pagine:

**Per Giocatori**:
- [Home](#) - Pagina principale
- [Guida Rapida](#) - Guida per nuovi giocatori
- [Creare Personaggio](#) - Guida creazione personaggi
- [Giocare Online](#) - Come giocare online

**Per DM**:
- [Guida DM](#) - Guida per Dungeon Master
- [Creare Avventure](#) - Come creare avventure
- [Narrare](#) - Tecniche di narrazione
- [Gestione Gruppo](#) - Gestire un gruppo

**Per Contributori**:
- [Come Contribuire](#) - Guida per contributori
- [Linee Guida](#) - Linee guida
- [Processo](# - Processo di contribuzione
- [Badge](#) - Sistema di badge

### Organizzazione

Usa sidebar per organizzare le pagine:

```
Home
├── Giocatori
│   ├── Guida Rapida
│   ├── Creare Personaggio
│   └── Giocare Online
├── DM
│   ├── Guida DM
│   ├── Creare Avventure
│   ├── Narrare
│   └── Gestione Gruppo
└── Contributori
    ├── Come Contribuire
    ├── Linee Guida
    ├── Processo
    └── Badge
```

---

## ⚙️ Configurare GitHub Actions

### Workflow per Automazione

Crea i seguenti workflow in `.github/workflows/`:

#### 1. Auto-assign Issues

```yaml
name: Auto Assign Issues
on:
  issues:
    types: [opened]

jobs:
  auto-assign:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/github-script@v6
        with:
          script: |
            github.rest.issues.addAssignees({
              issue_number: context.issue.number,
              assignees: ['alisio85']
            })
```

#### 2. Label Issues Automaticamente

```yaml
name: Auto Label Issues
on:
  issues:
    types: [opened, edited]

jobs:
  auto-label:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/labeler@v4
        with:
          repo-token: ${{ secrets.GITHUB_TOKEN }}
```

#### 3. Close Stale Issues

```yaml
name: Close Stale Issues
on:
  schedule:
    - cron: "0 0 * * *"

jobs:
  stale:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/stale@v8
        with:
          repo-token: ${{ secrets.GITHUB_TOKEN }}
          stale-issue-message: 'Questa issue è inattiva da 30 giorni.'
          days-before-stale: 30
          days-before-close: 7
```

#### 4. Deploy to GitHub Pages

```yaml
name: Deploy to GitHub Pages
on:
  push:
    branches: [main]

jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./docs
```

---

## 🌐 Configurare GitHub Pages

### Attivare GitHub Pages

1. Vai a "Settings" → "Pages"
2. Seleziona "Source": Deploy from a branch
3. Seleziona "Branch": main
4. Seleziona "Folder": /docs
5. Clicca su "Save"

### Creare Sito Web

Il sito web sarà automaticamente generato dai file markdown in `/docs/`.

**URL**: `https://alisio85.github.io/shadowbound/`

### Personalizzare

Crea un file `_config.yml` nella root:

```yaml
title: Shadowbound
description: Regolamento Dark Fantasy Open Source
theme: minima
```

---

## 💰 Configurare GitHub Sponsors

### Attivare GitHub Sponsors

1. Vai a "Settings" → "Sponsors"
2. Clicca su "Enable GitHub Sponsors"
3. Configura i livelli di sponsorizzazione

### Livelli di Sponsorizzazione

**Tier 1: Supporter** ($5/mese)
- Nome nel sito
- Badge "Supporter"

**Tier 2: Contributor** ($20/mese)
- Nome nel sito
- Badge "Contributor"
- Accesso a canali esclusivi

**Tier 3: Champion** ($50/mese)
- Nome nel sito
- Badge "Champion"
- Accesso a canali esclusivi
- Voto su direzione del progetto

**Tier 4: Legend** ($100/mese)
- Nome nel sito
- Badge "Legend"
- Accesso a canali esclusivi
- Voto su direzione del progetto
- Consultazioni private

### Ricompense per Sponsor

- Badge speciali
- Accesso a contenuti esclusivi
- Voto su direzione del progetto
- Consultazioni private
- Riconoscimento nel README

---

## 👥 Configurare GitHub Teams

### Creare Teams

1. Vai a "Settings" → "Teams"
2. Clicca su "New team"
3. Crea i seguenti team:

**Team Maintainer**:
- **Nome**: Maintainers
- **Permessi**: Admin
- **Membri**: @alisio85

**Team Contributor**:
- **Nome**: Contributors
- **Permessi**: Write
- **Membri**: Tutti i contributori attivi

**Team Moderator**:
- **Nome**: Moderators
- **Permessi**: Triage
- **Membri**: Moderatori della community

### Assegnare Repository

Assegna il repository ai team:
- Maintainer: Accesso completo
- Contributor: Accesso scrittura
- Moderator: Accesso triage

---

## 🎨 Personalizzazione

### Repository Profile

Personalizza il repository:

1. **Descrizione**: Aggiungi una descrizione accattivante
2. **Topics**: Aggiungi topics rilevanti
   - `dnd`
   - `ttrpg`
   - `dark-fantasy`
   - `italian`
   - `open-source`
   - `community-driven`
3. **Pinned Issues**: Pinnare issue importanti
4. **Pinned Discussions**: Pinnare discussioni importanti

### README

Assicurati che il README sia:
- Ben formattato
- Con emoji per visibilità
- Con link a tutte le risorse
- Con badge di stato

### Social Media

Aggiungi link ai social media:
- Discord
- Twitter/X
- Facebook
- Instagram
- YouTube

---

## 📊 Metriche e Analytics

### GitHub Insights

Usa GitHub Insights per:

- Monitorare attività del repository
- Analizzare contributori
- Visualizzare statistiche
- Identificare tendenze

### External Analytics

Integra strumenti esterni:

- **Google Analytics**: Per GitHub Pages
- **Discord Analytics**: Per server Discord
- **Twitter Analytics**: Per account Twitter

---

## 🎯 Best Practices

### Engagement

- Rispondi prontamente alle issue e discussioni
- Ringrazia i contributori
- Condividi i successi
- Celebra i milestone

### Moderazione

- Segui il Code of Conduct
- Modera le discussioni
- Gestisci i conflitti
- Mantieni un ambiente positivo

### Qualità

- Mantieni alta qualità dei contenuti
- Revisiona i contributi
- Fornisci feedback
- Migliora continuamente

---

## 📚 Risorse Aggiuntive

### Documentazione GitHub

- [GitHub Discussions](https://docs.github.com/en/discussions)
- [GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects)
- [GitHub Wiki](https://docs.github.com/en/wiki)
- [GitHub Actions](https://docs.github.com/en/actions)
- [GitHub Pages](https://docs.github.com/en/pages)
- [GitHub Sponsors](https://docs.github.com/en/sponsors)

### Guide

- [Building Communities](https://docs.github.com/en/communities)
- [Moderating Discussions](https://docs.github.com/en/communities/moderation)
- [Managing Organizations](https://docs.github.com/en/organizations)

---

## ❓ Domande Frequenti

### D: Quanto tempo serve per configurare tutto?

R: Circa 1-2 ore per configurare tutte le funzionalità base.

### D: Posso configurare tutto da solo?

R: Sì, puoi configurare tutto dalle impostazioni del repository.

### D: Devo pagare per queste funzionalità?

R: No, tutte queste funzionalità sono gratuite per repository pubblici.

### D: Posso usare queste funzionalità per repository privati?

R: Alcune funzionalità sono limitate per repository privati. Controlla la documentazione di GitHub.

### D: Come faccio a gestire la community?

R: Usa le guide create in `docs/community/` per gestire la community.

---

## 🤝 Supporto

Se hai domande sulla configurazione:

- Consulta la documentazione di GitHub
- Apri una issue nel repository
- Contatta il supporto di GitHub

---

**Buona fortuna nel configurare la tua community spettacolare su GitHub!** 🚀

---

**Creato per Shadowbound - Regolamento Dark Fantasy Open Source**

*Basato su D&D 5.2.1 SRD, modificato da alisio85 e la Shadowbound community*
*Licenza: Creative Commons Attribution 4.0 International (CC-BY-4.0)*
