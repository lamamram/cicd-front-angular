# FORMATION USINE LOGICIELLE

## l'outil gitlab runner

## clé principales du fichier .gitlab-ci.yml

* nom du job: aribtraire
* **script**: liste de commandes terminal
* **tags**: liste de tags associés à des runners
* **image**: image docker installée sur les conteneurs lancés par les runners
* **stages**: liste des étapes d'exécution du pipeline auxquelles se rattachent les jobs
* **needs**: permet de démarrer un job dès que les jobs en paramètre sont terminés, indépendamment du stage
* **trigger**: demande l'exécution d'un autre pipeline

