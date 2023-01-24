create env 

```bash
conda create -n wineq
```

activate env 

```bash
conda activate wineq
```

created a req file

install the req
```shell
pip install -r requirement.txt 
```

download the data from 

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5


```shell
git init 
```
```bash
dvc init 
```
```bash
dvc add data_given\winequality.csv
```
```bash
git add .
```
```bash
git commit -m "first commit"
```
one liner updates for README
```bash
git add . && git commit -m "update README.md"
```
```bash
git remote add origin https://github.com/kosi-so/winequality_simple.git
git branch -M main
git push origin main
```