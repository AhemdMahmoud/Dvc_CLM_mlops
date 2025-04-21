# Churn_mlops DVC with_ CLM
git init 
dvc init
python -m dvc add .\data\ .\models\   

 git add . & git commit -m "v1 added"
git branch -M main        
git remote add origin https://github.com/AhemdMahmoud/Dvc_CLM_mlops.git

dvc remote add -d myremote gdrive://1yK71x75olkzgZWcmIwqIV3lF1tjOjKOM  
git push origin main   
dvc push
