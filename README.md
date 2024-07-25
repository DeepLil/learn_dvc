create env

conda create - n wineq python=3.7 -y
create requirements.txt 
install the req
pip install -r requirements.txt

run the template.py

create a data_given folder and paste data inside the folder
data can be downloaded from https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

git init 
dvc init
dvc add data_given/wine_quality.csv
git add .
git commit -m "fist commit"

git remote add origin https://github.com/DeepLil/learn_dvc.git
git branch -M main
git push origin main