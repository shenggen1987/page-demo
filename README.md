李盛根的个人主页  
----使用
npm install 
bower install



npm install -g bower

step1:  npm init

step2: 
			新建一个目录 public/bower
			新建 .bowerrc
		  bower  
      vim .bowerrc
  --------内容如下
  {
	  "directory" : "public/bower"
	}

	bower install jquery --save

	bower install bootstrap --save

----pages 分支创建并提交
    git branch -b gh-pages
    git add .
    git commit -m 'all'
    git push origin gh-pages

===========fullpage 仿仟金顶首页，做一个个人简介     
	bower install fullpage --save    

