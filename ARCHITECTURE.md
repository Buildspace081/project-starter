# Architettura - [Nome progetto]

## Stato

- Fase: [proposta / implementata / in revisione].
- Ultima verifica con il codice: [data].

## Vista generale

Descrivi in poche righe come un utente raggiunge il prodotto e dove passano i dati. Aggiungi un diagramma solo se chiarisce un flusso reale.

## Componenti e responsabilita

| Componente | Responsabilita | Posizione nel repository | Dipendenze |
| --- | --- | --- | --- |
| [nome] | [cosa fa] | [percorso] | [altro componente/servizio] |

## Flussi principali

1. [Richiesta o evento iniziale].
2. [Elaborazione e persistenza, se presenti].
3. [Risposta, errore e osservabilita].

## Confini e integrazioni

- Sistemi esterni: [nome, scopo, proprietario, contratto].
- Confini tra progetti: [cosa non viene condiviso].
- Contratti pubblici: [API, eventi, schema, link].

## Ambienti e distribuzione

- Locale: [come gira].
- Staging: [come gira o Non applicabile].
- Produzione: [come gira o Da decidere].
- Build e deploy: [comandi/pipeline].

## Qualita e rischi

- Test ai confini: [quali].
- Monitoraggio: [log, metriche, alert o Da decidere].
- Rischi tecnici noti: [impatto e mitigazione].

## Decisioni correlate

- [Link a `docs/decisions/NNNN-...md`].
