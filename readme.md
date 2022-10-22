<<<<<<< HEAD
create env 

```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
=======
#create env

''' bash
conda create -n wineq python -y
'''

activate env

'''bash
>>>>>>> 1df9a984323f2274a29d0b73763f15ebf25ff3c4
conda activate wineq
```

created a req file

<<<<<<< HEAD
install the req
```bash
pip install -r requirements.txt
```
download the data from 

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing
=======
install requirement

'''bash
pip install -r requirement.txt
'''

#download data from 

https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec


''' bash
>>>>>>> 1df9a984323f2274a29d0b73763f15ebf25ff3c4

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
git add .
```
```bash
git commit -m "first commit"
```

oneliner updates  for readme

```bash
git add . && git commit -m "update Readme.md"
```
```bash
git remote add origin https://github.com/c17hawke/simple-dvc-demo.git
git branch -M main
git push origin main
```

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