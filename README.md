# DPC-Aggregati-Strutturali-ITC-NordOvest
## Repository degli aggregati strutturali italiani area ITC Nord-Ovest



[![GitHub license](https://img.shields.io/badge/License-Creative%20Commons%20Attribution%204.0%20International-blue)](https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITC-NordOvest/blob/master/LICENSE)
[![GitHub commit](https://img.shields.io/github/last-commit/pcm-dpc/DPC-Aggregati-Strutturali-ITC-NordOvest)](https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITC-NordOvest/commits/master)

## Avvisi
Repository in fase di caricamento

## Sommario
[Struttura del Repository](#Struttura-del-repository)

[DESCRIZIONE DEI DATI ORIGINALI](#DESCRIZIONE-DEI-DATI-ORIGINALI)

[Fonti dei dati originali](#Fonti-dei-dati-originali)

[Licenza dei dati originali](#Licenza-dei-dati-originali)

[Sistemi di riferimento degli dati originali](#Sistemi-di-riferimento-dei-dati-originali)

[DESCRIZIONE DEGLI AGGREGATI STRUTTURALI](#DESCRIZIONE-DEGLI-AGGREGATI-STRUTTURALI)

[Formato degli Aggregati Strutturali dati](#Formato-degli-Aggregati-Strutturali)

[Sistema di riferimento degli Aggregati Strutturali](#Sistema-di-riferimento-degli-Aggregati-Strutturali)

[Procedura per la generazione degli Aggregati Strutturali](#Procedura-per-la-generazione-degli-Aggregati-Strutturali)

[Verifiche di qualità degli Aggregati Strutturali](#Verifiche-di-qualità-degli-Aggregati-Strutturali)

[Occupazione di memoria Regionale](#Occupazione-di-memoria-Regionale)

[Aggiornamento dei dati](#Aggiornamento-dei-dati)

[Attori coinvolti](#Attori-coinvolti)

[Ulteriori approfondimenti](#Ulteriori-approfondimenti)

[Licenza](#Licenza)


## Struttura del repository
La serie di Dataset è organizzata in 5 repository corrispondenti alla classe 1 della Nomenclatura delle Unità territoriali statistiche (NUTS), che identifica la ripartizione del territorio dell'Unione europea a fini statistici. 
La classe 1 (NUTS-1) nel caso dell’Italia, ai fini statistici, rappresenta la divisione ufficiale delle macroregioni e consta di cinque gruppi: Nord-ovest, Nord-est, Centro, Sud e Isole. 
A ciascun gruppo è associato un proprio identificativo composto da una sequenza di tre lettere di cui le prime due corrispondono alla sigla dello Stato Italiano (IT).

<img src="https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITI-Centro/blob/master/RipartizioniISTAT.PNG" />

```
DPC-Aggregati-Strutturali-ITC-NordOvest/
│
├── NordOvest/
│   ├── Liguria/
│   │   ├── Genova/
│   │   │   ├── shapefile comuni
│   │   ├── Imperia/
│   │   │   ├── shapefile comuni
│   │   ├── LaSpezia/
│   │   │   ├── shapefile comuni
│   │   ├── Savona/
│   │   │   ├── shapefile comuni
│   ├── Lombardia/
│   │   ├── Bergamo/
│   │   │   ├── shapefile comuni
│   │   ├── Brescia/
│   │   │   ├── shapefile comuni
│   │   ├── Como/
│   │   │   ├── shapefile comuni
│   │   ├── Cremona/
│   │   │   ├── shapefile comuni
│   │   ├── Lecco/
│   │   │   ├── shapefile comuni
│   │   ├── Lodi/
│   │   │   ├── shapefile comuni
│   │   ├── Mantova/
│   │   │   ├── shapefile comuni
│   │   ├── Milano/
│   │   │   ├── shapefile comuni
│   │   ├── MonzaBrianza/
│   │   │   ├── shapefile comuni
│   │   ├── Pavia/
│   │   │   ├── shapefile comuni
│   │   ├── Sondrio/
│   │   │   ├── shapefile comuni
│   │   ├── Varese/
│   │   │   ├── shapefile comuni
│   ├── Piemonte/
│   │   ├── Alessandria/
│   │   │   ├── shapefile comuni
│   │   ├── Asti/
│   │   │   ├── shapefile comuni
│   │   ├── Biella/
│   │   │   ├── shapefile comuni
│   │   ├── Cuneo/
│   │   │   ├── shapefile comuni
│   │   ├── Novara/
│   │   │   ├── shapefile comuni
│   │   ├── Torino/
│   │   │   ├── shapefile comuni
│   │   ├── VerbanoCusioOssola/
│   │   │   ├── shapefile comuni
│   │   ├── Vercelli/
│   │   │   ├── shapefile comuni
│   ├── ValleAosta/
│   │   ├── Aosta/
│   │   │   ├── shapefile comuni
```

## DESCRIZIONE DEI DATI ORIGINALI
La serie di dataset degli Aggregati Strutturali rappresenta il risultato di una elaborazione realizzata. (in prevalenza) a partire dalla classe dell’edificato dei database geotopografici regionali. I poligoni derivati sono stati, inoltre, ripartiti sulla base dei confini delle unità amministrative ISTAT aggiornati al 2021. A differenza dei dati originali relativi all’edificato (o dei fabbricati catastali, in taluni casi), eterogenei per le loro provenienze e modalità di realizzazione - anche dal punto di vista temporale -, il prodotto finale derivato garantisce una armonizzazione a livello nazionale delle informazioni e delle elaborazioni effettuate  e dei contenuti generati. E' tuttavia necessario esaminare preliminarmente e in dettaglio alcune caratteristiche che descrivono la complessità e specificità dei dati originali utilizzati.

## Fonti dei dati originali

**LIGURIA**

**Disponibili nel Web:** https://www.regione.liguria.it/open-data/item/7099-carta-tecnica-regionale-1-5000-dal-2007-ii-edizione-3d-db-topografico.html 

**Tipo:** CTRN

**Edizione:** 2007/2013

**Scala:** 5000

**LOMBARDIA**

**Disponibili nel Web:** La Regione Lombardia aveva autonomamente già realizzato gli aggregati strutturali (di concerto con il Dipartimento della protezione civile) nell’ambito delle attività collegate alla realizzazione dell’Allegato n.2 del Programma nazionale di soccorso per il rischio sismico. I dati sono stati dunque trasmessi nel marzo del 2019, contestualmente all’intesa siglata con il Dipartimento. Successivamente, il 21 settembre 2020 la Regione ha comunicato di aver pubblicato il completamento di 262 comuni, fatta eccezione di alcuni comuni comaschi. Il Dipartimento della protezione civile, di intesa con la Regione Lombardia, ha pertanto generato nuovamente per l’intero territorio regionale gli aggregati in sostituzione dei precedenti. Nel mese di aprile 2021 sono stati anche forniti e integrati i dati completi della provincia di Como.

**Tipo:** DBT

**Edizione:** 2020/2021

**Scala:** 5000

**PIEMONTE**

**Disponibili nel Web:** La Regione Piemonte dispone di una propria Base Dati Territoriale di Riferimento degli Enti piemontesi (https://www.geoportale.piemonte.it/cms/progetti/progetto-mosaicatura-catastale ) e aveva autonomamente già valorizzato nella classe Edifici del DBT il campo IDAG relativo all’identificazione degli aggregati strutturali e li ha trasmessi a seguito di richiesta.

**Tipo:** https://www.geoportale.piemonte.it/cms/bdtre/bdtre-2. Questa base dati si compone di un “dato riposizionato [che] è costituito dalle geometrie catastali scaricate attraverso il Sistema di Interscambio (SigmaTer Piemonte) e trattate applicando parametri di shifting e deformazione per migliorarne la georeferenziazione rispetto agli Originali di Impianto e ad altri elementi di riferimento.”. Nel marzo 2021 è stata pubblicato l’ultimo aggiornamento https://www.geoportale.piemonte.it/cms/archivio-news/102-rilasciata-l-edizione-2021-della-bdtre-con-nuova-struttura-e-nuove-modalita-di-fruizione?fbclid=IwAR3Lki5z6BcT_jWnlkQSYFGv-yQR0cQDO5DMj9LfDpuVHnTDTZEAticyW0k .

**Edizione:** 2021

**Scala:** 2000/5000

**VALLE D'AOSTA**

**Disponibili nel Web:** https://mappe.partout.it/pub/geonavitg/geodownload.asp?carta=CTR

**Tipo:** CTRN

**Edizione:** 2005

**Scala:** 5000

## Licenza dei dati originali

**LIGURIA**

**Licenza dataset originale:** CC BY

**Autorizzazione specifica:** NO

**Attribuzione richiesta:** Regione Liguria

**LOMBARDIA**

**Licenza dataset originale:** IODL 2.0

**Autorizzazione specifica:** NO

**Attribuzione richiesta:** Regione Lombardia

**PIEMONTE**

**Licenza dataset originale:** CC BY 4.0

**Autorizzazione specifica:** NO

**Attribuzione richiesta:** Regione Piemonte

**VALLE D'AOSTA**

**Licenza dataset originale:** CC 0 1.0

**Autorizzazione specifica:** NO

**Attribuzione richiesta:** Regione Valle d’Aosta

## Sistemi di riferimento dei dati originali

**LIGURIA**

**Sistema Riferimento:** GCS_ETRS_1989

**EPSG:** 4258

**LOMBARDIA**

**Sistema Riferimento:** WGS_1984_UTM_Zone_32N

**EPSG:** 32632

**PIEMONTE**

**Sistema Riferimento:** WGS_1984_UTM_Zone_32N

**EPSG:** 32632

**VALLE D'AOSTA**

**Sistema Riferimento:** ED_1950 UTM Zone 32 N

**EPSG:** 23032

## DESCRIZIONE DEGLI AGGREGATI STRUTTURALI
In questa sezione viene descritta in maggior dettaglio la serie dei dataset degli Aggregati Strutturali che rappresentano il risultato dell'elaborazione dei dati originali precedentemente descritti.

## Formato degli Aggregati Strutturali
Il formato dei dati è shape. Ogni shape è formato da 4 file con le seguenti estensioni: .dbf, .prj, .shp, .shx.

La struttura dei file è la seguente:

| Nome campo                  | Descrizione                       | Formato                            | Esempio                            |
|-----------------------------|-----------------------------------|----------------------------------------|----------------------------------------|
| **IDAG**                        | Codice univoco dell’Aggregato Strutturale | 2 cifre: codice ISTAT Regione; 3 cifre: codice ISTAT Provincia; 3 cifre: codice ISTAT Comune; 10 cifre numero progressivo nel Comune; 2 cifre ulteriore identificativo (Manuale per la compilazione della Scheda AeDES http://www.protezionecivile.gov.it/documents/20182/0/2_LRManualeAedes_31_ottobre_GU_.pdf/8b4e4207-a767-4579-9971-d4c714a5fd4c - pagina 22) |07010013000000069200| 
| **Label**                       | ID Sequenziale nell’ambito del Comune. | Numero progressivo di identificazione dell’aggregato strutturale all’interno del Comune (utile per la rappresentazione in mappa). Questo ulteriore identificativo (in genere pari a 00, viene utilizzato in casi particolari, come quando è necessario ripartire un aggregato – inizialmente definito come un singolo poligono – in base alla realtà osservata dalla squadra durante il sopralluogo in due o più aggregati (Ad esempio, l’aggregato 08 036 022 0000000347 00 suddiviso in due genera i codici:08 036 022 0000000347 01 e 08 036 022 0000000347 02). |692|
| **Comune**              | Nome ISTAT del Comune.| Denominazione unità amministrative territoriali comunali ISTAT. | Castiglione Cavarese |

## Sistema di riferimento degli Aggregati Strutturali

Il sistema di riferimento ufficiale per l’Italia è il sistema ETRF2000 (all’epoca in cui venne definito 2008.0) ed è un obbligo per le Pubbliche Amministrazioni adottarlo in base a quanto stabilito dal DM 10 novembre 2011 “Adozione del Sistema di riferimento geodetico nazionale” (https://www.gazzettaufficiale.it/eli/id/2012/02/27/12A01799/sg).

Per facilitare il corretto utilizzo dei sistemi di riferimento all’interno dei software GIS, l’Istituto Geografico Militare (IGM) ha pubblicato una apposita Nota (https://www.igmi.org/++theme++igm/pdf/nuova_nota_EPSG.pdf), nella quale – in particolare – viene consigliato l’uso dei sistemi proiettati dell’RDN2008. 
Nel caso della Carta Nazionale degli Aggregati Strutturali pertanto è stato adottato il sistema proiettato RDN2008 / Italy zone (E-N) (EPSG7794).

Per facilitare e standardizzare le procedure di conversione tra i sistemi di riferimenti, infine, l’IGM ha reso disponibili (https://www.igmi.org/++theme++igm/pdf/nuovi_PRJ.zip) i file .prj da associare ai file cartografici e il Comitato Permanente Sistemi Geografici (CPSG) del Centro Interregionale per i Sistemi Informatici Geografici e Statistici (CISIS) ha messo a disposizione di tutti gli utenti il Programma ConveRgo (Il software (realizzato dall’Ing. V. Cima e disponibile in https://www.cisis.it/?page_id=3214 ) consente di eseguire le trasformazioni di coordinate fra i vari sistemi di riferimento in cui sono espressi i dati geografici (ROMA40, ED50, ETRS89 nelle due realizzazioni ETRF89 e ETRF2000), considerando anche i rispettivi sistemi cartografici (Gauss-Boaga, UTM-ED50, UTM-ETRF89 e UTM-ETRF2000).).

Pertanto, utilizzando il software ConveRgo e adottando il ,prj corrispondente al sistema prima nominato RDN2008 / Italy zone (E-N), ovvero l’EPSG 7794, sono stati trasformati tutti i dati dei singoli file regionali dai loro sistemi di riferimento originali in quello di destinazione sopraindicato.

## Procedura per la generazione degli Aggregati Strutturali

**Fase 1:** _Estrazione e selezione dei dati_

Ove disponibili, vengono scaricate le feature delle classi del DBT “Edifici”, “Edifici minori” e “Manufatti industriali”. Nell’ambito delle tipologie previste dalle specifiche dei DBT (https://www.cisis.it/wp-content/uploads/2020/10/Specifiche_DBGT_v2.0-1.pdf) vengono selezione in particolare la maggior parte delle feature previste, con l’esclusione di una piccola parte di oggetti ritenuti non di interesse ai fini dei sopralluoghi di rilievo del danno ai fini della valutazione di agibilità. Questa riselezione riguarda in prevalenza la classe degli edifici minori e dei manufatti industriali (ad es. sono esclusi, tombe, edicole funerarie, garage, attrezzature turistiche, tendoni pressurizzati tra le tipologie di edifici minori e serbatoi interrati, pale eoliche, pannelli fotovoltaici e torri di raffreddamento tra le tipologie di manufatti industriali).

**Fase 2:** _Riferimento alle Unità amministrative territoriali ISTAT_

Secondo il Manuale per la compilazione della Scheda AeDES (http://www.protezionecivile.gov.it/documents/20182/0/2_LRManualeAedes_31_ottobre_GU_.pdf/8b4e4207-a767-4579-9971-d4c714a5fd4c - pagina 22) gli aggregati strutturali devono essere identificati principalmente con riferimento ai codici ISTAT delle Regioni, Province e Comuni. Pertanto nell’attribuzione del codice IDAG e nella selezione delle relative feature sono stati utilizzati i dati delle Unità Amministrative Territoriali ISTAT con aggiornamento 2021 (https://www.istat.it/it/archivio/222527). Nell’operazione di selezione sono state incluse in ciascun comune le feature che avessero il proprio centroide all’interno del relativo poligono ISTAT.

**Fase 3:** _Elaborazione dei dati a livello comunale_

L’elaborazione principale avviene per tutti i comuni all’interno di ciascuna provincia e utilizza alcuni tool di geoprocessing resi disponibili dal software ArcGIS di ESRI, che è stato appunto utilizzato per le elaborazioni.
Ciascun poligono viene inizialmente convertito in line derivate dai segmenti che costituiscono i contorni dei medesimi poligoni tenendo conto se ciascun segmento è condiviso o meno con un poligono confinante (vedi figura: Fonte ESRI Inc.).

<img src="https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITI-Centro/blob/master/PolygonNeighbors.png" />

I segmenti che riguardano poligoni adiacenti vengono successivamente selezionati e i poligoni a cui essi appartengono sono uniti secondo il criterio di prevalenza del poligono con area maggiore e bordo comune più lungo.

**Fase 4:** _Memorizzazione dei risultati_

Ai nuovi poligoni generati vengono assegnati dei nuovi attributi secondo lo schema adottato (in particolare il codice IDAG) e vengono memorizzati in formato shapefile con un nome corrispondente al nome del comune ISTAT a cui si riferiscono. I nomi dei comuni per diventare nome di file vengono normalizzati rispetto ad alcune caratteristiche testuali che possono generare conflitti (ad es. spazi, accenti, apostrofi).
Tutti i dati generati durante le varie fasi dell’elaborazione sono conservati in appositi file in formato File Geodatabase ESRI. Anche i file originali sono conservati nei formati con i quali sono stati trasmessi al DPC.

**Fase 5:** _Elaborazione dei dati a livello regionale_

Per risolvere eventuali incongruenze generatesi ai bordi di comuni adiacenti, tutti i file comunali vengono successivamente uniti a livello provinciale e, infine, regionale e sottoposti alla medesima procedura illustrata in precedenza. In tal modo potranno essere ulteriormente accorpati – ove necessario – ulteriori poligoni adiacenti posti ai confini dei comuni e rimasti separati. L’aggregazione a livello regionale risulta infine propedeutica all’effettuazione dei controlli di qualità.

## Verifiche di qualità degli Aggregati Strutturali

**Fase 1:** _Verifica a livello comunale_
-	Controllo completezza dei dati
	
-	Controllo conformità allo schema dati
	
-	Verifica IDAG duplicati. Si evidenzia il caso della Regione Piemonte, che è l’unica regione per la quale non sono stati calcolati i nuovi valori di IDAG in quanto la regione li aveva precedentemente calcolati attribuendoli alla classe degli Edifici del BDTRE. Questo ha comportato, nella suddivisione nelle unità amministrative istata, anche delle discrepanze tra l comune ISTAT e il comune dal quale è stato ricavato il codice IDAG. In questa regione sono stati verificati anche gli UUID degli edifici, che in taluni casi sono risultati duplicati.

-	Verifica correttezza IDAG

**Fase 2:** _Verifica a livello regionale_

-	Effettuazione analisi di prossimità sui file regionali (viene mantenuto il campo IDAG)

-	Ricalcolo dei codici ProCom dei comuni adiacenti per controllo dei poligoni adiacenti ma appartenenti a comuni diversi

-	Join con della tabella generata dall’analisi di prossimità con il file regionale e analisi dei poligoni interessati

-	Verifica dei casi in cui è stata individuata sovrapposizione e successiva eliminazione di feature duplicate

-	Verifica dei casi con segmenti adiacenti ed eventuale unione con editing manuale

-	Verifica dei casi di vertici adiacenti. Si considerano solo i casi di 2 o più vertici coincidenti perché possono evidenziare adiacenze complesse. Questi casi, ove riscontrati, sono corretti da editing manuale

## Occupazione di memoria Regionale

**LIGURIA**

**Size (Mb):** 153

**Numero delle features:** 312561

**LOMBARDIA**

**Size (Mb):** 1400

**Numero delle features:** 2120407

**PIEMONTE**

**Size (Mb):** 404

**Numero delle features:** 1430851

**VALLE D'AOSTA**

**Size (Mb):* *22,9

**Numero delle features:** 67814

## Aggiornamento dei dati
Non pianificato

## Attori coinvolti
Attività istituzionale realizzata in collaborazione tra il Servizio Sistemi Informativi e di comunicazione dell’Ufficio Risorse umane e strumentali e servizi generali di funzionamento (RUS) e i Servizi Attività di rilievo del danno e misure provvisionali e Supporto agli interventi strutturali e gestioni rientrate in ordinario, dell’Ufficio Attività per il superamento dell’emergenza e il supporto agli interventi strutturali (POST), entrambi appartenenti al Dipartimento della protezione civile della Presidenza del Consiglio dei Ministri.

**A cura di:**

Pierluigi Cara

**Revisione della documentazione a cura di:**

Maria Giovanna Martini, Cosmo Mercuri, Simona Papa, Filomena Papa, Angelo Giuseppe Pizza e Carmelo Vairo.

**Referenti regionali (per il tramite della “Commissione speciale Protezione civile” della Conferenza delle Regioni e delle Province autonome):**

_Abruzzo:_ Raffaella Molinari; _Basilicata:_ Alfredo Marino; _Calabria:_ Antonio Morabito; _Campania:_ Massimiliano Rauci; _Emilia-Romagna:_ Fiorella Galluccio; _Friuli Venezia Giulia:_ Fulvio Nodari; _Lazio:_ Adelaide Sericola; _Liguria:_ Mariano Strippoli; _Lombardia:_ Antonella Belloni; _Marche:_ Piepaolo Tiberi; _Molise:_ Diego Antonecchia; _Piemonte:_ Erika Ceriana Mayneri; _Puglia:_ Pasquale Cafaro; _Sardegna:_ Antonio Usai; _Sicilia:_ Antonio Torrisi; _Toscana:_ Massimo Baglione; _Umbria:_ Michele Bellezza; _Valle d’Aosta:_ Gianfranco Maccaferri; _Veneto:_ Umberto Trivelloni; _Provincia Autonoma di Bolzano:_ Diego Mantovani; _Provincia Autonoma di Trento:_ Mauro Zambotto.

**Referenti CISIS:**

Umberto Trivelloni, Gian Bartolomeo Siletto e Claudio Mazzi.

**Ringraziamenti:**

Flavio Celestino Ferrante e Maurizio Ambrosanio (Agenzia delle Entrate - Direzione Centrale Servizi Catastali, Cartografici e di Pubblicità Immobiliare); Mirco Sturari (Regione Marche); Laura Garbati (Consulente CISIS); Stefano Olivucci (Regione Emilia-Romagna); Stefano Campus (Regione Piemonte); Antonella Cuccurullo (Regione Lombardia); David Colmano (P.A. di Bolzano); Maria Basi (Regione Abruzzo).

## Ulteriori approfondimenti

[Relazione tecnica finale](https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITI-Centro/blob/master/CartografiaNazionaleAggregatiStrutturali_Finale.pdf)

## Licenza
Il titolare della serie di dataset degli Aggregati Strutturali è la Presidenza del Consiglio dei Ministri - Dipartimento della protezione civile e ad esso va riferita la citazione di attribuzione principale. Nelle citazioni vanno altresì riportate le attribuzioni riportate nella sezione "Licenza dei dati originali", richieste da ciascun soggetto che ha fornito - per la sua porzione territoriale - il dato originale.
[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [Visualizza licenza](https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITI-Centro/blob/master/LICENSE)
