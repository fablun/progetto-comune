# Progetto Comune

**Le migliori istituzioni che l'umanità ha costruito, messe insieme per una società più giusta, ricca e felice.**

Un documento vivo e aperto che raccoglie le soluzioni politiche, economiche e sociali che hanno dimostrato di funzionare nella storia e nel mondo, ne verifica le prove, ne ricava dei principi e li combina in un sistema adattabile a paesi diversi.

📖 **Leggi il documento:** <https://fablun.github.io/progetto-comune/> (si aggiorna automaticamente a ogni modifica).
✏️ **Contribuisci:** leggi [come partecipare](docs/contribuire.md).

## Struttura

```
docs/
├── index.md                 Presentazione
├── metodo.md                Come scegliamo e valutiamo le soluzioni
├── indice.md                Mappa completa del lavoro
├── modello-scheda.md        Modello per proporre nuove schede
├── contribuire.md           Regole di partecipazione
├── registro.md              Versioni principali
└── aree/
    └── risorse-e-conflitti/ Prima area: 10 schede + sintesi
```

## Pubblicare il sito

Il sito è costruito con [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) e pubblicato su GitHub Pages da un'azione automatica (`.github/workflows/pubblica.yml`).

1. Nelle impostazioni del repository, sezione **Pages**, la sorgente è **GitHub Actions**.
2. Ogni modifica al ramo `main` aggiorna il sito in un paio di minuti.

Per vederlo sul tuo computer:

```bash
pip install -r requirements.txt
mkdocs serve
```

## Licenza

I testi sono pubblicati con licenza [Creative Commons Attribuzione – Condividi allo stesso modo 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it). Vedi [LICENSE](LICENSE).
