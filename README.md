# PriMus MDO Updater

Interfaccia web per aggiornare le **incidenze di manodopera** (`<IncMDO>`) nei file di computo metrico PriMus (formato XMLPwe di ACCA software), leggendo le percentuali da un elenco prezzi in formato Excel.

Funziona interamente nel browser — nessun server, nessuna installazione.

## Funzionalità

- Drag & drop per caricare il file XML PriMus e il file Excel
- Selezione del foglio Excel e configurazione delle colonne (tariffa, % manodopera)
- Supporto per valori decimali (`0.35`) e interi (`35`)
- Anteprima della mappatura colonne in tempo reale
- Report con statistiche, tabella delle modifiche e log dettagliato
- Download diretto del file XML aggiornato

## Utilizzo

Apri `primus_manodopera_gui.html` in un browser moderno (Chrome, Firefox, Edge). Nessuna dipendenza da installare.

## Compatibilità

Testato con file PriMus XMLPwe generati da ACCA PriMus. La Processing Instruction proprietaria `<?mso-application progid="PriMus.Document.XPWE"?>` viene preservata nell'output.

## Licenza

Questo progetto è distribuito sotto i termini della **GNU General Public License versione 3** (GPL-3.0).

