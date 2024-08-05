# Mise en place de sémaphore

### Définir un Dockerfile

* MYSQL
  - Prendre la configuration par défaut de mysql.
  - Changer l'endroit du stockage de donnée (volume).

* Semaphore
  - Prendre la configuration par défaut.
  - Changer les éléments nécessaire (mot de passe)

* Volumes :
  - Ajouter des volumes en fonction de vos besoins (data:)

### Création de groupes et de users

* Utiliser l'inventaire présent dans `` enalean-infrastructure.git/roles/enalean_users_sysadmin/tasks/ ``
* Ajouter les groupes via `` enalean-infrastructure.git/inventory/group_vars/all/ `

# Les prérequis d'un template

* Playbook repository (github)
* Playbook filename
* Un inventaire
* Une clé SSH

# Connection Okta

Toutes les informations sont disponibles à ``enalean-infrastructure.git/roles/enalean_monitoring/templates/etc/grafana/grafana.ini.j2``
