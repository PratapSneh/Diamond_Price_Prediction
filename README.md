## End To End ML Project

### create a environment
```
conda create -p venv python==3.8
```

### activate environment
```
conda activate venv/
```

After creating requirements.txt file we can install all required libraries using 
```
pip install -r requirements.txt
```
We create setup.py file to convert this project into package when required (Folder into Packages).

-e. in requirements.txt file trigger the setup.py file everytime when requirements.txt file executed to build the package again.

Inside the src folder entire lifecycle of machine learning project should run.

__init__.py is used for importing the packages in different different files anywhere.

Any generic or common functionality for the entire project can be created in utils.py file 



### create a new repository on the command line
echo "# FSDSRegression" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/PratapSneh/Diamond_Price_Prediction.git
git push -u origin main


### push an existing repository from the command line
git remote add origin https://github.com/PratapSneh/Diamond_Price_Prediction.git
git branch -M main
git push -u origin main


Having trouble commiting updates from main? (! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/PratapSneh/Diamond_Price_Prediction.git')

Try the following to fix your remote/upstream references:

git pull origin
git checkout -b main
git branch main -u origin/main
git remote set-head origin main
git branch --set-upstream-to=origin/main main
git branch -d master
git branch -d -r origin/master




