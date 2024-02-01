Exercici GIT 3: Desfer canvis
=============================

Per a realitzar aquests exercicis és necessari haver realitzat prèviament els exercicis sobre l'historial de canvis.
Es farà entrega en un document PDF.

#Exercici 1

  **1. Elimina l'última línia del fitxer índex.txt i guarda-ho.**
    
       He entrat en fitxer index.txt i he eliminat la ultima línia del fitxer.
       
   **2. Comprova l'estat del repositori.**
    
       Comprovem l’estat del repositori en un git status
       
    **3. Desfés els canvis realitzats al fitxer índex.txt per tornar a la versió anterior del fitxer.**
    
       Per tornar a la versió anterior en el següent comandament:
       
    **4. Torna a comprovar l'estat del repositori.**
    
       Fem el mateix que abans en el git status.
       
#Exercici 2

    **1. Elimina l'última línia del fitxer índex.txt i guarda-ho.**
    
       He entrat dins del fitxer índex he borrat la ultima línia he guardat i després per a comprovar li he fet un cat.
       
    **2. Afegeix els canvis a la zona d'intercanvi temporal.**
    
       He guardat els canvis i he fet el git estatus.
       
    **3. Comprova de nou l'estat del repositori.**
    
       En el comandament git add que el havia fent en la activitat anterior.
       
    **4. Treu els canvis de la zona d'intercanvi temporal, però mantin-los al directori de treball.**
        git status
        
    **5. Comprova de nou l'estat del repositori.**
    
       Mirem el estat actual del repositori.
       
    **6. Desfés els canvis realitzats al fitxer índex.txt per tornar a la versió anterior del fitxer.**
    
       Per a desfer els canvis he utilitzat aquest comandament.
       
    **7. Torna a comprovar l'estat del repositori.**
    
       Tornem a vorer el estat .
       
#Exercici 3

    **1. Elimina l'última línia del fitxer índex.txt i guardar-ho.**
    
       Fem el mateix que abans entrem dins de index.txt borrer la ultima línia i guarde.
       
    **2. Elimina el fitxer capítols/capitol3.txt.**
    
       Per a eliminar el fitxer he utilitzat el comandament rm capitol3.txt
       
    **3. Afegeix un fitxer nou capítols/capitol4.txt buit.**
    
       He creat el fitxer capitol4.txt buit.
       
    **4. Afegeix els canvis a la zona d'intercanvi temporal.**
    
       Ja tenim el canvis guardats.
       
    **5. Comprova de nou l'estat del repositori.**
    
       Ja tenim el nou estat del repositori.
       
    **6.Treu els canvis de la zona d'intercanvi temporal, però mantin-los al directori de treball.**
       
       git reset --soft HEAD
       
    **7. Comprova de nou l'estat del repositori.**
    
       git status
       
    **8. Desfés els canvis realitzats per tornar a la versió del repositori.**
       
       git reset --hard HEAD
       
    **9. Torna a comprovar l'estat del repositori.**
       
       git status
       
# Exercici 4

    **1. Elimina l'última línia del fitxer índex.txt i guardar-ho.**
    
       Ja tenim la ultima linia del fitxer index eliminat i guardat.
       
    **2. Elimina el fitxer capítols/capitol3.txt.**
    
       Per a eliminar el fitxer he utilitzat aquest comandament que es mostra en la image.
       
    **3. Afegeix els canvis a la zona d'intercanvi temporal i fer un commit amb el missatge "Borrat accidental."**
    
       He guadat i he fet el git commit: git add . git commit -m "Borrat accidental"
       
    **4. Comprova l'historial del repositori.**
    
       Asi tenim el historial del repositori en un git log: 
       
    **5. Desfés l'últim commit, però mantin els canvis anteriors al directori de treball i a la zona d'intercanvi temporal.**
    
       He utilitzat aquest comandament: lorena@a217pc12:~/Escriptori/llibre/capitols$ git reset --soft HEAD^

    **6. Comprova l'historial i l'estat del repositori.**
    
       Açi comprovem el que ens manen: git log
       
    **7. Torna a fer el commit amb el mateix missatge d'abans.**
       Ja el tenim fet git commit -m "Borrat accidental"
       
    **8. Desfés l'últim commit i els canvis anteriors al directori de treball, tornant a la versió anterior del repositori.**
       
       git reset --hard HEAD^
       
    **9. Comprova de nou l'historial i l'estat del repositori.**
    
       Ja tenim el historial i el repositori l’estat en un git status.


