---
layout: default
---

# Tabelle e matrici: le strutture bidimensionali
* * *

<img align="left" hspace="20" width="200" src="https://user-images.githubusercontent.com/16359799/192094768-6ef3a876-8ed8-4c39-adbe-a2b6e8f650a9.png"> 

Le tabelle e le matrici sono particolari elementi con struttura a griglia, formate da colonne e da righe.

Le tabelle vengono utilizzate per incolonnare dati o testo in modo ordinato.

Solitamente le tabelle usano graficamente dei bordi per separare i singoli elementi (celle) contenuti. Così vi saranno dei bordi verticali (colonne) e dei bordi orizzontali (righe). Il contenuto di ciascuna cella viene presentato all'interno di questi bordi.

Le matrici sono dei tipi particolari di tabelle che, graficamente, non presentano un bordo. In matematica, in particolare in algebra lineare, una matrice è una tabella ordinata di elementi.

EDICO permette di lavorare con tabelle e matrici.

Proprio perché queste strutture si espandono su più righe e colonne sono chiamati elementi bidimensionali
dove la prima dimensione sono le righe e la seconda dimensione le colonne.

In questo tutorial si è cercato di raccogliere tutti gli strumenti che EDICO mette a disposizione quando si lavora con le tabelle normali e con le matrici. L'esposizione cercherà di organizzare gli argomenti trattati in ordine di difficoltà crescente.

Partiremo con qualche esempio sulle tabelle, usate già a partire dalle scuole primarie, proseguiremo poi nel presentare le principali operazioni con le matrici, introdotte in scuola secondaria ad esempio per la risoluzione dei sistemi di equazioni e disequazioni. Nell'ultima parte presenteremo gli strumenti messi a disposizione di EDICO per facilitare l'apprendimento di specifici argomenti di algebra lineare, che potrebbero trovare svolgimento durante la scuola secondaria o l'università.

## Allegati
[Gli esempi che svolgeremo in questo tutorial sono disponibili già completati a questo link](esempi.edi)



## L'uso delle tabelle

E' possibile inserire una tabella in tre modi distinti
* Premendo CTRL+ALT+T ;
* Dal menu Inserisci, scegliendo Tabella;
* Premendo F5 e scegliendo tabella.


In qualunque caso, dando INVIO ci verrà chiesto di specificare un dimensionamento della tabella (numero di righe e numero di colonne).

Possiamo scrivere il valore con la tastiera. Per spostarci fra un campo di testo e l'altro possiamo usare il tasto TAB.

Nell'esempio vediamo un caso in cui impostiamo una tabella con 3 righe e 4 colonne:

