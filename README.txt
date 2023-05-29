prova con 2 collaboratori

per associare github al proprio pc:
- istalla gh (per esempio usando brew install gh)
- lancia gh auth login e segui le istruzioni


creare un progetto collaborativo:
A) Crea un nuovo repository
A) crea un nuovo commit e lancia git push
B) git clone <repository>

da qui in avanti si lavora come al solito:
- git pull origin main   //per scaricare l'ultima versione del repository
// per aggiornare una versione
- git add -A
- git commit -m "messaggio"
- git push -u -f origin main

// oppure creando prima un nuovo branch
- git checkout -b newBranch
//sviluppa e crea nuovi commit su questo branch
//poi quando è tutto funzionante si fa un merge dei due rami:
- git checkout main
- git merge newBranch 
