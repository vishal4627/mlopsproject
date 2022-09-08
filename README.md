create env

'''bash
conda create -n wineq python=3.7 -y
'''

activate env
'''bash
conda activate wineq
'''

created a req file

install the req
'''bash
pip install -r requirements.txt
'''

git init

dvc init

dvc add data_given/winequality.csv

git add.

git  commit -m "first commit"

oneliner updates for readme
git add . && git commit -m "update Readme.md"

git remote add origin https://github.com/c17hawke/simple-dvc-demo.git
git branch -M main
git push origin main