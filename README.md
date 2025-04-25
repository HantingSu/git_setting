# git 初始環境設定

- 只要照著複製貼上就可以
 ``` shell=1
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
git config --global color.ui true
git config --global core.editor vim
git config --global alias.co commit
git config --global alias.lg "log --color --graph --all --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --"
```
