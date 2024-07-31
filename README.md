# kodeklour-engineer-docker-level3.2-mapping-volume
L'équipe Nautilus DevOps teste la conteneurisation des applications, qui devrait bientôt être migrée sur des environnements basés sur des conteneurs Docker. Lors de la réunion debout d'aujourd'hui, l'un des membres de l'équipe s'est vu confier la tâche de créer et de tester un conteneur Docker répondant à certaines exigences. Vous trouverez ci-dessous plus de détails :


un. Sur App Server 1 dans Stratos DC, extrayez l'image nginx (de préférence la dernière balise mais d'autres devraient également fonctionner).


b. Créez un nouveau conteneur avec le nom ecommerce à partir de l'image que vous venez d'extraire.


c. Mappez le volume hôte /opt/data avec le volume conteneur /home. Il existe un fichier sample.txt présent sur le même serveur sous /tmp ; copiez ce fichier dans /opt/data. Veuillez également garder le conteneur en état de fonctionnement.
