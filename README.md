# hechao633139.github.io
G云平台APP中常见问题功能

1. git安装和配置SSH Key，在GitHub中Add Key
2. 安装Node Js
3. 下载npm，配置阿里数据源 npm config set registry https://registry.npm.taobao.org
4. GitHub上创建仓库，本地创建仓库文件夹执行git hint，git clone代码克隆到本地
5. 本地创建hexo文件夹，执行 $ cnpm install -g hexo-cli 安装hexo
6. 本地搭建hexo博客，执行hexo init创建模板，执行hexo server输入 http://localhost:4000就能访问hexo主页了
7. 将博客托管到GitHub上，修改上述hexo init执行后生成的_config.yml文件夹
8. deploy:
  type: git
  repository: git@github.com:hechao633139/hechao633139.github.io.git
  branch: master
  
  9. 运行：npm install hexo-deployer-git --save
     运行：hexo g  //（本地生成静态文件）
     运行：hexo d  //（将本地静态文件推送至Github）
     
 10. 删除git clone文件夹中无用的，只剩下index.html并修改里面内容
 11. 最后上传执行
    git add .  //注意后面的‘点’
    git commit -m "first commit"  //first commit 换成你要提交的信息，而且这个命令不能少
    git remote add origin git@github.com:hechao633139/hechao633139.github.io.git  //换成你要提交的GitHub仓库SSH地址
    git push -u origin master
