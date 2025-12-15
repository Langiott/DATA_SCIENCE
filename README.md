# Data Science
![we](/we.webp)

Vediamo quindi senza ulteriori indugi quelli che sono i 5 migliori siti web per imparare il Machine Learning:

-TOWARDS DATA SCIENCE
Il primo sito che consigliamo per imparare il Machine Learning è sicuramente Towards Data Science.Sezione di Medium dedicata proprio a questo settore, è possibile trovare sia argomenti di tipo teorico sia pratico, con tutorial e notebook. La sua principale virtù sta nel fatto di gestire argomenti sia ad alto ed altissimo livello, sia roba molto pratica e specifica.

-ANALYTICS VIDHYA
Rispetto al precedente, questo sito ha anche una serie di interessantissimi corsi, sia gratuiti sia a pagamento.Sul sito, che trovi a questo link, è presente un importantissimo numero di articoli del loro blog con un forte accento sull’implementazione di algoritmi e pipeline in Python.

-DATA SCIENCE CENTRAL
Questo è stato uno dei primi siti che io abbia mai navigato nel settore del Machine Learning e della Data Science. E’ possibile infatti navigare tra le sue moltissime sezioni per trovare sicuramente qualche spunto particolarmente interessante. Rispetto ai primi due siti web menzionati, ha un focus più specifico sulla Statistica e sulla Data Science.

-KDNUGGETS
Immenso sito web con articoli che spaziano dal Machine Learning alla Data Science, dall’AI alla Statistica.
ùMolto simile al sopracitato Data Science Central, KDnuggets è stato fondato da Gregory Piatetsky-Shapiro, un vero e proprio guru della Data Science (no. 1 in LinkedIn Top Voices 2018: Data Science & Analytics).Ciò che però differenzia questo sito è la sua capacità di stare sempre sul pezzo e di mostrare una grande moltitudine di news, scoperte e studi scientifici sui temi d’interesse. Una dedizione davvero incredibile da parte dei curatori permette quindi di rimanere sempre aggiornati sui temi del Machine Learning, consentendo una formazione continua.

-KAGGLE
Naturalmente, non potevamo non menziona Kaggle, sito web di cui abbiamo già parlato qui.Kaggle infatti oltre alle sue fantomatiche competizioni ha tutta una serie di pagine di blog e corsi di approfondimenti e tutorial. E’ possibile osservare i kernel degli altri concorrenti e seguire i Master nelle loro analisi per andare a conoscere (ed eventualmente rubare) tutti i trucchi del mestiere.

# Qlik:
Qlik è una piattaforma di analisi dei dati che consente agli utenti di estrarre, trasformare e visualizzare dati da diverse fonti. Offre strumenti avanzati di analisi e dashboard interattivi per aiutare le aziende a prendere decisioni basate sui dati.

# Table:
"Table" (tavola) in genere si riferisce a una rappresentazione tabellare dei dati. Questo può includere fogli di calcolo, database o qualsiasi altro formato in cui i dati sono organizzati in righe e colonne.

# Power BI:
Power BI è un'applicazione di business intelligence sviluppata da Microsoft. Consente agli utenti di connettersi a diverse fonti di dati, creare report interattivi e dashboard, e condividere facilmente queste analisi con altre persone. Power BI è ampiamente utilizzato per l'analisi e la visualizzazione dei dati aziendali.


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
