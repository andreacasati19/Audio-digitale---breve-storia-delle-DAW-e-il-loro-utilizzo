---
title: Relazione del progetto d'esame di Editoria Digitale
author: Andrea Casati (mat. 963119)
date:  a.a. 2023/2024
institute: Università degli Studi di Milano
course: Editoria Digitale
tags: audiodigitale, daw, digitalaudioworkstation
version: 0.1
kind: Document
bibliography: bibliografia.bib
csl: IEEE.csl
---

![Logo UNIMI](./logo/minerva.jpg){width=100px height=100px}

# Audio digitale - breve storia delle DAW e il loro utilizzo
Cenni sull'audio digitale e breve evoluzione storica e panoramica di utilizzo dei software per la produzione, mix e master di audio digitale.

## Introduzione

Il progetto ha come obiettivo la creazione di un eBook con cenni sull'audio digitale, sulla storia e sull'utilizzo dei software per la creazione e produzione dell'audio digitale.
Il seguente prodotto editoriale è rivolto a un pubblico di neofiti e curiosi, che vogliono ampliare la propria cultura personale in materia. È adatto a chiunque voglia avvicinarsi al mondo dell'audio digitale e delle DAW in modo graduale senza scendere troppo nel dettaglio e nei tecnicismi.
Le tecnologie adottate per la realizzazione del seguente eBook sono:

- **Xcode** per la scrittura dei documenti LaTeX, Markdown, xml e BibTeX
- **LaTeX** per la scrittura del contenuto dell'ebook
- **Markdown** per la scrittura del contenuto dell'ebook
- **BibTeX** formato per la scrittura della bibliografia e sitografia
- **LLM** (nella fattispecie GPT-4o) per la creazione di parte dei contenuti in maniera automatica mediante adeguato prompt engineering
- **pandoc** per la trasformazione di formato (dal documento LaTeX al prodotto editoriale finito in formato ePub)
- **ePub** formato per la distribuzione del prodotto editoriale finale.
- **xml** linguaggio per la scrittura dei metadati
- **Dublin Core** standard per la rappresentazione dei metadati dell'epub

La raccolta documentale ha principalmente incluso l'interazione con il LLM di OpenAI: GPT-4o. Il contenuto dell'ebook è stato quasi interamente generato tramite AI, con prompt engineering adeguato e con correzione e finalizzazione umana al termine della generazione dei testi.

Il risultato raggiunto è quello di un "tascabile digitale": un ebook leggero, discorsivo e adatto a chiunque. Si tratta di un testo ben strutturato, diviso per punti e con nozioni semplici ma mai banali.

## Ideazione 

### Tema

Lo scopo di questo prodotto editoriale è quello di esprimere in maniera semplice ed esausitiva dei concetti base sull'audio digitale e sui software in grado di manipolare e produrre audio digitale. Non si tratta quindi di un manuale, un volume tecnico, quanto più una lettura leggera, di passatempo. L'obiettivo è quello di cercare di avvicinare al mondo dell'audio digitale e della sua manipolazione i neofiti e tutti coloro che sono alle prime armi; in definitiva il pubblico adatto a questo prodotto editoriale è quindi poco esperto nel campo.
"Audio digitale - breve storia delle DAW e il loro utilizzo" è quindi un "tascabile digitale", una prima lettura sull'argomento, seguita poi eventualmente da letture più approfondite e tecniche.

I temi affrontati dal prodotto sono principalmente due: audio digitale e software per la produzione audio (DAW). Per quanto riguarda l'audio digitale, campo molto esteso e carico di tecnicismi non adatti a un lettore inesperto, vengono trattate solamente le basi, per introdurre al lettore concetti necessari per comprendere la sezione successiva sulle DAW. 
Riguardo l'audio digitale vengono quindi espressi solo dei concetti, preceduti da un breve parentesi storica sull'argomento, giusto per inquadrare il periodo storico di sviluppo. I concetti espressi riguardano definizione di audio digitale, campionamento, quantizzazione, formati di file, codifiche, caratteristiche dell'audio digitale e infine una sezione sul ruolo dell'audio digitale in era moderna.  

