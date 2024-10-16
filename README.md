# Wiki Chocopoly IT

Jusqu'à ce que Chocopoly devienne (très probablement) une commission de l'AGEPOLY, l'association dispose de son propre serveur VPS chez Pulseheberg pour héberger ses services IT.

Une instance caprover est utilisé (permet de déployer des images docker facilement) : https://captain.sys.chocopoly.ch. Le mot de passe est disponible dans le repo de secrets.

Pour modifier un repo, un simple push suffit et la CI met à jour le site automatiquement.

Les services :
* le site web public
* le site web interne pour les staff (permet de s'enregistrer pour staffer à un évènement)
* le bot Telegram (pour gérer les stocks)

## Site web interne (staff)

URL: https://staff.chocopoly.ch  
Repo: https://github.com/chocopoly-epfl/chocopoly-site-staff

Les données peuvent être visualisées via PHPMyAdmin: https://chocopoly-phpmyadmin.sys.chocopoly.ch (mdp sur le repo de secrets)

## Site web public

URL: https://chocopoly.ch  
Repo: https://github.com/chocopoly-epfl/chocopoly-site-public

Les données peuvent être visualisées via PGAdmin: https://chocopoly-pgadmin.sys.chocopoly.ch (mdp sur le repo de secrets)

## Telegram Bot

Repo: https://github.com/chocopoly-epfl/chocopoly-telegram-bot
