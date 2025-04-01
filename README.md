Projet : Mini Gestionnaire de Tâches Collaboratif

🎯 Objectifs pédagogiques
Créer une application web dynamique en Java avec JSP. Utiliser la programmation orientée objet (POO). Manipuler des collections d’objets Java
📚 Contexte
Dans le cadre de votre module sur la programmation Java, vous devez créer une application web simple permettant à un utilisateur de :
- Ajouter des tâches
- Consulter la liste de ses tâches

Chaque tâche doit contenir :
- Un titre
- Une description

Les tâches doivent être conservées le temps de la session de l’utilisateur (pas besoin de base de données).
🔧 Contraintes techniques
• Créer une classe Java représentant une tâche (Task) avec des attributs privés.
• L’ajout de tâches se fait via un formulaire HTML dans une page JSP
• Les tâches sont enregistrées dans une liste stockée en session (type ArrayList<Task>)
• L'affichage des tâches utilise une boucle dans une page JSP
• Le projet doit pouvoir être déployé dans un serveur Apache Tomcat
http://ec2-15-237-202-85.eu-west-3.compute.amazonaws.com/{votre_prénom}
✅ Fonctionnalités attendues
Fonction	Détail
Ajouter une tâche	Formulaire dans une page JSP
Afficher les tâches	Liste visible avec titre et description
Accueil	Page d'accueil avec navigation vers les autres fonctionnalités
Suppression d’une tâche	Permettre la suppression d'une tâche
Date d’échéance	La tâche contiendra une « date d’échéance »
Tâche terminée	Permettre de marquer une tâche comme terminée
📅 Durée estimée
Temps de réalisation estimé : 4 heures.
💼 Livrables attendus
•	Le lien URL de votre Repository GitHub contenant l'application fonctionnelle : JSP, classe(s) Java (Task.java), fichier web.xml.
•	Votre application disponible sur le serveur AWS suivant : 
http://ec2-15-237-202-85.eu-west-3.compute.amazonaws.com/{votre_prénom}
