# GitHubアカウントの切り替え方
複数のGitアカウントを所持している際, アカウントを切り替えてpushするコマンドを記す.
```
git remote set-url origin git@github.com.sub:hotaru-ngc/Cpp-prac1.git
git remote add origin https://github.com/hotaru-ngc/Cpp-prac1.git
git push -u origin master
```
