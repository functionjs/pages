# pages

html pages live server readme.md   git commands
---

## hint for html Live Server in codespace
if you have not istalled Live Server extension for Visual Studio Code, you can install it from terminal by 
```bash
code --install-extension ritwickdey.LiveServer
```
Then you can right click on html file and select "Open with Live Server"

## git
Do not forget to execute commands to ensure that all Your work synked back to repo:

testing which repo and branch You use:
```bash
git status
```

commit (complete) changes in codespace
```bash
git commit -m "Update files from codespace"
```

push commited changes from codespace back to repo (from which original files were copied) to main branch
```bash
git push origin main
```
Do not forget to press CtrlSHiftR in github repo page to see what is current reality!

### If changes not staged for commit:
#### Option 0: Adding one file
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)

#### Option 1: Fastest 
git commit -am "Update modified files only" && git push origin main

#### Option 2: If you create new files too
git add . && git commit -m "Update all files including newly created" && git push origin main


## server.js

## mtable.html

[multiplication table](mtable.html)

---

## formulas

 Inline $z = \int_0^\infty \frac{\sin(x)}{x} dx$ formula

 Outline 
 $$z = \int_0^\infty \frac{\sin(x)}{x} dx$$
 formula


