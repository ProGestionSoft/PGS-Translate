# Guide de Contribution - PGSTranslate

Merci de contribuer à **PGSTranslate** ! Ce guide vous explique comment participer au projet de manière efficace. Nous accueillons vos propositions pour ajouter ou améliorer les traductions de PRO GESTION SOFT sur ses différentes plateformes.

---

## 🛠️ Étapes pour contribuer

### 1. **Forkez le dépôt**
Créez une copie de ce dépôt dans votre compte GitHub en cliquant sur le bouton "Fork".

### 2. **Clonez votre fork**
Clonez votre dépôt localement pour y apporter des modifications :

```bash
git clone https://github.com/<votre-utilisateur>/PGSTranslate.git
cd PGSTranslate
```

### 3. Créez une nouvelle branche
Créez une branche spécifique pour vos modifications :

```bash
git checkout -b ajout-traduction-[langue]-[plateforme]
```

### 4. Modifiez les fichiers
Naviguez dans le répertoire translations pour trouver les fichiers correspondant à la plateforme et à la langue que vous souhaitez modifier. Exemple pour le logiciel :

```bash
translations/
├── software/
│   ├── en.json
│   ├── fr.json
│   └── es.json
```

***Format attendu des fichiers JSON***
- Utilisez une structure clé-valeur.
- Les clés doivent rester identiques pour toutes les langues.

Exemple :
```bash
{
    "welcome_message": "Bienvenue sur PRO GESTION SOFT !",
    "login_button": "Se connecter"
}
```

### 5. Testez vos modifications
Assurez-vous que vos modifications respectent le format JSON :

```bash
npm install -g jsonlint
jsonlint translations/software/fr.json
```

### 6. Soumettez une Pull Request
Une fois vos modifications terminées :

```bash
git add .
git commit -m "Ajout d'une traduction pour [langue] sur [plateforme]"
git push origin ajout-traduction-[langue]-[plateforme]
```

Rendez-vous sur la page de votre dépôt forké et créez une Pull Request vers la branche principale (main) de ce dépôt.

## ✅ Règles à respecter
### 1. Respect du format JSON :
- Vérifiez que vos fichiers sont correctement formatés.
- Toutes les clés doivent être présentes pour chaque langue.

### 2. Cohérence des traductions :
- Maintenez un ton professionnel.
- Évitez les abréviations ou le langage informel.

### 3. Clarté des contributions :
- Incluez une description détaillée dans vos Pull Requests.
- Mentionnez la plateforme et la langue concernées.

### 4. Documentation :

Si vous ajoutez une nouvelle clé, fournissez une description de son utilisation dans votre Pull Request.

## 🚀 Proposer des idées ou signaler un problème
Pour signaler une erreur ou proposer une nouvelle fonctionnalité, ouvrez une issue avec les informations suivantes :

- ***Plateforme concernée*** (logiciel, site de recrutement, etc.).
- ***Langue*** : La langue concernée par votre demande.
- ***Description*** : Expliquez clairement le problème ou l'idée.


## 🔧 Processus de validation
Nous utilisons GitHub Actions pour vérifier les contributions. Ces validations incluent :

- Vérification du format JSON.
- Vérification que toutes les clés sont présentes pour chaque langue.
Les mainteneurs examineront vos modifications avant qu'elles ne soient fusionnées dans la branche principale.

---
Merci de participer à l'amélioration de PRO GESTION SOFT ! Votre contribution aide à rendre notre solution accessible à davantage d'utilisateurs à travers le monde. Si vous avez des questions, n'hésitez pas à ouvrir une issue.

Bon travail et merci pour votre aide précieuse ! 🚀
