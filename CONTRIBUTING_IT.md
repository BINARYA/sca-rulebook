# Come contribuire: creare una Pull Request (PR)

Questo repository accetta contributi tramite **Pull Request** (PR).

✅ Regola principale: **non si fa push su `main`**.  
Le modifiche si propongono con una PR e verranno revisionate e approvate dal maintainer.

---

## Metodo 1 — Solo da GitHub (senza terminale)

### 1) Fai un fork del repo
1. Apri la pagina di questo repository su GitHub.
2. Clicca **Fork** (in alto a destra).
3. Otterrai una copia del progetto nel *tuo* account GitHub.

### 2) Crea un branch nel tuo fork e fai le modifiche
1. Nel tuo fork, vai su **Code**.
2. Clicca sul selettore dei branch (di solito mostra `main`).
3. Scrivi un nome nuovo per il branch, ad esempio:
   - `fix/typo-readme`
   - `feature/miglioria-x`
4. Clicca **Create branch**.
5. Modifica i file:
   - apri un file e clicca l’icona ✏️ per modificarlo, oppure carica nuovi file.
6. Salva con un commit:
   - inserisci un messaggio breve e chiaro
   - conferma il commit **sul tuo branch** (non su `main`)

### 3) Apri la Pull Request verso questo repo
1. Nel tuo fork, vai su **Pull requests**.
2. Clicca **New pull request**.
3. Controlla che sia impostato:
   - **base repository**: questo repository (quello originale)
   - **base branch**: `main`
   - **head repository**: il tuo fork
   - **compare branch**: il tuo branch (es. `fix/typo-readme`)
4. Clicca **Create pull request**.
5. Compila titolo e descrizione e invia.

✅ Fatto! Il maintainer vedrà la PR, farà la review e (se ok) la mergerà.

---

## Metodo 2 — Con Git da terminale

### 1) Fai un fork su GitHub
1. Apri la pagina di questo repository su GitHub.
2. Clicca **Fork** (in alto a destra).

### 2) Clona il tuo fork in locale
Sostituisci `TUO-USERNAME` e `NOME-REPO` con i valori corretti:

```bash
git clone https://github.com/TUO-USERNAME/NOME-REPO.git
cd NOME-REPO
```

### 3) Crea un branch, fai le modifiche e pusha
```bash
git checkout -b fix/descrizione-breve
# fai le modifiche ai file
git add .
git commit -m "Fix: descrizione breve"
git push -u origin fix/descrizione-breve
```

### 4) Crea la PR su GitHub
1. Vai sulla pagina del tuo fork su GitHub.
2. GitHub mostrerà un bottone **Compare & pull request**: cliccalo.
   - In alternativa: tab **Pull requests** → **New pull request**
3. Controlla che la PR sia:
   - **dal tuo branch** → verso **`main`** di questo repository
4. Clicca **Create pull request**.

✅ Fatto! Il maintainer farà review e merge.

---

## Mini checklist prima di aprire la PR
- La PR è piccola e chiara (meglio 1 cosa alla volta).
- Hai descritto **cosa** cambia e **perché**.
- Se ci sono test o comandi di verifica, hai indicato come li hai eseguiti.

---

## Template descrizione PR (consigliato)
Copia/incolla nella PR:

- **Cosa cambia:** …
- **Perché:** …
- **Come testare (se applicabile):** …

Grazie per il contributo! 🙌
