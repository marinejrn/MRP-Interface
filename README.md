
# Système de Planification des Besoins en Matériel (MRP) 🚀  
Ce projet est une application web basée sur Flask conçue pour gérer efficacement les données de Planification des Besoins en Matériel (MRP). 

Dans ce projet nous prenons le cas d'une entreprise de skateboard. 🛹  

L'application permet aux utilisateurs de saisir et de traiter les Besoins Bruts et les Quantités Disponibles, tout en mettant à jour un fichier Excel en temps réel. Une interface intuitive et une intégration fluide des fichiers Excel en font un outil idéal pour la gestion des données dans la chaîne d'approvisionnement.

## Fonctionnalités principales ✨

🔐 Système de connexion sécurisé : Accès uniquement avec des identifiants valides.

🗂️ Workflow étape par étape :
- Saisir les Besoins Bruts hebdomadaires.  
- Saisir les Quantités Disponibles pour des catégories prédéfinies (Skateboards, Boards...).
 
🔄 Mises à jour dynamiques :
Affichage des messages de succès ou d'erreur sur une page de confirmation.

📊 Intégration des fichiers Excel :
Téléchargez le fichier Excel par défaut ou spécifiez un fichier personnalisé à modifier.
  
💻 Interface responsive :
Design moderne et intuitif grâce à HTML/CSS.

## Technologies utilisées 💡
- Python avec Flask : Développement backend et routage.
- HTML/CSS : Interface utilisateur responsive et esthétique.
- openpyxl : Lecture, écriture et modification des fichiers Excel.
- Bootstrap (optionnel) : Amélioration du design et de la responsivité.

## Un aperçu ? 👀
En premier nous avons la page d'authentification (en local depuis VSCode) :
![image](https://github.com/user-attachments/assets/ccfd0208-8d91-4108-9c92-b38487561302)

Ensuite l'utilisateur doit telecharger le fichier excel automatisé et entrer le chemin d'accès jusqu'à ce fichier : 
![image](https://github.com/user-attachments/assets/82a4d781-428e-40ff-8fa6-ba97d59a4528)

Enfin il a accès à l'interface pour pouvoir entrer les quantités qu'il souhaite produire par semaine et son stock actuel : 
![image](https://github.com/user-attachments/assets/22042c12-39a5-4157-b7ae-febe39ef80cc)

![image](https://github.com/user-attachments/assets/f4cc7418-7f5d-41a7-b377-2886dfa15def)
