xmlcom.com website

```
[remote "origin"]
	url = git@github.com:dgdosen/xmlcom-com.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
	remote = origin
    merge = refs/heads/master
[remote "octopress"]
    url = git://github.com/imathis/octopress.git
    fetch = =refs/heads/*:refs/remotes/octopress/*
[remote "heroku"]
	url = git@heroku.com:xmlcom-com.git
	fetch = +refs/heads/*:refs/remotes/heroku/*
```
