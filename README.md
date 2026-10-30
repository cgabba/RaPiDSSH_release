# RaPiDSSH Distribution & Release Repository

Repository ufficiale per la distribuzione e l'aggiornamento automatico di **RaPiDSSH** (Remote Desktop & SSH Session Manager).

## 🚀 Ultima Versione: **v1.4.33**
- **Data rilascio**: 2026-10-30
- **Pacchetto Portable (Zero Installazione)**: [Scarica RaPiDSSH-v1.4.33-Portable.zip](https://github.com/cgabba/RaPiDSSH_release/releases/download/v1.4.33/RaPiDSSH-v1.4.33-Portable.zip)
- **Feed Manifest Aggiornamenti**: [version.json](https://raw.githubusercontent.com/cgabba/RaPiDSSH_release/main/version.json)

### Novità di questa versione:
Novità di RaPiDSSH v1.4.33:

  • Ripristino Prompt su 'Pulisci Schermo' (SSH & Telnet): il comando 'Pulisci Schermo' invia ora la sequenza standard Form Feed (Ctrl+L / Ctrl+L) alla shell remota. Il terminale viene ripulito e la shell ridisegna istantaneamente il prompt attivo in cima allo schermo con il comando corrente
  • Correzione Dimensioni Finestra 'Accedi come...': rimossa l'altezza fissa rigida e introdotto SizeToContent con margini ariosi, evitando che i pulsanti e il campo password vengano tagliati o compressi a seconda dei DPI
  • Miglioramento Contrasto e Supporto Tema Chiaro: convertiti i dialoghi modali e gli elementi della GUI alle risorse di stile dinamiche (ThemeMainBackground, ThemeForeground, ThemeBorderBrush), garantendo perfetta leggibilità e contrasto elevato in modalità Chiara

---
*Per il codice sorgente e la documentazione del progetto, visitare il repository principale.*
