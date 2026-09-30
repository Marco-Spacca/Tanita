# Phoenix Fitness — Gestione Atleti

Sistema web per la gestione e il monitoraggio delle misurazioni degli atleti.

## Funzionalità

- **Ricerca atleti** con autocomplete
- **Scheda atleta** con anagrafica e storico misurazioni
- **Nuova misurazione** con calcolo automatico dell'età
- **Tabella storica** con ordinamento per data
- **Grafici interattivi** (linee/barre) con massimo 4 parametri simultanei
- **Persistenza locale** tramite localStorage

## Deploy su GitHub Pages

1. Crea un nuovo repository su GitHub
2. Carica il file `index.html` nella root del repository
3. Vai su **Settings → Pages**
4. Seleziona la branch `main` e la cartella `/ (root)`
5. Salva e attendi qualche minuto per il deploy

Il sito sarà disponibile su: `https://<username>.github.io/<repository>/`

## Tecnologie

- HTML5, CSS3, Vanilla JavaScript
- Nessuna dipendenza esterna
- Canvas API per i grafici
- localStorage per la persistenza

## Struttura

```
├── index.html    # Applicazione completa (single-file)
└── README.md     # Questo file
```

## Note

- I dati sono salvati localmente nel browser (localStorage)
- Per un uso multi-dispositivo è necessario un backend con database
- Il sito è completamente responsive e funziona offline dopo il primo caricamento
