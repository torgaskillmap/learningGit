# learningGit

Instructions
=======
- Fork repo from GitHub UI

![image](https://user-images.githubusercontent.com/85481359/123950142-aa00ae00-d9a3-11eb-85e1-1b1a2226b92b.png)


- Clone repo to the local machine 
```
git clone clone https://github.com/viv-garot/learningGit.git
```

- Create and checkout branch on local machine 
```
git checkout -b newbranch 
```

- Add a remote pointing to the original repo you have forked on
```
git remote add upstream https://github.com/torgaskillmap/learningGit.git
```

- Do the codes changes locally
```
 Edit file, add screenshots, ...
```

- Push the changes from the *newbranch* to the remote fork
```
git push origin newbranch
```

- Create PR on GitHub from fork/branch into org/main

![image](https://user-images.githubusercontent.com/85481359/123951062-a6b9f200-d9a4-11eb-887b-e503d83cc6db.png)


- Merge the PR on GitHub

![image](https://user-images.githubusercontent.com/85481359/123951829-7faff000-d9a5-11eb-81cc-e5fdd595a7ae.png)

- Update local clone repo with changes from the original repo
```
git pull upstream main
git push origin main
``` 
