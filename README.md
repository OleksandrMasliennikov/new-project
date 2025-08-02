# new-project
# create on GitHub new repository "new-project"

# in your local environment, create a directory "new-project" and go there

  mkdir new-project && cd new-project

# repository initialization

  git init

# create a README.md file

  echo "#new-rroject" > README.md

# make the first commit

  git add README.md
  git commit -m "init"

# remote add origin

  git remote add origin https://github.com/<username>/new-project.git
  git branch -M main
  git push -u origin main

# create a new branch "development" and switch to it

  git branch development
  git checkout development
