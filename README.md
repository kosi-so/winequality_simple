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

setup commands 
```bash
pip install -e .
```
build your own package command
```bash
python setup.py sdist bdist_wheel
```

create web app 

create github workflow folder 

create Ci/cD yaml file 
```bash
.github\workflows\ci-cd.yaml
```

add Heroku path to ci-cd.yaml 

create Procfile

Update prediction_service/prediction.py with new error classes and validation functions 

Update test_config.py with new tests. this new tests are tests for incorrect range andincorrect columns 

Create branch main-mlflow 

update dvc.yaml with "log_production_model

update params.yaml with "ml_flow_config"

update train_and_evaluate.py with mlflow functions 

create an artifacts folder

mlflow server command -

mlflow server \
--backend-store-uri sqlite:///mlflow.db \
--default-artifact-root ./artifacts \
--host 0.0.0.0 -p 1234
