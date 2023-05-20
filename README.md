```git init
 2333  clar
 2334  clear
 2335  git branch -D main
 2336  git branch -M main
 2337  touch index.html style.css
 2338  code
 2339  code .
 2340  git add .
 2341  git status
 2342  git commit -m "Getstarted commit"
 2343  clear
 2344  git remote add origin https://github.com/gracebir/gymn-exercise-git.git
 2345  git push -u origin main
 2346  touch README.md
```


``` 
 2412  git checkout main
 2413  touch home.html about.html team.html
 2414  clear
 2415  git add home.html
 2416  git stash
 2417  git add about.html
 2418  git stash
 2419  git add team.html
 2420  git stash
 2421  git stash pop
 2422  git stash apply 3bcd47bebbf22f242996e5477428a45b64ebaaaf
 2423  git diff stash@{0}
 2424  clea
 2425  rclear
 2426  clear
 2427  git stash list
 2428  git stash apply stash@\{2\} --index
 2429  git status
 2430  git stash apply stash@\{0\} --index
 2431  git stash apply stash@{0} --index
 2432  git restore --staged team.html
 2433  git status
 2434  clear
 2435  git commit -m "home and about page"
 2436  clear
 2437  git stash pop
 2438  clear

```