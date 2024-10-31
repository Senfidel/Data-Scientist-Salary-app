1. clonage du dépot
`git clone https://github.com/`
2. voir le status
`git status` 
3. Ajouter des fichier sur GitHub
`git add .`
4. Faire un commit 
`git commit -m ""`
5. faire un push
`git push` ou `git push origin main`
6. Résolution des problèmes courants
Erreur de branche en retard (behind error) : Si vous voyez une erreur indiquant que votre branche est "behind" (en retard) par rapport à la branche sur GitHub, vous devrez d’abord récupérer les modifications en ligne 
`git pull origin main --rebase`
`git push origin main`

Conflits de fusion (merge conflicts) : Si un conflit de fusion apparaît après le pull, Git vous demandera de résoudre manuellement les conflits dans les fichiers affectés. Une fois les conflits résolus, vous pouvez ajouter, committer et pousser les modifications :
`git add .`
`git commit -m "Résolution des conflits"`
`git push origin main`