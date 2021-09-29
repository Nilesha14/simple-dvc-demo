create env
```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

created req file
install req file
```bash
pip install -r requirements.txt
```

download the data and keep in data_given folder

git init

dvc init

dvc add data_given/winequality.csv

git add . 

git commit -m "fist commit"

git add . && git commit -m "update README.md"

git remote add origin https://github.com/Nilesha14/simple-dvc-demo.git

git branch -M main

git push -u origin main


tox command -
```bash
tox
```

for rebuilding -
```bash
tox -r 
```

pytest command
```bash
pytest -v
```

setup commands -
```bash
pip install -e . 
```

build your own package commands-
```bash
python setup.py sdist bdist_wheel
```
