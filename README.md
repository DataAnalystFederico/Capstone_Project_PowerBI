# Olist Store BI Analysis

## Descrizione del Progetto
Questo progetto analizza i dati di Olist Store, una piattaforma di e-commerce brasiliana, per fornire un report di Business Intelligence (BI) dettagliato e interattivo. 

Il dataset contiene informazioni sugli ordini dal 2016 al 2018 e consente di analizzare metriche fondamentali come il numero di ordini, i ricavi e le valutazioni dei clienti. L'obiettivo del progetto è sviluppare una dashboard interattiva in Power BI per supportare decisioni aziendali strategiche.

### Obiettivi Principali
1. **Andamento degli Ordini nel Tempo:**
   - Analisi del conteggio degli ordini mese per mese, con confronto rispetto all'anno precedente.
   - Filtraggio degli ordini in base al loro status (ad es. consegnati, cancellati, ecc.).

2. **Andamento dei Ricavi nel Tempo:**
   - Calcolo dei ricavi totali mese per mese (inclusi costi di spedizione) con variazione percentuale rispetto all'anno precedente.
   - Filtraggio basato sullo status dell'ordine.

3. **Distribuzione del Rating:**
   - Analisi delle valutazioni dei clienti (review score) per comprendere la qualità del servizio.

### Analisi Aggiuntive
- Distribuzione geografica degli ordini.
- Analisi per prodotto e categoria.

### Caratteristiche Tecniche
- **Riduzione e Ristrutturazione Dati:** Implementazione di uno schema a stella per ottimizzare l'analisi.
- **Dimensione Calendario:** Creazione di una dimensione temporale per supportare analisi temporali.
- **UX Migliorata:** Utilizzo di filtri, drill-through e un layout intuitivo per migliorare l'esperienza utente.

---

## Contenuto del Repository
- **Dashboard PDF:** [La dashboard finale in formato PDF](./Dashboard - Olist(E-commerce).pdf) per una rapida consultazione.
- **File di Sviluppo Power BI:** Il file .pbix per esplorare e modificare la dashboard al link: [Google Drive - Power BI File](https://drive.google.com/drive/folders/1_PCy1Pd8et0mV0F2cp6sNJh2BT6RPEMX?hl=it).
- **Dataset:** [Scarica i file CSV utilizzati per l'analisi](https://drive.google.com/drive/folders/1_PCy1Pd8et0mV0F2cp6sNJh2BT6RPEMX?hl=it).

---

## Dataset Utilizzati
Le tabelle seguenti sono state integrate per costruire l'analisi:
- **olist_orders_dataset:** Dati sugli ordini.
- **olist_order_items_dataset:** Dati sugli articoli venduti.
- **olist_products_dataset:** Dati sui prodotti.
- **olist_order_reviews_dataset:** Dati sulle recensioni dei clienti.
- **olist_customers_dataset:** Dati sui clienti.

---

## Requisiti
Per visualizzare o modificare la dashboard, è necessario:
- Microsoft Power BI Desktop
- I file CSV forniti nel link del repository

---

## Come Iniziare
1. Scarica i file CSV dai link forniti.
2. Apri il file .pbix con Power BI Desktop.
3. Esplora la dashboard interattiva o personalizzala per le tue esigenze.