La sezione più corposa del prodotto editoriale è quella riguardo le DAW. I temi trattati in questa sezione sono: introduzione alle DAW e il loro utilizzo, parentesi storica e di sviluppo, differenze rispetto alla controparte analogica. Il libro ha termine con un elenco di DAW più utilizzate e una sezione sulle prospettive e gli sviluppi futuri.

Per avere una panoramica del materiale già a disposizione del lettore la ricerca sullo stato dell'arte riguardo gli argomenti trattati è stata effettuata mediante il tool di ricerca avanzata di Google.
Riguardo la **ricerca sull'audio digitale** la ricerca effettuata è la seguente:
"audio digitale" nella campo di ricerca *tutte queste parole:*

Riguardo la **ricerca sui software DAW** le ricerche sono state le seguenti:

- "DAW" nel campo di ricerca *tutte queste parole:*
- "storia delle DAW" nel campo di ricerca *tutte queste parole:*
- "cos'è una DAW" nel campo di ricerca *tutte queste parole:*
- "a cosa serve una DAW" nel campo di ricerca *tutte queste parole:*
- "daw più utilizzate" nel campo di ricerca *tutte queste parole:*
- "innovazioni delle daw" nel campo di ricerca *tutte queste parole:*
- "futuro della produzione audio" nel campo di ricerca *tutte queste parole:*

