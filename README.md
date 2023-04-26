# POPEYE - Embarquez pour le monde incroyable des conteneurs !

<img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/00/Popeye_the_Sailor.png/220px-Popeye_the_Sailor.png" height=100 align="left">
<br></br>
<p>Popeye, est un projet avec pour objectifs de comprendre la conteneurisation avec Docker et de définir le deploiement d'une application de sondage web.</p>

<div align="center">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/conserve_sf.png" height=40" align="center">
  <p><b>SKILLS DOCKER :</b></p>
  <p>Comprendre la conteneurisation</p>
  <p>Création de dockerfile</p>
  <p>Gestion d'image</p>
</div>
<br></br>
<div align="center">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/olive_sf.png" height=60 align="center">
  <p><b>DESCRIPTION :</b></p>
  <p>Conteneuriser et définir le déploiement d'une simple application de sondage Web.</p>
  <p>Il y a cinq éléments constituant la demande :</p>
</div>

 <div align="left">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/flask_sf.png" height="40" align="left">
  <p>Poll, une application Web Flask Python qui rassemble les votes et les place dans une file d'attente Redis.</p>
</div>

  <p>- Une file d'attente Redis, qui contient les votes envoyés par l'application Poll, en attendant qu'ils soient consommés par
  le travailleur.</p>
  <p>- The Worker, une application Java qui consomme les votes se trouvant dans la file d'attente Redis, et les stocke dans
  une base de données PostgreSQL.</p>
  <p>- Une base de données PostgreSQL, qui stocke (en permanence) les votes stockés par le Worker.</p>
  <p>- Résultat, une application web Node.js qui récupère les votes de la base de données et affiche les bon, résultat.</p>
</div>
