# Cahier des charges

## Contexte
Dans un cadre ou les communautés de musique sont souvent divisées en petites communautés sur internet, le MusiVerse vient en liant de ces communautés, proposant une plateforme de partage, une encyclopédie communautaire et une expérience basée autour du regroupement de ces petits groupes.

## Objectifs
- Centraliser les informations sur des outils ou instruments en lien avec la musique:
  - Gain de temps lors de la recherche


- Partage d'avis sur l'objet
  - Fiabiliser les informations

## Acteurs
- Administrateur: Plus haut grade de gestion
- Modérateur: Modère les modifications sur les publications et les commentaires
- Contributeur: Publie, édite et commente 
- Visiteur: Peut accéder aux publications

## Périmètre du système
![Use Case MusiVerse](../assets/useCaseMusicVerse.jpg)

## Règles métiers
RGPD, lien vers site extérieur (conditions d'utilisations du site en question etc...).

## Description des cas d'utilisation

### Créer un compte
| Cas d'utilisation         | Nom                   |
|---------------------------|-----------------------|
| Acteur primaire           | Visiteur              |
| Système                   | Système global        |
| Date de création          | 20/04/2023            |
| Date de modification      | 20/04/2023            |
| Auteur de la modification | Côme PICARD           |
| Précondition              | Ne pas être identifié |

| Opérations :  | Description                               |
|---------------|-------------------------------------------|
| 1             | Choisir l'action de connexion             |
| 2             | Choisir l'option "Créer un compte"        |
| 3             | Renseigner les _informations_ du compte   |
| 4             | Le système envoie un code à l'utilisateur |
| 5             | Remplir le code envoyé par mail           |
| 6             | Confirmer la création du compte           |




## Exigences fonctionnelles
- Le système doit afficher la liste de tous les équipements
- Le système doit afficher le détail d'un équipement choisi
- Le système doit pouvoir filtrer la liste des équipements
- Le système doit permettre à tout contributeur d'ajouter un équipement
- Le système doit permettre à un administrateur de gérer le compte d'un modérateur ou d'un contributeur
- Le système doit permettre à un modérateur de gérer le compte d'un contributeur
- Le système doit permettre à un contributeur d'approuver ou de désapprouver un aspect ou un commentaire de l'équipement
- Le système doit permettre à un contributeur de poster un commentaire sur un équipement

## Exigences non-fonctionnelles
- L'expérience utilisateur doit être fluide et intuitive
- Le système doit être léger et le plus réactif possible

## Contraintes


## Prestation attendues
1. [Planning]()
2. [Guide de démarrage]()
3. [Documentation]()
## Annexe

### Dictionnaire des données

| Nom                | Label              | Type               | Taille             |
|--------------------|--------------------|--------------------|--------------------|
| Colonne 1, Ligne 1 | Colonne 2, Ligne 1 | Colonne 3, Ligne 1 | Colonne 4, Ligne 1 |