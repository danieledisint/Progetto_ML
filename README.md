# 🤖 Project ML | Guida per il Team

Benvenuti nel repository del nostro progetto di Machine Learning.

Questa guida rapida e sintetica copre il flusso di lavoro essenziale per lo sviluppo collaborativo utilizzando Git e Jupyter Notebooks.

## 📌 Flusso di Lavoro Semplice (Focus sul Notebook)

L'obiettivo è lavorare in isolamento sul proprio Notebook Jupyter (chiamato `section*.ipynb`) e integrare le modifiche solo alla fine del ciclo di sviluppo.

### 1. Preparazione Iniziale (Solo la prima volta)

1.  **Clona il Repository:** Apri il terminale e clona il progetto.
    ```bash
    git clone [https://github.com/danieledisint/Progetto_ML.git](https://github.com/danieledisint/Progetto_ML.git)
    cd Progetto_ML
    ```
2.  **Crea il tuo Branch Personale:** Crea un nuovo branch con il tuo nome per isolare il tuo lavoro.
    ```bash
    git checkout -b <il-tuo-nome>
    ```
    *(Esempio: `git checkout -b daniele`)*

### 2. Sviluppo Quotidiano

#### A. Inizio Sessione (Sincronizzazione)

Prima di iniziare a lavorare, assicurati che il tuo branch sia allineato con il branch principale (`main` o `master`).

1.  Passa al branch principale:
    ```bash
    git checkout main
    ```
2.  Aggiorna il branch principale con le ultime modifiche remote:
    ```bash
    git pull origin main
    ```
3.  Torna al tuo branch di lavoro e incorpora le modifiche:
    ```bash
    git checkout <nome-tuo-branch>
    git merge main
    ```

#### B. Lavoro sul Notebook

1.  Apri il tuo **Notebook Jupyter** e lavora sul codice e sull'analisi.
    *(È consigliato che ognuno lavori sul proprio file `.ipynb` per minimizzare i conflitti, ad esempio `section1.ipynb`)*
2.  Salva regolarmente il tuo Notebook.

### 3. Salvare e Pubblicare il Lavoro

Alla fine della giornata o quando completi una fase di lavoro:

1.  **Aggiungi le Modifiche:** Aggiungi il tuo Notebook e qualsiasi altro file modificato all'area di staging.
    ```bash
    git add section*.ipynb
    ```
    *Suggerimento: Usa `git add .` se sei sicuro di voler includere tutte le modifiche.*
2.  **Crea il Commit:** Salva le modifiche localmente con un messaggio chiaro.
    ```bash
    git commit -m "Descrizione sintetica del lavoro svolto oggi/della feature completata"
    ```
3.  **Pubblica su GitHub:** Invia il commit al tuo branch remoto su GitHub.
    ```bash
    git push origin <il-tuo-nome>
    ```

### 4. Richiesta di Revisione (Integrazione)

Quando il tuo codice è pronto per essere unito al branch principale (`main`), apri una **Pull Request (PR)**:

* Vai alla pagina del repository su GitHub.
* Dovresti vedere un pulsante **"Compare & pull request"**.
* Seleziona come base il branch **`main`** e come sorgente il tuo **`<nome-tuo-branch>`**.
* Aggiungi un titolo e una descrizione chiari e assegna i revisori (il resto del team).

---
## 🛠️ Regole Chiave per i Notebook Jupyter

* **Evita i Commit con Output Ponderoso:** Per mantenere i file `.ipynb` snelli e veloci da revisionare, **pulisci sempre gli output** (grafici, grandi dataframe) prima di committare.
    * *Jupyter: `Kernel` > `Restart & Clear Output`*
* **Gestione dei Conflitti:** Se Git segnala un conflitto (`CONFLICT`), parlane subito con il team. I conflitti nei file `.ipynb` sono difficili da risolvere manualmente.

---
