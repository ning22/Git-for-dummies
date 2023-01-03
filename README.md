Demo:<br />
![Demo](git-for-dummy.png)<br />

Helpful link to start git: <br />
https://git-scm.com/book/en/v2/Appendix-C%3A-Git-Commands-Getting-and-Creating-Projects

A simplified version of guide to start git: <br />
https://rogerdudler.github.io/git-guide/ <br />
http://hua-zhou.github.io/teaching/biostatm280-2019winter/slides/04-git/git


##  基本操作
```
git init <br />
git status <br />
git add $FILE # 將文件由工作區添加到暫存區 <br />
git add -a <br />
git checkout # 暫存區的内容恢復到工作區
git commit -m "commnt here" # 文件由暫存區添加到倉庫區， -m后為提交説明 <br />
git log # 查看提交日志<br />
git reset # 將代碼恢復到已經提交的某一個版本中 <br />
git reset --hard $版本號 # 將代碼恢復到指定版本 <br />
git reset --hard head~1 # 1:上一次提交，2：上上次提交，0：當前提交 <br />
.gitinore # 文件名固定，不需要被git管理的文件路徑添加到其中 <br />
```
## Branches
```

```
## Configuration of username and email 
```
git config user.name
git config user.email
git config --global user.name
git config --global user.email
git config --list
```


