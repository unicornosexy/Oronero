# Oronero

Come pagina iniziale abbiamo la Home Page che mostra il nome dell'hotel e una freccia che ci indirizza verso la pagina principale

Cliccata la freccia abbiamo la posibilità di selezionare tra i 4 riquadri opportunamente incorniciati 

Se clicchiamo sul luogo ci porterà sulla posizione di google maps.
per fare ciò basterà mettere il link fornito da google maps ref

Se clicchiamo sull'orario ci darà i calendari di giugno e luglio con le disponibilità presenti.
per fare le tabelle ho controllato i calendari effettivi di giugno e luglio e li ho riportati in tabelle, ho aggiunto poi i colori per i giorni disponibili (oro) e non (grigio)

Se clicchiamo sui prezzi ci mostrerà le camere.
ho messo le camere in orizzaontale con sotto le descrizioni, per fare ciò ho messo le foto all'interno di section con opportuni centramenti sullo schermo e container che con i comandi display: flex, justify-content:center, e align-items avvicina le varie immagini

Se clicchiamo sulle chat abbiamo le FAQ e sotto le recensioni.
per le domande chieste frequentemente ho sempre usato section e in seguito troviamo 3 recensioni le "stelle" rapresentate come quadrati o mezzi quadrati allineati tra loro, per fare il mezzo quadrato ho fatto un rettangolo e l'ho girato con transform:skewX(deg)

tra le pagine possiamo navigare utilizzando 3 frecce animate, per farle ho utilizzato 3 quadrati, lasciandone solo le estremità di sinitra e basse, le ho girate con  transform: translate( px, px); per fare l'animazione invece ho usato @keyframes animate con le varie percentuali
