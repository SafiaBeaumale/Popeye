# POPEYE - Embarquez pour le monde incroyable des conteneurs !

<img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/00/Popeye_the_Sailor.png/220px-Popeye_the_Sailor.png" height=100 align="left">
<br></br>
Popeye, est un projet avec pour objectifs de comprendre la conteneurisation avec Docker et de définir le deploiement d'une application de sondage web.

<br></br>
<img src="https://user-images.githubusercontent.com/91611187/234561013-4f34665d-7626-4c8a-b4ad-e34d905775a4.png" height=40" align="left">
<div align="left"<b>SKILLS DOCKER</b>:</div>
- Comprendre la conteneurisation
<br></br>
- Création de dockerfile
<br></br>
- Gestion d'image
</p>

DESCRIPTION
Conteneuriser et définir le déploiement d'une simple application de sondage Web.
Il y a cinq éléments constituant la demande :
- Poll, une application Web Flask Python qui rassemble les votes et les place dans une file d'attente Redis.
- Une file d'attente Redis, qui contient les votes envoyés par l'application Poll, en attendant qu'ils soient consommés par
le travailleur.
- The Worker, une application Java qui consomme les votes se trouvant dans la file d'attente Redis, et les stocke dans
une base de données PostgreSQL.
- Une base de données PostgreSQL, qui stocke (en permanence) les votes stockés par le Worker.
- Résultat, une application web Node.js qui récupère les votes de la base de données et affiche les bon, résultat.
