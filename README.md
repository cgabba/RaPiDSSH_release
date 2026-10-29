# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.21**
- **Data rilascio**: 2026-10-29
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.21-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.21/RaPiDSSH-v1.4.21-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.21:

  • Importazione Avanzata CSV con Mappatura Colonne: nuovo wizard guidato per associare visivamente qualsiasi colonna di file CSV (anche con decine di campi da CMDB, GLPI, vCenter) ai dati di RaPiDSSH, anteprima in tempo reale, gestione duplicati (aggiorna, salta o duplica) e memorizzazione di profili di mapping riutilizzabili
  • Fix Logout Terminale SSH e Telnet: la chiusura della sessione remota ('logout' / 'exit') chiude ora istantaneamente e in modo pulito la scheda di connessione senza blocchi o pop-up pendenti
  • Fix Copia Comandi Lunghi nel Terminale: introdotta gestione intelligente del soft-wrap, eliminando i ritorni a capo involontari quando si copiano e incollano comandi estesi che vanno a capo visivamente
  • Auto-Scroll al Prompt: digitando o incollando comandi mentre si consulta lo storico o i log scorrendo in alto, la vista si riallinea automaticamente in fondo sulla riga attiva del cursore

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*