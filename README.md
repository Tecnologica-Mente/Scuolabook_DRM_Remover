# Scuolabook_DRM_Remover
DRM Protection Removal and Downloader for Scuolabook Platform

ITALIAN

1) Scaricare l'archivio ed estrarlo in una posizione a piacere
2) Scaricare la versione portable di Python a 32-bit o 64-bit (a seconda del sistema operativo installato) dal sito:
https://sourceforge.net/projects/portable-python/
Se non si sa quale versione installare, scegliere quella a 32-bit.
Estrarre l'archivio appena scaricato e spostare tutti i file nella stessa cartella dove si è estratto l'archivio del punto 1) (vedi immagine allegata "files_position_image.png" - tutti i file devono stare nella stessa cartella).
3) Fare doppio clic sul file "Scuolabook_DRM_Remover_AIO.cmd" e premere il tasto 1 sulla tastiera per avviare l'installazione/aggiornamento del programma. Attendere il completamento dell'operazione.
4) Collegarsi al sito:
http://www.scuolabook.it/
ed eseguire l'accesso con le proprie credenziali.
5) Nella schermata "La mia libreria", dove vengono visualizzati i propri libri, cliccare su "Leggi" in corrispondenza del libro che si vuole scaricare. Premere sulla tastiera il tasto F12 per visualizzare la DevTools.
a) Se si sta utilizzando Google Chrome, spostarsi nella scheda "Network" e premere F5 per aggiornare la pagina. Tra i numerosi file elencati, cercare quello che ha nome "ping.json?_r=XXXXXXXXXXXXX" dove al posto di XXXXXXXXXXXXX viene indicato il codice ISBN del libro.
b) Se si sta utilizzando Firefox, spostarsi nella scheda "Rete" e ripetere gli stessi passi del punto a).
c) Se si sta utilizzando Microsoft Edge, spostarsi nella scheda "Rete" e ripetere gli stessi passi del punto a).
6) Andare sul menù di Scuolabook DRM Remover e premere il tasto 2 sulla tastiera. Quando richiesto inserire come "Book URL" il link completo https://webapp.scuolabook.it/books/######## presente nella barra degli indirizzi del browser e premere Invio. Inserire come "Cookie" il campo Cookie presente nel file del punto a) e come "Effective number of pages" il numero effettivo di pagine che compone il libro (si può anche lasciare vuoto, ma il rilevamento automatico potrebbe non scaricare le pagine finali del libro). Inizierà il download del libro. Attendere il completamento dell'operazione. Il PDF sbloccato del libro verrà scaricato nella stessa cartella dove si trova il file "download.py" con il nome del libro selezionato.
7) Per scaricare gli altri libri sarà sufficiente ripetere i passi dal punto 5).

Divertitevi ;-)

p.s. Ricorda che sei responsabile di ciò che stai facendo su Internet e anche se questo script esiste, potrebbe non essere legale nel tuo paese creare backup personali dei libri.

L'UTILIZZO DEL SOFTWARE È A PROPRIO ESCLUSIVO RISCHIO E PERICOLO. IL SOFTWARE È FORNITO DAI DETENTORI DEL COPYRIGHT E DAI COLLABORATORI "COSÌ COM'È" E NON SI RICONOSCE ALCUNA ALTRA GARANZIA ESPRESSA O IMPLICITA, INCLUSE, A TITOLO ESEMPLIFICATIVO, GARANZIE IMPLICITE DI COMMERCIABILITÀ E IDONEITÀ PER UN FINE PARTICOLARE. IN NESSUN CASO IL PROPRIETARIO DEL COPYRIGHT O I RELATIVI COLLABORATORI POTRANNO ESSERE RITENUTI RESPONSABILI PER DANNI DIRETTI, INDIRETTI, INCIDENTALI, SPECIALI, PUNITIVI, O CONSEQUENZIALI (INCLUSI, A TITOLO ESEMPLIFICATIVO, DANNI DERIVANTI DALLA NECESSITÀ DI SOSTITUIRE BENI E SERVIZI, DANNI PER MANCATO UTILIZZO, PERDITA DI DATI O MANCATO GUADAGNO, INTERRUZIONE DELL'ATTIVITÀ), IMPUTABILI A QUALUNQUE CAUSA E INDIPENDENTEMENTE DALLA TEORIA DELLA RESPONSABILITÀ, SIA NELLE CONDIZIONI PREVISTE DAL CONTRATTO CHE IN CASO DI "STRICT LIABILITY", ERRORI (INCLUSI NEGLIGENZA O ALTRO), ILLECITO O ALTRO, DERIVANTI O COMUNQUE CORRELATI ALL'UTILIZZO DEL SOFTWARE, ANCHE QUALORA SIANO STATI INFORMATI DELLA POSSIBILITÀ DEL VERIFICARSI DI TALI DANNI.

