# Presto Shop

Presto Shop è un'applicazione web sviluppata con Laravel e Livewire, che permette agli utenti di acquistare e vendere articoli usati. Dispone di funzionalità avanzate come gestione degli annunci, revisione da parte di moderatori, supporto multilingua e analisi delle immagini con Google AI Vision.

## Caratteristiche Principali
- *E-commerce*: Facilita l'acquisto e la vendita di articoli usati.
- *Funzionalità CRUD*: Gestione completa di annunci, utenti e categorie.
- *Pagina Revisori*: Per l'approvazione o il rifiuto degli annunci pubblicati.
- *Google AI Vision*: Analizza e classifica le immagini caricate.
- *Login e Registrazione*: Sistema di autenticazione sicuro tramite Laravel Fortify.
- *Modulo Annunci Avanzato*: Form dedicato per la pubblicazione degli annunci.
- *Supporto Multilingua*: Traduzione completa dell'interfaccia.

## Tecnologie Utilizzate
### Backend:
- PHP 8.3
- Laravel 11
- Livewire
- Laravel Fortify

### Frontend:
- Bootstrap 5.3
- Bootstrap Icons

### AI:
- Google AI Vision

### Gestione Pacchetti:
- Node.js con npm

### Requisiti di Sistema
- *PHP*: >= 8.3
- *Composer*: Installato nel sistema
- *Node.js*: >= 16.x
- *Database*: MySQL

## Installazione e Configurazione
Segui questi passaggi per clonare e configurare il progetto:

1. Clona la repository:
   sh
   git clone 
   
2. Installa le dipendenze PHP:
   sh
   composer install
   
3. Crea il file .env e configura il database:
   sh
   cp .env.example .env
   
4. Genera la chiave dell'applicazione:
   sh
   php artisan key:generate
   
5. Esegui le migrazioni per creare il database:
   sh
   php artisan migrate
   
6. Installa le dipendenze JavaScript:
   sh
   npm install
   
7. Compila i file CSS e JavaScript:
   sh
   npm run dev
   
8. Avvia il server di sviluppo:
   sh
   php artisan serve
   
9. Avvia i processi in background per i job della coda:
   sh
   php artisan queue:work
   

## Pacchetti Utilizzati
- google/cloud-vision ^1.10
- laravel/fortify ^1.25
- laravel/framework ^11.31
- laravel/scout ^10.11
- laravel/tinker ^2.9
- livewire/livewire ^3.5
- outhebox/blade-flags ^1.5
- spatie/image ^3.7
- teamtnt/laravel-scout-tntsearch-driver ^14.0

## Utilizzo dell'Applicazione
### Homepage:
- Visualizzazione degli annunci più recenti.

### Login e Registrazione:
- Creazione di un account e accesso per gestire gli annunci.

### Pubblicazione Annuncio:
- Creazione di un nuovo annuncio tramite il modulo dedicato.

### Sezione Revisori:
- Gli amministratori possono approvare o rifiutare gli annunci inviati dagli utenti.

## Funzionalità per Sviluppatori
- *Gestione CRUD*: Possibilità di aggiungere, modificare ed eliminare annunci, utenti e categorie.
- *Integrazione con Google AI Vision*: Analisi delle immagini per garantire conformità e qualità.
- *Sistema Multilingua*: Traduzione completa dell'interfaccia.

## Licenza
Questo progetto è rilasciato sotto licenza *MIT*. Consulta il file LICENSE per maggiori dettagli.

Grazie per aver scelto *Presto Shop*! Per domande o suggerimenti, non esitare a contattarmi.
