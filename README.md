# Archivio Appunti

### Università degli Studi Roma Tre

Repository personale di appunti raccolti durante il percorso universitario in Ingegneria Informatica. Ogni cartella corrisponde a una materia del corso di studi e contiene slide, dispense e materiali di esercitazione organizzati per capitolo.

---

## Struttura della Repository

Ogni materia è contenuta in una cartella dedicata, con la seguente organizzazione interna:

```
Materia/
├── README.md              # Indice del corso e descrizione della materia
├── Materia.pdf            # Materiale di riferimento complessivo
├── sections/              # Appunti teorici divisi per capitolo
└── ex/                    # Esercitazioni e materiali pratici (se presente)
```

| Cartella | Contenuto |
|----------|-----------|
| **`/sections`** | Appunti teorici, uno per capitolo (file PDF numerati). |
| **`/ex`** | Esercitazioni, esami svolti e laboratori pratici. |

> **Nota:** in [Reti di Calcolatori](Reti%20di%20Calcolatori/README.md) la teoria è in `/ex` e i laboratori Kathará in `/sections`.

---

## Materie

### Laurea Magistrale

| Materia | Descrizione |
|---------|-------------|
| [Automata, Languages and Computing](Automata,%20Languages%20and%20Computing/README.md) | Linguaggi formali, calcolabilità e teoria della complessità |
| [Internet and Data Centers](Internet%20and%20Data%20Centers/README.md) | Architettura di Internet, routing e data center |

### Laurea Triennale

| Materia | Descrizione |
|---------|-------------|
| [Economia Applicata all'Ingegneria](Economia%20Applicata%20all'Ingegneria/README.md) | Microeconomia, contabilità direzionale e capital budgeting |
| [Ethical Hacking](Ethical%20Hacking/README.md) | Sicurezza informatica, penetration testing e tool di rete in Python |
| [Reti di Calcolatori](Reti%20di%20Calcolatori/README.md) | Architettura delle reti, protocolli ISO/OSI e laboratori Kathará |
| [Sistemi Operativi](Sistemi%20Operativi/README.md) | Processi, memoria, scheduling e programmazione concorrente |

---

## Come scaricare

Repository: [github.com/adducec03/my-uni-notes](https://github.com/adducec03/my-uni-notes)

### Intera repository

**Opzione 1 — Git (consigliata)**

```bash
git clone https://github.com/adducec03/my-uni-notes.git
```

**Opzione 2 — ZIP da GitHub**

1. Apri la [pagina della repository](https://github.com/adducec03/my-uni-notes)
2. Clicca **Code** → **Download ZIP**

### Una sola materia

GitHub non permette di scaricare una singola cartella dall'interfaccia web. Puoi usare uno di questi metodi:

**Opzione 1 — Sparse checkout (solo la cartella che ti serve)**

Sostituisci `NOME_MATERIA` con il nome esatto della cartella (es. `Sistemi Operativi`, `Ethical Hacking`):

```bash
git clone --filter=blob:none --sparse https://github.com/adducec03/my-uni-notes.git
cd my-uni-notes
git sparse-checkout set "NOME_MATERIA"
```

**Opzione 2 — SVN export (senza clonare tutta la repo)**

Scarica direttamente la cartella. Sostituisci `NOME_MATERIA` con il nome della materia (gli spazi vanno tra virgolette):

```bash
svn export "https://github.com/adducec03/my-uni-notes/trunk/NOME_MATERIA"
```

Esempi:

```bash
svn export "https://github.com/adducec03/my-uni-notes/trunk/Sistemi Operativi"
svn export "https://github.com/adducec03/my-uni-notes/trunk/Ethical Hacking"
svn export "https://github.com/adducec03/my-uni-notes/trunk/Automata, Languages and Computing"
```

> Richiede **Subversion** installato (`brew install svn` su macOS). Crea una cartella locale con lo stesso nome della materia.

**Opzione 2b — Dal browser (senza terminale)**

Apri un servizio come [download-directory.github.io](https://download-directory.github.io/), incolla l'URL della cartella su GitHub (es. `https://github.com/adducec03/my-uni-notes/tree/main/Sistemi%20Operativi`) e scarica lo ZIP.

**Nomi cartelle disponibili**

| Materia | Nome cartella |
|---------|---------------|
| Automata, Languages and Computing | `Automata, Languages and Computing` |
| Internet and Data Centers | `Internet and Data Centers` |
| Economia Applicata all'Ingegneria | `Economia Applicata all'Ingegneria` |
| Ethical Hacking | `Ethical Hacking` |
| Reti di Calcolatori | `Reti di Calcolatori` |
| Sistemi Operativi | `Sistemi Operativi` |
