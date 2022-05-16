1. omitted  
2. 
```shell
git log --all --graph --decorate --oneline  
git log README.md  
git blame xxx  
```
3. remove the big file committed but not pushed  
```shell
git rm --cached giant_file  
git commit --amend -CHEAD  
git push  
```
4.
```shell
git stash  
git stash pop
```
5. omitted  
6.   
```shell
git config --global core.excludesfile ~/.gitignore_global # to ignore git files globally
```
7. omitted  
 