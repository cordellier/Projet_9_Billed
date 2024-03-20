# Frontend

**Organisation de l'espace de travail :**

**Création du dossier de travail :**
Créez un dossier nommé "bill-app" dans lequel vous allez cloner le projet backend et frontend.

**Clonage du projet backend :**
git clone https://github.com/OpenClassrooms-Student-Center/Billed-app-FR-Back.git

**Clonage du projet frontend :**
git clone https://github.com/OpenClassrooms-Student-Center/Billed-app-FR-Front.git

**Votre structure de dossier devrait ressembler à ceci :**
bill-app/

- Billed-app-FR-Back
- Billed-app-FR-Front

**Comment lancer l'application en local ?**

## Étape 1 - Lancer le backend :

Suivez les indications dans le README du projet backend.

## Étape 2 - Lancer le frontend :

**Allez au répertoire cloné :**
cd Billed-app-FR-Front

**Installation des packages npm :**
npm install

**Installation de live-server pour lancer un serveur local :**
npm install -g live-server

**Lancement de l'application :**
live-server

[Accédez à l'adresse](http://127.0.0.1:8080/)

**Comment lancer tous les tests en local avec Jest ?**
npm run test

**Comment lancer un seul test ?**
Installez jest-cli :
npm i -g jest-cli
jest src/**tests**/your_test_file.js

**Comment voir la couverture de test ?**
http://127.0.0.1:8080/coverage/lcov-report/

## Comptes et utilisateurs :

Vous pouvez vous connecter en utilisant les comptes suivants :

## Administrateur :

Utilisateur : admin@test.tld
Mot de passe : admin

## Employé :

Utilisateur : employee@test.tld
Mot de passe : employee
