# Registro Recuperi Git

**un file è stato aggiunto all'indice per sbaglio e va tolto dall'indice senza perdere le modifiche:**
- Comando: `git restore --staged <nome-file>`
- Effetto: Il file esce dall'indice ma le modifiche rimangono intatte nell'area di lavoro.

**un file è stato modificato nell'area di lavoro e la modifica va scartata, tornando all'ultimo commit:**
- Comando: `git restore <nome-file>`
- Effetto: Le modifiche nell'area di lavoro vengono eliminate e il file torna allo stato dell'ultimo commit.

**l'ultimo messaggio di commit contiene un errore di battitura e va corretto senza creare un nuovo commit:**
- Comando: `git commit --amend -m`
- Effetto: L'ultimo commit viene aggiornato con il nuovo testo senza creare un commit aggiuntivo nella history.