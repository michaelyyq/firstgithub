# How to use msysgit
first try,April sixth,2016

this is my first time to use github,which makes me excited.

> using Typora is so happy. 



## Download [msysgit](http://msysgit.github.io/)傻瓜式安装

## 创建ssh-keygen(无需输入账号密码)

1. `ssh-keygen -t rsa -C"michaelyuyanqing@hotmail.com"`  ---其中ssh-keygen中无空格

2. 在users/.../.ssh/下有个id_rsa.pub文件，用记事本打开全选复制

3. 打开github主页，进入SSH Keys，添加SSH Key，将上面内容黏贴到里面

4. msysgit 测试`ssh -T git@github.com`其中为T为大写

5. ```
   git config --global user.email "michaelyuyanqing@hotmail.com"
   git config --global user.name "michaelyyq"
   ```

 ## 克隆github库

1. 在本地git 库中，右击鼠标git bash打开命令行
2. `git clone https://github.com/michaelyyq/firstgithub.git`
3. 创建新的文件`git add a.txt`
4. 提交到本地代码库`git commit -m "saysomething"`
5. 提交到github上`git push`
6. `git push origin master`

## 打开github更新查看内容











