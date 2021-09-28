create env
```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

created req file
```bash
touch requirements.txt
```
contains of req file
```
dvc
dvc[gdrive]
sklearn
```

install req file
```bash
pip install -r requirements.txt
```

touch README.MD

touch template.py

write code in template file

python template.py

mkdir data_given

download the data and keep in data_given folder

git init

dvc init

dvc add data_given/winequality.csv

git add . 
git commit -m "fist commit"

git add . && git commit -m "update README.md"

