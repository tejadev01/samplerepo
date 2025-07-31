
## Git tutorial:

git init -> to initalize the git repo <br>
git add . -> to stage all changes git add create.py(we can also  give file name to stage particular file).
git commit -m "first commit" -> To commit the or to save the current staged data. m for message
git restore --staged create.py -> to unstage the file (go to untracked we again need to git add .)

git log -> to log all previous commit details.
git stash -> to make all added(staged) changes back stage to work on clean tree.
git stash pop -> get all stashed changes back
git stash clear -> If you dont want that stashed changes we can clear that it wont get back.
