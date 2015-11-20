# rapport-stage
Rapport de stage à la DSI de la mairie de Nouméa du 28/10/2015 au 20/11/2015.

pré-requis :

* installer correctement pandoc [ici](http://pandoc.org/installing.html]


pour générer le pdf, on utilise la commande :

    pandoc rapport.md -o files/rapport.pdf -V fontsize=12pt -V linestretch=1 -V linkcolor=black --number-sections --table-of-contents -V documentclass=scrreprt -V lang=french 

vous pouvez le consulter [ici](files/rapport.pdf "rapport")
