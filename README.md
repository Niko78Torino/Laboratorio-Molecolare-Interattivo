Laboratorio Molecolare Interattivo 3D
Questo progetto è un'applicazione web interattiva che simula un laboratorio di chimica virtuale, permettendo agli utenti di visualizzare, costruire e manipolare molecole in uno spazio tridimensionale. È stato sviluppato con scopi didattici per offrire un'esperienza intuitiva e visiva della struttura molecolare.

Funzionalità Principali
Visualizzazione 3D Realistica: Le molecole sono renderizzate in 3D utilizzando la libreria three.js, consentendo una chiara visualizzazione di atomi e legami.

Controlli Interattivi: Gli utenti possono ruotare, spostare e zoomare la camera per ispezionare la molecola da qualsiasi angolazione.

Molecole Predefinite: È possibile caricare molecole di base comuni (come Metano, Acqua, Benzene) da un menu a tendina per iniziare rapidamente.

Costruttore di Molecole: La funzionalità più potente del laboratorio. Gli utenti possono:

Selezionare un atomo esistente nella scena 3D.

Scegliere uno qualsiasi dei 118 elementi da una tavola periodica completa.

Aggiungere il nuovo atomo, che verrà automaticamente legato a quello selezionato.

Ottimizzazione della Geometria: Un algoritmo semplificato permette di "rilassare" la struttura della molecola, ricalcolando le posizioni degli atomi per ottenere una conformazione geometricamente più stabile e realistica.

Pannello Informativo Dinamico: Un pannello aggiorna in tempo reale la formula chimica e la massa molecolare totale della struttura visualizzata.

Interfaccia Utente Moderna: L'interfaccia è pulita, reattiva e costruita con Tailwind CSS.

Come Utilizzare il Laboratorio
Aprire il File: Apri il file laboratorio_molecolare.html in un qualsiasi browser web moderno.

Scegliere una Molecola: Usa il menu a tendina "Seleziona Molecola" nel pannello di sinistra per caricare una delle molecole preimpostate.

Esplorare la Scena:

Ruota: Clicca con il tasto sinistro del mouse e trascina.

Sposta (Pan): Clicca con il tasto destro del mouse e trascina.

Zoom: Usa la rotellina del mouse.

Costruire una Nuova Molecola:

Clicca su un atomo nella scena 3D per selezionarlo (verrà evidenziato).

Clicca su un elemento nella tavola periodica a sinistra. Un nuovo atomo di quell'elemento verrà aggiunto e legato all'atomo che avevi selezionato.

Ottimizzare la Struttura: Dopo aver aggiunto più atomi, clicca sul pulsante "Ottimizza Geometria" per vedere gli atomi riposizionarsi in una configurazione più stabile.

Resettare la Visuale: Se perdi l'orientamento, clicca su "Resetta Visuale" per riportare la camera alla sua posizione iniziale.

Dettagli Tecnici
Frontend: HTML5, CSS3, JavaScript (ES6)

Styling: Tailwind CSS

Rendering 3D: Three.js

Autore e Licenza
Autore: Nicola Nicolaci

Anno: 2025

Licenza: Copyright - Riservato per uso didattico.
