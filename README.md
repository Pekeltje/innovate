# NOTICE
In de code moet nog redelijk wat gecomment worden,
er staat al wel het 1 en ander.

# NOTICE
Er moet nog wat meer gesleutelt worden aan het
doorgeven van de posities, het werkt wel
maar de code is spuuglelijk.
Het probleem zit hem in de scope. Het heeft wat onderzoek nodig

# NOTICE
de synchronisatie loopt nog niet lekker, 
Alle spelers updaten wel, maar de 1 kan wat sneller zijn dan de ander.
Dit wordt niet niet gelijkgetrokken, moet nog

/**************************************************
** GIT COMMANDS
**************************************************/
# Stap 1 - voegt alle wijzigingen toe voor de commit
git add --all                                       

# Stap 2 - Het voor stadium om naar git toe te schrijven
git commit -m "Beschrijving van de wijzigingen"  

# Stap 3 - Schrijft de wijzigingen naar het project op Github
git push -u origin master                           
     
     
/**************************************************
** MAP STRUCTURE
**************************************************/
# Hoofdfolder voor alle bestanden
innovate

# folder voor alles wat de players te zien krijgen
client

# plaats voor wat niet een Node Package Module is
lib

# Plaats voor alle node package module 
node_modules

# hier staan de vorige versies van de map innovate
oude snakes


# Hier wordt de server in opgebouwd
game.js

# Dit ziet de gebruiker als die de site bereikt
index.html

# Dit is een identifier van het project, geeft de dependencies weer
package.json

# Dit is een klasse die in game.js wordt gebruikt, het beschrijft de spelers
Player.js

# dit is de README die je nu leest
README.md