
#Git CheatSheet – Workflow Ajout Projet
#####

# 1. Vérifier l’état
git status

# 2. Créer une branche
git checkout -b ajout_PXX

# 3. Ajouter fichiers
git add .

# 4. Commit
git commit -m "Ajout projet PXX"

# 5. Envoyer sur GitHub
git push origin ajout_PXX

# 6. (Sur GitHub) → Pull Request → Merge

# 7. Mettre à jour main local
git checkout main
git pull origin main


#Git CheatSheet – Correction rapide

# 1. Vérifier l’état
git status

# 2. Ajouter seulement les fichiers modifiés
git add -u

# 3. Commit avec un message clair
git commit -m "Correction [fichier|projet]"

# 4. Envoyer directement sur main
git push origin main
