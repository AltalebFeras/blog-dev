# Cahier des Charges (BLOG DEV)

## 1. Contexte

Vous devez créer un blog qui présente les différents articles publiés de façon publique sur le blog. Ce blog sera accessible au tout public et servira à présenter les articles, de les rechercher par catégories, de les rechercher par date de publications, de les commenter et de les liker.  
Les administrateurs pourront gérer les articles, c’est-à-dire les supprimer et il pourra faire de même avec les utilisateurs.

## 2. Administration

La partie administration sera accessible par l’adresse du serveur back. Seuls les administrateurs pourront y accéder.  
L’administrateur ne peut que se connecter via un formulaire de connexion déconnexion.  
Les administrateurs pourront supprimer tous les articles publiés et pourront aussi supprimer tous les comptes présents sur la plateforme. Les administrateurs pourront modifier leur compte (nom, prénom, mail, mot de passe) mais ils ne pourront pas les supprimer.  
Chaque utilisateur pourra modifier les articles qu’il aura publiés, il pourra modifier son compte (nom, prénom, mail, mot de passe), et le supprimer.  
Lorsque l’utilisateur valide son compte par mail, l’administrateur en est informé par mail afin de confirmer ou de refuser la validation du compte.  
Chaque article devra être confirmé par l’administrateur avant qu’il ne soit publié.

## 3. Interface Grand Public

Dès votre arrivée sur le site, la page d’accueil sera visible avec tous les articles en statut public de tous les utilisateurs en fonction du plus récent publié. Il y aura des filtres en fonction des catégories et de la date (Catégories d’articles : front-end, UI/UX, Back-end, Design).  
Il sera possible de voir les détails des articles publiés.  
Une page de formulaire sera dédiée à l’inscription et la connexion des utilisateurs.  
Lorsque l’utilisateur sera connecté à son compte, il aura accès à un tableau de bord qui lui permettra de publier des articles, en précisant dans quelle catégorie se trouve l’article.  
Lors de la publication de l’article, il faudra que la date de publication et l’auteur de l’article soit visible dans les informations liées à cet article.

## 4. Technique

- L’administration ne sera accessible qu’aux admins
- Les mots de passes sont chiffrés
- Validation du compte par un lien envoyé par mail

## 5. Options (Facultatif)

- Barre de recherche par titre et contenu des articles sur la page d’accueil
- Pagination jusqu’à 10 articles par page
- Envoi d’un mail pour un nouveau mot de passe (bouton mot de passe oublié)
- Ajouter et supprimer une image sur le profil utilisateur
- Envoie de mail pour confirmer  la suppression du compte utilisateur

[link figma](https://www.figma.com/design/jlA8UTDomowAV8TbKN8whn/Untitled?t=rTaAryHnQVwmUjDw-0)