![Esempio](https://user-images.githubusercontent.com/16359799/192092735-1409d9a2-7fed-45c2-aa28-9fadb18cc42c.png)

Il cursore verrà riportato nell'editor lineare.

Rileggendo o consultando una tabella potrebbe essere difficile comprenderne al volo le dimensioni. EDICO ci riporterà il numero di righe e colonne contenute in una tabella richiamando la funzione "Mostra dimensioni".
Per attivarla procediamo come segue:

1. Posizioniamo il cursore sulla tabella
2. Premiamo Alt+F11

![Tabella 3 per 4](https://user-images.githubusercontent.com/16359799/192101447-48aaf079-55d9-45b2-aae9-e2b46c1f583f.png)

Edico ci riporterà che la tabella è una 3 per 4.

In alternativa è anche possibile richiamare la funzione "Mostra dimensioni" dal menu Azioni.

Prendiamoci il tempo di esplorare ciò che abbiamo creato. Sul nostro display braille o Scorrendo con le freccette troviamo una serie di marcatori come:
* inizio tabella  
* Nuova colonna  
* Nuova colonna  
* Nuova colonna  
* Nuova riga  
* eccetera
* fine tabella 

Fra questi marcatori possiamo andare a inserire manualmente il contenuto della nostra tabella. Ad esempio se vogliamo riempire la prima riga con:

| Profitto | Nord | Centro | Sud |


lo possiamo fare andando a premere control+j per aprire un blocco di testo e quindi a scrivere "Profitto" fra il marcatore di inizio tabella e il primo marcatore di nuova colonna, e a seguire "nord", "centro" e "sud".
Per vedere l'esempio svolto fare riferimento all'Esempio 1 del file allegato.

![image](https://user-images.githubusercontent.com/16359799/192093181-7a6c9bbb-2b83-46e7-9a49-f711609af245.png)

Se questa modalità è comoda quando abbiamo a che fare con tabelle piccole, che magari riusciamo a leggere interamente in modo lineare nel display braille, diventa poco pratica e di difficile gestione quando i dati cominciano a essere molti.
Se già cominciassimo a riempire le altre righe della tabella in questo modo, sarebbe molto facile perdere l'orientamento.

Per questo motivo EDICO mette a disposizione l'editor bidimensionale.

## Editor Bidimensionale

Come nel caso delle strutture didattiche delle operazioni questo è disponibile in due modi: Editor Bidimensionale e Editor Bidimensionale in celle.

Manteniamo posizionato il cursore all'interno della nostra tabella e premiamo F10:
![Editor bidimensionale](https://user-images.githubusercontent.com/16359799/192093733-303a2ee5-9652-4197-8a69-cea62507556a.png)

Viene così aperto l'editor bidimensionale.

Nel display braille visualizzeremo l'intera riga della tabella, con i marcatori di nuova colonna.
Per spostarci alla seconda riga premiamo Freccia giù.
Sul display braille, a inizio riga, leggeremo sempre anche la coordinata della riga in cui siamo. Ad esempio, la prima riga comparirà come:

Riga1 edt Profitto. Nord. Centro. Sud.

La sintesi vocale leggerà l'intera riga della tabella.

Come si vede in una tabella di EDICO è possibile aggiungere anche i vari blocchi come il testo.

Questo tipo di Editor è molto comodo per chi lavora in braille se si desidera avere a disposizione sul display l'intera riga della tabella.

L'editor bidimensionale appare in una finestra di dialogo che contiene:
* Una barra dei menu
* Tanti campi di testo uno per ogni riga della tabella (nel nostro caso 3 campi di testo)
* Un pulsante Aggiorna attivabile anche premendo semplicemente INVIO.

Ci si può spostare fra i vari controlli premendo TAB. Ci si può spostare fra le varie righe anche usando le frecce su e giù.

Quando abbiamo concluso premiamo ESC per chiudere l'editor bidimensionale senza salvare le modifiche e tornare nel documento.

L'editor bidimensionale in celle è simile all'editor bidimensionale. A differenza di quest'ultimo però, mostrerà sul display braille e leggerà in sintesi vocale una singola cella della tabella alla volta.
Manteniamo posizionato il cursore all'interno della nostra tabella e premiamo Shift+F11.
![Editor bidimensionale in celle](https://user-images.githubusercontent.com/16359799/192093749-b17b6bf3-26fc-4e34-a7a5-6e6fbc81bc39.png)

Come si può notare, in questo caso la sintesi vocale leggerà solo la cella della tabella su cui abbiamo posizionato il cursore. Anche il display braille mostrerà il contenuto di una singola cella.

Sul display braille, prima del contenuto, possiamo leggere le coordinate. Così, ad esempio, leggeremo:

c1 1    profitto

premiamo TAB e troviamo

c1 2    nord 

premiamo TAB e troviamo

c1 3    centro

eccetera

La finestra di dialogo è del tutto simile a quella dell'editor bidimensionale in righe. La barra dei menu in entrambi i casi consente di inserire simboli grazie al menu Inserisci.
E' poi possibile aggiungere e rimuovere righe e colonne dal menu Modifica, Selezionare delle porzioni della tabella dal menu Seleziona e richiamare la calcolatrice dal menu Strumenti.

Una funzione interessante viene messa a disposizione dal menu Azioni che permette di passare al volo fra l'editor bidimensionale e l'editor bidimensionale in celle.

Prendetevi del tempo per esplorare le varie opzioni presenti. 
Al termine potete completare l'esercizio aggiungendo due righe alla tabella copiando quella qui sotto:

| Profitto | Nord | Centro | Sud |
| --- | --- | --- | --- |
| TV | 10000€ | 9000€ | 8500€ |
| Radio | 3400€ | 2300€ | 4000€ |

![Esempio](https://user-images.githubusercontent.com/16359799/192100537-bb2e3ec9-0c29-4f28-aa8e-33ee07aa09c7.png)

La tabella in questo caso rappresenta una informazione. Nello specifico i profitti di un negozio di elettronica nel mese di Febbraio. Possiamo completare l'esercizio aggiungendo un testo che descrive la tabella. Ad esempio: 

Profitto febbraio (euro) 

![Esempio](https://user-images.githubusercontent.com/16359799/192100666-40addced-357d-4031-985b-9530be29b42b.png)

Per vedere l'esempio svolto fare riferimento all'Esempio 2 del file allegato.

Proviamo ora ad aggiungere una ulteriore tabella, ad esempio con i profitti del mese di marzo. Copiare questa tabella preceduta dal testo 

Profitto marzo (euro)

| Profitto | Nord | Centro | Sud |
| --- | --- | --- | --- |
| TV | 9800€ | 9300€ | 8100€ |
| Radio | 3400€ | 2400€ | 4400€ |

Provate l'inserimento con l'editor bidmensionale o l'editor bidimensionale in celle per comprendere le differenze fra i due strumenti anche in fase di inserimento e spostamento fra le celle.

![image](https://user-images.githubusercontent.com/16359799/192101141-c548e1a9-0adb-4dbc-85e9-49f975461d65.png)

Per l'esempio già scritto fare riferimento all'Esempio 3 del file allegato.

A partire dall'editor bidimensionale è anche possibile spostarsi rapidamente alla tabella precedente o successiva. Se, ad esempio stiamo valutando i profitti di marzo e vogliamo compararli coi profitti di febbraio, possiamo spostarci alla tabella precedente semplicemente premendo Pagina Su o scegliendo "tabella precedente" dal menu "Vai a".

![Vai a tabella precedente](https://user-images.githubusercontent.com/16359799/192101307-7c3d8caf-9a66-40bf-bfa8-01de359a721c.png)

Si può naturalmente effettuare l'operazione inversa premendo Pagina Giù o selezionando la relativa voce dal menu "Vai a".

## L'uso delle matrici

EDICO ci permette di gestire le matrici in modo del tutto analogo a ciò che abbiamo visto con le tabelle. Possiamo quindi richiamare le stesse funzioni già viste nella sezione precedente. 

Richiamando l'esempio precedente, supponiamo di voler calcolare, per ciascun periodo, la differenza fra i due profitti.

Impostiamo quindi due matrici A e B, di cui la prima conterrà i dati di febbraio mentre la seconda conterrà i dati di marzo.

Avremo quindi che

$$
A=\begin{pmatrix}
10000 & 9000 & 8500 \\
3400 & 2300 & 4000
\end{pmatrix}
$$

$$
B=\begin{pmatrix}
9800 & 9300 & 8100 \\
3400 & 2400 & 4400
\end{pmatrix}
$$

Vogliamo quindi scrivere le matrici A e B in EDICO.

E' possibile inserire una matrice in tre modi distinti
* Premendo CTRL+ALT+M ;
* Dal menu Inserisci, scegliendo Matrice;
* Premendo F5 e scegliendo matrice.

Scegliamo il modo a noi più congeniale.
Creiamo quindi una semplice matrice 2 per 3 in modo del tutto simile a come abbiamo fatto in precedenza per le tabelle:
![creazione matrice](https://user-images.githubusercontent.com/16359799/192102547-6e7fe497-a262-4800-95ba-d2ffe40ce660.png)

Similmente a ciò che avviene con le tabelle, ci troveremo di fronte ad una serie di marcatori:
* matrice
* Nuova colonna
* Nuova colonna
* Nuova riga
* Nuova colonna
* Nuova colonna
* fine matrice 

Proprio come nel caso delle tabelle è possibile utilizzare l'editor bidimensionale e l'editor bidimensionale in celle per gestire la matrice.
Procedo quindi nello scrivere le due matrici $A$ e $B$.

Ecco mentre sto scrivendo $A$:
![scrivo la matrice A](https://user-images.githubusercontent.com/16359799/192102838-34a30ca5-dcc3-46df-9adf-65e413fb3610.png)

Copiamo anche $B$ e dovremmo ora avere un qualcosa di simile a ciò che appare in figura:
![esempio](https://user-images.githubusercontent.com/16359799/192102998-3f58dfb6-ca6a-4d87-9a3c-bd6d75f63a41.png)

Per l'esempio già scritto fare riferimento all'Esempio 4 del file allegato.

A questo punto, applicando le regole delle matrici, possiamo calcolare la matrice:

$$C = B - A$$

## Operazioni con le matrici
Per effettuare la sottrazione fra le due matrici possiamo usare l'editor bidimensionale e scriverci a mano tutte le operazioni. 
Ci troveremmo però a dover gestire 3 matrici contemporaneamente $A$, $B$ e $C$.

Questo, se all'inizio può aiutarci a capire come impostare correttamente il calcolo, a tendere rischia di portarci a effettuare errori di copiatura.

EDICO in questo caso offre una funzione in più che può essere richiamata dal menu Strumenti e che va a impostare automaticamente i calcoli (senza risolverli).

Per utilizzarla dobbiamo per prima cosa scrivere l'operazione che vogliamo svolgere e quindi copiamo la matrice B, aggiungiamo un meno, quindi copiamo la matrice A:


$$
\begin{pmatrix}
9800 & 9300 & 8100 \\
3400 & 2400 & 4400
\end{pmatrix}
-
\begin{pmatrix}
10000 & 9000 & 8500 \\
3400 & 2300 & 4000
\end{pmatrix}
$$

Scegliamo quindi il menu Strumenti, quindi Calcolo Matriciale, quindi Operazioni con sviluppo
![selezione da menu](https://user-images.githubusercontent.com/16359799/192113702-c5f3e7e5-bb0b-4d01-8a72-f160bbe2394d.png)

Il programma ci scriverà in automatico la matrice su cui dovremo andare a effettuare i calcoli.
Notare che la matrice creata dal programma viene messa in una nuova riga senza assegnarvi un nome o un'uguaglianza. Sarà quindi necessario poi procedere con gli opportuni adeguamenti.
![esempio con matrice e sottrazioni da svolgere](https://user-images.githubusercontent.com/16359799/192113729-4d97309c-7573-4eb9-93a5-9d7544dfa521.png)

Per andare alla matrice $C$ già scritta fare riferimento all'esempio 5 del file allegato.

Ora possiamo duplicare la riga con Control+d che, in questo caso duplicherà la riga dell'editor lineare e quindi l'intera matrice.

![le due righe duplicate](https://user-images.githubusercontent.com/16359799/192103895-f700b55f-cc73-490b-9822-295a1a3163d9.png)

Quindi possiamo entrare nuovamente nell'editor bidimensionale con F11 e svolgere le sottrazioni aiutandoci con la calcolatrice.

* Possiamo selezionare i singoli elementi della matrice (le singole sottrazioni) con F12
* Possiamo calcolarne il risultato e salvarlo negli appunti con Shift+F9
* Infine possiamo incollarlo con Control+V
![image](https://user-images.githubusercontent.com/16359799/192103932-3a95dfd1-21c4-478a-969b-e59f279de856.png)

Otteniamo quindi la matrice calcolata 

$$
C=\begin{pmatrix}
-200 & 300 & -400 \\
0 & 100 & 400
\end{pmatrix}
$$

Per andare allo svolgimento del calcolo fare riferimento all'esempio 6 del file allegato.

Un ulteriore aiuto in EDICO è relativo al calcolo automatico delle operazioni fra matrici.
Per ottenere la matrice $C$ risultato già calcolata si può scegliere dal menu Strumenti, Calcolo matriciale la funzione Operazioni con matrici.
![risultato](https://user-images.githubusercontent.com/16359799/192104882-d45953da-a90d-40f1-b555-26be59126259.png)

Notare che la matrice risultato viene concatenata all'operazione. Sarà quindi necessario poi procedere con gli opportuni adeguamenti.
![risultato](https://user-images.githubusercontent.com/16359799/192104919-836d5c3e-46d7-4a27-bf05-75e201c1fa94.png)

Per vedere un esempio di risoluzione automatica dei calcoli, fare riferimento all'Esempio 7 del file allegato.

Questi strumenti possono essere impiegati anche per effettuare operazioni più complicate come le operazioni di moltiplicazione (riga per colonna) fra matrici, vettori e scalari.
Ad esempio se volessimo calcolare Qual è il profitto di febbraio suddiviso per area dovremmo effettuare l'operazione:

$$
\begin{pmatrix}
1 & 1
\end{pmatrix} \cdot A
$$

Andiamo quindi a creare una matrice con 1 riga e 2 colonne che riempiamo con 1. Moltiplichiamo quindi questa matrice per $A$.
![risultato](https://user-images.githubusercontent.com/16359799/192106752-11736975-9d3b-432f-a63f-e974b42516c6.png)

E a questo punto possiamo vedere qual è il profitto complessivo di febbraio moltiplicando per il vettore unitario verticale.
Andiamo a creare quindi una matrice 3 per 1 e riempiamola con "1" e la moltiplichiamo per il vettore risultante dalla precedente operazione. Attiviamo quindi la funzione "Operazioni con matrici" dal menu Strumenti, Calcolo matriciale.
![risultato](https://user-images.githubusercontent.com/16359799/192106845-b8e94e4b-c129-4a20-8833-950d4085e2d4.png)

e si ottiene il valore  $37200$ .

Per i dettagli si può fare riferimento all'Esempio 8 del file allegato.

Un'ultima facile operazione che è possibile svolgere in automatico è il calcolo della trasposta. La matrice trasposta di una matrice assegnata si ottiene scambiandone le righe con le colonne. 
Ad esempio, per calcolare la trasposta di $C$ sarà sufficiente scegliere Strumenti, calcolo matriciale, trasposta
![trasposta di C](https://user-images.githubusercontent.com/16359799/192107861-62436e8b-17e2-402f-9d08-277da5413bd8.png)

E si ottiene:

$$
C^T=\begin{pmatrix}
-200 & 0 \\
300 & 100 \\
-400 & 400
\end{pmatrix}
$$

## Studio di matrici quadrate
Una matrice è detta quadrata quando il numero di righe è uguale al numero di colonne.
Queste matrici hanno particolari proprietà come i *determinanti*.

A ogni matrice quadrata viene associato un numero reale, detto determinante della matrice. Per indicare il determinante di una matrice si può scrivere «det» davanti alla matrice, oppure scrivere gli stessi elementi della matrice, delimitati da due righe verticali.

### Determinante e traccia
EDICO ci permette di calcolare sia in modo manuale che in modo automatico il determinante di una matrice.

Ad esempio, se vogliamo calcolare il determinante della matrice:

$$
M=\begin{pmatrix}
1&0&-3\\
1&-1&1\\
-1&1&0\\
\end{pmatrix}
$$

Procediamo come segue:

1. Scriviamo la matrice in EDICO come abbiamo già fatto negli esempi precedenti: ![image](https://user-images.githubusercontent.com/16359799/192727257-de575e2d-f86c-417c-aa95-73f8251f63fb.png)
2. Copiamo la matrice quindi apriamo l'editor bidimensionale
3. Per applicare la regola di Sarrus in EDICO scegliamo dal menu Modifica la voce "Nuova Colonna", per due volte ![image](https://user-images.githubusercontent.com/16359799/192729370-c5d03eaa-4a73-4f0a-99fb-dd31d8fba6d5.png)
4. Andiamo quindi per ogni riga a ricopiare le prime due colonne e otteniamo quindi:

$$
\begin{pmatrix}
1&0&-3&1&0\\
1&-1&1&1&-1\\
-1&1&0&-1&1\\
\end{pmatrix}
$$

6. Usiamo l'editor in celle, aggiungiamo una riga e nella prima colonna dell'ultima riga eseguiamo i calcoli come in figura: ![image](https://user-images.githubusercontent.com/16359799/192775761-ee8e5106-7646-4086-9bd7-9111b2010c74.png)
7. Una volta calcolato copiamo negli appunti i calcoli e cancelliamo la riga in più: ![image](https://user-images.githubusercontent.com/16359799/192735707-c6f18493-a3d3-4f85-940b-6fb1ecf5eb02.png)
8. E riportiamo nel quaderno i calcoli scrivendo quindi:

$$
det \begin{pmatrix}
1&0&-3\\
1&-1&1\\
-1&1&0\\
\end{pmatrix} = 0+0-3+3-1+0 = -1
$$

![image](https://user-images.githubusercontent.com/16359799/192736345-f8833e7c-04e5-458a-9b2c-c67e4124f9e9.png)

Per avere lo svolgimento già scritto è possibile fare riferimento all'Esempio 9 del file allegato.

E' anche possibile calcolare automaticamente il determinante. Per farlo procedere come segue:

1. Aprire la matrice quadrata scritta in precedenza nell'editor bidimensionale
2. Dal menu azioni scegliere "Calcola determinante". Il determinante verrà calcolato e mostrato a schermo ![image](https://user-images.githubusercontent.com/16359799/192737055-221e7df6-da72-4160-b05e-744649dd263f.png).
3. E' anche possibile copiare il determinante scegliendo l'apposita voce dal menu Azioni.

Se in una riga abbiamo solo una matrice possiamo anche calcolare il determinante scegliendo dal menu Strumenti, Calcolo matriciale, la voce determinante come in figura:
![Determinante da finestra principale del programma](https://user-images.githubusercontent.com/16359799/192737972-6da8481e-3fb7-4973-bcc8-5e647fb2dd26.png)

Allo stesso modo è possibile calcolare la traccia della matrice.

### Matrice dei cofattori, aggiunta e inversa di una matrice
EDICO ci offre una struttura didattica per comprendere e facilitare il calcolo della matrice dei cofattori.
Considerando sempre l'esempio precedente, se vogliamo calcolare il cofattore nella posizione $a_{1,1}$ possiamo procedere nel modo seguente:
1. Scriviamo la matrice originale
2. Dal menu Strutture didattiche scegliamo Cofattori
3. Dal menu Modifica scegliamo "Elimina Riga" (per eliminare la prima riga) e "Elimina Colonna" per eliminare la prima colonna. Procediamo quindi al calcolo del determinante e all'applicazione della regola
5. Ci annotiamo il cofattore nell'apposito spazio premendo TAB ![Calcoliamo il primo cofattore, nel nostro caso -1](https://user-images.githubusercontent.com/16359799/192747666-3f166e46-db15-4c44-b1ed-9c863b80f6b2.png)
6. Scegliamo copia cofattore dal menu Azioni quindi la struttura didattica ci riporterà in automatico alla matrice originale.
![Dopo aver copiato il programma ci riporta alla matrice originale](https://user-images.githubusercontent.com/16359799/192747966-029f31f0-e2d9-470c-9100-0ac2ceeb69d4.png)

E' anche possibile effettuare il calcolo automatico della matrice di cofattori di un elemento dall'editor bidimensionale. Per ottenerlo attivare la funzione "Cofattori di un elemento" dal menu Azioni.

Per avere il calcolo automatico della matrice aggiunta di una matrice possiamo procedere come segue:
1. Copiamo la matrice di partenza in una nuova riga.
2. Dal menu Strumenti scegliamo Calcolo matriciale quindi Aggiunta
3. Otterremo l'aggiunta nella stessa riga della matrice data, come in figura: ![image](https://user-images.githubusercontent.com/16359799/192749145-c152996f-447d-4d9c-9b83-f54389fbf468.png)
5. Sistemiamo opportunamente e otteniamo nel nostro foglio di lavoro l'aggiunta scritta correttamente (per scriverne il simbolo ricordiamoci che questo è richiamabile  dal menu F5 come cofattori o scrivendo adj.).
![image](https://user-images.githubusercontent.com/16359799/192749522-22ade351-99a7-4569-bf06-833d5a88b1b8.png)

Infine possiamo calcolare l'inversa di una matrice in modo automatico.
Proviamo con l'inversa della matrice dell'esempio precedente. 
Per farlo procedere come segue
1. Copiamo la matrice in una nuova riga
2. Dal menu Strumenti scegliamo Calcolo matriciale quindi Inversa
3. Otterremo l'inversa nella stessa riga della matrice data, come in figura: ![image](https://user-images.githubusercontent.com/16359799/192739397-75a06a0e-aa03-455e-a8f7-09d0d91cdb75.png)
4. Sistemiamo opportunamente e otteniamo nel quaderno l'inversa scritta correttamente.
![image](https://user-images.githubusercontent.com/16359799/192739801-483cb9fb-a7fd-487f-a9a5-f9a1f1be78ea.png)

Per un riferimento a questi calcoli si veda l'Esempio 10 del file allegato.
