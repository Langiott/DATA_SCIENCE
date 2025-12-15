# Data Science
![we](/we.webp)
## I migliori siti per imparare il Machine Learning

Di seguito una selezione di cinque risorse online utili per apprendere e approfondire il Machine Learning, combinando teoria e pratica.

- **Towards Data Science**  
  Sezione di Medium dedicata a Machine Learning e Data Science. Offre articoli che spaziano da concetti teorici avanzati a tutorial pratici con esempi e notebook.

- **Analytics Vidhya**  
  Piattaforma completa che propone articoli tecnici e corsi strutturati, gratuiti e a pagamento, con un forte focus sull’implementazione in Python.

- **Data Science Central**  
  Portale storico del settore, con contenuti orientati principalmente a statistica e Data Science, utile per approfondimenti teorici.

- **KDnuggets**  
  Sito di riferimento per Machine Learning, AI e Data Science, noto per l’aggiornamento costante su news, studi scientifici e trend di settore.

- **Kaggle**  
  Oltre alle competizioni, offre corsi, tutorial e notebook condivisi dalla community, permettendo di apprendere tecniche pratiche osservando il lavoro di altri data scientist.

---

## Strumenti di Business Intelligence

- **Qlik**  
  Piattaforma di Business Intelligence per l’estrazione, trasformazione e visualizzazione dei dati, con dashboard interattive e modello associativo.

- **Table (Tabelle)**  
  Rappresentazione strutturata dei dati in righe e colonne, tipica di fogli di calcolo e database, usata come base per l’analisi quantitativa.

- **Power BI**  
  Strumento di Business Intelligence di Microsoft per la creazione di report e dashboard interattivi, ampiamente utilizzato in ambito aziendale.

---

# 🎮 Video Games Data Analysis Project

Analisi esplorativa e visuale dei dati relativi al mercato dei videogiochi, con particolare attenzione a **generi**, **vendite per piattaforma** e **distribuzione geografica**, utilizzando strumenti di Business Intelligence come **Qlik Sense**, **Tableau** e **Power BI**.

---

## 📌 Obiettivo del progetto

L’obiettivo del progetto è analizzare l’evoluzione storica del mercato videoludico dal 1980 al 2016, individuando:
- i **generi di videogiochi più diffusi**,
- le **console più vendute nel tempo**,
- la **distribuzione geografica delle vendite**, con un focus specifico sull’Europa.

L’analisi mira a evidenziare trend di mercato, differenze regionali e relazioni tra piattaforme, generi e periodi storici.

---

## 📂 Dataset utilizzati

### 1️⃣ Video Games Sales Dataset 2022 – Updated Extra Features
**Fonte:** Kaggle  

Questo dataset contiene informazioni sulle vendite di videogiochi pubblicati dal 1980 al 2016, con suddivisione geografica.

**Principali attributi:**
- `Name` – Titolo del gioco  
- `Platform` – Piattaforma di pubblicazione  
- `Year_of_Release` – Anno di uscita  
- `Genre` – Genere del gioco  
- `Publisher` – Editore  
- `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales` – Vendite per area geografica  
- `Global_Sales` – Vendite globali complessive  

Il dataset è stato **trasformato tramite pivoting** per consentire analisi temporali e geografiche più efficaci, in particolare per l’uso in Tableau.

---

### 2️⃣ Backloggd Dataset
**Fonte:** Backloggd / Kaggle  

Dataset più ampio e orientato al comportamento degli utenti, contenente:
- informazioni su **plays**, **playing**, **wishlist** e **backlog**
- dati su **generi**, **piattaforme** e **sviluppatori**
- milioni di sessioni di gioco e valutazioni

Questo dataset è stato utilizzato soprattutto per analisi di **engagement** e **distribuzione dei generi**.

---

## 📊 Visualizzazioni principali

### 🟠 1. Distribuzione dei generi di videogiochi
**(Grafico a torta)**  

Rappresenta la percentuale dei giochi suddivisi per genere.

**Insight principali:**
- I generi più rappresentati sono **MOBA**, **Turn-Based Strategy** e **Brawler**.
- I generi con meno titoli (es. Visual Novel, Music, Quiz) rappresentano nicchie specifiche.
- Il numero di giochi per genere non coincide necessariamente con il volume di vendite.

---

### 🟢 2. Vendite Wii in Europa nel 2008
**(Mappa geografica europea)**  

Visualizza una **stima delle vendite della console Nintendo Wii in Europa** nel 2008, anno di massimo picco del mercato console.

**Insight principali:**
- I principali mercati europei risultano **Germania, Regno Unito, Francia, Italia e Spagna**.
- L’Europa rappresenta un’area strategica per Nintendo nel periodo di massimo successo della Wii.
- Le vendite sono state disaggregate per paese a partire dal valore complessivo europeo.

---

### 🔵 3. Andamento delle vendite delle console nel tempo
**(Grafico a linee multi-piattaforma)**  

Mostra l’evoluzione delle vendite globali delle principali console dal 1980 al 2016.

**Insight principali:**
- Crescita progressiva fino al **picco tra il 2007 e il 2009**.
- **PlayStation 2** risulta la console più venduta e longeva.
- Dopo il 2010 si osserva un calo delle vendite, dovuto a saturazione del mercato e transizione verso digitale e mobile gaming.
