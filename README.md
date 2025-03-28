# Game Master Helper - Documentazione

Questo documento descrive la struttura e le funzionalità della single page applicazione "Game Master Helper", pensata per supportare un Game Master nella creazione e gestione della propria partita. L'applicazione consente di inserire parametri specifici e ricevere suggerimenti su mostri, boss e mappe consigliate in base all'input fornito.

## Descrizione Generale

L'obiettivo dell'applicazione è quello di offrire un’interfaccia intuitiva che permetta di:
- **Inserire Parametri della Partita:** Come il livello del party, l'ambiente di gioco e il tipo di scontro (mostro o boss).
- **Generare Suggerimenti Dinamici:** Fornire consigli testuali riguardo l'incontro (mostro o boss) e indicazioni sulle mappe più adatte in base all'ambiente selezionato.
- **Gestire Tutte le Funzionalità in un'unica Pagina:** La struttura single page facilita l'interazione e la consultazione rapida.

## Caratteristiche Principali

- **Form di Input:**
  - **Livello del Party:** Campo numerico per indicare il livello complessivo dei personaggi.
  - **Ambiente di Gioco:** Selezione a tendina (ad es. foresta, deserto, caverna).
  - **Tipo di Scontro:** Selezione a tendina per scegliere tra mostro e boss.
  
- **Suggerimenti per l'Incontro:**
  - Basati sui parametri inseriti, il sistema genera un suggerimento testuale che indica l'adeguatezza di un incontro con un mostro o un boss.
  
- **Mappe Consigliate:**
  - Viene indicata una mappa collegata all'ambiente scelto, per aiutare il Game Master a visualizzare l'ambientazione dell'incontro.
  
- **Design Responsive:**
  - La pagina è ottimizzata per una visualizzazione sia su desktop che su dispositivi mobili.


1. **Avviare l'Applicazione:**  
   Aprire il file `index.html` in un browser web moderno.

2. **Inserire i Parametri:**  
   Compilare il form con:
   - Il livello del party.
   - L'ambiente di gioco scelto.
   - Il tipo di scontro desiderato (mostro o boss).

3. **Generare i Suggerimenti:**  
   Cliccare sul pulsante per generare i suggerimenti.  
   Verrà visualizzato:
   - Un messaggio che indica il suggerimento per l'incontro.
   - La mappa consigliata in base all'ambiente selezionato.


