# POPEYE - Embarquez pour le monde incroyable des conteneurs

<img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/00/Popeye_the_Sailor.png/220px-Popeye_the_Sailor.png" height=100 align="left">
<br></br>
<p>Popeye, est un projet avec pour objectifs de comprendre la conteneurisation avec Docker et de définir le deploiement d'une application de sondage web.</p>
<br></br>
<div align="center">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/image_readme/conserve_sf.png" height=40" align="center">
  <p><b>SKILLS DOCKER :</b></p>
  <p>Comprendre la conteneurisation</p>
  <p>Création de dockerfile</p>
  <p>Gestion d'image</p>
</div>
<br></br>
<div align="center">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/image_readme/olive_sf.png" height=60 align="center">
  <p><b>DESCRIPTION :</b></p>
  <p>Conteneuriser et définir le déploiement d'une simple application de sondage Web.</p>
  <p>Il y a cinq éléments constituant la demande :</p>
</div>

<div align="left">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/image_readme/flask_sf%20(1).png" height=30 align="left">
  <p align="left">Poll, une application Web Flask Python qui rassemble les votes et les place dans une file d'attente Redis.</p>
</div>

<div align="left">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/image_readme/redis_sf%20(1).png" height=30 align="left">
  <p align="left">Une file d'attente Redis, qui contient les votes envoyés par l'application Poll, en attendant qu'ils soient consommés par
  le worker.</p>
</div>

<div align="left">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/image_readme/java_sf%20(1).png" height=30 align="left">
  <p align="left">Le Worker, une application Java qui consomme les votes se trouvant dans la file d'attente Redis, et les stocke dans
  une base de données PostgreSQL.</p>
</div>

<div align="left">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/image_readme/postgresql_sf%20(1).png" height=30 align="left">
  <p align="left">Une base de données PostgreSQL, qui stocke (en permanence) les votes stockés par le Worker.</p>

<div align="left">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/image_readme/node_js_sf(1).png" height=30 align="left">
  <p align="left">Résultat, une application web Node.js qui récupère les votes de la base de données et affiche les bon, résultat.</p>
</div>
<br></br>
<div align="center">
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/image_readme/gontrand_sf.png" height=60 align="center">
  <p><b>SCHÉMA :</b></p>
  <img src="https://github.com/SafiaBeaumale/Popeye/blob/main/image_readme/schema.png" height=300 width=500 align="center">
</div>
  
