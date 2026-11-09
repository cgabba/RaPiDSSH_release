# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.66**
- **Data rilascio**: 2026-11-09
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.66-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.66/RaPiDSSH-v1.4.66-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.66:

• Correzione Crittografica UltraVNC MS-Logon II: allineato rigorosamente l'algoritmo di cifratura rfbEncryptBytes2 alle specifiche standard UltraVNC (formato Big-Endian della chiave Diffie-Hellman, IV iniziale a 64 bit e cifratura FIPS 46 DES pura senza inversione di bit), consentendo l'autenticazione con successo su server UltraVNC protetti con account Windows e domini Active Directory.
• Supporto Asincrono Completo Bridge Stream VNC: integrati gli override ReadAsync e WriteAsync in MsLogonBridgeStream e PreHandshakeStream per garantire un flusso continuo e privo di blocchi durante il rendering grafico e la gestione input.

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
