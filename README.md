






setting up your virtual environments....
first create and navigate into a new directory on your computer

if using pipenv:

```sh
pipenv install python-dotenv psycopg2-binary
pipenv shell
```

If using conda:

```sh
conda create -n db-env python=3.7
conda activate db-env
pip install python-dotenv psycopg2
```
