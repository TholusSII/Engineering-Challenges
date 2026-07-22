# Engineering Challenges — GitHub workflow

Le projet LaTeX principal se trouve dans `work_ec08/`.

## Compilation locale

Depuis la racine du dépôt :

```bash
cd work_ec08
latexmk -pdf -file-line-error -halt-on-error -interaction=nonstopmode main.tex
```

Le PDF produit est `work_ec08/main.pdf`.

Pour supprimer les fichiers temporaires :

```bash
cd work_ec08
latexmk -c
```

## Compilation automatique sur GitHub

Le workflow `.github/workflows/latex.yml` compile automatiquement le manuel :

- à chaque push sur `main` qui modifie le projet ;
- à chaque pull request vers `main` ;
- manuellement depuis l’onglet **Actions** avec **Run workflow**.

Après compilation :

1. ouvrir l’onglet **Actions** du dépôt ;
2. ouvrir l’exécution `Compile Engineering Challenges` ;
3. télécharger l’artefact `Engineering-Challenges-build` ;
4. l’archive contient `Engineering_Challenges.pdf` et le journal `main.log`.

## Première mise en ligne

Dans un terminal placé à la racine de ce dossier :

```bash
git init
git branch -M main
git remote add origin https://github.com/TholusSII/Engineering-Challenges.git
git add .
git commit -m "Set up LaTeX project and automatic build"
git push -u origin main
```

Si le dépôt est déjà cloné, utiliser seulement :

```bash
git add .
git commit -m "Add automatic LaTeX build"
git push
```
