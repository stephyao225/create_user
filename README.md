# create_user
creation de compte utilsateur depuis un fichier csv en mass avec ansible 

Ansible propose un module user dédié à la gestion des comptes utilisateurs sur vos systèmes. Il permet de créer, modifier et supprimer des utilisateurs, ainsi que de définir leurs attributs.

  ETapes
  Créez un fichier inventory.yaml qui liste les hôtes sur lesquels vous souhaitez créer des comptes utilisateurs.
  Créez un fichier playbook (par exemple creer_comptes.yml) qui définit les tâches à exécuter.
  Utilisez le module user avec l'état present pour créer les utilisateurs
  Utilisez la commande ansible-playbook pour exécuter le playbook et créer les users 
