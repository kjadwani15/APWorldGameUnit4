# Game Hopper Actual
make sure open terminal in worldGameBazaar directory

to fetch:

git fetch origin            

git reset --hard origin/main


to push:

git add .

git commit -m "NAME IT HERE"

git push origin main

to set up lfs:

git lfs track "*.uasset" "*.umap"

git lfs push --all origin main

git add .

git commit -m "NAME IT HERE"

git push -u origin main
