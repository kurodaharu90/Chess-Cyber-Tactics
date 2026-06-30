TACTICAL CYBER ARENA
User Manual · Version 4.0 · Quantum Chess Matrix
This manual is organized in two language versions. The English version appears first, followed by the Italian version. Each section explains the main functions of Tactical Cyber Arena, from chess rules to tactical analysis tools and PGN management.
Contents / Indice
English version: 1. Chess Rules · 2. Main Interface · 3. Panels and Features · 4. Visual and Audio Feedback · 5. Special Modes · 6. Game Functions · 7. PGN Import and Export · 8. Mobile Notes · 9. Quick Tips · 10. Credits
Versione italiana: 1. Regole degli scacchi · 2. Interfaccia principale · 3. Pannelli e funzionalità · 4. Effetti visivi e sonori · 5. Modalità speciali · 6. Funzioni di partita · 7. Esportazione / Importazione PGN · 8. Note per dispositivi mobili · 9. Suggerimenti rapidi · 10. Crediti

Welcome to Tactical Cyber Arena, a chess experience with a cyber-themed interface and real-time tactical analysis. The game applies standard chess rules and helps players identify threats, defenses, and opportunities during play. The interface is designed for both desktop and mobile devices.
1. Chess Rules
The engine follows FIDE chess rules, including legal piece movement, captures, castling, en passant, promotion, check, checkmate, stalemate, the fifty-move rule, turn alternation, and full move history. Illegal moves that leave the king in check are not allowed.
2. Main Interface
The main area includes an 8×8 board with coordinates, legal move indicators, capture indicators, a status bar showing the current turn and game state, and a side panel that moves below the board on mobile devices.
3. Panels and Features
•	Command Terminal: starts a new game, undoes moves, rotates the board, enables tactical vision, highlights board control, displays radar information, and manages audio.
•	PGN Data Exchange: exports the current game in PGN format or imports a PGN sequence to replay a game.
•	Global Radar Status: shows board-control percentages and castling availability for each side.
•	Material Deallocation: lists captured pieces and shows the material balance.
•	Operations Log: displays the move list and allows navigation through the game history.
•	Min Threats Detected: identifies pins, skewers, forks, and other tactical patterns in the current position.
4. Visual and Audio Feedback
The interface uses animations and visual overlays to make the game state easier to read: movement trails, capture effects, check highlights, tactical lines and circles, defense indicators, notifications, and short audio cues. Audio can be disabled at any time.
5. Special Modes
•	Ctrl Board: highlights the squares controlled by the player to move.
•	Vision Mode: shows the squares attacked by a selected piece and marks direct threats.
•	Radar Mode: displays board-control percentages and castling status in the side panel.
6. Game Functions
Players can start a new game, undo moves, promote pawns, review the move history, and manage end-of-game screens. At the end of a game, the final position can be kept on screen or the system can be restarted.
7. PGN Import and Export
The game can export the current match as PGN text for use in other chess tools. It can also import PGN text, replace the current game, and replay the sequence up to the final position.
8. Mobile Notes
On smaller screens, the board adapts to the available width, the side panel moves below the board, buttons remain touch-friendly, screen rotation is supported, and visual effects are reduced where needed to preserve performance.
9. Quick Tips
•	Keep the tactical panel open to monitor pins, forks, and skewers while playing.
•	Use the move history to review key positions after a game.
•	Enable Radar Mode to compare board control and castling options.
•	Import PGN games to study tactical patterns in previously played or well-known matches.
10. Credits
Development: FIDE-compliant chess engine, tactical analysis for pins, skewers, forks and defenses, cyber-themed interface inspired by neon visuals.
Version: 4.0 — “Quantum Chess Matrix”
Technology: Pure HTML/CSS/JavaScript, with no external dependencies.
Tactical Cyber Arena combines standard chess play with a visual layer designed to support tactical reading. Use the tools available in the interface to follow the position, review key moments, and refine your decisions during the game.
TACTICAL CYBER ARENA
Manuale utente · Versione italiana
Versione 4.0 · Quantum Chess Matrix con analisi tattica in tempo reale
Benvenuto in Tactical Cyber Arena, un’esperienza di gioco degli scacchi con interfaccia a tema cyber e analisi tattica in tempo reale. Il gioco applica le regole standard degli scacchi e aiuta a individuare minacce, difese e opportunità durante la partita. L’interfaccia è ottimizzata per desktop e dispositivi mobili.
________________________________________
1. Regole degli scacchi
Il motore segue integralmente le regole FIDE:
•	Movimento dei pezzi: pedoni, cavalli, alfieri, torri, regina, re.
•	Cattura, arrocco (corto e lungo), en passant, promozione a regina/torre/alfiere/cavallo.
•	Scacco, scacco matto, stallo e patta per la regola delle 50 mosse.
•	Alternanza dei turni e cronologia completa della partita.
Non sono consentite mosse illegali che lascino il proprio re sotto scacco.
________________________________________
2. Interfaccia principale
2.1 Scacchiera
•	8×8 case con effetto neon (chiare/scure).
•	Coordinate (a-h, 1-8) sui bordi.
•	Clicca su un pezzo per selezionarlo: le case di destinazione legali vengono evidenziate con un pallino verde (✔) o un anello rosso tratteggiato (⚔) se la mossa cattura un pezzo.
•	Clicca su una casa di destinazione per eseguire la mossa.
•	Click fuori dai pezzi deseleziona.
2.2 Barra di stato
•	In alto sopra la scacchiera mostra il turno di gioco (CORE PROCESS: WHITE / BLACK).
•	In caso di scacco compare la scritta “OVERVOLTAGE – CHECK TO …”.
•	A fine partita mostra il risultato (es. “BLACK WINS”, “STALEMATE”, “DRAW”).
2.3 Pannello laterale
Contiene tutte le sezioni di controllo e analisi.
________________________________________
3. Pannelli e funzionalità
3.1 Command Terminal
Pulsanti principali:
Pulsante	Funzione
♟ Initialize Grid	Nuova partita, ripristina la scacchiera.
↺ Rollback	Annulla l’ultima mossa (si può annullare fino all’inizio).
⇅ Rotate Matrix	Ruota la scacchiera di 180° (prospettiva nera/bianca).
👁 Vision	Attiva/disattiva la Visione tattica (vedi §5.2).
🟩 Ctrl Board	Evidenzia il controllo territoriale del giocatore di turno.
📊 Radar	Mostra/nasconde il pannello Global Radar (dominio e arrocco).
🔊 Audio	Abilita/disabilita gli effetti sonori.
3.2 PGN Data Exchange
•	Export: genera la partita in formato PGN (testo) e la mostra in una finestra.
•	Import: incolla una partita in formato PGN e clicca su Import Data. La partita verrà riprodotta fino alla fine (visualizzando l’ultima posizione, anche se terminata).
Dopo l’importazione, se la partita è conclusa, puoi chiudere il banner di fine gioco con il pulsante ✖ Close senza resettare la scacchiera.
3.3 Global Radar Status
Visibile quando il pulsante 📊 Radar è attivo.
•	Domain W / B: percentuale di case controllate dai pezzi bianchi e neri.
•	Potential Castling W / B: indica se l’arrocco è ancora possibile (K side, Q side o None).
3.4 Material Deallocation
•	Mostra i pezzi catturati da ciascun colore (con icone).
•	La differenza di materiale (es. +3 se il Bianco ha mangiato un cavallo in più).
3.5 Operations Log
Elenco delle mosse in notazione algebrica.
•	Ogni mossa è un tasto cliccabile: facendo click su una mossa si salta direttamente a quella posizione nella cronologia.
•	Le frecce ◀ ▶ permettono di navigare avanti e indietro nella storia della partita.
Quando si naviga nella cronologia, la scacchiera entra in modalità storia (sfondo “flashback”). I pezzi rimangono ben distinguibili (bianchi e neri) ma sono leggermente più trasparenti per indicare che non è la posizione corrente. Per uscire dalla modalità storia e tornare alla partita, basta premere il pulsante ▶ fino alla fine, oppure cliccare su una casa vuota della scacchiera.
3.6 Min Threats Detected
Feed in tempo reale di tutte le minacce tattiche presenti nella posizione corrente:
•	PIN (inchiodatura): assoluta (se il pezzo inchiodato copre il re) o relativa.
•	LASER SKEWER (infilata): un pezzo di valore elevato è davanti a uno meno prezioso.
•	TRUE FORK (forchetta): due pezzi nemici sono attaccati contemporaneamente, con valutazione del guadagno.
•	Se non ci sono minacce, appare “Stable grid. No attack vectors.”
Ogni scheda è cliccabile e aggiorna l’overlay visivo sulla scacchiera.
________________________________________
4. Effetti visivi e sonori
•	Movimento dei pezzi: animazione fluida con effetto scia.
•	Cattura: il pezzo catturato viene rimosso con un effetto visivo.
•	Scacco: la casa del re lampeggia di rosso.
•	Segnali tattici: sulla scacchiera compaiono linee e cerchi colorati:
o	Rosa (Pin), Giallo (Skewer), Verde (Fork).
•	Visione: quando attiva e un pezzo è selezionato, appaiono linee verso tutte le case attaccate.
•	Scudi 🛡️ e rotture 💥 compaiono quando un pezzo acquisisce o perde una difesa tattica.
•	Toast di notifica in alto a destra per eventi importanti (inchiodatura, forchetta, scacco, ecc.), con dissolvenza automatica.
•	Suoni: brevi effetti sonori sintetizzati per mosse, catture, scacchi e scoperte tattiche. Possono essere disattivati con il pulsante Audio.
________________________________________
5. Modalità speciali
5.1 Ctrl Board
Quando attivo, tutte le case attaccate dai pezzi del giocatore di turno vengono illuminate con un alone (verde per il Bianco, rosa per il Nero). Utile per visualizzare il dominio spaziale.
5.2 Vision Mode
Clicca su un pezzo con Vision attiva: appaiono linee viola o rosse che mostrano tutte le case attaccate da quel pezzo. Le linee rosse indicano minacce dirette a pezzi nemici.
5.3 Radar Mode
Mostra le percentuali di controllo e lo stato degli arrocchi nel pannello laterale.
________________________________________
6. Funzioni di partita
•	Nuova partita: clic su “♟ Initialize Grid”.
•	Annulla mossa: clic su “↺ Rollback”. Funziona anche dopo la fine della partita (il banner si chiude automaticamente).
•	Promozione: quando un pedone raggiunge l’ultima traversa, si apre un popup per scegliere il pezzo (Regina, Torre, Alfiere o Cavallo).
•	Fine partita: un banner a tutto schermo mostra il risultato. Puoi riavviare (“♟ Reboot System”) o semplicemente chiudere (“✖ Close”) per restare sulla posizione finale.
________________________________________
7. Esportazione / Importazione PGN
•	Esporta: genera il testo PGN della partita in corso. Puoi copiarlo e incollarlo in altri software.
•	Importa: incolla una stringa PGN (es. 1. e4 e5 2. Nf3 Nc6 ...). Il gioco cancella la partita corrente e riproduce tutte le mosse, arrestandosi alla fine. Se il PGN contiene un risultato (1 0, 0 1, 1/2 1/2) il banner di fine partita apparirà alla fine dell’importazione.
________________________________________
8. Note per dispositivi mobili
L’interfaccia si adatta automaticamente a schermi piccoli:
•	La scacchiera occupa la larghezza disponibile (fino a 80vw).
•	Il pannello laterale si sposta sotto la scacchiera.
•	I pulsanti sono abbastanza grandi da essere toccati con il dito.
•	La rotazione dello schermo è supportata.
•	I font e gli effetti visivi sono ridotti al minimo per mantenere le prestazioni.
________________________________________
9. Suggerimenti rapidi
•	Analizza tattiche: lascia attivo il pannello “Min Threats” mentre giochi per vedere in tempo reale se stai creando forchette o inchiodature.
•	Naviga la storia: dopo una partita, clicca sulle mosse per rivedere i momenti chiave; i pezzi rimarranno visibili e potrai analizzare la posizione passata.
•	Usa il Radar per capire chi ha il controllo della scacchiera e se l’arrocco è ancora possibile.
•	Importa PGN per studiare partite famose: il motore riconoscerà tattiche e le mostrerà a video.
________________________________________
10. Crediti
Sviluppo: Motore di scacchi conforme FIDE, analisi tattica (pin, skewer, fork, difese), interfaccia cyber punk ispirata al neon.
Versione: 4.0 — “Quantum Chess Matrix”
Linguaggio: HTML/CSS/JavaScript puro, nessuna dipendenza esterna.
________________________________________
Tactical Cyber Arena combina il gioco degli scacchi con un livello visivo pensato per supportare la lettura tattica della posizione. Usa gli strumenti disponibili nell’interfaccia per seguire la partita, rivedere i momenti chiave e migliorare le tue decisioni durante il gioco.

