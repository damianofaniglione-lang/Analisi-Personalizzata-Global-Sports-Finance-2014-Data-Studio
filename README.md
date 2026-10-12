# Analisi-Personalizzata-Global-Sports-Finance-2014-Data-Studio
Analisi finanziaria interattiva sui payroll dei team sportivi e i guadagni degli atleti nel 2014, realizzata con Google Looker Studio.
## Link al Report Interattivo
[Clicca qui per esplorare la Dashboard live su Google Looker Studio](https://datastudio.google.com/reporting/a850faff-f410-49da-9183-6e20a285c847/page/HF5AG)

## Anteprima della Dashboard
![Anteprima Dashboard](Anteprima%20Progetto.png)

## Dataset Originale
Se desideri consultare i dati grezzi utilizzati per questa analisi, puoi scaricarli direttamente da qui:
[Scarica il file Global Sports Finances](Global%20Sport%20Finances.xlsx)

## Tecnologie Utilizzate e Competenze Sviluppate
- **Google Looker Studio:** Per la modellazione dati e la data visualization.
- **Data Cleaning (RegEx & String Manipulation):** Utilizzo di funzioni avanzate (`REGEXP_EXTRACT`, `REPLACE`, `CAST`) per ripulire formati stringa complessi (es. trasformazione del testo "\$105 M" in valori numerici di valuta reale).
- **GitHub:** Per il versionamento e la documentazione del progetto.

## Principali Insight estratti
- **Gestione del Budget:** Isolamento delle leghe sportive ed estrazione dei Top 10 Team per Payroll globale.
- **Modelli di Guadagno degli Atleti:** Analisi della correlazione tra stipendio sul campo (`Salary/Winnings`) e contratti pubblicitari (`Endorsements`) tramite grafici a dispersione.
- **Segmentazione:** Creazione di campi calcolati condizionali (`CASE WHEN`) per categorizzare gli atleti in fasce di mercato (*Top Earner* vs *Elite Athlete*).
