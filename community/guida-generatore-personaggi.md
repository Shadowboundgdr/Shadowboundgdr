# 🎲 Guida per il Generatore di Personaggi Online

> *"Il generatore di personaggi online rende facile creare personaggi per Shadowbound. Scopri come usarlo e contribuire al suo sviluppo."*

---

## 📋 Sommario

- [Cos'è il Generatore](#cosè-il-generatore)
- [Come Usarlo](#come-usarlo)
- [Funzionalità](#funzionalità)
- [Architettura Tecnica](#architettura-tecnica)
- [Come Contribuire](#come-contribuire)
- [Roadmap](#roadmap)

---

## 🌟 Cos'è il Generatore

Il Generatore di Personaggi Online di Shadowbound è un'applicazione web che permette di:

- **Creare personaggi** in modo rapido e semplice
- **Calcolare automaticamente** statistiche e valori derivati
- **Esportare** personaggi in vari formati (PDF, JSON, Markdown)
- **Condividere** personaggi con la community
- **Personalizzare** con opzioni avanzate

### Piattaforma

- **Tecnologia**: React + Node.js
- **Hosting**: GitHub Pages (coming soon)
- **Accesso**: Gratuito e open source
- **Licenza**: CC-BY-4.0

---

## 🚀 Come Usarlo

### Accesso

Per accedere al generatore:

1. Vai su [shadowbound-character-generator.netlify.app](https://shadowbound-character-generator.netlify.app) (coming soon)
2. Oppure clona il repository locale: `git clone https://github.com/alisio85/shadowbound-generator.git`

### Creazione Personaggio

**Passo 1: Scegli Razza**
- Seleziona la razza dal menu
- Scegli la sottorazza (se disponibile)
- Vedi i bonus agli attributi automaticamente applicati

**Passo 2: Scegli Classe**
- Seleziona la classe dal menu
- Scegli la sottoclasse (se disponibile)
- Vedi le abilità della classe

**Passo 3: Assegna Attributi**
- Usa il metodo preferito (Standard, Point Buy, Manuale)
- Assegna punti agli attributi
- Vedi i modificatori calcolati automaticamente

**Passo 4: Scegli Background**
- Seleziona il background dal menu
- Vedi le competenze e equipaggiamento

**Passo 5: Personalizza**
- Aggiungi nome e descrizione
- Scegli allineamento
- Aggiungi backstory
- Personalizza equipaggiamento

**Passo 6: Esporta**
- Esporta in PDF
- Esporta in JSON
- Esporta in Markdown
- Condividi con la community

---

## ⚙️ Funzionalità

### Funzionalità Base

- **Selezione Razza**: Tutte le razze di Shadowbound
- **Selezione Classe**: Tutte le classi di Shadowbound
- **Calcolo Attributi**: Automatico e manuale
- **Valori Derivati**: PF, AC, PM, PO calcolati automaticamente
- **Background**: Tutti i background standard
- **Equipaggiamento**: Equipaggiamento standard per classe

### Funzionalità Avanzate

- **Point Buy**: Sistema point buy per attributi
- **Multiclasse**: Supporto per multiclasse
- **Sottoclassi**: Tutte le sottoclassi disponibili
- **Artefatti**: Aggiunta di artefatti magici
- **Customizzazione**: Nome, descrizione, backstory
- **Esportazione Multipla**: PDF, JSON, Markdown

### Funzionalità Future

- **Integrazione Community**: Condividi personaggi direttamente
- **Build Salva**: Salva build per riutilizzo
- **Build Pubbliche**: Condividi build con la community
- **Integrazione VTT**: Esporta per Roll20, Foundry
- **API**: API per integrazioni di terze parti

---

## 🏗️ Architettura Tecnica

### Frontend

**Tecnologie**:
- React 18
- TypeScript
- TailwindCSS
- React Router

**Componenti**:
- `CharacterForm`: Form principale per creare personaggi
- `RaceSelector`: Selettore razza
- `ClassSelector`: Selettore classe
- `AttributeAssigner`: Assegnazione attributi
- `BackgroundSelector`: Selettore background
- `CharacterPreview`: Anteprima del personaggio
- `ExportOptions`: Opzioni di esportazione

### Backend

**Tecnologie**:
- Node.js
- Express
- MongoDB (per salvataggio build)

**API Endpoints**:
- `GET /api/races`: Lista delle razze
- `GET /api/classes`: Lista delle classi
- `GET /api/backgrounds`: Lista dei background
- `POST /api/characters`: Salva personaggio
- `GET /api/characters/:id`: Ottieni personaggio
- `GET /api/builds`: Lista build pubbliche

### Database

**Schema Personaggio**:
```json
{
  "id": "string",
  "name": "string",
  "race": "string",
  "subrace": "string",
  "class": "string",
  "subclass": "string",
  "attributes": {
    "strength": number,
    "dexterity": number,
    "constitution": number,
    "intelligence": number,
    "wisdom": number,
    "charisma": number
  },
  "background": "string",
  "alignment": "string",
  "backstory": "string",
  "equipment": ["string"],
  "createdAt": "date",
  "updatedAt": "date"
}
```

---

## 🤝 Come Contribuire

### Setup Sviluppo

1. **Clone il repository**:
```bash
git clone https://github.com/alisio85/shadowbound-generator.git
cd shadowbound-generator
```

2. **Installa dipendenze**:
```bash
npm install
```

3. **Avvia il server di sviluppo**:
```bash
npm run dev
```

4. **Apri il browser**:
```
http://localhost:3000
```

### Contributi

**Bug Fix**:
1. Trova il bug
2. Crea un branch: `git checkout -b fix/nome-bug`
3. Correggi il bug
4. Testa le correzioni
5. Apri una PR

**Nuova Funzionalità**:
1. Discuti la funzionalità nelle Issues
2. Crea un branch: `git checkout -b feature/nome-funzionalità`
3. Implementa la funzionalità
4. Aggiungi test
5. Apri una PR

**Traduzione**:
1. Traduci i file di localizzazione
2. Aggiungi la nuova lingua
3. Testa la traduzione
4. Apri una PR

### Linee Guida

- **Codice**: Segui le convenzioni di codice di React
- **Commit**: Usa messaggi di commit chiari
- **PR**: Descrivi le modifiche nella PR
- **Test**: Aggiungi test per nuove funzionalità
- **Documentazione**: Aggiorna la documentazione

---

## 🗺️ Roadmap

### Fase 1: MVP (Minimum Viable Product)

- [x] Selezione razza
- [x] Selezione classe
- [x] Assegnazione attributi
- [x] Selezione background
- [x] Calcolo valori derivati
- [x] Esportazione PDF
- [ ] Esportazione JSON
- [ ] Esportazione Markdown

### Fase 2: Funzionalità Avanzate

- [ ] Point Buy
- [ ] Multiclasse
- [ ] Sottoclassi
- [ ] Artefatti
- [ ] Customizzazione avanzata
- [ ] Salvataggio locale
- [ ] Build salva

### Fase 3: Integrazione Community

- [ ] Account utente
- [ ] Salvataggio cloud
- [ ] Build pubbliche
- [ ] Condivisione social
- [ ] Integrazione GitHub
- [ ] Badge per creatori

### Fase 4: Integrazioni

- [ ] Export Roll20
- [ ] Export Foundry
- [ ] API pubblica
- [ ] Webhook
- [ ] Integrazione Discord

### Fase 5: Localizzazione

- [ ] Inglese
- [ ] Spagnolo
- [ ] Francese
- [ ] Tedesco
- [ ] Portoghese

---

## 📚 Risorse per Sviluppatori

### Documentazione

- [React Documentation](https://react.dev/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [TailwindCSS Documentation](https://tailwindcss.com/docs)
- [Node.js Documentation](https://nodejs.org/docs)

### Strumenti

- **VS Code**: Editor di codice
- **Git**: Controllo versione
- **Postman**: Testing API
- **MongoDB Compass**: Gestione database

### Community

- [GitHub Issues](https://github.com/alisio85/shadowbound-generator/issues)
- [GitHub Discussions](https://github.com/alisio85/shadowbound-generator/discussions)
- [Discord](https://discord.gg/shadowbound) (coming soon)

---

## ❓ Domande Frequenti

### D: Il generatore è gratuito?

R: Sì, il generatore è completamente gratuito e open source.

### D: Posso usarlo offline?

R: Sì, puoi clonare il repository e usarlo offline.

### D: Posso contribuire al codice?

R: Sì! Tutti i contributi sono benvenuti. Leggi la guida per contributori.

### D: I miei dati sono sicuri?

R: Sì, i dati sono salvati localmente nel tuo browser. Non vengono condivisi con terze parti.

### D: Posso esportare il personaggio in altri formati?

R: Attualmente supportiamo PDF, JSON e Markdown. Pianifichiamo di aggiungere altri formati.

---

## 🤝 Supporto

Se hai domande o problemi:

- Apri una issue nel repository del generatore
- Unisciti alle GitHub Discussions
- Contatta i maintainer via GitHub

---

**Buon divertimento nel creare i tuoi personaggi!** 🎲

---

**Creato per Shadowbound - Regolamento Dark Fantasy Open Source**

*Basato su D&D 5.2.1 SRD, modificato da alisio85 e la Shadowbound community*
*Licenza: Creative Commons Attribution 4.0 International (CC-BY-4.0)*
