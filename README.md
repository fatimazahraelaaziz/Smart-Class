# Smart Class - Application Mobile

## Description

Cette application mobile est destinée aux étudiants pour automatiser le processus de vérification de présence en utilisant des codes QR. Elle permet aux étudiants de scanner des codes pour le check-in et le check-out des cours, offrant une vue d'ensemble sur leurs présences et facilitant ainsi la gestion des absences par l'administration. 

Cette application est liée à une plateforme principalement conçue pour l’administration, qui a accès à toutes les informations concernant les étudiants et répertorie leurs absences. De ce fait, cette plateforme facilite le calcul des IPE (Interdiction au Passage d'Évaluation). 

Le lien du repo GitHub de la plateforme est : [Smart Class Platform](https://github.com/maryamtamlalti2001/Smart-Class-).

## Fonctionnalités

### Authentification
- Les étudiants doivent s'authentifier avec un nom d'utilisateur et un mot de passe fournis par l'administration.
- Après la connexion, les étudiants doivent remplir leurs informations personnelles.

### Vérification de présence par code QR
- Les étudiants peuvent scanner un code QR au début et à la fin de chaque séance pour enregistrer leur présence.
- L'heure exacte du check-in et du check-out s'affiche automatiquement après chaque scan.
- Une fonctionnalité de localisation est incluse lors du scan.

### Vue d’ensemble sur les présences
- Les étudiants peuvent consulter les jours et heures de présence pour chaque mois.
- Les détails de présence sont affichés pour chaque jour sélectionné.

## Technologies Utilisées
- **Framework:** Flutter

## Installation
1. Clonez le dépôt:
   ```sh
   git clone https://github.com/votre-repo/application-mobile.git

2. Accédez au répertoire du projet:
 ```sh
cd application-mobile
```
3. Installez les dépendances:
 ```sh
flutter pub get
```
4. Exécutez l'application:
 ```sh
flutter run
```

## Contribuer
- Forkez le projet.
- Créez votre branche de fonctionnalité (git checkout -b feature/AmazingFeature).
- Commitez vos modifications (git commit -m 'Add some AmazingFeature').
- Poussez vers la branche (git push origin feature/AmazingFeature).
- Ouvrez une Pull Request.

## Documentation

Pour plus de détails sur chaque étape, veuillez consulter la [documentation](https://github.com/fatimazahraelaaziz/Smart-Class/edit/master/Rapport_Smart_Class.pdf) associée ci-dessus.
