---
layout: default
---

# Da PDF a EDICO... quasi in due click

*di Leonardo Frosi*
* * *
La versione 2025 di Edico Targato Italia introduce nuove funzioni che aiutano la trascrizione di documenti in Edico.
Fino ad ora gli utenti, per trascrivere in Edico contenuti matematici, dovevano leggere il documento, cartaceo o digitale, e trascriverlo manualmente nel programma.
L’esistenza di riconoscitori OCR che riconoscono anche contenuto matematico non era molto conosciuta, tra questi [Mathpix](https://mathpix.com/). 
Questo OCR è in grado, da un’immagine o documento PDF, di restituire un documento in vari formati, tra cui LaTeX o HTML.

<iframe width="560" height="315" src="https://www.youtube.com/embed/6mfpW2zXhlk?si=SdquCTTk0xXsBUAf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

 - - -

Nessuno dei formati disponibili direttamente dall’esportazione di Mathpix è supportato con buoni risultati dall’importazione in Edico.
A questo punto si introduce la nuova utility di Edico Targato Italia, l’utility contiene diverse opzioni, tra cui dei pulsanti per il reset della configurazione di JAWS per Edico, il reset del profilo Edico di NVDA, l’accesso al codice sorgente di Edico TI e, infine, un pulsante che permette la conversione di documenti HTML in documenti XHTML, formato supportato per l’importazione in EDICO.

## Procedimento per convertire immagini o documenti pdf in un formato importabile in EDICO

1. per iniziare è necessario creare un account Mathpix, per fare ciò, bisogna accedere al sito [www.Mathpix.com]((https://mathpix.com/)), quindi scegliere login nella barra dei menù e creare un nuovo account o accedere. Con l’account gratuito è possibile caricare un massimo di dieci pagine PDF al mese.
2. Una volta effettuato l’accesso, nel paragrafo **“Snip Webapp”**, premere il pulsante **“launch app”**.
3. Si aprirà la home dell’applicazione web, In questa pagina è già possibile scegliere di caricare un File, scegliendo il pulsante “upload pdf” o semplicemente copiando e incollando il File desiderato.
4. Si aprirà una finestra di dialogo con un riassunto delle informazioni sul File caricato dove è anche possibile modificare il nome del File o scegliere di caricarne altri. Premendo il pulsante “upload” il File verrà caricato e selezionandolo si aprirà un’anteprima.
5. Nella finestra di anteprima scegliere il pulsante “Export As” e scegliere il formato HTML. Una volta salvato il File html nel computer, entra in gioco la nuova utility di Edico TI, per aprirla, nel menù start di Windows, cercare **"Utility di EDICO"**.
6. nell’utility premere il pulsante “Converti da Mathpix a XHTML per EDICO” e scegliere il File html prodotto da Mathpix. L’ utility creerà un documento xhtml nella stessa cartella dove si trova il documento html scelto.
7. a questo punto avviare EDICO e scegliere **“Importa”** dal menù **File**, scegliere la voce **XHTML** e il File creato dall’utility. Edico importerà il documento.

*ℹ️ NOTA: i documenti così importati probabilmente perderanno gran parte dell’impaginazione del documento originale, ma il contenuto è riconosciuto in modo abbastanza affidabile. Edico potrebbe dare degli errori dovuti a segni di punteggiatura nel blocco matematica (“,”, “.”, “;”) che andranno sostituiti con le combinazioni “ctrl +,” e “ctrl +.”.*

⚠️AVVISO:
- l’utility non è ancora stata testata con tutte le possibili casistiche di documenti, per cui, l’importazione in Edico potrebbe dare l’errore “importazione fallita”, il che significa che non tutto il documento è stato correttamente importato, in questi casi la maggior parte del testo viene importata ma è necessario un confronto con il documento originale per completare le parti mancanti nel documento Edico.
- un confronto da parte dell’utente con il documento originale è sempre consigliato dato che gli OCR non riconoscono sempre con precisione il contenuto del documento.