Licenza MIT (Massachusetts Institute of Technology)

------------------------------------------------------------------------------------
ENGLISH

1) Download the archive and extract it to a location of your choice
2) Download the portable version of Python 32-bit or 64-bit (depending on the installed operating system) from the site:
https://sourceforge.net/projects/portable-python/
If you don't know which version to install, choose the 32-bit version.
Extract the archive just downloaded and move all the files to the same folder where the archive of point 1) was extracted (see attached image "files_position_image.png" - all files must be in the same folder).
3) Double click on the "Scuolabook_DRM_Remover_AIO.cmd" file and press the 1 key on your keyboard to start installing/updating the program. Wait for the operation to complete.
4) Connect to the site:
http://www.scuolabook.it/
and log in with your credentials.
5) In the "My Library" screen, where your books are displayed, click on "Read" next to the book you want to download. Press the F12 key on your keyboard to view DevTools.
a) If you are using Google Chrome, move to the "Network" tab and press F5 to refresh the page. Among the numerous files listed, look for the one with the name "ping.json?_r=XXXXXXXXXXXXX" where the ISBN code of the book is indicated instead of XXXXXXXXXXXXX.
b) If you are using Firefox, move to the "Network" tab and repeat the same steps as in point a).
c) If you are using Microsoft Edge, move to the "Network" tab and repeat the same steps as in point a).
6) Go to the Scuolabook DRM Remover menu and press the 2 key on the keyboard. When requested, enter the complete link https://webapp.scuolabook.it/books/######## in the browser address bar as "Book URL" and press Enter. Enter the Cookie field present in the file in point a) as "Cookie" and the actual number of pages that make up the book as "Effective number of pages" (you can also leave it blank, but automatic detection may not download the final pages of the book). The book will begin downloading. Wait for the operation to complete. The unlocked PDF of the book will be downloaded to the same folder where the "download.py" file with the name of the selected book is located.
7) To download the other books, simply repeat the steps from point 5).

Enjoy ;-)

p.s. Remember that you are responsible for what you are doing on the Internet and even if this script exists, it might not be legal in your country to create personal backups of books.

USE OF THE SOFTWARE IS AT YOUR OWN RISK. THE SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND COLLABORATORS "AS IS" AND THERE IS NO EXPRESS OR IMPLIED WARRANTY, INCLUDING, BUT NOT LIMITED TO, IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR. IN NO EVENT SHALL THE OWNER OF THE COPYRIGHT OR ITS COLLABORATORS BE HELD LIABLE FOR DIRECT, INDIRECT, INCIDENTAL, SPECIAL, PUNITIVE, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, DAMAGES, DAMAGES ARISING FROM THE LOSS OF DATA OR FAILURE TO EARN, INTERRUPTION OF BUSINESS), CAUSED BY ANY CAUSE AND REGARDLESS OF THE THEORY OF LIABILITY, BOTH IN THE CONDITIONS PROVIDED BY THE CONTRACT AND IN CASE OF "STRICT LIABILITY", ERRORS (INCLUDING NEGLIGENCE OR OTHERWISE), ARISING OR OTHERWISE RELATED TO YOUR USE OF THE SOFTWARE, EVEN IF YOU HAVE BEEN INFORMED OF THE POSSIBILITY OF SUCH DAMAGES.

MIT (Massachusetts Institute of Technology) licence
