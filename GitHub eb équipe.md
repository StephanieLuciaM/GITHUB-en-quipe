# Travailler avec Git et GitHub en équipe

### Pré-requis
- Projet déjà créé sur GitHub.
- Environnement installé (VS Code et un terminal).

### Règles de base
1. Ne jamais coder directement sur la branche master/main (sauf pour le tout premier commit).
2. Utiliser des branches pour chaque nouvelle fonctionnalité ou correction de bug.
3. Faire des pull requests (PR) pour intégrer les changements sur la branche principale.

### Étapes à suivre

#### 1. Cloner le dépôt
```sh
git clone https://github.com/votre-repo.git
cd votre-repo
```

#### 2. Créer une nouvelle branche
Dans le terminal de VS Code :
```sh
git checkout -b ma-nouvelle-fonctionnalité
```
Nommez vos branches de manière descriptive pour que l’équipe sache à quoi elles correspondent.

#### 3. Ajouter vos modifications
Après avoir codé vos modifications, ajoutez-les :
```sh
git add .
```

#### 4. Committer les modifications
```sh
git commit -m "Description de la fonctionnalité ou du bugfix"
```

#### 5. Pousser la branche vers GitHub
```sh
git push origin ma-nouvelle-fonctionnalité
```

#### 6. Créer une pull request sur GitHub
1. Allez sur votre dépôt sur GitHub.
2. Cliquez sur l’onglet "Pull requests".
3. Cliquez sur "New pull request".
4. Sélectionnez votre branche.
5. Ajoutez une description de ce que fait la pull request.
6. Assignez des reviewers si nécessaire.
7. Cliquez sur "Create pull request".

#### 7. Gérer les Pull Requests
- Un ou plusieurs membres de l'équipe revisent la pull request.
- Les membres peuvent laisser des commentaires, suggérer des modifications ou approuver les changements.
- Une fois approuvée, la pull request est fusionnée dans la branche master/main.

### Exemple de flux de travail pour une fonctionnalité

1. **Création de la branche :**
   ```sh
   git checkout -b fonctionnalite-utilisateur
   ```

2. **Développement :** Codez votre fonctionnalité dans VS Code.

3. **Ajout et commit des modifications :**
   ```sh
   git add .
   git commit -m "Ajout de la fonctionnalité utilisateur"
   ```

4. **Push de la branche :**
   ```sh
   git push origin fonctionnalite-utilisateur
   ```

5. **Création de la pull request :**
   - Allez sur votre dépôt sur GitHub.
   - Cliquez sur l’onglet "Pull requests".
   - Cliquez sur "New pull request".
   - Sélectionnez votre branche et suivez les étapes décrites ci-dessus.

6. **Review et merge :**
   - Les membres de l'équipe révisent et fusionnent la pull request.

