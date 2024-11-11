Projet realisé Par Moukrim El MOSTAPHA et VIVIEN MARION

------------------------------------PARTIE BACKEND-------------------------------------------

# login.html et signup.html sont respectivement un formulaire de connexion et un formulaire d'inscription utilisant Firebase Authentification.

Pour s'inscrire :
l'utilisateur remplit le formulaire avec une adresse e-mail, un mot de passe et un nom d'utilisateur, puis clique sur le bouton "Sign up".
Le programme récupère les valeurs saisies par l'utilisateur.
Il utilise la fonction createUserWithEmailAndPassword de Firebase Auth pour créer un nouvel utilisateur avec l'adresse e-mail et le mot de passe fournis.
Une fois l'utilisateur créé avec succès, le programme enregistre également le nom d'utilisateur et l'adresse e-mail dans notre base de données Firebase en utilisant la fonction set avec une référence appropriée.
Enfin, il affiche une boîte de dialogue pour informer l'utilisateur que son compte a été créé avec succès. Si une erreur se produit lors de la création de l'utilisateur, il affiche un message d'erreur approprié.

Pour la connexion :
l'utilisateur saisit son adresse e-mail et son mot de passe, puis clique sur le bouton "Login".
Le programme récupère les valeurs saisies par l'utilisateur.
Il utilise la fonction signInWithEmailAndPassword de Firebase Auth pour tenter de connecter l'utilisateur avec l'adresse e-mail et le mot de passe fournis.
Si la connexion est réussie, le programme met à jour la date et l'heure de la dernière connexion de l'utilisateur dans notre base de données Firebase en utilisant la fonction update avec une référence appropriée.
Ensuite, il affiche une boîte de dialogue avec le message "Vous êtes connecté ! Veuillez retourner sur la page du site." pour informer l'utilisateur que sa connexion a réussi. Si une erreur se produit lors de la connexion, il affiche un message d'erreur approprié.

----------------------------------PARTIE FRONTEND------------------------------------------------

Ce projet web est un site de vente de vêtements réalisé en JavaScript/CSS/HTML. Vous pouvez parcourir une liste de produits dans différentes pages, les ajouter au panier, de les supprimer du panier et de passer à la caisse pour effectuer un achat (fonctionnalité de paiement non-ajoutée). Vous pouvez vous inscrire et alors, votre compte sera enregistré dans une base de donnée gérée par firebase. Vous aurez la capacité après de vous connecter. Si vos identifiants ne respectent pas certaines règles (mot de passe assez long, adresse mail valide ...) un message d'erreur adapté vous sera renvoyé.

## Fonctionnalités

- Affichage des produits disponibles sur différent onglets
- Ajout de produits au panier
- Suppression de produits du panier
- Calcul du total du panier
- Vidage complet du panier
- Validation de l'achat

## Comment utiliser

1. Clonez ce dépôt sur votre machine locale.
2. Ouvrez le fichier `web.html` dans votre navigateur page d'accueil.
- [Accueil](#accueil) : Permet de revenir à la page d'accueil.
- [Hommes](#hommes) : Affiche les produits pour hommes.
- [Femmes](#femmes) : Affiche les produits pour femmes.
- [Accessoires](#accessoires) : Affiche les produits d'accessoires.

3. Parcourez la liste des produits disponibles.
4. Cliquez sur le bouton "Ajouter au panier" pour ajouter un produit au panier.
5. Pour supprimer un produit du panier, cliquez sur le bouton "Supprimer" à côté du produit correspondant.
6. Pour vider complètement le panier, cliquez sur le bouton "Vider le panier".
7. Pour passer à la caisse et effectuer un achat, cliquez sur le bouton "Paiement".



# script.js est un fichier en javascript qui permet d'utiliser un panier et contient donc toutes les fonctions pour l'utiliser

# toutes les images sont en .jpg/.avif/.png

# accessoires.html, web.html, homme.html, femme.html

Affichage du site avec un en-tête, une section avec la barre supérieure, un pied de page, le panier, les catégories, les produits avec des images, des prix, boutons d'ajout.

# web.css, demo.css et cssFile.css utilise la bibliothèque css pour disposer les éléments du site, les couleurs, formes etc