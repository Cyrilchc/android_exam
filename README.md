# Examen

## Récupération du projet

## Exercices

1. Ajouter les contraintes dans les fichiers de layout (1 point)

2. Ajouter les getters/setters dans la classe de l'entité `Contact.java` (1 point)

3. Ajouter les requêtes dans l'interface de DAO `ContactDAO.java` (1 point)

4. Compléter la classe de ViewModel `ContactViewModel.java` (3 points)

5. Compléter la classe de base de données `Database.java` (1 points)

   * Compléter l'annotation afin de définir le schema
   * Compléter le code
   
6. Compléter la classe `ContactAdapter.java` afin d'afficher le contenu d'une entrée dans la base (2 points)

7. Compléter la classe `MainActivity.java`: (6 points)
   
   * Ajouter les listeners
      * Sur le bouton d'ajout
      * Clic sur la liste afin de permettre l'édition
      * Clic long sur la liste afin de permettre la suppression
   * Ajouter le code pour démarrer l'activité `EditActivity.java` pour ajouter une nouvelle entrée
   * Ajouter le code pour démarrer l'activité `EditActivity.java` pour éditer une entrée existante
   * Ajouter le code pour demander la suppression et effectuer la suppression si validée par l'utilisateur
   * Ajouter le code pour afficher le contenu de la base de données dans la liste

8. Compléter la classe `EditActivity.java`: (5 points)

   * Ajouter le bouton de retour
   * Ajouter le menu `edit_menu.xml`
   * Gérer le bouton de retour afin de fermer l'activité
   * Gérer la sauvegarde au clic sur le bouton de sauvegarde du menu
   * Récupérer le contenu du contact passé en paramètres