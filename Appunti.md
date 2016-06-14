## Comandi generici

|Comando|Risultato|
|------|---------|
|`Ctrl+o`|_Chrome_ Apre finestra per caricare file|
|`Ctrl+s`|_Chrome_ Scarica la pagina internet|
|`Ctrl+shift+i`|_Chrome_ Per ispezionare il contenuto della pagina web|
|`Ctrl+U`|_Chrome_ visualizza il codice sorgente|




## Comandi della _Command Palette_ Atom

Una volta aperta la _Command Palette_ è possibile ricercare alcuni comandi scrivendone anche solo una parte.

Ad esempio, scrivere "preview" restringe la lista dei comandi visualizzati ai soli comandi che contengono tale parola.

|Comando| Risultato |
|---------|-----------|
|
|`MarkDown Preview: Toggle`| Mostra il rendering MarkDown del file corrente |
|`Ctrl+k+b`|Apre-chiude la barra laterale|
|`Ctrl+shift+p`|Apre la _Command Palette_|

## Codici Shell

|Comando|Risultato|
|-----|---------|
|`cd ../`|Si sposta nella _directory_ sovrastante|
|`pwd`|Mostra il percorso della _directory_ corrente|
|`ls`|Mostra contenuto della _directory_ corrente|
|`touch (nomefile)`|Crea un file (vuoto)|
|`rm (nomefile)`|Elimina un file|
|`mkdir (nomecartella)`|Crea una _directory_|
|`rmdir (nomecartella)`|Elimina una _directory_ vuota|
|`ctrl+c`|Interrompe il comando in esecuzione (manda il segnale `SIGINT` a quel processo)|
|`cd (nome-cartella)`|Entra nella cartella *nome*|
|`rm -r`|Elimina tutti i file all'interno della cartella|
|`Ctrl+c`|Interrompe il comando|
|`curl -k -L  --output prova.html`| ... |

## Comandi GitShell

|Comando|Risultato|
|-----|---------|
|`git log`|Visualizza la lista dei *Commit*|
|`q`|Permette di uscire dal comando *git log*|
|`git status`|Visualizza lo stato corrente del tuo *repository*|
|`git branch`|Mostra tutti i *branch* presenti nel tuo repository locale, con un asterisco su *quello corrente*|
|`git checkout -b (nome-del-branch)`|Crea un nuovo *branch* a partire dal branch corrente|

## Comandi HTML e CSS

|Comando|Risultato|
|------|--------|
|`<a href="(url_immagine)">`| Permette di inserire un collegamento. Si inserisce in`<a>` che successivamente andrà chiusa.|
|`<img src="(url_immagine)" alt=(descrizione_immagine)>`| Permette di inserire un immagine, con descrizione. Si può modificarne altezza (es.height="numero") e larghezza (es.width="numero")|
|`<h3>`| E' un marcatore per scrivere in grassetto|
|`<div>`| Permette di dividere in gruppi, fungendo da contenitore (vedi sotto per comandi)|
|`(es.border):(numero)px;`| Permette di modificare il "contenitore" `<div>`. vedi tabella giù.|
|`<meta charset="utf-8" />`| Questo tag spiega al browser che nel documento ci saranno caratteri dell'insieme UTF-8, come lettere accentate. Si posiziona in `head`.|
|`<br />`|Permette di andare a capo|
|`width=(numero) height=(numero)`|Imposta altezza e larghezza ad un immagine|
|`style="margin-(left/right):(numero)px"`|permette di distanziare il testo. Si inserisce all'interno di `<p>`|
|`<style type="text/css">`| Permette di inserire dei comandi di `css` nel documento `html`|
|`{background-color:(colore);}`| Permette di dare un colore allo sfondo pagina|
|`background-image:url("(nomefile)");`| Permette di inserire un immagine come sfondo|
|`background-repeat:no-repeat;`| Permette di non riempire il documento con ripetizioni dell'immagine|
|`<p class="(nomeclasse)">`| Permette di indicare una classe|
|`text-align:(center/left/right/justify);`| Permette di impostare la *giustificazione* del testo|
|`color:(colore);`| Permette di colorare un testo|
|`text-indent:(numero)px;`| Permette di indicare una rientranza nel testo.|
|`font-style:(comando);`| Permette di impostare il carattere (es.italic/oblique/normal)|
|`font-weight:(comando);`| Permette di impostare lo "spessore" (es.bold)|
|`font-size:(numero)pz;`| Permette di immpostare la dimensione del testo|
|`<link rel="stylesheet" href="(nome.css)" />`| Permette di collegare un file `css` ad uno `html`, si inserisce in `<head>`.|
|`text-transform:(comando);`| Permette di trasformare il testo (vedi sotto per comandi).|

|Comando|Risultato|
|------|---------|
|`text-transform`|
|*capitalize*| Ogni prima lettera è in maiuscolo|
|*uppercase*| Il testo è tutto in maiuscolo|
|*lowercase*| Il testo è tutto in minuscolo|
|`<div>`|     
|*width*| Larghezza del `<div>`|
|*height*| Altezza del `<div>`|
|*padding*| Distanza del margine sinistro del `<div>`|
|*border*| Grandezza cornice del `<div>`. Si può specificare con (es.`soldi`) e un colore (es.`red`)|
|*margin*| Distanza del `<div>` dal bordo pagina.|
|*dotted*| la linea del `<div>` diventa tratteggiata|
|*double*| la linea del `<div>` diventa doppia|

## Javascript

|Comando|Risultato|
|-------|--------|
|`<script type="text/javascript">`| Permette di inserire comandi javascript in un documento `html`|
|`</script>`| Marcatore di chiusura per `javascript`|
