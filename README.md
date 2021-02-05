___
# Git 下载项目
```

  git clone 地址
  
  git clone -b （分支） 地址
  
```
# Git 下载单文件夹项目
```

  git init demo_git_test && cd demo_git_test
  
  git config core.sparsecheckout true
  
  echo 'demo002/*' >> .git/info/sparse-checkout # * 标识下面全部  ! 表示排除
  
  git remote add origin 地址
  
  git pull origin master
  
```

# Git 上传
```
  git init
  
  git remote add origin 地址
  
  git add .
  
  git commit  -m  "提交信息"
  
  git push -u origin master
  
```
