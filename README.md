create env
```bash
conda create -n wineq python=3.7 -y
```
conda activate wineq

conda env list

create requirements.txt file
```bash
touch requirements.txt
pip install -r requirements.txt
touch README.md
```

git init

dvc init

dvc add data_given/winequality.csv

git add . && git commit -m "first commit"

git remote add origin https://github.com/keithferns98/simple_wine_cicd.git

git branch -M main

git push -u origin main