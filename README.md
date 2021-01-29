echo "# branching" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/LinnLatt7012/branching.git
git push -u origin main
