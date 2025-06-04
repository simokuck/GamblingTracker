🎰 Gambling Tracker – App Web per Tracciamento Sessioni di Gioco

Gambling Tracker è una web app leggera sviluppata in HTML, CSS e JavaScript vanilla, progettata per tenere traccia delle proprie sessioni di gioco d’azzardo o da casinò online. Non richiede backend né installazione: funziona completamente lato client tramite localStorage.

⸻

🚀 Funzionalità principali

	•	Inserimento sessioni: l’utente seleziona un gioco, inserisce un importo (positivo o negativo) e una data.
	•	Persistenza dati: tutte le sessioni vengono salvate nel localStorage del browser.
	•	Riepilogo per periodo:
	•	Statistiche giornaliere, settimanali e mensili.
	•	Bilancio totale, numero di sessioni, miglior e peggior gioco.
	•	Resoconto per gioco:
	•	Sessioni totali, saldo cumulato, win rate, vittorie e sconfitte.
	•	Esportazione dati:
	•	In formato .csv compatibile con Excel.
	•	Include cronologia completa e riepilogo per gioco.
	•	Importazione dati:
	•	Da file .csv o .json (backup).

⸻

🧱 Struttura dell’app

	•	Tutto il codice è contenuto in un singolo file HTML (game-tracker_v3.html).
	•	Il CSS è interno e include uno stile responsive per dispositivi mobili.
	•	Il JS è inline e gestisce:
	•	Manipolazione DOM
	•	Gestione stato (array di sessioni)
	•	Calcoli statistici
	•	Funzioni di import/export
	•	Gestione dinamica delle tab e delle notifiche

⸻

📦 Storage e backup

	•	I dati vengono salvati nel browser tramite localStorage, sotto una chiave personalizzabile (es. gaming-tracker-data).
	•	L’utente può esportare o importare file JSON per il backup manuale o lo spostamento tra dispositivi.
	•	In alternativa è disponibile l’esportazione CSV con cronologia e sommari.

⸻

📌 Note per lo sviluppo

	•	Non ci sono dipendenze esterne o build step.
	•	Il salvataggio avviene in automatico a ogni modifica.
	•	Per testare versioni differenti, si può cambiare la chiave localStorage dal campo “Nome Dati Locali”.

⸻

🛡️ Avvertenze

	•	I dati sono memorizzati solo localmente. Pulire la cache o usare la modalità incognito comporta la perdita dei dati.
	•	Per evitare perdite, si consiglia di usare regolarmente l’opzione 💾 Salva Backup.
