# Immagini per Twine

Per poter utilizzare le immagini in Twine devi:

1. creare un repo in Github
2. assicurati che la sua visibilità sia impostata su *pubblica* (per verificare puoi andare sulla lista dei tuoi repo e leggere l'impostazione attuale. Se la vuoi cambiare vai in *Settings -> General -> Danger Zone -> Change repository visibility*)
3. carica le immagini che vuoi utilizzare
4. in Github apri l'immagine che vuoi usare
5. copia il link dalla barra degli indirizzi
6. in Twine:
   1. crea un tag ``<img src="">``
   2. all'interno dei doppi apici incolla il link che hai copiato in Github
   3. aggiungi all'indirizzo **``?raw=True``**
   4. aggiungi eventuali proprietà del tag ``img`` per modificarne il comportamento (larghezza, altezza, stile...)
7. verifica il funzionamento
