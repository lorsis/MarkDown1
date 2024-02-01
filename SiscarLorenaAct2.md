Exercici GIT 2:Ús de l’historial de canvis
==========================================
Per a realitzar aquests exercicis és necessari haver realitzat prèviament els exercicis de creació i
actualització de repositoris. (Exercici 1)
L'entrega es farà en un document PDF.

#Exercici 1

**1.Mostra l'historial de canvis del repositori.**

Com podem vorer el git log ens mostra el historial.

**2.Crea la carpeta capítols i dins d'ella crea el fitxer capitol1.txt amb el següent text.**

Com podem vorer en les captures primer hem creat la carpeta capítols i
dins d’ella hem creat un fitxer que es diu captitol1 i en el comandament
cat ens mosta el text de dins del fitxer.

**3.Afegeix els canvis a la zona d'intercanvi temporal (staging area).**

He afegit els canvis en un git add.

**4.Fes un commit dels canvis amb el missatge "Afegit capítol 1."**

git commit -m "Afegit capitol 1"

**5.Torna a mostrar l'historial de canvis del repositori.**

Ens mostra historial i apareix el captitol1 posant el comandament git log.

#Exercici 2

**1.Crea el fitxer capitol2.txt a la carpeta capítols amb el següent text:**

Com podem vorer he entrar en la carpeta capitols i dins he creat el fitxer captol2 i en el
comandamen cat podem vorer el text que he posat.

**2.Afegeix els canvis a la zona d'intercanvi temporal.**
*
He guadat el fitxer que hem creat en el comadament git add . .

**3.Fes un commit dels canvis amb el missatge "Afegit capítol 2."**

Fem el git commit -m en el captitol2.

**4.Mostra les diferències entre l'última versió i les dues versions anteriors.**

Ací podem vorer la diferències entre l’última versió i la anterior.

#Exercici 3

**1.Crea el fitxer capitol3.txt a la carpeta capítols amb el següent text:**

Fem els mateixos passo que anteriorment creem el fitxer i després en cat
comprovem el text.

**2.Afegeix els canvis a la zona d'intercanvi temporal.**

Fem el mateix comandament que estem utilitzant el git add.

**3.Fes un commit dels canvis amb el missatge "Afegit capítol 3."**

Fem el git commit -m afegit captitol 3

**4.Mostra les diferències entre la primera i l'última versió del repositori.**
Ens mostra les diferències, amb el comandament git diff HEAD^ HEAD.

#Exercici 4

**1.Afegir al final del fitxer índex.txt la següent línia.**

Com podem vorer hem entrat dins de nano index.txt i per vorer el continguts he utilitzant
el comandament cat.

**2.Afegir els canvis a la zona d'intercanvi temporal.**

He guadat el fitxer index

**3.Fer un commit dels canvis amb el missatge "Afegit capítol 5 a l'índex."**

He fet el git commit -m

**4.Mostrar qui ha fet canvis sobre el fitxer índex.txt.**

He utilitzant el git blame mostra que ha fet els canvis del fitxer.

