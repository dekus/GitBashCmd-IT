<h1 align="center"><Git-Bash></h1>

## Links

- [Download](https://git-scm.com/downloads)

## Screenshots

![Home](https://github.com/dekuzx/GitBashCmd-IT/assets/111773957/7640a7b5-bf3d-44ca-924c-4027bff9d457)

## Comandi di base

### `pwd` - Print Working Directory
Il comando `pwd` mostra la directory corrente in cui ti trovi. Questo è utile per conoscere la posizione corrente all'interno del file system.

### `ls` - List
Il comando `ls` elenca i file e le cartelle nella directory corrente. 

### `ls -a` - List All
Il comando `ls -a` elenca tutti i file, inclusi quelli nascosti di configurazione, nella directory corrente.

### `cd` - Change Directory
Il comando `cd` permette di spostarsi in una sotto-cartella dalla directory corrente. Ad esempio, `cd nome_cartella` ti sposterà nella cartella "nome_cartella".

### `cd ../` - Spostarsi Indietro
Puoi utilizzare `cd ../` per tornare alla directory genitore, cioè la directory sopra quella corrente.

### `mkdir` - Make Directory
Il comando `mkdir` crea una nuova cartella nella directory corrente e deve essere seguito dal nome desiderato per la cartella. Ad esempio, `mkdir nuova_cartella` crea una cartella chiamata "nuova_cartella".

### `rmdir` - Remove Directory
Il comando `rmdir` elimina una cartella e deve essere seguito dal nome della cartella da rimuovere. Ad esempio, `rmdir cartella_da_eliminare` elimina la cartella "cartella_da_eliminare".

### `rm -r` - Rimuovere una Cartella con Contenuti
Il comando `rm -r` viene utilizzato per eliminare una cartella e tutti i suoi contenuti, inclusi file e sotto-cartelle. Questo comando è utile quando si desidera rimuovere una struttura di directory completa.

### `touch` - Creare un File
Il comando `touch` crea un nuovo file nella directory corrente. Ad esempio, `touch nuovo_file.txt` crea un file chiamato "nuovo_file.txt".

### `vim` - Modificare un File con Vim
Il comando `vim` è utilizzato per modificare un file senza aprirlo in un editor di testo esterno come Visual Studio Code. Ad esempio, `vim file_da_modificare.txt` aprirà il file "file_da_modificare.txt" in Vim.

### `:w` - Salvare le Modifiche in Vim
In Vim, `:w` viene utilizzato per salvare le modifiche apportate a un file. Questo comando salva il file senza uscire da Vim.

### `:wq` - Salvare e Uscire da Vim
In Vim, `:wq` viene utilizzato per salvare le modifiche apportate a un file e uscire dall'editor.

### `cat` - Visualizzare il Contenuto di un File
Il comando `cat` mostra il contenuto di un file sulla console. Ad esempio, `cat file_da_visualizzare.txt` mostra il contenuto del file "file_da_visualizzare.txt".

### `cp` - Copia un File
Il comando `cp` è utilizzato per copiare un file e incollarlo in un'altra cartella. Ad esempio, `cp file_da_copiare.txt cartella_di_destinazione/` copierà il file "file_da_copiare.txt" nella cartella "cartella_di_destinazione".

### `cp -r` - Copia una Cartella con Contenuti
Il comando `cp -r` copia una cartella e tutti i suoi contenuti in un'altra cartella. Ad esempio, `cp -r cartella_da_copiare/ cartella_di_destinazione/` copierà la cartella "cartella_da_copiare" e tutto ciò che contiene nella cartella "cartella_di_destinazione".

### `mv` - Spostare un File o una Cartella
Il comando `mv` è utilizzato per spostare un file o una cartella da una posizione a un'altra. Ad esempio, `mv file_da_spostare.txt cartella_di_destinazione/` sposterà il file "file_da_spostare.txt" nella cartella "cartella_di_destinazione".

### `rm` - Rimuovere un File
Il comando `rm` elimina un file. Ad esempio, `rm file_da_eliminare.txt` elimina il file "file_da_eliminare.txt".

### `&&` - Eseguire Comandi in Sequenza
Il doppio simbolo `&&` permette di eseguire più comandi in sequenza sulla stessa riga. Ad esempio, `mkdir cartella3 && touch file2.txt` eseguirà prima il comando `mkdir cartella3` e successivamente `touch file2.txt`.
