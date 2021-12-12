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
```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add . && git commit -m "first commit"
```
```bash
git remote add origin https://github.com/keithferns98/simple_wine_cicd.git
```
```bash
git branch -M main
```
```bash
git push -u origin main
```

tox command
```bash
tox
```

for rebuilding-
```bash
tox -r
```

pytest command-
```bash
pytest -v
```

setup commands -
```bash
pip install -e
```
Build your own package commands-
```bash
python setup.py sdist bdist wheel
```

