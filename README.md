# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.64**
- **Data rilascio**: 2026-11-06
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.64-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.64/RaPiDSSH-v1.4.64-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.64:

• Diagnostica Avanzata & Logging Completo Connessioni VNC: introdotto VncDiagnosticStream per l'analisi e registrazione dettagliata nel log diagnostico (rapidssh.log) di tutte le fasi dell'handshake RFB (versione server/client, metodi di autenticazione offerti, challenge DES, SecurityResult ed errori restituiti dal server).
• Parsing Intelligente Host e Display VNC: supporto automatico per sintassi 'host:porta' e 'host:display' (es. :1 -> porta 5901), con timeout di connessione TCP e messaggi di errore descrittivi a schermo anziché il generico 'Connessione fallita'.
• Risoluzione Airspace RDP su Pausa Caffè: eliminata l'interferenza delle finestre Win32 ActiveX di Desktop Remoto (RdpSessionControl) che bucavano l'overlay scuro di blocco schermo durante la 'Pausa Caffè', ripristinandone la piena visibilità e interattività allo sblocco senza disconnessioni.
• Allineamento Pixel-Perfect Icone e Testi nei Menu: separazione formale tra proprietà Icon ed etichetta Header con colonna icona a larghezza uniforme (22px) e SharedSizeScope su tutti i menu principali e contestuali, garantendo un perfetto allineamento verticale di tutte le voci.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
