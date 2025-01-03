# vitepress学习历程

## 过程记录

**初始化**

````js
npm add -D vitepress //安装vitepress

npx vitepress init //初始化

npm run docs:dev//启动vitepress
````

**构建静态文件**
````js
npm run docs:build //构建

npm run docs:preview //预览
````

**上传github**
````js
创建新仓库：（代码实现）
  先 create repository
  再 给自己的库起一个名字
  点 add readme.md

  初始化git项目：git init

  克隆远程项目：git clone repertory rul

  上传：git add . //添加文件到暂存区stage
       git commit -m "Initial commit"//提交暂存区内容到本地仓库，同时附上提示信息

  链接远程仓库：git remote add origin https://github.com/USERNAME/REPO_NAME.git  
  //将 USERNAME 和 REPO_NAME 替换为自己的 GitHub 用户名和仓库名称。

  查看文件状态：git status[filename]

  最后 git push -u origin master //如果分支在master上就这样写
````


**ubuntu安装**
````js
报错：
SMBus Host Controller not enabled!

55.689367] Bluetooth: hci0: unexpected cc 0xc12 length: 2 < 3 enabled!
这条信息表示蓝牙控制器（hci0）收到了一个意外的命令代码（cc 0xc12），并且命令长度不正确（2小于3）。这通常意味着蓝牙设备或驱动程序遇到了某种异常。

55.689401] Bluetooth: hci0: Opcode 0xc12 failed: -38
这条信息进一步确认了上一条信息中的问题，表示执行Opcode 0xc12时失败，返回值为-38。在Linux系统中，错误码-38通常表示“操作无效”（EINVAL）。

后面莫名解决了
````
