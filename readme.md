

## Steps

1. Create a env
2. Activate it
3. Create a jupyter env
4. Start jupityer

### Popular commands

```bash

# if jupyter is not installed
# brew install jupyter

#Step 1
python3 -m venv jenv
#second parameter the name of the engv


##Step 2
source jenv/bin/activate

#if you want to install required 
python3 -m pip install -r requirements.txt

#check env
which python3

#Step 3
pip install ipykernel

python -m ipykernel install --name=jpy-venv
# to deactive jupyter kernelspec uninstall jpy-venv

# Start Jupyter
jupyter notebook

```


## References

https://learnpython.com/blog/python-requirements-file/
https://realpython.com/python-virtual-environments-a-primer/



* [netflix/](./projects/netflix)
  * [Netflix.ipynb](./projects/netflix/Netflix.ipynb)
  * [readme.md](./projects/netflix/readme.md)
* [titanic/](./projects/titanic)
  * [Titanic.ipynb](./projects/titanic/Titanic.ipynb)
  * [readme.md](./projects/titanic/readme.md)

