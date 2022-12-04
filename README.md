# step 1 : **create env**

# step 2 : **conda create -n wineq python=3.7 -y**

# step 3 : **activate env**
>conda activate wineq


# step4 : **created a req file**

# step 5 : **install the req**

# step 6 : **pip install -r requirements.txt**

# step 7 : **git init**

# step 8 : **dvc init**

# step 9 : **dvc add data_given/winequality.csv**

# step 10 : **git add.**

# step 11 : **git  commit -m "first commit"**

# oneliner updates for readme
> **git add . && git commit -m "update Readme.md"**

> **git remote add origin https://github.com/vishal4627/mlopsproject**
> **git branch -M main**
> **git push origin main**

# tox command
> **tox**

# tox rebuild
> **tox -r**

# pytest command
> **pytest -v**

# setup commands 
> **pip install -e**

# **create an artifcats folder**

# **mlflow server command -**
>mlflow server \
>   --backend-store-uri sqlite:///mlflow.db \
>    --default-artifact-root ./artifacts \
>    --host 127.0.0.1 -p 1234