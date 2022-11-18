PROJET 7 – GROUPOMANIA

---

Installation de l’application

---

Backend

Le backend a été réalisé avec Node.js, Express.js et avec la base de données MongoDB

Installation :

Configuration du backend :
Mettre les informations du cluster de la base de données dans /config/db.js, pour cela il faut créer un fichier .env dans /config/ en mettant les informations suivantes :

- PORT= 5000
- CLIENT_URL =http://localhost :3000
- DB_USER_PASS=groupomania:Socialsite2022
- TOKEN_SECRET= 990bf68e6adf1be5f1671bba3bec6920569224545f1f7d7b587b48beed277bc11936881ff5ad
  Ensuite dans le terminal il faut écrire :
  Cd backend, puis npm install et ensuite npm start

Frontend

Configuration du frontend :
Créer un fichier.env et mettre l’information suivante :

- REACT_APP_API_URL=http://localhost:5000/

Ensuite dans le terminal il faut écrire:
cd frontend, puis npm install, puis npm start
