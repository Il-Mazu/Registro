# Registro Scolastico

Un'applicazione web moderna per la gestione del registro scolastico personale, progettata per aiutare gli studenti a tracciare i voti, le assenze e calcolare le medie in modo semplice ed efficiente.

## 🎯 Caratteristiche Principali

### Gestione Voti
- **Aggiunta moduli**: Crea e gestisci materie scolastiche personalizzate
- **Tracciamento voti**: Registra voti con descrizione e data
- **Calcolo automatico medie**: Visualizza istantaneamente la media di ogni materia e la media generale
- **Sistema di colori**: Voti alti (verde), medi (giallo), bassi (rosso) per un rapido riconoscimento

### Gestione Assenze
- **Registrazione assenze**: Traccia assenze intere e ritardi
- **Calcolo ore totali**: Monitora automaticamente il totale delle ore di assenza
- **Indicatori visivi**: Barre di progresso per visualizzare il rispetto dei limiti di assenza

### Sincronizzazione Cloud
- **Backup automatico**: Sincronizzazione con Firebase Firestore
- **Accesso multi-dispositivo**: I dati sono accessibili da qualsiasi dispositivo
- **Modalità offline**: L'app continua a funzionare anche senza connessione internet
- **Autenticazione sicura**: Login con email e password per proteggere i dati

## 🛠️ Tecnologie Utilizzate

### Frontend
- **React 18**: Libreria JavaScript per l'interfaccia utente
- **CSS3 Puro**: Styling moderno con variabili CSS e design responsive
- **Font Google**: DM Serif Display e DM Mono per un'estetica professionale

### Backend & Storage
- **Firebase Firestore**: Database NoSQL real-time per la sincronizzazione
- **Firebase Authentication**: Sistema di autenticazione sicuro
- **LocalStorage**: Cache locale per funzionamento offline

### Architettura
- **Single Page Application (SPA)**: Esperienza utente fluida e reattiva
- **Modulare**: Codice organizzato e manutenibile
- **Responsive Design**: Ottimizzato per desktop, tablet e smartphone

## 🚀 Come Iniziare

### Prerequisiti
- Un browser web moderno (Chrome, Firefox, Safari, Edge)
- Connessione internet (per la sincronizzazione cloud)

### Installazione Locale
1. Clona questo repository:
   ```bash
   git clone https://github.com/tuo-username/registro.git
   cd registro
   ```

2. Apri `index.html` nel tuo browser preferito

### Configurazione Firebase (Opzionale)
Per abilitare la sincronizzazione cloud:

1. **Crea un progetto Firebase**:
   - Vai su [console.firebase.google.com](https://console.firebase.google.com)
   - Clicca "Add project" e segui le istruzioni

2. **Abilita Firestore Database**:
   - Menu laterale → Build → Firestore Database
   - Clicca "Create database"
   - Scegli "Start in test mode" → "Done"

3. **Abilita Authentication**:
   - Menu laterale → Build → Authentication
   - Clicca "Get started"
   - Abilita "Email/Password"

4. **Ottieni le credenziali**:
   - Icona ⚙ (Project Settings) → tab "General"
   - Scorri fino a "Your apps" → clicca `</> (Web)`
   - Registra l'app e copia i valori necessari

5. **Configura l'applicazione**:
   - Apri l'applicazione nel browser
   - Segui la procedura di configurazione iniziale
   - Inserisci le credenziali Firebase quando richiesto

## 📁 Struttura del Progetto

```
registro/
├── index.html          # File HTML principale con l'applicazione React
├── styles.css          # Foglio di stile separato per il design
├── README.md           # Documentazione del progetto
└── .git/              # Cartella Git (se presente)
```

## 🎨 Design e UX

### Tema Scuro Professionale
- Palette di colori elegante con contrasti ottimizzati
- Design minimalista che riduce l'affaticamento visivo
- Interfaccia pulita e professionale

### Esperienza Utente
- **Navigazione intuitiva**: Sidebar chiara con icone descrittive
- **Feedback visivo**: Animazioni sottili e transizioni fluide
- **Stato del database**: Indicatore in tempo reale dello stato di connessione
- **Toast notifications**: Messaggi non intrusivi per conferme operazioni

### Responsive Design
- Layout adattivo per diverse dimensioni schermo
- Ottimizzazione per dispositivi mobili
- Touch-friendly su smartphone e tablet

## 🔒 Privacy e Sicurezza

- **Dati crittografati**: Trasmissione sicura tramite HTTPS
- **Autenticazione Firebase**: Sistema di login sicuro e affidabile
- **Storage locale**: I dati rimangono disponibili anche offline
- **Niente tracciamento**: L'applicazione non raccoglie dati analytics

## 📊 Funzionalità Tecniche

### Gestione Dati
- **Sincronizzazione real-time**: Aggiornamenti istantanei su tutti i dispositivi
- **Cache intelligente**: Ottimizzazione delle performance con localStorage
- **Migrazione dati**: Importazione automatica da vecchie versioni
- **Backup automatico**: Salvataggio progressivo per prevenire perdite

### Performance
- **Lazy loading**: Caricamento ottimizzato dei componenti
- **Virtual scrolling**: Gestione efficiente di liste lunghe
- **Minimal bundle**: Nessuna dipendenza pesante, caricamento rapido

## 🤝 Contributi

I contributi sono benvenuti! Se vuoi migliorare il progetto:

1. Fai fork del repository
2. Crea un branch per la tua feature (`git checkout -b feature/nuova-funzione`)
3. Fai commit delle tue modifiche (`git commit -am 'Aggiunta nuova funzione'`)
4. Fai push del branch (`git push origin feature/nuova-funzione`)
5. Apri una Pull Request

## 📝 Licenza

Questo progetto è rilasciato sotto licenza MIT. Sentiti libero di utilizzarlo, modificarlo e distribuirlo come preferisci.

## 🐛 Segnalazione Bug

Se trovi un bug o hai suggerimenti per miglioramenti:

1. Controlla se esiste già un'issue aperta
2. Se non esiste, crea una nuova issue con:
   - Titolo descrittivo
   - Passaggi per riprodurre il problema
   - Screenshot se pertinente
   - Informazioni sul browser e sistema operativo

## 🚀 Sviluppi Futuri

- [ ] Grafici andamento voti nel tempo
- [ ] Esportazione dati in PDF/Excel
- [ ] Notifiche promemoria scadenze
- [ ] Integrazione con calendari scolastici
- [ ] Supporto multi-lingua
- [ ] Temi personalizzabili

## 👤 Autore

Realizzato con ❤️ per semplificare la gestione scolastica degli studenti.

---

**Registro Scolastico** - Il tuo compagno fidato per il successo accademico
