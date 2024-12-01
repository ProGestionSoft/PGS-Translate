# PGSTranslate - Proposez des traductions pour PRO GESTION SOFT

Bienvenue dans le dépôt **PGSTranslate**, le projet collaboratif dédié à l'amélioration et l'ajout de traductions pour **PRO GESTION SOFT**. Ce dépôt vous permet de proposer des traductions pour plusieurs plateformes et de contribuer à une meilleure accessibilité de notre solution.

---

## 📚 Plateformes concernées

Les traductions peuvent être proposées pour les plateformes suivantes :
1. **Logiciel de gestion** : Interface utilisateur du logiciel PRO GESTION SOFT.
2. **Site de recrutement** : Plateforme de publication d'offres d'emploi et de gestion des candidatures.
3. **Site vitrine (site d'accueil)** : Présentation et promotion de PRO GESTION SOFT.
4. **Site de documentation** : Guide d'utilisation et API.

---

## 🌍 Langues supportées

- **Langues existantes** : Français, Anglais.
- **Nouvelles langues** : Vous pouvez proposer des traductions pour d'autres langues (ex. Espagnol, Allemand, Arabe, etc.).

---

## 🚀 Comment contribuer ?

Nous accueillons avec plaisir toutes vos contributions, qu'il s'agisse de nouvelles traductions ou d'améliorations des traductions existantes. Suivez ces étapes pour commencer :

### 1. **Clonez le dépôt**
```bash
git clone https://github.com/ProGestionSoft/PGSTranslate.git
```

### 2. Identifiez la plateforme et la langue
Naviguez dans le dossier translations pour trouver les fichiers correspondant à votre contribution :

```bash
translations/
├── software/
├── recruitment-site/
├── documentation-site/
└── ...
```

### 3. Ajoutez ou modifiez une traduction
Les fichiers de traduction sont au format JSON.
Exemple :

```bash
json
{
    "welcome_message": "Bienvenue sur PRO GESTION SOFT !",
    "login_button": "Se connecter"
}
```

### 4. Soumettez une Pull Request
Une fois vos modifications terminées :

```bash
git add .
git commit -m "Ajout d'une traduction pour [langue] sur [plateforme]"
git push origin <votre-branche>
Créez une Pull Request sur GitHub pour que votre contribution soit examinée.
```

## 🛠️ Validation automatique
Nous utilisons GitHub Actions pour vérifier automatiquement :

- Le format des fichiers JSON.
- La présence des clés obligatoires dans chaque langue.

## 📋 Règles pour contribuer
Veuillez respecter les règles suivantes :

1. Suivez le format JSON existant (clé-valeur).
2. Évitez de supprimer ou de modifier les clés existantes sans justification.
3. Ajoutez des descriptions claires dans vos issues et pull requests.
4. Consultez notre fichier CONTRIBUTING.md pour plus de détails.

## 🤝 Rejoignez notre communauté !
Nous sommes ravis de recevoir vos contributions et suggestions. Si vous avez des questions ou des idées, ouvrez une issue ou contactez-nous directement.

## 📜 Licence
Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier dans les conditions prévues par cette licence.

Merci pour votre contribution à l'amélioration de PRO GESTION SOFT ! 🎉