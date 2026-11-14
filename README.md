# Cash-Cash

Budget et investissement, avec des données stockées uniquement sur votre PC.

## Télécharger

**[⬇ Télécharger l'installateur pour Windows](https://github.com/Nemeth-NM/cash-cash-releases/releases/latest/download/Cash-Cash-Programme-win-Setup.exe)**

Ce lien donne toujours la dernière version. Elle fonctionne sous Windows 10 ou 11, en 64 bits.

> N'utilisez pas le bouton vert **Code → Download ZIP** de cette page : il ne télécharge que ce texte, pas l'application.

## Installer

1. Lancez `Cash-Cash-Programme-win-Setup.exe`.
2. Windows peut afficher « Windows a protégé votre ordinateur ». L'application n'est pas signée par un éditeur payant, d'où ce message. Cliquez sur **Informations complémentaires**, puis **Exécuter quand même**.
3. L'installation se fait sans droits d'administrateur, et Cash-Cash s'ouvre aussitôt. Un raccourci est créé dans le menu Démarrer.

## Premiers pas

- **Pour essayer** : choisissez **Créer un profil de démonstration**. Ses données sont inventées, et vous pourrez le supprimer ensuite.
- **Pour vos comptes** : créez votre profil et choisissez un mot de passe. Vos données sont alors chiffrées.
- **Notez la clé de récupération** affichée à la création, et gardez-la en lieu sûr. Elle n'est montrée qu'une fois. Sans votre mot de passe et sans elle, personne ne peut rouvrir vos données, pas même l'auteur de l'application.
- **Importez vos relevés** : téléchargez-les depuis l'espace client de votre banque, au format OFX, QIF ou CSV (Caisse d'Épargne), puis ouvrez la page **Import**.
- Le profil se verrouille après une période d'inactivité, réglable dans **Sécurité du profil** (menu en haut à droite).

Plusieurs personnes peuvent utiliser le même PC : chacune a son profil et son mot de passe.

## Vos données

- Elles restent sur votre PC, dans `%LocalAppData%\Cash-Cash`, et ne sont jamais envoyées ailleurs.
- Le seul accès à Internet sert à vérifier, au lancement, si une nouvelle version existe. Vous pouvez le désactiver dans **Application et mises à jour**.
- Une sauvegarde automatique est faite à chaque ouverture d'un profil. Les dix dernières sont conservées.

## Mettre à jour

Quand une nouvelle version existe, un bandeau le signale. Elle ne se télécharge que si vous cliquez dessus. Vos données sont conservées.

## Désinstaller

Dans **Paramètres Windows → Applications**, désinstallez **Cash-Cash**. Vos données sont conservées, au cas où vous réinstalleriez. Pour tout effacer, supprimez aussi le dossier `%LocalAppData%\Cash-Cash`.
