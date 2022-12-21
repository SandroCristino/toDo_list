index.js
    - lade liste 
    - Eventlistener auf +add list
        start workflow.addNewList
    - EventListener auf list items
        stelle dazugehörige liste dar 

workflow.js
    - addNewList()
        - öffnen eingabe für EINGABENAME & btn für enter
        - const list = new List(EINGABENAME)
        - const list safe in local storage
            - eingabename+key
        - refresh()
    - refresh()
        - update leftContainer die Listen
            nehme liste id
            lösche daten der liste
            fügen li hinzu mit Name aus local storage
        - update rightContainer die Listen
            - build() 
    - build()
        while liste.lenght {
            div 
            Hacken  Name der List           Prio Date    
                    darunter description
            Daten werden aus der Liste entnommen vom local storage

        }

Storage
    -  pro Liste ein JSON String
       
        
        
        
        
