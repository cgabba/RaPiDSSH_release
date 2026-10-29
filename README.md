# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.29**
- **Data rilascio**: 2026-10-29
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.29-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.29/RaPiDSSH-v1.4.29-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.29:

  • Backup Automatico Completo Cifrato (.rsbak): archiviazione automatica non presidiata in background di tutte le impostazioni, configurazioni griglie e tutti i file di database connessioni (.enc) con crittografia standard bancario AES-256-GCM
  • Trigger Configurabili: esecuzione configurabile all'avvio, alla chiusura dell'applicazione o al salvataggio manuale
  • Protezione Trasparente DPAPI: la password del backup automatico è memorizzata in modo sicuro tramite Windows DPAPI legato all'utente locale senza richiedere popup di conferma all'uscita
  • Politica di Retention e Rotazione: rotazione cronologica automatica con limite personalizzabile del numero di copie e dei giorni di conservazione
  • Nuova Scheda 'Backup Automatico' nelle Impostazioni e comandi rapidi nel menu Strumenti

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*