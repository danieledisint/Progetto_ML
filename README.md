## 📚 Guida alla Contribuzione al Progetto

Questo documento descrive il flusso di lavoro Git/GitHub che adottiamo per mantenere il codice organizzato e collaborare in modo efficiente.

### 📌 Regole Fondamentali

1.  **Non lavorare mai direttamente sul branch `main`**.
2.  Ogni nuova funzionalità o correzione di bug deve avere il suo **branch dedicato**.
3.  Usa sempre le **Pull Request (PR)** per proporre modifiche.

-----

### Passo 1: Clonare il Repository (Solo la Prima Volta)

Apri il terminale sul tuo computer e scarica una copia locale del progetto:

```bash
git clone https://github.com/danieledisint/Progetto_ML
cd Progetto_ML
```

### Passo 2: Creare un Branch di Lavoro

Prima di iniziare una nuova attività (funzione o bugfix), crea un nuovo branch. Usa un nome descrittivo (es. `feature/aggiungi-login` o `fix/risolvi-errore-sidebar`).

1.  Assicurati di essere sul branch principale e aggiornalo:
    ```bash
    git checkout main
    git pull origin main
    ```
2.  Crea e passa al tuo nuovo branch:
    ```bash
    git checkout -b nome-del-tuo-branch
    ```

### Passo 3: Lavorare e Committare le Modifiche

Lavora sui file del progetto. Quando hai completato una parte significativa o un'intera funzionalità:

1.  **Aggiungi i file modificati** all'area di staging:
    ```bash
    git add .
    ```
2.  **Salva la modifica** (commit) con un messaggio chiaro e conciso:
    ```bash
    git commit -m "feat: Aggiunta logica di controllo utenti nel modulo X"
    ```
    *(Consiglio: usa prefissi come `feat:` per nuove funzionalità, `fix:` per correzioni di bug, `docs:` per documentazione.)*

### Passo 4: Spingere (Push) le Modifiche su GitHub

Carica il tuo branch locale sul repository remoto:

```bash
git push origin nome-del-tuo-branch
```

### Passo 5: Aprire una Pull Request (PR)

Una volta che il tuo codice è pronto per essere unito al branch `main`:

1.  Vai sul [repository GitHub](https://github.com/danieledisint/Progetto_ML).
2.  GitHub ti avviserà che è stato caricato un nuovo branch e ti chiederà di **"Open a Pull Request"**.
3.  **Completa i dettagli della PR:**
      * **Titolo:** Deve spiegare cosa fa la modifica.
      * **Descrizione:** Spiega il contesto, le scelte fatte e i ticket (Issues) che risolve.
4.  Assegna la PR a un collega per la **Code Review** (revisione del codice).

### Passo 6: Revisione e Unione (Merge)

1.  Un collega rivedrà il tuo codice sulla PR. Potrebbe chiedere modifiche.
2.  Se sono necessarie modifiche, torna al **Passo 3** (lavori, committi e fai un altro `git push`). Le modifiche appariranno automaticamente sulla PR.
3.  Una volta approvata, la PR verrà unita (merged) nel branch `main`.

### Passo 7: Pulizia

Dopo che la PR è stata unita:

1.  Torna al branch `main`:
    ```bash
    git checkout main
    ```
2.  Aggiorna la copia locale:
    ```bash
    git pull origin main
    ```
3.  Cancella il branch di lavoro (non è più necessario):
    ```bash
    git branch -d nome-del-tuo-branch
    ```

-----

Seguendo questo flusso, eviteremo sovrascritture accidentali e manterremo una cronologia pulita e verificata del progetto\!
