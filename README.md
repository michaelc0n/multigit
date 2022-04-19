# multigit  


# usage

## prerequisite for local testing

```
cd ..
mkdir gitrepos
cd gitrepos && git init repo1
git init repo2 && cd ..
export MG_ROOT=../gitrepos && export MG_REPOS=repo1,repo2
cd multigit
```