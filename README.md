# Monter un HAProxy et deux serveurs Apaches

 ## Installation de Docker (Debian / Ubuntu)
 sudo apt update<br/>
 sudo apt install docker.io<br/>
 sudo usermod -aG docker $USER<br/>
 sudo apt install docker-compose<br/>

 ## Lancer le docker compose
 docker-compose up -d

 ## Arrêter le docker compose
 docker-compose down

 ## Adresses IP (Non exposées)
 Serveur Web 1 : 192.168.0.11<br/>
 Serveur Web 2 : 192.168.0.22<br/>
 HA Proxy : 192.168.0.33<br/>
