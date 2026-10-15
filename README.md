# EMAD - Task 1 (Flutter)

**Autore:** Giuseppe Di Somma  
**Corso:** Elementi di Mobile & App Development (EMAD)  
**Obiettivo:** Creazione, personalizzazione ed esecuzione di un'applicazione Flutter su emulatore e dispositivo mobile fisico, con pubblicazione del codice sorgente su GitHub.

---

## 📱 Descrizione del Progetto

L'applicazione è basata su Flutter ed è stata personalizzata inserendo il nome e cognome dello studente (**Giuseppe Di Somma**) sia nell'intestazione (`AppBar`) sia all'interno della schermata iniziale principale con una card identificativa dedicata.

### Funzionalità principali:
- Visualizzazione del nome e cognome (**Giuseppe Di Somma**) nel titolo e nella card profilo.
- Contatore interattivo conforme al template Flutter Material 3 con bottone flottante per incrementare.
- Supporto multipiattaforma (Android, iOS, Web, Windows).

---

## 🚀 Istruzioni per l'esecuzione

### Prerequisiti
- Flutter SDK (versione 3.24+ o successiva)
- Android SDK o Android Studio con emulatore configurato
- Per il deploy su smartphone: dispositivo Android con **Debug USB** abilitato.

### Comandi utili

1. **Installazione dipendenze:**
   ```bash
   flutter pub get
   ```

2. **Verifica ambiente:**
   ```bash
   flutter doctor
   ```

3. **Esecuzione su emulatore o dispositivo connesso:**
   ```bash
   flutter run
   ```

4. **Creazione dell'APK per Android:**
   ```bash
   flutter build apk --debug
   ```