Come tool di monitoraggio del pubblico è stato utilizzato [**Answer The Public**](https://answerthepublic.com).
La ricerca è stata effettuata su:

- "audio digitale"
- "digital audio workstation"

I risultati della ricerca sono presenti nella seguente repository di GitHub: [**Link al repository**](https://github.com/andreacasati19/Audio-digitale---breve-storia-delle-DAW-e-il-loro-utilizzo/tree/main/relazione/monitoraggio)

### Destinatari

Il seguente prodotto editoriale, come già accennato, si rivolge a un pubblico di neofiti e curiosi che desiderano approcciare l'argomento con una lettura semplice e ampliare la propria cultura personale.

Per la descrizione delle *personas* e del pubblico potenziale per il prodotto editoriale in questione è stato deciso di sviluppare i seguenti aspetti descrittivi dei personaggi: nome, età, professione, istruzione, interessi, luogo di residenza, stile di vita, obiettivi, esperienza con l'audio digitale, punti di forza, bisogni, sfide, motivazioni, comportamenti online. In ultimo è stato deciso di aggiungere una citazione personale, come se il personaggio potesse parlare e descriversi in una frase.
I personaggi (in questo caso tre) sono di fantasia, a cura della sensibilità del creatore.
Le descrizioni delle personas sono presenti nella seguente repository di GitHub: [**Link al repository**](https://github.com/andreacasati19/Audio-digitale---breve-storia-delle-DAW-e-il-loro-utilizzo/tree/main/relazione/personas)

### Requisiti di accettazione

Per valutare i requisiti di accettazione di questo prodotto editoriale da parte dei destinatari già specificati è necessario analizzare due aspetti: *utilità percepita* e *facilità d'uso*.
Come già accennato il prodotto editoriale in questione si pone l'obiettivo di gettare le basi su dei temi complicati e molto tecnici. Ha come obiettivo quello di creare una base di conoscenza sugli argomenti per poi eventualmente essere seguito da letture più approfondite in materia. Pertanto è necessario che il libro soddisfi a livello di utilità percepita e di facilità d'uso i requisiti appena esposti.  
Dal punto di vista dell'utilità percepita, essendo il volume un *tascabile digitale*, deve porsi in modo semplice, con schema passo-passo, senza troppi tecnicismi. Deve essere semplice ma non banale. Deve esporre in modo chiaro, semplice ma non semplicistico. Il prodotto deve quindi affrontare i temi passo dopo passo, aggiungendo informazioni e tecnicismi (seppur pochi e basilari) gli uni dopo gli altri. La struttura del volume deve essere: dal generale al particolare.  
Dal punto di vista della facilità d'uso è importante l'utilizzo del linguaggio: deve essere semplice, discorsivo ma anche schematico. È importante che vi siano sezioni discorsive, per accompagnare il lettore, ma anche sezioni a punto-elenco, per non annoiare il lettore e rendere la lettura più fruibile e schematica.

L'aspetto di innovazione è quello di provare rendere semplici e intuitive informazioni complesse, quasi sempre distribuite solo su piattaforme o prodotti editoriali adatti a esperti del settore e non certamente per neofiti e curiosi.

### Canali di distribuzione

L'obiettivo, come già specificato, è quello di creare un *tascabile digitale*. Il formato è quindi quello di un eBook, più adatto anche visti gli argomenti trattati riguardo la *tecnologia* in senso ampio.  
I canali di distribuzione possono essere: market place, book store online, web e in generale Internet. Il formato più adatto a questo tipo di distribuzione è il formato ePub; non sono esclusi però anche altri tipi di formato quali WebBook e PDF.

Dal punto di vista dello stile grafico l'intenzione generale è quella di catturare l'attenzione del lettore inesperto: troppe parole senza grafici, immagini e in generale senza uno stile visuale accattivante rischiano di far perdere l'attenzione del lettore.  
L'identità visuale in questo tipo di contenuti (poco tecnici e adatti al pubblico *pop*) è fondamentale. Lo stile sarà orientato verso un'espressione informale, senza compromettere il significato.

Il seguente prodotto editoriale potrebbe essere inserito in una *collana editoriale digitale*: una raccolta di *tascabili digitali* con lo scopo di rendere accessibili a un pubblico inesperto e curioso temi specifici e di nicchia. Il progetto editoriale potrebbe quindi essere sviluppato anche in una serie di podcast e in formati non necessariamente atti alla lettura.

Per la distribuzione dell'ebook sono stati presi in considerazione tre principali online ebook stores:

- *Amazon (ebook Kindle)*
- *Apple Books*
- *Google Play Libri*

Per quanto riguarda lo store Amazon ebook Kindle è possibile utilizzare la piattaforma Amazon Kindle Direct Publishing se il prodotto è in self-publishing. In ogni caso per l'upload è richiesto uno dei seguenti formati: DOC, DOCX, KPF, ePub e MOBI. I formati elencati consentono la completa compatibilità con i tablet Fire, con l'applicazione Kindle e la tecnologia Kindle E-ink.

Per la distribuzione sullo store Apple Books è necessario effettuare l'upload del contenuto in uno dei seguenti formati: ePub, PDF, documento di testo o file iBooks.

Per quanto riguarda invece Google Play Libri il formato del contenuto deve essere uno tra i seguenti: ePub e PDF.

Per tutti gli stores elencati è necessario che l'eventuale PDF con il contenuto abbia la possibilità del testo selezionabile.

## Processo di Produzione

### Acquisizione dei contenuti

L'acquisizione dei contenuti è iniziata con la consultazione di pagine web (riportate in sitografia del libro) sugli argomenti trattati dal prodotto editoriale. La consultazione ha riguardato forum, blog, canali di divulgazione multimediale (YouTube) e manuali tecnici sull'utilizzo di specifiche DAW.
L'acquisizione dei contenuti in questa fase è stata fatta mediante fonti libere, quindi a costo pari a zero.  
Successivamente l'acquisizione di gran parte del contenuto del prodotto è stata fatta con generazione automatica mediante la piattaforma [OpenAI](https://openai.com/). È stato utilizzato il modello ML [GPT-4o](https://openai.com/index/hello-gpt-4o/).  
Il costo di questa fase di acquisizione riguarda due aspetti:

- costo di abbonamento al servizio openAI - GPT4o
- costo in termini di tempo per:
    - prompt engineering adeguato e fine tuning
    - revisione e redazione del contenuto generato

Entrambe le modalità di acquisizione dei contenuti hanno richiesto un lavoro di redazione e revisione manuale.

È da sottolineare inoltre che GPT-4o non ha accesso ai libri in commercio. Il contenuto generato si basa su:

- informazioni e dati, preesistenti rispetto all'interrogazione, accumulati durante il processo di addestramento (contenuti presenti fino all'anno 2023)
- informazione e dati presenti sul web (articoli, notizie, blog, forum)

In generale per sottostare alle leggi sul copyright il modello mette in atto strategie quali:

- evitare la riproduzione diretta
- utilizzo di citazioni 
- utilizzo di materiale di dominio pubblico o open source
- generazione di contenuti originali

L'approccio alla generazione dei contenuti con GPT-4o è iniziata specificando in modo preciso l'obiettivo del contenuto, i destinatari e il formato finale.  
Nella fase successiva è stato determinato l'indice dell'ebook mettendo a punto tutti i temi da trattare e il titolo definitivo del prodotto.
La fase successiva è stata quella di generazione vera e propria del testo. A testo generato sono state adottate tecniche di fine tuning per determinare il linguaggio, il livello di dettaglio, la lunghezza di ciascuna sezione e la modalità di scrittura, a tratti discorsiva e a tratti molto schematica.
Nel seguente repository sono riportati alcuni screeshot di parti della *conversazione* di prompt engineering: [**repository GitHub**](https://github.com/andreacasati19/Audio-digitale---breve-storia-delle-DAW-e-il-loro-utilizzo/tree/main/relazione/prompt%20engineering)

Le fonti riportate nella stesura automatica sono quindi da considerarsi indirette: i contenuti generati si basano su riassunti, blog, recensioni e articoli a loro volta basati sui volumi riportati in bibliografia.

La bibliografia, sitografia e i testi di approfondimento sono riportati al termine del libro in modo da consentire al lettore di raggiungere facilmente letture, volumi e informazioni più dettagliate e specifiche.

### Gestione documentale

Di seguito è riportato lo schema del flusso (disponibile anche in formato immagine .svg o .bpmn al [**seguente repository**](https://github.com/andreacasati19/Audio-digitale---breve-storia-delle-DAW-e-il-loro-utilizzo/tree/main/relazione/flusso)

![Schema del flusso](flusso/flusso.png)

### Tecnologie adottate

Come già accennato le tecnologie adottate per generare il prodotto editoriale sono le seguenti:

- **Xcode** per la scrittura dei documenti LaTeX, Markdown, xml e BibTeX
- **LaTeX** per la scrittura del contenuto dell'ebook
- **Markdown** per la scrittura del contenuto dell'ebook
- **BibTeX** formato per la scrittura della bibliografia e sitografia
- **LLM** (nella fattispecie GPT-4o) per la creazione di parte dei contenuti in maniera automatica mediante adeguato prompt engineering
- **pandoc** per la trasformazione di formato (dal documento LaTeX al prodotto editoriale finito in formato ePub)
- **ePub** formato per la distribuzione del prodotto editoriale finale.
- **xml** linguaggio per la scrittura dei metadati
- **Dublin Core** standard per la rappresentazione dei metadati dell'epub

In particolare per lo scenario di distribuzione considerato (ebook distribuito digitalmente), considerato che il formato ePub è supportato da tutte le piattaforme di distribuzione di ebook, quest'ultimo è la soluzione migliore per l'esportazione del prodotto finale.  
Il flusso di produzione ha quindi termine con la trasformazione di formato con il software Pandoc.
Il comando Pandoc atto alla creazione del prodotto finale ePub è il seguente:  
```pandoc content.tex -o Audio\ digitale\ -\ breve\ storia\ delle\ DAW\ e\ il\ loro\ utilizzo.epub --citeproc --bibliography=bibliografia.bib --number-section --toc=true --css stylesheet.css --csl=IEEE.csl --epub-metadata=metadata.xml```  

In particolare:

- ```content.tex``` è il nome del file del contenuto del libro in formato LaTeX da trasformare
- ```Audio\ digitale\ -\ breve\ storia\ delle\ DAW\ e\ il\ loro\ utilizzo.epub``` indica il nome del documento ePub finale per la distribuzione finale
- ```--citeproc``` abilita il modulo di elaborazione delle citazioni di Pandoc che elabora le citazioni e le bibliografie
- ```--bibliography=bibliografia.bib``` indica che la bibliografia è situata nel file ```bibliografia.bib``` in formato BibTeX
- ```--number-section``` indica a Pandoc di numerare automaticamente le sezioni del libro
- ```--toc=true``` indica a Pandoc di generare la table of contents
- ```--css stylesheet.css``` indica a Pandoc la presenza di un file .css per lo stile grafico
- ```--csl=IEEE.csl``` indica che il file ``IEEE.csl```contiene le regole di formattazione delle citazioni
- ```--epub-metadata=metadata.xml``` indica che i metadati da applicare sono contenuti nel file ```metadata.xml```

### Esecuzione del flusso

Nel seguente [**repository GitHub**](https://github.com/andreacasati19/Audio-digitale---breve-storia-delle-DAW-e-il-loro-utilizzo/tree/main/progetto%20editoriale) sono presenti tutti i documenti per poter riprodurre il flusso di produzione documentale. Si noti che per poter generare l'ebook in formato ePub è necessario di disporre del software Pandoc per la trasformazione di formato.
Sono presenti:

- *README.md*: documento Markdown che contiene le istruzioni per creare l'ebook in formato ePub a partire da tutte le risorse che lo compongono
- *content.tex*: documento LaTeX in cui è descritto il contenuto vero e proprio dell'ebook
- *content.md*: documento Markdown in cui è descritto il contenuto vero e proprio dell'ebook
- *bibliografia.bib*: documento BibTeX in cui è descritta la bibliografia e sitografia dell'ebook
- *IEEE.csl*: documento CSL che descrive la formattazione della bibliografia nell'ebook
- *stylesheet.css*: documento CSS che descrive il formato grafico dell'ebook
- *images*: directory di immagini da inserire nell'ebook

## Valutazione dei risultati raggiunti

### Valutazione del flusso di produzione

Dal punto di vista della riduzuone dei tempi di gestione documentale, la modalità di acquisizione dei contenuti consente una rapida raccolta dei dati e dei contenuti stessi. In generale in questo tipo di contenuto editoriale, generato con AI, il costo temporale di produzione è inversamente proporzionale al costo temporale di revisione e controllo degli errori. Aumentando il tempo di generazione, ad esempio con prompt engineering adeguato e fine tuning, la fase di revisione diviene più leggera e meno costosa in termini di tempo.  
La qualità dei contenuti generati risulta comunque nel complesso soddisfacente, in linea con le specifiche richieste in fase di ideazione. Esiste certamente un margine di miglioramento dal punto di vista della qualità del contenuto a discapito del costo di produzione. Per il livello richiesto in fase di specifiche il prodotto finale risulta in linea.  
Per quanto riguarda l'accettazione del prodotto editoriale, il contenuto si presenta come già accennato fruibile e accettabile: una fase di revisione accurata consentirebbe ancora meglio di raggiungere un pubblico meno esperto.  
Il formato ePub si presenta adatto agli scopi di distribuzione: la compatibilità è assicurata dai più importanti stores online di ebook. Per aumentare la portabilità è possibile anche la distribuzione in formato PDF.  
Il soddisfacimento di nuovi scenari d'uso può avvienire mediante due modalità d'azione: riscrittura mediante AI generativa con livello di specificità maggiore o modifica dell'attuale contenuto rendendolo più corposo e dettagliato.

### Limiti emersi

Il principale limite trovato è la difficile identificazione delle fonti con l'utilizzo delle AI generative: l'elenco fonti fornito dal modello stesso è di difficile controllo e revisione.
L'AI generativa si dimostra molto utile nella diminuzione di costo, anche in termini temporali, anche se richiede comunque un lavoro di redazione manuale e di revisione delle fonti.

## Conclusioni

Il risultato finale è un ebook fruibile dal pubblico target desiderato: il linguaggio è semplice e accessibile. I risultati più soddisfacenti sono stati raggiunti specialmente nell'ambito di raccolta dati e contenuti da parte di strumenti AI: il processo è stato rapido e a costo ridotto.
Il contenuto generato è fruibile, a tratti troppo schematico e poco discorsivo, ma con fine tuning e prompt engineering adeguato è possibile adeguare lo stile di scrittura del modello a proprio piacimento.
Le limitazioni emerse riguardano sopratutto il riuscire a essere efficacemente esaustivi nelle spiegazioni di argomenti spesso complessi nonostante l'approccio molto basilare nei concetti. Il risultato è comunque stato raggiunto in maniera efficacie con una qualità dei contenuti molto soddisfacente.

## Bibliografia e sitografia

---
nocite: '@*'
---
