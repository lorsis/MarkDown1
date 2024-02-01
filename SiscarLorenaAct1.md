Exercici GIT 1: Exercicis de creació i actualització de repositoris.
====================================================================

Indica els comandaments amb els quals resoldries els escenaris plantejats en els diferents
exercicis:

#Exercici 1

**1.Crea un repositori nou amb el nom llibre i mostrar el seu contingut.**

Primer obrim la terminal, ara posem el comandament mkdir llibre per a crear la carpeta,
una volta hem creat la carpeta per a entrar dins li diem cd llibre, una volta dins la carpeta
iniciem el git posant el comandament git init, després per vorer que que hem iniciat en git li
fem un ls -a i mirem el contingut de la carpeta .git.

**2.Configura Git definint el nom de l'usuari, el correu electrònic i activar l'exida en color. Mostrar la configuració final.**

Per a configurar el git posem els següents comandament el primer es el nom del usuari, el
correu electrònic, el tercer comandament el que fa es utilitzar els colors a la seua interfície
d’usuari, el quart comandament mostra tota la configuració del usuari actual , el quint
comandament el que fa es mostra domes les configuracions globals de git per a l’usuari
actual i el últim el que fa es mostra només les configuracions locals de Git per al projecte
actual.

#Exercici 2

**1.Comprova l'estat del repositori.**

Per a comprovar l’estat del repositori posem el comandament git status i com vorem
encara no tenim res en la branca masater.

**2.Crea un fitxer índex.txt amb el següent contingut.**

Per a crear un fitxer he utilitzat el comandament nano i dins
li he posat capítol 1... en el comandament cat heu podem vorer que hem escrit.

**3.Comprova de nou l'estat del repositori.**

Comprovem l’estat del repositori i ens mostra el fitxer index.txt

**4.Afegeix el fitxer a la zona d'intercanvi temporal.**

He guardat el fitxer en un git add.

**5.Tornar a comprovar una vegada més l'estat del repositori.**

Ara ja ens mostra en verd com a que s’ha guardat el fitxer.

#Exercici 3

**Realitza un commit dels últims canvis amb el missatge "Afegit índex del llibre." i veure l'estat del repositori.**
He fet el git commit -m i després està l’estat del repositori.

#Exercici 4

**1.Canvia el fitxer índex.txt perquè continga el següent.**

He entrar en el fitxer anterior que havia creat i he afegit el capítol 4 i he canviat el nom del
capítol 3, després per a comprovar he fet el comandament cat index.txt per vorer el text
del fitxer.

**2.Mostra els canvis respecte a l'última versió guardada al repositori.**

Per a que ens mostre els canvis fem un git diff.

**3.Fer un commit dels canvis amb el missatge "Afegit capítol 3 sobre gestió de branques".**

Fem un git add i després fem el git commit.

#Exercici 5

**1.Mostrar els canvis de l'última versió del repositori respecte a l'anterior.**

Mostra la informació dels commits en un registre.

**2.Canviar el missatge de l'últim commit a "Afegit capítol 3 sobre gestió de branques a l'índex."**

He fet un git commit

**3.Tornar a mostrar els últims canvis del repositori.**
git log -p -1

#Exercici 6

**Indica a Git que vols ignorar tots els fitxers que comencen per "daw", tots els que tenen l'extensió out i les imatges (jpg, png, bmp i gif).**

He creat el fitxer i en el comandament cat es veu el que he añadit.

