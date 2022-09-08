create env

conda create -n wineq python=3.7 -y

activate env

conda activate wineq


created a req file

install the req

pip install -r requirements.txt

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

tox command

 tox

tox rebuild

tox -r

pytest command

pytest -v


setup commands 

pip install -e