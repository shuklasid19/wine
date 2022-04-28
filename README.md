create a environment python=3.7

```
bash
conda create -n wineq python=3.7 -y

```


activate env

```
bash

conda activate wineq
```

create a req file 

install the requirements.txt
```
bash
pip install -r requirements.txt
```

repository initialization
git init

init dvc
dvc init

add data to dvc
dvc add data_given/winequality.csv


add and commit
git add . && git commit -m "first push "

```bash
git remote add origin https://github.com/shuklasid19/wine.git
git branch -m main
git push origin main
```