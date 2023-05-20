# Bundle 1

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

## Bundle 2

```
2446  git checkout -b ft/bundle-2
 2447  touch services.html
 2448  clear
 2449  git add services.html
 2450  git status
 2451  git commit -m "service page"
 2452  clear
 2453  git push
 2454  git push --set-upstream origin ft/bundle-2
 2455  git checkout main
 2456  git checkout -b ft/service-redesign
 2457  touch services.html
 2458  git add service.html
 2459  git commit -m "service page"
 2460  git push --set-upstream origin ft/service-redesign
 2461  git checkout main
 2462  touch service.html
 2463  clear
 2464  git add .
 2465  git commit -m "service redesign"
 2466  git push
 2467  git checkout ft/service-redesign
 2468  git pull
 2469  git pull origin main
 2470  git checkout main
 2471  git pull origin main
 2472  git checkout ft/service-redesign
 2473  git merge main
 2474  git status
 2475  git add .
 2476  git commit -m "solve conflict"
 2477  clear
 2478  git push
```