# 🎲 Sistema di Gioco - Shadowbound

> *"In Umbra, le regole sono diverse. Le ombre cambiano tutto."*

---

## 📋 Sommario

- [Concetti Base](#concetti-base)
- [Attributi](#attributi)
- [Punti Ferita](#punti-ferita)
- [Tiri di Dado](#tiri-di-dado)
- [Combattimento](#combattimento)
- [Magia](#magia)
- [Ombre](#ombre)
- [Corruzione](#corruzione)

---

## 🎯 Concetti Base

Shadowbound usa un sistema di gioco originale basato su d20, ma con meccaniche uniche che riflettono il mondo oscuro di Umbra.

### I Tre Pilastri

1. **Attributi**: Le capacità innate del personaggio
2. **Abilità**: Le competenze acquisite
3. **Ombre**: La connessione con le entità oscure

### Il Dado Base

Tutti i tiri usano un **d20** (dado a 20 facce). Il risultato viene modificato da:

- Modificatore dell'attributo pertinente
- Bonus di competenza (se applicabile)
- Vantaggio o svantaggio

---

## 📊 Attributi

I sei attributi fondamentali:

| Attributo | Descrizione | Modificatore |
|-----------|-------------|--------------|
| **FORZA (FOR)** | Potenza fisica, atletica | -5 a +5 |
| **DESTREZA (DES)** | Agilità, riflessi, equilibrio | -5 a +5 |
| **COSTITUZIONE (COS)** | Salute, resistenza | -5 a +5 |
| **INTELLIGENZA (INT)** | Memoria, ragionamento, conoscenza | -5 a +5 |
| **SAGGEZZA (SAG)** | Percezione, intuizione, volontà | -5 a +5 |
| **CARISMA (CAR)** | Personalità, influenza, comando | -5 a +5 |

### Valori Tipici

- **8**: Sotto la media (-1)
- **10**: Media (+0)
- **12**: Sopra la media (+1)
- **14**: Buono (+2)
- **16**: Eccellente (+3)
- **18**: Eccezionale (+4)

---

## 💚 Punti Ferita

### PF Base

I Punti Ferita (PF) rappresentano la salute del personaggio.

**Formula**: 10 + modificatore COSTITUZIONE

### PF Massimi

Il massimo di PF che un personaggio può avere.

**Formula**: PF Base + bonus da classe/razza

### PF Temporanei

PF extra che durano fino alla fine del combattimento o dopo un breve riposo.

### Morte

Quando i PF scendono a 0:

1. Il personaggio è **incosciente**
2. Ogni round, tira d20:
   - **1-9**: Il personaggio muore
   - **10-14**: Il personaggio rimane incosciente
   - **15-20**: Il personaggio si stabilizza

---

## 🎲 Tiri di Dado

### Tiri di Abilità

Quando fai un'azione incerta:

1. Tira d20
2. Aggiungi modificatore attributo
3. Aggiungi bonus competenza (se competente)
4. Confronta con la Difficoltà (DC)

### Difficoltà (DC)

| Livello | DC | Descrizione |
|---------|----|------------|
| Facile | 10 | Azioni semplici |
| Medio | 15 | Azioni standard |
| Difficile | 20 | Azioni complesse |
| Molto Difficile | 25 | Azioni estreme |
| Impossibile | 30 | Azioni quasi impossibili |

### Vantaggio e Svantaggio

- **Vantaggio**: Tira due d20, usa il più alto
- **Svantaggio**: Tira due d20, usa il più basso

### Successo Critico

Se un tiro d20 è un **20 naturale** (20):

- Successo automatico
- Effetto bonus (a discrezione del DM)

### Fallimento Critico

Se un tiro d20 è un **1 naturale** (1):

- Fallimento automatico
- Effetto negativo (a discrezione del DM)

---

## ⚔️ Combattimento

### Iniziativa

All'inizio del combattimento, ogni personaggio tira iniziativa:

**Formula**: d20 + modificatore DESTREZZA

L'ordine va dal più alto al più basso.

### Turno

Ogni turno, un personaggio può:

1. **Azione**: Attaccare, lanciare incantesimo, ecc.
2. **Movimento**: Spostarsi fino alla velocità
3. **Azione Bonus**: Azioni minori (dodge, disengage, ecc.)
4. **Reazione**: Un'azione fuori turno (opportunity attack, ecc.)

### Attacco

Per attaccare:

1. Tira d20 + bonus attacco
2. Confronta con Classe Armatura (AC) del bersaglio
3. Se colpisci, tira il danno

### Bonus Attacco

**Corpo a corpo**: FORZA + bonus competenza
**A distanza**: DESTREZZA + bonus competenza

### Classe Armatura (AC)

**Formula**: 10 + modificatore DESTREZZA + armatura + scudo

### Danno

Il danno base è determinato dall'arma o incantesimo.

**Formula**: dado danno + modificatore FORZA/DESTREZZA

---

## ✨ Magia

### Punti Magia (PM)

Invece di slot, Shadowbound usa Punti Magia.

**PM Base**: 5 + modificatore INTELLIGENZA

**PM Massimi**: PM Base + bonus da classe

### Lancio di Incantesimi

Per lanciare un incantesimo:

1. Scegli un incantesimo dal tuo elenco
2. Paga il costo in PM
3. Tira d20 + modificatore INTELLIGENZA + bonus competenza
4. Confronta con DC del bersaglio

### Costo in PM

| Livello Incantesimo | Costo PM |
|-------------------|----------|
| Cantrip (0°) | 0 |
| 1° | 2 |
| 2° | 3 |
| 3° | 5 |
| 4° | 7 |
| 5° | 9 |

### Recupero PM

- **Riposo Breve** (1 ora): Recupera 1/4 PM massimi
- **Riposo Lungo** (8 ore): Recupera tutti i PM

### Scuole di Magia

- **Ombra**: Manipolazione delle ombre
- **Luce**: Manipolazione della luce
- **Sangue**: Magia legata al sangue
- **Spirito**: Comunicazione con spiriti
- **Mente**: Controllo mentale e illusioni

---

## 🌑 Ombre

In Umbra, le ombre sono entità senzienti. Questo influenza il gioco.

### Punti Ombra (PO)

I personaggi hanno Punti Ombra che rappresentano la loro connessione con le entità oscure.

**PO Base**: 0

**PO Massimi**: 5 + modificatore CARISMA

### Uso dei PO

I PO possono essere usati per:

1. **Vantaggio**: 1 PO = vantaggio su un tiro
2. **Resistenza**: 2 PO = resistere a un effetto
3. **Potere Ombra**: 3 PO = usare un potere speciale delle ombre

### Recupero PO

- **Riposo Breve**: Recupera 1 PO
- **Riposo Lungo**: Recupera tutti i PO
- **Azione Ombra**: Recupera 1 PO (azione bonus)

### Poteri Ombra

Poteri speciali che possono essere usati spendendo PO:

- **Passo nell'Ombra**: Teletrasportarsi tra ombre (3 PO)
- **Parola d'Ombra**: Comunicare con le ombre (2 PO)
- **Maschera d'Ombra**: Diventare invisibile nell'oscurità (3 PO)

---

## 💀 Corruzione

L'esposizione alle ombre può causare corruzione.

### Livelli di Corruzione

| Livello | Effetto |
|---------|---------|
| **0** | Nessun effetto |
| **1-2** | -1 a un attributo |
| **3-4** | -1 a due attributi |
| **5-6** | -2 a due attributi |
| **7-8** | -2 a tutti gli attributi |
| **9+** | Possesso da ombre |

### Acquisizione Corruzione

- Esposizione prolungata alle ombre
- Uso frequente di poteri ombra
- Contatto con entità oscure

### Purificazione

La corruzione può essere purificata solo con:

- Rituali specifici
- Aiuto divino
- Sacrifici significativi

---

## 🎭 Competenze

### Bonus Competenza

All'inizio, il bonus competenza è **+2**.

Aumenta a **+3** al livello 5, **+4** al livello 10, **+5** al livello 15.

### Skill

Le skill sono competenze specifiche:

- **Atletica (FOR)**
- **Acrobazia (DES)**
- **Percezione (SAG)**
- **Investigazione (INT)**
- **Persuasione (CAR)**
- **Intimidazione (CAR)**
- **Furtività (DES)**
- **Conoscenza Arcana (INT)**
- **Medicina (SAG)**
- **Sopravvivenza (SAG)**
- **Storia (INT)**
- **Religione (INT)**

---

## 📊 Progressione

### Livelli

I personaggi guadagnano livelli guadagnando XP (Punti Esperienza).

| Livello | XP Minimo | Bonus Competenza |
|---------|-----------|------------------|
| 1 | 0 | +2 |
| 2 | 100 | +2 |
| 3 | 300 | +2 |
| 4 | 600 | +2 |
| 5 | 1,000 | +3 |
| 6 | 1,500 | +3 |
| 7 | 2,500 | +3 |
| 8 | 4,000 | +3 |
| 9 | 6,000 | +3 |
| 10 | 9,000 | +4 |

### Miglioramento di Livello

Quando sali di livello:

1. Aumenta PF massimi
2. Aumenta PM massimi (se mago)
3. Impara nuove abilità
4. Scegli un miglioramento (attributo o feat)

---

## 🎯 Regole Speciali

### Penombra Permanente

Il mondo è sempre in penombra. Questo influenza:

- **Visione**: Tutti hanno visione adattata alla penombra (18 m)
- **Stealth**: Vantaggio ai tiri di furtività nell'oscurità
- **Magia della Luce**: Incantesimi di luce sono più potenti ma più rari

### Ombre Viventi

Le ombre possono:

- Osservare e trasmettere informazioni
- Influenzare azioni in luoghi molto oscuri
- Manifestarsi in forma fisica (raro)

### Resistenza alla Corruzione

Alcuni personaggi hanno resistenza alla corruzione:

- **Elfi dell'Ombra**: Vantaggio ai tiri contro corruzione
- **Nani del Gelo**: Resistenza +2 alla corruzione
- **Umani**: Nessun bonus o malus

---

## 🎲 Esempi di Tiri

### Esempio 1: Attacco

**Situazione**: Guerriero con FOR +3 attacca con spada

1. Tira d20 = 15
2. Aggiungi FOR +3 = 18
3. AC del nemico = 15
4. **Colpisco!**
5. Tiro danno: d8 + 3 = 6 + 3 = 9 danni

### Esempio 2: Skill Check

**Situazione**: Ladro con DES +4 tenta di scassinare una serratura

1. Tira d20 = 12
2. Aggiungi DES +4 = 16
3. DC della serratura = 15
4. **Successo!**

### Esempio 3: Incantesimo

**Situazione**: Mago con INT +3 lancia Fire Bolt (costo 2 PM)

1. Paga 2 PM (PM attuali: 8 → 6)
2. Tira d20 = 14
3. Aggiungi INT +3 = 17
4. DC del bersaglio = 13
5. **Successo!**
6. Tiro danno: d10 = 7 danni

---

## 📚 Appendice

### Glossario

- **AC**: Classe Armatura
- **DC**: Classe Difficoltà
- **PF**: Punti Ferita
- **PM**: Punti Magia
- **PO**: Punti Ombra
- **XP**: Punti Esperienza

### Riferimenti

Questo sistema è originale e creato specificamente per Shadowbound.

---

**Creato per Shadowbound - Regolamento Dark Fantasy Open Source**

*Basato su D&D 5.2.1 SRD, modificato da alisio85 e la Shadowbound community*
*Licenza: Creative Commons Attribution 4.0 International (CC-BY-4.0)*
