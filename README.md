# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.59**
- **Data rilascio**: 2026-11-05
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.59-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.59/RaPiDSSH-v1.4.59-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.59:

• Risolto Crash su Menu Contestuali con Separatori: rimosso l'ItemContainerStyle restrittivo su ContextMenu che causava InvalidOperationException ('Non è possibile applicare al tipo Separator uno stile destinato al tipo MenuItem') all'apertura del menu delle schede o dei controlli.
• Riproduzione Completa Video Flottante: risolto l'evento prematuro di chiusura automatica del player video; introdotto il controllo della durata effettiva (NaturalDuration) e il timer watchdog di riproduzione completa prima della chiusura.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
