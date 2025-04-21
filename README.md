git lfs install
git lfs track "*model.tensors" 
git lfs push --all origin main
git add .
git commit -m "large file to git"
git push -u origin main
