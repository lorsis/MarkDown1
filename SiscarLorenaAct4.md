Exercici GIT 4: Gestió de branques
=================================

Per a realitzar aquests exercicis és necessari haver realitzat prèviament els exercicis sobre desfer
canvis.

#Exercici 1
Crea una nova branca bibliografia i mostrar les branques del repositori.

Per crear la nova branca he utilitzat el següent comandament que es pot vorer en la imatge i per
mostrar les branques.

#Exercici 2

**1.Crear el fitxer capítols/capitol4.txt i afegir el següent text**

Per a crear el fitxer capitol4.txt he utilitzat el comandament nano capitol4.txt i per a
comprovar que s’ha guadat heu podem comprovar en cat.

**2.Afegir els canvis a la zona d'intercanvi temporal.**

Per a guarda-ho utilitzem el següent comandament.
lorena@a217pc12:~/Escriptori/llibre/capitols$ git add capitol4.txt

**3.Fer un commit amb el missatge "Afegit capítol 4."**

Per fer el commit -m

**4.Mostrar la història del repositori incloent totes les branques.**

Ací tenim el historial del repositori de totes les branques: git log --graph --all --oneline

**Exercici 3**

**1.Canvia a la branca bibliografia.**

Per canviar de branca utilitzem el comandament git checkout bibliografia i ens diu que
hem canviat de branca.

**2.Crea el fitxer bibliografia.txt i afegir la següent referència:**

Com podem comprovar en la image hem creat el fitxer i hem afegit lo següent: nano bibliografia.txt i després fem un cat bibliografia.txt

**3.Afegeix els canvis a la zona d'intercanvi temporal.**

He utilitzat aquest comandament git add bibliografia.txt

**4.Fes un commit amb el missatge "Afegida primera referència bibliogràfica."**

He fet el git commit amb el missatge: git commit -m "Afegida primera referència bibliogràfica."

**5.Mostra la història del repositori incloent totes les branques.**
Ací esta el historial de totes les branques: git log --graph --all --online

#Exercici 4

**1.Fusiona la branca bibliografia amb la branca master.**

He tornat a la rama master: lorena@a217pc12:~/Escriptori/llibre$ git checkout master
S'ha canviat a la branca «master»

**2.Mostra la història del repositori incloent totes les branques.**
Com mostra la imatge totes les branques.

**3.Elimina la branca bibliografia.**
Per a eliminar la branca bibliografia he utilitzat el següent comandament: git branch -d
bibliografia

**4.Mostra de nou la història del repositori incloent totes les branques.**
Ací tenim el historial de nou:git log --graph --all --online

#Exercici 5

**1.Crea la branca bibliografia.**

La tronem a crear la branca: git branch bibliografia

**2.Canvia a la branca bibliografia.**

Ja estem en la branca en el següent comandament: git checkout bibliografia

**3.Canvia el fitxer bibliografia.txt perquè continga les següents referències:**
Ara el fitxer té lo següent: nano bibliografia.txt i després un cat

**4.Afegeix els canvis a la zona d'intercanvi temporal i fer un commit amb el missatge "Afegida nova referència bibliogràfica."**
He fet el següent commit: git commit -m "Agefida nova referencia biblografica

**5.Canvia a la branca master.**
Ja estem en la branca master: lorena@a217pc12:~/Escriptori/llibre$ git checkout master

**6.Canvia el fitxer bibliografia.txt perquè continga les següents referències:**

Ja tenim el que ens demana: nano bibliografia.txt, cat bibliografia

**7.Afegeix els canvis a la zona d'intercanvi temporal i fer un commit amb el missatge "Afegida nova referència bibliogràfica."**

Ja tenim el commit fet: lorena@a217pc12:~/Escriptori/llibre$ git commit -a -m "Afegida
nova referència bibliogràfica"

**8.Fusiona la branca bibliografia amb la branca master.**

Per a fusionar la branca master he utilitzat el següent comandament: git merge bibliografia

**9.Resol el conflicte deixant el fitxer bibliografia.txt amb les referències:**
Dins del fitxer tenim lo següent que es mostra en la imatge: cat bibliografia.txt

**10.Afegeix els canvis a la zona d'intercanvi temporal i fes un commit amb el missatge "Resolt conflicte de bibliografia."**

He fet el següent commit: lorena@a217pc12:~/Escriptori/llibre$ git commit -a -m "Resolt
conflicte de bibliografia"

**11.Mostra la història del repositori incloent totes les branques.**

Com podem vorer el següent historial en la imatge: git log --graph --all --oneline

