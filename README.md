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

> This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
>
> This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
>
> You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.

---

*Progetto non affiliato ad ACCA software S.p.A.*
