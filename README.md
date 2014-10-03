#Cheat-sheets Briony Den Haese

##1) Initiele setup voor bestanden via terminal up te loaden op bitbucket
* mkdir /path/to/your/project *Hier kan je gewoon een map aanmaken om vanuit deze map te werken*
* cd /path/to/your/project
* git init
* git remote add origin *link naar bitbucket die hier nodig is, bij mij was dit https://BrionyDH@bitbucket.org/sebastienpattyn/labo-taken.git*

Het volgende is om een klein bestand te maken en dit up te loaden:
* echo "Briony Den Haese" >> contributors.txt
* git add contributors.txt
* git commit -m 'Initial commit with contributors'
* git push -u origin master

##2) Een bestand aanpassen in bitbucket
* echo "Sebastien Pattyn" >> contributors.txt *Dit is gewoon een voorbeeld van een aanpassing van een bestand, je kan ook gewoon in de folder een bestand zetten en dit uploaden*
* git add contributors.txt
* git commit -m '*Gekozen tekst bij commit*'
* git push -u origin master

##3)

