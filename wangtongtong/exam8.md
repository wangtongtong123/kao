##8. 描述在linxu系统上安装nodejs具体步骤
  解压后，在bin文件夹中已经存在node以及npm，如果进入到对应文件的中执行命令行一点问题都没有，
  不过不是全局的，所以将这个设置为全局就好了。
　　cd node-v0.10.28-linux-x64/bin
　　ls
　　。/node -v
　　之后，node文件夹具体放在哪，叫什么名字都可以自己设置。然后设置全局：
　　ln -s /home/kun/mysofltware/node-v0.10.28-linux-x64/bin/node /usr/local/bin/node
　　ln -s /home/kun/mysofltware/node-v0.10.28-linux-x64/bin/npm /usr/local/bin/npm
　　这里/home/kun/mysofltware/这个路径是你自己放的，你将node文件解压到哪里就是哪里。
