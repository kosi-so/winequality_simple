create env 

'''bash
conda create -n wineq
'''

activate env 

'''bash
conda activate wineq
'''

created a req file

install the req
'''bash
pip install -r requirement.txt 
'''

download the data from 

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5


git init 

dvc init 

dvc add data_given\winequality.csv

git add .

git commit -m "first commit"
