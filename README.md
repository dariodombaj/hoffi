# hoffi
Klasse für Hoffi
cd Desktop/hoffi
git init
git add . # Add everything in the current directory (".")
git commit

git remote add origin https://github.com/dariodombaj/hoffi
git fetch origin

# Rebase your local root commit onto the remote root commit
git rebase --onto origin/master --root

# Now you can push to your remote
git push origin master
