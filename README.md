# Git-Subtree-demo

Updated demo code.


## Code logic
```
git remote add subtree-spoon-knife https://github.com/AhsenBaig-boilerplate/Git-subtree-Spoon-Knife.git
```

```
git subtree add --prefix spoon-knife/ https://github.com/AhsenBaig-boilerplate/Git-subtree-Spoon-Knife.git main --squash
```

```
git subtree pull --prefix spoon-knife/ https://github.com/AhsenBaig-boilerplate/Git-subtree-Spoon-Knife.git main --squash
```

```
git subtree push --prefix spoon-knife/ https://github.com/AhsenBaig-boilerplate/Git-subtree-Spoon-Knife.git main
```
