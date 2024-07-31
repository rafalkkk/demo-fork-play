# demo-fork-plan

To make a copy for yourself just do a "fork"

To make a copy within your account bare-copy the repo locally and load it as a mirror:

```bash
git clone --bare https://github.com/rafalkkk/demo-fork-play.git
cd demo-fork-play.git
git push --mirror https://github.com/rafalkkk/demo-fork-play-01
```

You will see that the remote branches are not tracked with local branches:

```
git branch
git branch --remote
```

To start tracking them use:

```
git checkout --track origin/sport
git checkout --track origin/health
git checkout --track origin/familiy-health
```

Other methods:
https://stackoverflow.com/questions/10312521/how-do-i-fetch-all-git-branches
