## Download 📥
Puoi [scaricare](https://github.com/i-decosmis/HTS_KSE_VE_CONV/archive/refs/heads/main.zip) il file zip o clonare la repository.
* Estrai la cartella dall'archivio zip scaricato.
* Le cartelle che contengono le immagini e il file PSD compresso sono `Poker Size` e `Tarot Size`.
* La cartella `Open Sans and Patua One` contiene dei font necessari per aprire il progetto PSD, tutto viene spiegato in basso.

## Contenuto 🧐
* **File PNG** per ogni espansione (KSE, VE, CONV), suddivisi per lingua (Italiano e Inglese).
* **File PSD** per le carte in formato poker e tarocco, preparati con il template di Make Playing Cards (MPC).
* **Carte dei Mostri e dei Leader di Squadra modificabili**, senza nomi, in modo da poter aggiungere traduzioni usando i file PSD forniti.
* Una **traduzione completa in italiano** di tutte le carte.

## Organizzazione dei File 📌
I file sono organizzati in due cartelle principali:
* **Formato Poker**
* **Formato Tarocco**

Ogni cartella contiene sia i file PSD (compressed in a 7z archive) che PNG, organizzati per tipo di carta e includendo i retro delle carte.

### Organizzazione dei PNG 🖼️
Tutti i file PNG sono pronti per essere caricati sul sito [Make Playing Cards](https://www.makeplayingcards.com/), con i seguenti dettagli:
* [Formato Poker: 63 x 88mm](https://www.makeplayingcards.com/design/custom-blank-card.html)
* [Formato Tarocco](https://www.makeplayingcards.com/design/design-your-own-tarot-cards.html)

Le carte sono organizzate per categoria (es. `Sfide`), poi per lingua e per espansione. Ogni espansione include due versioni:
* **Con Etichetta**: Etichette personalizzate create per distinguere le carte per categoria, come ad esempio:<br />
  <img src="../../Poker Size\Heroes\ENG\KSE\With Label\Renovern.png" alt="Logo" width="350">

* **Senza Etichetta**: Carte standard senza etichette personalizzate, per esempio:<br />
  <img src="../../Poker Size\Heroes\ENG\KSE\Without Label\Renovern.png" alt="Logo" width="350">

> Nota: Per la carta `L'Arciere Ritmico`, ho scelto di mantenere l'etichetta originale, quindi questa carta appare con l'etichetta in tutte le versioni.

## Dettagli dei File PSD 📸
**REQUISITI**:
* Installare i font presenti nella cartella `Open Sans and Patua One`. Nel caso di `Open Sans` consiglio di installare i due file ttf presenti nella cartella `Open_Sans` e ignorare la cartella `static`.

Estrai il file PSD con cui vuoi lavorare dall'archivio 7z e aprilo.

Nei file di Photoshop, ogni espansione è organizzata per categoria (es. `Challenges`) ed etichettata per espansione (es. `KSE`). Per ogni **cartella di ogni carta** nel file PSD, troverai i seguenti livelli:
* **Livello KSE/VE/CONV**: Un livello con l’etichetta creata per ogni espansione. (Per la carta `Sfida dello Stregone`, l’etichetta è stata leggermente abbassata per evitare di coprire il nome della carta).
* **Livello ITA**: L'immagine finale in italiano.
* **Cartella ITA**: Contiene i nomi e le descrizioni in italiano posizionati su ogni carta. **Puoi usare questo testo come base per tradurre in altre lingue**.
* **Livello Nascondi**: Nasconde il testo inglese sull'immagine di base della carta.
* **Livello Senza Nome (solo per Mostri e Leader di Squadra)**: Una versione della carta con il nome rimosso.
* **Livello Inglese**: La carta base in inglese.

## FAQ ❓
**D: Perché hai spostato l’etichetta solo sulla carta `Sfida dello Stregone` e non su tutte le altre per renderle uniformi?**

R: Preferisco che l’etichetta rimanga alla stessa altezza precisa su tutte le carte, perché mi piace così. Su quasi tutte le carte, questa posizione funziona perfettamente senza coprire dettagli importanti. Tuttavia, sulla carta `Sfida dello Stregone`, l’etichetta coprirebbe parte del nome, quindi ho regolato leggermente l’altezza solo per questa carta, per assicurare che il nome rimanga visibile.

**D: Quale impostazioni usare per stampare le carte sul sito [Make Playing Cards](https://www.makeplayingcards.com/)?**

R: Prossimamente farò il l'ordine e le impostazioni che userò sono queste:
* Card Stock: M29 (Da questo [post](https://www.reddit.com/r/HereToSlay/comments/w7u6fc/does_anyone_know_what_type_of_cardstock_the_cards/)).
* Print Type: Full Color Print.
* Finish: MPC card finish (Da questo [post](https://www.reddit.com/r/mpcproxies/comments/rycpki/mpc_card_stock_options_a_review/)).
* Altre opzioni a vostra decisione.

Appena riceverò le carte fisiche aggiornerò con le mie considerazioni.