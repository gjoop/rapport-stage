# rapport-stage
Bienvenue dans le dépot GitHub de mon rapport de stage à la DSI de la Mairie de Nouméa s'étant déroulé du 28/10/2015
au 20/11/2015.

Celui-ci à été rédigé avec le Markdown modifiée de Pandoc.
Vous trouverez ici toutes les sources utilisées.

pré-requis :

* installer correctement pandoc [ici](http://pandoc.org/installing.html)


pour générer le pdf, on utilise la commande :

    pandoc rapport.md -o files/rapport.pdf -V fontsize=12pt -V linestretch=1 -V linkcolor=black --number-sections --table-of-contents -V documentclass=scrreprt -V lang=french 

vous pouvez le consulter [ici](files/rapport.pdf "rapport")
