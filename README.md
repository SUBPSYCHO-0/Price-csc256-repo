# create local repo and add README
git init
echo "(paste README contents here)" > README.md
git add README.md
git commit -m "Add README with project overview and getting started"
# set remote (replace <username> and lastname)
git branch -M main
git remote add origin git@github.com:<username>/lastname-csc256-repo.git
git push -u origin main
