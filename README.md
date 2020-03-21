# Advanced Notes Application

Win 10 extra:
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

Setup:
```bash
# create virtual env
python -m venv .venv

# setup requirements
pip install -r .\requirements.txt
```

Git steps:
```bash
# Init repository
git init

# check status
git status

# add(stage) files
git add .

# commit files
git commit -m "Message"

# Add remote server (optional)
git remote add origin git@github.com:dyachoksa/notes.git

# push to remote server (first time)
git push -u origin master

# push to remote server (regular)
git push


# clone a new repository
git clone git@github.com:dyachoksa/notes.git

# pull from server
git pull
```
