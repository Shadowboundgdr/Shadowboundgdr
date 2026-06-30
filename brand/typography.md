# 🔤 Guida Tipografica di Shadowbound

> *"La tipografia definisce la voce visiva di Shadowbound. Ogni font ha un ruolo e un significato."*

---

## 📋 Sommario

- [Font Principale](#font-principale)
- [Font Secondario](#font-secondario)
- [Gerarchia Tipografica](#gerarchia-tipografica)
- [Utilizzo](#utilizzo)
- [Linee Guida](#linee-guida)
- [Download](#download)

---

## 🎭 Font Principale

### Cinzel

**Stile**: Serif, elegante, fantasy
**Designer**: Nicole Fally
**Licenza**: SIL Open Font License (OFL)

**Caratteristiche**:
- Elegante e sofisticato
- Leggibile anche in piccole dimensioni
- Perfetto per titoli e testi importanti
- Richiama tipografia classica e fantasy

**Varianti**:
- Cinzel Regular
- Cinzel Bold
- Cinzel Black
- Cinzel Medium

**Utilizzo**:
- Titoli principali
- Nomi propri
- Testo del logo "SHADOWBOUND"
- Intestazioni di livello 1 e 2

**Alternative**:
- Cormorant Garamond
- Playfair Display
- Libre Baskerville
- Crimson Pro

---

## 📝 Font Secondario

### Inter

**Stile**: Sans-serif, moderno, leggibile
**Designer**: Rasmus Andersson
**Licenza**: SIL Open Font License (OFL)

**Caratteristiche**:
- Moderno e pulito
- Altamente leggibile
- Perfetto per corpo del testo
- Funziona bene su schermi digitali

**Varianti**:
- Inter Regular
- Inter Medium
- Inter SemiBold
- Inter Bold

**Utilizzo**:
- Corpo del testo
- Documentazione
- UI e interfacce
- Testo di supporto

**Alternative**:
- Roboto
- Open Sans
- Lato
- Source Sans Pro

---

## 📐 Gerarchia Tipografica

### Livello 1: Titolo Principale

**Font**: Cinzel Bold
**Dimensione**: 48-72px
**Colore**: Argento Lunare (#C0C0C0)
**Spaziatura**: 0.05em
**Maiuscolo**: Tutte maiuscole

**Esempio**:
```
SHADOWBOUND
```

### Livello 2: Sottotitolo

**Font**: Cinzel Medium
**Dimensione**: 32-48px
**Colore**: Argento Lunare (#C0C0C0)
**Spaziatura**: 0.03em
**Maiuscolo**: Tutte maiuscole

**Esempio**:
```
REGOLAMENTO DARK FANTASY
```

### Livello 3: Intestazione

**Font**: Cinzel Regular
**Dimensione**: 24-32px
**Colore**: Bianco Puro (#FFFFFF)
**Spaziatura**: 0.02em
**Maiuscolo**: Titolo Case

**Esempio**:
```
Sistema di Gioco
```

### Livello 4: Sottointestazione

**Font**: Inter SemiBold
**Dimensione**: 18-24px
**Colore**: Bianco Puro (#FFFFFF)
**Spaziatura**: 0.01em
**Maiuscolo**: Title Case

**Esempio**:
```
Creazione del Personaggio
```

### Livello 5: Corpo del Testo

**Font**: Inter Regular
**Dimensione**: 16px
**Colore**: Bianco Puro (#FFFFFF)
**Spaziatura**: 0em
**Maiuscolo**: Sentence case

**Esempio**:
```
Shadowbound è un regolamento dark fantasy...
```

### Livello 6: Testo Piccolo

**Font**: Inter Regular
**Dimensione**: 14px
**Colore**: Grigio Chiaro (#808080)
**Spaziatura**: 0em
**Maiuscolo**: Sentence case

**Esempio**:
```
© 2024 Shadowbound Community
```

---

## 📱 Utilizzo

### Sito Web

**Header**:
- Font: Cinzel Bold
- Dimensione: 24px
- Colore: Argento Lunare

**Navigazione**:
- Font: Inter Medium
- Dimensione: 16px
- Colore: Bianco Puro

**Body**:
- Font: Inter Regular
- Dimensione: 16px
- Colore: Bianco Puro

### Documentazione

**Copertina**:
- Font: Cinzel Bold
- Dimensione: 48px
- Colore: Argento Lunare

**Intestazioni**:
- Livello 1: Cinzel Bold, 36px
- Livello 2: Cinzel Medium, 28px
- Livello 3: Inter SemiBold, 24px

**Corpo**:
- Font: Inter Regular, 16px
- Interlinea: 1.5
- Margini: 20px

### Social Media

**Bio**:
- Font: Inter Regular
- Dimensione: 16px
- Colore: Bianco Puro

**Post**:
- Font: Inter Regular
- Dimensione: 16px
- Colore: Bianco Puro

---

## 📏 Linee Guida

### Spaziatura

**Letter Spacing**:
- Cinzel: 0.02-0.05em per titoli
- Inter: 0-0.02em per corpo del testo

**Line Height**:
- Titoli: 1.2
- Corpo del testo: 1.5
- Testo piccolo: 1.4

**Margini**:
- Tra paragrafi: 20px
- Tra sezioni: 40px
- Tra intestazioni e testo: 10px

### Dimensioni Minime

**Desktop**:
- Corpo del testo: 16px minimo
- Titoli: 24px minimo

**Mobile**:
- Corpo del testo: 14px minimo
- Titoli: 20px minimo

### Accessibilità

- Usa dimensioni leggibili
- Mantieni contrasto sufficiente
- Non usare solo colore per enfasi
- Fornisci alternative per dislessici

---

## 📥 Download

### Font

**Cinzel**:
- [Google Fonts](https://fonts.google.com/specimen/Cinzel)
- [GitHub](https://github.com/NDPSoftware/Cinzel)

**Inter**:
- [Google Fonts](https://fonts.google.com/specimen/Inter)
- [GitHub](https://github.com/rsms/inter)

### CSS

```css
@import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700;900&family=Inter:wght@400;500;600;700&display=swap');

:root {
  --font-primary: 'Cinzel', serif;
  --font-secondary: 'Inter', sans-serif;
}

body {
  font-family: var(--font-secondary);
  font-size: 16px;
  line-height: 1.5;
}

h1, h2, h3 {
  font-family: var(--font-primary);
  text-transform: uppercase;
}

h1 {
  font-size: 48px;
  font-weight: 900;
  letter-spacing: 0.05em;
}

h2 {
  font-size: 36px;
  font-weight: 700;
  letter-spacing: 0.03em;
}

h3 {
  font-size: 24px;
  font-weight: 400;
  letter-spacing: 0.02em;
}
```

---

## 🧪 Strumenti di Test

### Pairing Font

- [Font Pair](https://fontpair.co/)
- [Typ.io](https://typ.io/)
- [Typescale](https://typescale.com/)

### Accessibilità

- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [WAVE](https://wave.webaim.org/)

---

## 🤝 Contribuire alla Tipografia

Se vuoi suggerire nuovi font:

1. Apri una issue con la tag `design`
2. Suggerisci il font con link
3. Spiega perché è appropriato
4. Fornisci esempi di utilizzo
5. Attendi la revisione

---

**Grazie per aver contribuito alla tipografia di Shadowbound!** 🔤

---

**Creato per Shadowbound - Regolamento Dark Fantasy Open Source**

*Basato su D&D 5.2.1 SRD, modificato da alisio85 e la Shadowbound community*
*Licenza: Creative Commons Attribution 4.0 International (CC-BY-4.0)*
