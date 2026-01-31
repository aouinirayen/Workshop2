# 🌟 Système de Gestion des Suggestions - Workshop Angular n°2

## 📋 Description
Application Angular pour gérer une liste de suggestions avec fonctionnalités de :
- Affichage des suggestions
- Système de likes
- Ajout aux favoris
- Recherche par titre et catégorie

## 🚀 Installation et Lancement

### 1. Installer les dépendances
```bash
npm install
```

### 2. Lancer l'application
```bash
npm start
```
ou
```bash
ng serve --open
```

L'application s'ouvrira automatiquement dans votre navigateur à l'adresse : `http://localhost:4200`

## 📁 Structure du Projet

```
SuggestionApp/
├── src/
│   ├── app/
│   │   ├── core/
│   │   │   ├── header/          # Composant en-tête
│   │   │   ├── footer/          # Composant pied de page
│   │   │   └── list-suggestion/ # Composant liste des suggestions
│   │   ├── models/
│   │   │   └── suggestion.ts    # Interface Suggestion
│   │   ├── app.component.*      # Composant racine
│   │   └── app.module.ts        # Module principal
│   ├── main.ts                  # Point d'entrée
│   ├── index.html              # Page HTML principale
│   └── styles.css              # Styles globaux
├── angular.json                # Configuration Angular
├── package.json                # Dépendances npm
└── tsconfig.json               # Configuration TypeScript
```

## 🎯 Fonctionnalités Implémentées

### ✅ Data Binding
- **Interpolation** : `{{ suggestion.title }}`
- **Property Binding** : `[class.acceptee]="..."`
- **Event Binding** : `(click)="incrementLikes(...)"`
- **Two-way Binding** : `[(ngModel)]="searchText"`

### ✅ Directives
- **ngFor** : Boucle sur les suggestions
- **ngIf** : Affichage conditionnel des boutons

### ✅ Interface
- Modèle de données `Suggestion` avec typage fort

 ✅ Fonctionnalités Métier
1. **Like** : Incrémente le nombre de likes
2. **Favoris** : Ajoute une suggestion aux favoris
3. **Recherche** : Filtre par titre ou catégorie
4. **Statuts visuels** : Couleurs différentes selon le statut

 🎨 Statuts des Suggestions

- 🟢 **Acceptée** : Bordure verte, boutons visibles
- 🔴 **Refusée** : Bordure rouge, boutons cachés, opacité réduite
- 🟠 **En attente** : Bordure orange, boutons visibles

📚 Concepts Angular Utilisés

1. **Components** : Architecture modulaire
2. **Modules** : Organisation avec NgModule
3. **Services** : (À venir dans les prochains workshops)
4. **Directives** : ngFor, ngIf
5. **Pipes** : date formatting
6. **Forms** : FormsModule pour ngModel

 🔧 Prérequis

- Node.js (v18 ou supérieur)
- npm (v9 ou supérieur)
- Angular CLI (v18)



 
**Workshop** : n°2 - Manipulation des Composants  
